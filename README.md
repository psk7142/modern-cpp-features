# C++20/17/14/11

> **NOTICE** 오역 확인 및 원문 참조에 유용하도록 아래와 같은 순서로 작성하고 있습니다. ([기여하기](/CONTRIBUTING.md))
>
> **원문 제목**
>
> > 번역한 제목(없을 수도 있음)
>
> 번역본 파트
>
> 원문 파트

## TOC

- [Overview](#overview)
  - [C++20 Overview](#c20-overview)
  - [C++17 Overview](#c17-overview)
  - [C++14 Overview](#c14-overview)
  - [C++11 Overview](#c11-overview)
- [Acknowledgements](#acknowledgements)
- [작성자](#작성자)
- [라이센스](#License)

## Overview

많은 설명과 예제들은 다양한 자료로부터 요약한 것입니다.(대략적인 출처는 [Acknowledgements](#acknowledgements) 섹션을 참조하세요.)

### [C++20 Overview](/CPP20.md#Overview)

C++20은 아래와 같은 새로운 언어 기능을 포함합니다.

- [concepts](/CPP20.md#concepts)
- [designated initializers](/CPP20.md#designated-initializers)
- [template syntax for lambdas](/CPP20.md#template-syntax-for-lambdas)
- [range-based for loop with initializer](/CPP20.md#range-based-for-loop-with-initializer)
- [likely and unlikely attributes](/CPP20.md#likely-and-unlikely-attributes)
- [deprecate implicit capture of this](/CPP20.md#deprecate-implicit-capture-of-this)
- [class types in non-type template parameters](/CPP20.md#class-types-in-non-type-template-parameters)
- [constexpr virtual functions](/CPP20.md#constexpr-virtual-functions)
- [explicit(bool)](/CPP20.md#explicitbool)
- [char8_t](/CPP20.md#char8_t)
- [immediate functions](/CPP20.md#immediate-functions)
- [using enum](/CPP20.md#using-enum)

C++20은 아래와 같은 새로운 라이브러리 기능을 포함합니다:

- [concepts library](/CPP20.md#concepts-library)
- [synchronized buffered outputstream](/CPP20.md#synchronized-buffered-outputstream)
- [std::span](/CPP20.md#stdspan)
- [bit operations](/CPP20.md#bit-operations)
- [math constants](/CPP20.md#math-constants)
- [std::is_constant_evaluated](/CPP20.md#stdis_constant_evaluated)

### [C++17 Overview](/CPP17.md#overview)

C++17은 아래와 같은 새로운 언어 기능을 포함합니다.

- [template argument deduction for class templates - 클래스 템플릿에 대한 템플릿 인자 추론](/CPP17.md#template-argument-deduction-for-class-templates)
- [declaring non-type template parameters with auto - auto를 사용한 타입이 아닌 템플릿 매개 변수 선언](/CPP17.md#declaring-non-type-template-parameters-with-auto)
- [folding expressions - Fold 형식](/CPP17.md#folding-expressions)
- [new rules for auto deduction from braced-init-list - braced-init-list에서 auto 추론에 대한 새로운 규칙.](/CPP17.md#new-rules-for-auto-deduction-from-braced-init-list)
- [constexpr lambda - constexpr 람다](/CPP17.md#constexpr-lambda)
- [lambda capture this by value - 값에 의한 람다 'this' 캡처](/CPP17.md#lambda-capture-this-by-value)
- [inline variables - 인라인 변수](/CPP17.md#inline-variables)
- [nested namespaces - 내포된 namespace](/CPP17.md#nested-namespaces)
- [structured bindings - 구조화된 바인딩](/CPP17.md#structured-bindings)
- [selection statements with initializer - 초기화자가 있는 선택문](/CPP17.md#selection-statements-with-initializer)
- [constexpr if](/CPP17.md#constexpr-if)
- [utf-8 character literals - utf-8 문자열 리터럴](/CPP17.md#utf-8-character-literals)
- [direct-list-initialization of enums - enum의 직접 목록 초기화](/CPP17.md#direct-list-initialization-of-enums)
- [fallthrough, nodiscard, maybe_unused attributes - fallthrough, nodiscard, maybe_unused 속성들](/CPP17.md#fallthrough-nodiscard-maybe_unused-attributes)

C++17은 아래와 같은 새로운 라이브러리 기능을 포함합니다:

- [std::variant](/CPP17.md#stdvariant)
- [std::optional](/CPP17.md#stdoptional)
- [std::any](/CPP17.md#stdany)
- [std::string_view](/CPP17.md#stdstring_view)
- [std::invoke](/CPP17.md#stdinvoke)
- [std::apply](/CPP17.md#stdapply)
- [std::filesystem](/CPP17.md#stdfilesystem)
- [std::byte](/CPP17.md#stdbyte)
- [splicing for maps and sets - map과 set에 대한 접합](/CPP17.md#splicing-for-maps-and-sets)
- [parallel algorithms - 병렬 알고리즘](/CPP17.md#parallel-algorithms)

### [C++14 Overview](/CPP14.md#overview)

C++14은 아래와 같은 새로운 언어 기능을 포함합니다.

- [binary literals - 바이너리 리터럴](/CPP14.md#binary-literals)
- [generic lambda expressions - 일반화 람다 표현식](/CPP14.md#generic-lambda-expressions)
- [lambda capture initializers - 람다 캡처 초기화자](/CPP14.md#lambda-capture-initializers)
- [return type deduction - 반환 타입 추론](/CPP14.md#return-type-deduction)
- [decltype(auto) - 선언된 형식(auto)](/CPP14.md#decltypeauto)
- [relaxing constraints on constexpr functions - constexpr 함수에 대한 제약 완화](/CPP14.md#relaxing-constraints-on-constexpr-functions)
- [variable templates - 변수 템플릿](/CPP14.md#variable-templates)
- [\[\[deprecated\]\] attribute - \[\[deprecated\]\] 속성](/CPP14.md#deprecated-attribute)

C++14은 아래와 같은 새로운 라이브러리 기능을 포함합니다:

- [user-defined literals for standard library types - 표준 라이브러리 타입에 대한 사용자 정의 리터럴](/CPP14.md#user-defined-literals-for-standard-library-types)
- [compile-time integer sequences - 컴파일 시간 정수 시퀀스](/CPP14.md#compile-time-integer-sequences)
- [std::make_unique](/CPP14.md#stdmake_unique)

### [C++11 Overview](/CPP11.md#overview)

C++11은 아래와 같은 새로운 언어 기능을 포함합니다.

- [move semantics - 이동 semantic](/CPP11.md#move-semantics)
- [variadic templates - 가변인자 템플릿](/CPP11.md#variadic-templates)
- [rvalue references - rvalue 레퍼런스(참조)](/CPP11.md#rvalue-references)
- [forwarding references - 전달 레퍼런스(참조)](/CPP11.md#forwarding-references)
- [initializer lists - 초기화자 목록(초기화 리스트)](/CPP11.md#initializer-lists)
- [static assertions - 정적 어써트](/CPP11.md#static-assertions)
- [auto](/CPP11.md#auto)
- [lambda expressions - 람다 표현식](/CPP11.md#lambda-expressions)
- [decltype](/CPP11.md#decltype)
- [type aliases - 타입 별칭](/CPP11.md#type-aliases)
- [nullptr](/CPP11.md#nullptr)
- [strongly-typed enums - 강 타입 열거](/CPP11.md#strongly-typed-enums)
- [attributes - 속성](/CPP11.md#attributes)
- [constexpr - 상수 표현식](/CPP11.md#constexpr)
- [delegating constructors - 위임 생성자](/CPP11.md#delegating-constructors)
- [user-defined literals - 사용자 정의 리터럴](/CPP11.md#user-defined-literals)
- [explicit virtual overrides - 명시적인 virtual 오버라이드](/CPP11.md#explicit-virtual-overrides)
- [final specifier - final 지정자](/CPP11.md#final-specifier)
- [default functions - 기본 함수](/CPP11.md#default-functions)
- [deleted functions - 삭제 함수](/CPP11.md#deleted-functions)
- [range-based for loops - 범위 기반 for 문](/CPP11.md#range-based-for-loops)
- [special member functions for move semantics - 이동 semantic에 대한 특별한 멤버 함수들](/CPP11.md#special-member-functions-for-move-semantics)
- [converting constructors - 생성자 변환](/CPP11.md#converting-constructors)
- [explicit conversion functions - 명시적인 변환 함수](/CPP11.md#explicit-conversion-functions)
- [inline-namespaces - 인라인 namespace](/CPP11.md#inline-namespaces)
- [non-static data member initializers - 비정적 데이터 멤버의 초기화](/CPP11.md#non-static-data-member-initializers)
- [right angle brackets - 우측 꺽쇠 괄호](/CPP11.md#right-angle-brackets)
- [ref-qualified member functions - 참조 자격을 갖춘 멤버 함수](/CPP11.md#ref-qualified-member-functions)
- [trailing return types - 반환 타입 추론](/CPP11.md#trailing-return-types)
- [noexcept specifier - noexcept 한정자](/CPP11.md#noexcept-specifier)

C++11은 아래와 같은 새로운 라이브러리 기능을 포함합니다:

- [std::move](/CPP11.md#stdmove)
- [std::forward](/CPP11.md#stdforward)
- [std::thread](/CPP11.md#stdthread)
- [std::to_string](/CPP11.md#stdto_string)
- [type traits](/CPP11.md#type-traits)
- [smart pointers](/CPP11.md#smart-pointers)
- [std::chrono](/CPP11.md#stdchrono)
- [tuples](/CPP11.md#tuples)
- [std::tie](/CPP11.md#stdtie)
- [std::array](/CPP11.md#stdarray)
- [unordered containers - 비정렬 컨테이너](/CPP11.md#unordered-containers)
- [std::make_shared](/CPP11.md#stdmake_shared)
- [std::ref](/CPP11.md#stdref)
- [memory model - 메모리 모델](/CPP11.md#memory-model)
- [std::async](/CPP11.md#stdasync)
- [std::begin/end](/CPP11.md#stdbeginend)

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

## 작성자

Anthony Calandra - [Original Repository](https://github.com/AnthonyCalandra/modern-cpp-features)
박성규(0x0d5) - This Repository

## License

[Original Repository](https://github.com/AnthonyCalandra/modern-cpp-features) - MIT

[This Repository](/LICENSE) - MIT
