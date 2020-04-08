# C++20/17/14/11

## Overview

Many of these descriptions and examples come from various resources (see [Acknowledgements](#acknowledgements) section), summarized in my own words.

### [C++20 Overview](/modern-cpp-features/CPP20)

C++20은 아래와 같은 새로운 언어 기능을 포함합니다.

- [concepts](/modern-cpp-features/CPP20#concepts)
- [designated initializers](/modern-cpp-features/CPP20#designated-initializers)
- [template syntax for lambdas](/modern-cpp-features/CPP20#template-syntax-for-lambdas)
- [range-based for loop with initializer](/modern-cpp-features/CPP20#range-based-for-loop-with-initializer)
- [likely and unlikely attributes](/modern-cpp-features/CPP20#likely-and-unlikely-attributes)
- [deprecate implicit capture of this](/modern-cpp-features/CPP20#deprecate-implicit-capture-of-this)
- [class types in non-type template parameters](/modern-cpp-features/CPP20#class-types-in-non-type-template-parameters)
- [constexpr virtual functions](/modern-cpp-features/CPP20#constexpr-virtual-functions)
- [explicit(bool)](/modern-cpp-features/CPP20#explicitbool)
- [char8_t](/modern-cpp-features/CPP20#char8_t)
- [immediate functions](/modern-cpp-features/CPP20#immediate-functions)
- [using enum](/modern-cpp-features/CPP20#using-enum)

C++20은 아래와 같은 새로운 라이브러리 기능을 포함합니다:

- [concepts library](/modern-cpp-features/CPP20#concepts-library)
- [synchronized buffered outputstream](/modern-cpp-features/CPP20#synchronized-buffered-outputstream)
- [std::span](/modern-cpp-features/CPP20#stdspan)
- [bit operations](/modern-cpp-features/CPP20#bit-operations)
- [math constants](/modern-cpp-features/CPP20#math-constants)
- [std::is_constant_evaluated](/modern-cpp-features/CPP20#stdis_constant_evaluated)

### [C++17 Overview](/modern-cpp-features/CPP17)

C++17은 아래와 같은 새로운 언어 기능을 포함합니다.

- [template argument deduction for class templates - 클래스 템플릿에 대한 템플릿 인자 추론](/modern-cpp-features/CPP17#template-argument-deduction-for-class-templates)
- [declaring non-type template parameters with auto - auto를 사용한 타입이 아닌 템플릿 매개 변수 선언](/modern-cpp-features/CPP17#declaring-non-type-template-parameters-with-auto)
- [folding expressions - Fold 형식](/modern-cpp-features/CPP17#folding-expressions)
- [new rules for auto deduction from braced-init-list - braced-init-list에서 auto 추론에 대한 새로운 규칙.](/modern-cpp-features/CPP17#new-rules-for-auto-deduction-from-braced-init-list)
- [constexpr lambda - constexpr 람다](/modern-cpp-features/CPP17#constexpr-lambda)
- [lambda capture this by value - 값에 의한 람다 'this' 캡처](/modern-cpp-features/CPP17#lambda-capture-this-by-value)
- [inline variables - 인라인 변수](/modern-cpp-features/CPP17#inline-variables)
- [nested namespaces - 내포된 namespace](/modern-cpp-features/CPP17#nested-namespaces)
- [structured bindings - 구조화된 바인딩](/modern-cpp-features/CPP17#structured-bindings)
- [selection statements with initializer - 초기화자가 있는 선택문](/modern-cpp-features/CPP17#selection-statements-with-initializer)
- [constexpr if](/modern-cpp-features/CPP17#constexpr-if)
- [utf-8 character literals - utf-8 문자열 리터럴](/modern-cpp-features/CPP17#utf-8-character-literals)
- [direct-list-initialization of enums - enum의 직접 목록 초기화](/modern-cpp-features/CPP17#direct-list-initialization-of-enums)
- [fallthrough, nodiscard, maybe_unused attributes - fallthrough, nodiscard, maybe_unused 속성들](/modern-cpp-features/CPP17#fallthrough-nodiscard-maybe_unused-attributes)

C++17은 아래와 같은 새로운 라이브러리 기능을 포함합니다:

- [std::variant](/modern-cpp-features/CPP17#stdvariant)
- [std::optional](/modern-cpp-features/CPP17#stdoptional)
- [std::any](/modern-cpp-features/CPP17#stdany)
- [std::string_view](/modern-cpp-features/CPP17#stdstring_view)
- [std::invoke](/modern-cpp-features/CPP17#stdinvoke)
- [std::apply](/modern-cpp-features/CPP17#stdapply)
- [std::filesystem](/modern-cpp-features/CPP17#stdfilesystem)
- [std::byte](/modern-cpp-features/CPP17#stdbyte)
- [splicing for maps and sets - map과 set에 대한 접합](/modern-cpp-features/CPP17#splicing-for-maps-and-sets)
- [parallel algorithms - 병렬 알고리즘](/modern-cpp-features/CPP17#parallel-algorithms)

### [C++14 Overview](/modern-cpp-features/CPP14)

C++14은 아래와 같은 새로운 언어 기능을 포함합니다.

- [binary literals - 바이너리 리터럴](/modern-cpp-features/CPP14#binary-literals)
- [generic lambda expressions - 일반화 람다 표현식](/modern-cpp-features/CPP14#generic-lambda-expressions)
- [lambda capture initializers - 람다 캡처 초기화자](/modern-cpp-features/CPP14#lambda-capture-initializers)
- [return type deduction - 반환 타입 추론](/modern-cpp-features/CPP14#return-type-deduction)
- [decltype(auto) - 선언된 형식(auto)](/modern-cpp-features/CPP14#decltypeauto)
- [relaxing constraints on constexpr functions - constexpr 함수에 대한 제약 완화](/modern-cpp-features/CPP14#relaxing-constraints-on-constexpr-functions)
- [variable templates - 변수 템플릿](/modern-cpp-features/CPP14#variable-templates)
- [\[\[deprecated\]\] attribute - \[\[deprecated\]\] 속성](/modern-cpp-features/CPP14#deprecated-attribute)

C++14은 아래와 같은 새로운 라이브러리 기능을 포함합니다:

- [user-defined literals for standard library types - 표준 라이브러리 타입에 대한 사용자 정의 리터럴](/modern-cpp-features/CPP14#user-defined-literals-for-standard-library-types)
- [compile-time integer sequences - 컴파일 시간 정수 시퀀스](/modern-cpp-features/CPP14#compile-time-integer-sequences)
- [std::make_unique](/modern-cpp-features/CPP14#stdmake_unique)

### [C++1 Overview](/modern-cpp-features/CPP11)

C++11은 아래와 같은 새로운 언어 기능을 포함합니다.

- [move semantics - 이동 semantic](/modern-cpp-features/CPP11#move-semantics)
- [variadic templates - 가변인자 템플릿](/modern-cpp-features/CPP11#variadic-templates)
- [rvalue references - rvalue 레퍼런스(참조)](/modern-cpp-features/CPP11#rvalue-references)
- [forwarding references - 전달 레퍼런스(참조)](/modern-cpp-features/CPP11#forwarding-references)
- [initializer lists - 초기화자 목록(초기화 리스트)](/modern-cpp-features/CPP11#initializer-lists)
- [static assertions - 정적 어써트](/modern-cpp-features/CPP11#static-assertions)
- [auto](/modern-cpp-features/CPP11#auto)
- [lambda expressions - 람다 표현식](/modern-cpp-features/CPP11#lambda-expressions)
- [decltype](/modern-cpp-features/CPP11#decltype)
- [type aliases - 타입 별칭](/modern-cpp-features/CPP11#type-aliases)
- [nullptr](/modern-cpp-features/CPP11#nullptr)
- [strongly-typed enums - 강타입 enum](/modern-cpp-features/CPP11#strongly-typed-enums)
- [attributes - 속성](/modern-cpp-features/CPP11#attributes)
- [constexpr - 상수 표현식](/modern-cpp-features/CPP11#constexpr)
- [delegating constructors - 위임 생성자](/modern-cpp-features/CPP11#delegating-constructors)
- [user-defined literals - 사용자 정의 리터럴](/modern-cpp-features/CPP11#user-defined-literals)
- [explicit virtual overrides - 명시적인 virtual 오버라이드](/modern-cpp-features/CPP11#explicit-virtual-overrides)
- [final specifier - final 지정자](/modern-cpp-features/CPP11#final-specifier)
- [default functions - 기본 함수](/modern-cpp-features/CPP11#default-functions)
- [deleted functions - 삭제 함수](/modern-cpp-features/CPP11#deleted-functions)
- [range-based for loops - 범위 기반 for 문](#range-based-for-loops)
- [special member functions for move semantics - 이동 semantic에 대한 특별한 멤버 함수들](/modern-cpp-features/CPP11#special-member-functions-for-move-semantics)
- [converting constructors - 생성자 변환](/modern-cpp-features/CPP11#converting-constructors)
- [explicit conversion functions - 명시적인 변환 함수](/modern-cpp-features/CPP11#explicit-conversion-functions)
- [inline-namespaces - 인라인 namespace](/modern-cpp-features/CPP11#inline-namespaces)
- [non-static data member initializers - 비정적 데이터 멤버의 초기화](/modern-cpp-features/CPP11#non-static-data-member-initializers)
- [right angle brackets - 우측 꺽쇠 괄호](/modern-cpp-features/CPP11#right-angle-brackets)
- [ref-qualified member functions - 참조 자격을 갖춘 멤버 함수](/modern-cpp-features/CPP11#ref-qualified-member-functions)
- [trailing return types - 반환 타입 추론](/modern-cpp-features/CPP11#trailing-return-types)
- [noexcept specifier - noexcept 한정자](/modern-cpp-features/CPP11#noexcept-specifier)

C++11은 아래와 같은 새로운 라이브러리 기능을 포함합니다:

- [std::move](/modern-cpp-features/CPP11#stdmove)
- [std::forward](/modern-cpp-features/CPP11#stdforward)
- [std::thread](/modern-cpp-features/CPP11#stdthread)
- [std::to_string](/modern-cpp-features/CPP11#stdto_string)
- [type traits](/modern-cpp-features/CPP11#type-traits)
- [smart pointers](/modern-cpp-features/CPP11#smart-pointers)
- [std::chrono](/modern-cpp-features/CPP11#stdchrono)
- [tuples](/modern-cpp-features/CPP11#tuples)
- [std::tie](/modern-cpp-features/CPP11#stdtie)
- [std::array](/modern-cpp-features/CPP11#stdarray)
- [unordered containers - 비정렬 컨테이너](/modern-cpp-features/CPP11#unordered-containers)
- [std::make_shared](/modern-cpp-features/CPP11#stdmake_shared)
- [std::ref](/modern-cpp-features/CPP11#stdref)
- [memory model - 메모리 모델](/modern-cpp-features/CPP11#memory-model)
- [std::async](/modern-cpp-features/CPP11#stdasync)
- [std::begin/end](/modern-cpp-features/CPP11#stdbeginend)

## Acknowledgements

- [cppreference](http://en.cppreference.com/w/cpp) - especially useful for finding examples and documentation of new library features.
- [C++ Rvalue References Explained](http://thbecker.net/articles/rvalue_references/section_01.html) - a great introduction I used to understand rvalue references, perfect forwarding, and move semantics.
- [clang](http://clang.llvm.org/cxx_status.html) and [gcc](https://gcc.gnu.org/projects/cxx-status.html)'s standards support pages. Also included here are the proposals for language/library features that I used to help find a description of, what it's meant to fix, and some examples.
- [Compiler explorer](https://godbolt.org/)
- [Scott Meyers' Effective Modern C++](https://www.amazon.com/Effective-Modern-Specific-Ways-Improve/dp/1491903996) - highly recommended book!
- [Jason Turner's C++ Weekly](https://www.youtube.com/channel/UCxHAlbZQNFU2LgEtiqd2Maw) - nice collection of C++-related videos.
- [What can I do with a moved-from object?](http://stackoverflow.com/questions/7027523/what-can-i-do-with-a-moved-from-object)
- [What are some uses of decltype(auto)?](http://stackoverflow.com/questions/24109737/what-are-some-uses-of-decltypeauto)
- And many more SO posts I'm forgetting...

## Author

Anthony Calandra

## Content Contributors

See: <https://github.com/AnthonyCalandra/modern-cpp-features/graphs/contributors>

## License

MIT
