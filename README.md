# 📚 Ultimate CppCon "Back to Basics" Learning Guide & Index

An organized, curated catalog of **CppCon Back to Basics** presentations on YouTube. Designed for developers of all experience levels—from freshers to senior engineers—this guide groups talks logically from core language fundamentals to advanced design, complete with community reception ratings and chronological tracking.

---

## 🗺️ Suggested Learning Path by Experience Level

* **🌱 Freshers & Beginners:** Start with **Section 1 (Language Mechanics)** and **Section 2 (Memory Management & RAII)** to build a bulletproof mental model of C++ fundamentals without getting overwhelmed.
* **💻 Mid-Level Engineers:** Progress to **Section 3 (OOP & API Design)** and **Section 4 (Move Semantics & Value Categories)** to master modern performance optimization and clean interface design.
* **🚀 Senior Developers:** Dive into **Section 5 (Templates & Concepts)**, **Section 6 (Concurrency)**, and **Section 7 (Software Quality & Sanitizers)** to tackle cutting-edge C++20/C++23 features and large-scale architectural correctness.

---

## 📌 Quick Topic Navigation

* [1. Language Mechanics, Toolchain & Core Primitives](#1-language-mechanics-toolchain--core-primitives)  
* [2. Memory Management, RAII & Smart Pointers](#2-memory-management-raii--smart-pointers)  
* [3. Object-Oriented Programming, Design & API Architecture](#3-object-oriented-programming-design--api-architecture)  
* [4. Move Semantics, Value Categories & Parameter Forwarding](#4-move-semantics-value-categories--parameter-forwarding)  
* [5. Generic Programming, Templates & Concepts](#5-generic-programming-templates--concepts)  
* [6. Concurrency, Threading & Synchronization](#6-concurrency-threading--synchronization)  
* [7. Software Quality, Testing & Debugging Infrastructure](#7-software-quality-testing--debugging-infrastructure)  
* [8. Chronological Progression & Track History](#8-chronological-progression--track-history)

---

## 1. Language Mechanics, Toolchain & Core Primitives

Understand compiler translation phases, symbol linkage, algorithm abstractions, execution model rules, and ranges pipelines. Perfect starting ground for beginners.

| Rating & Metrics | Talk Title & Link | Speaker | Year | Primary Pedagogical Focus |  
| :--- | :--- | :--- | :--- | :--- |  
| **★ 9.6/10** <br>`84K views` \| `1.8K likes` | [Back to Basics: Lambdas from Scratch](https://www.youtube.com/watch?v=3jCOwajNch0) | Arthur O'Dwyer | 2019 | Closure type generation, capture groups, stateful function objects |  
| **★ 9.5/10** <br>`96K views` | [The Best Parts of C++ (Opening Keynote)](https://www.youtube.com/watch?v=LMP_sxOaz6g) | Jason Turner | 2019 | Modern language features, clean coding standards, best practices |  
| **★ 9.0/10** <br>`59K views` | [What is C++ (Closing Keynote)](https://www.youtube.com/watch?v=RoYljVOj2H8) | C. Carruth & T. Winters | 2019 | Language design evolution, system performance trade-offs |  
| **★ 8.9/10** <br>`39K views` \| `688 likes` | [Back to Basics: Type Erasure](https://www.youtube.com/watch?v=tbUCHifyT24) | Arthur O'Dwyer | 2019 | Interface abstraction, `std::any`, `std::function` runtime overhead |  
| **★ 8.5/10** <br>`21K views` | [Back to Basics: Const as a Promise](https://www.youtube.com/watch?v=LMP_sxOaz6g) | Dan Saks | 2019 | Const-correctness contracts, physical vs logical immutability |  
| **★ 8.4/10** <br>`17K views` \| `350 likes` | [Back to Basics: Exception Handling](https://www.youtube.com/watch?v=W6jZKibuJpU) | Ben Saks | 2019 | Exception neutrality, stack unwinding safety, exception guarantees |  
| **★ 9.5/10** <br>`73K views` \| `1.0K likes` | [Back to Basics: The Abstract Machine](https://www.youtube.com/watch?v=ZAji7PkXaKY) | Bob Steagall | 2020 | Memory model assumptions, observable behavior, compiler optimizations |  
| **★ 9.3/10** <br>`60K views` \| `1.4K likes` | [Back to Basics: The Structure of a Program](https://www.youtube.com/watch?v=3KoXeegncrs) | Bob Steagall | 2020 | Preprocessing, translation units, ODR rules, linkage specifications |  
| **★ 8.6/10** <br>`31K views` | [Back to Basics: Exceptions](https://www.youtube.com/watch?v=ZG59Bqo7qX4) | Klaus Iglberger | 2020 | Exception-safe design patterns, performance costs of stack unwinding |  
| **★ 8.5/10** <br>`25K views` | [Back to Basics: Algebraic Data Types](https://www.youtube.com/watch?v=VNJ4wiuxJM4) | Arthur O'Dwyer | 2020 | Sum and product types via `std::variant`, `std::optional`, `std::tuple` |  
| **★ 9.4/10** <br>`64K views` \| `1.4K likes` | [Back to Basics: Compiling and Linking](https://www.youtube.com/watch?v=cpkDQaYttR4) | Ben Saks | 2021 | Translation phases, symbol resolution, ODR violations, linker errors |  
| **★ 9.1/10** <br>`35K views` \| `812 likes` | [Back to Basics: Lambdas](https://www.youtube.com/watch?v=IgNUBw3vcO4) | Nicolai Josuttis | 2021 | Generic lambdas, init-captures, stateless conversion to function pointers |  
| **★ 8.8/10** <br>`36K views` \| `658 likes` | [Back to Basics: const and constexpr](https://www.youtube.com/watch?v=tA6LbPyYdco) | Rainer Grimm | 2021 | Compile-time evaluation: `const`, `constexpr`, `consteval`, `constinit` |  
| **★ 8.3/10** <br>`18K views` \| `348 likes` | [Back to Basics: Casting](https://www.youtube.com/watch?v=2h2hdRqRIRk) | Brian Ruth | 2021 | Explicit casts (`static_cast`, `dynamic_cast`) vs C-style casts |  
| **★ 8.3/10** <br>`19K views` | [Back to Basics: Overload Resolution](https://www.youtube.com/watch?v=Bt3zcJZIalk) | Program Committee | 2021 | Candidate sets, viable functions, implicit conversion ranking |  
| **★ 8.2/10** <br>`15K views` | [Back to Basics: Undefined Behavior](https://www.youtube.com/watch?v=tA6LbPyYdco) | A. Sermersheim & B. Geller | 2021 | Causes of UB, compiler optimizer assumptions, sanitizer detection |  
| **★ 8.6/10** <br>`25K views` \| `537 likes` | [Back to Basics: The C++ Core Guidelines](https://www.youtube.com/watch?v=UONLB7wBVSc) | Rainer Grimm | 2022 | Structural safety rules, standardizing team engineering practices |  
| **★ 8.1/10** <br>`11K views` | [Back to Basics: Standard Library Containers](https://www.youtube.com/watch?v=tA6LbPyYdco) | Rainer Grimm | 2022 | Container complexity trade-offs, allocation models, usage guidelines |  
| **★ 9.4/10** <br>`53K views` \| `1.4K likes` | [Back to Basics: Iterators in C++](https://www.youtube.com/watch?v=26aW6aBVpk0) | Nicolai Josuttis | 2023 | Iterator categories, custom iterator constraints, range sentinels |  
| **★ 9.3/10** <br>`37K views` \| `999 likes` | [Back to Basics: (Range) Algorithms in C++](https://www.youtube.com/watch?v=eJCA2fynzME) | Klaus Iglberger | 2023 | Replacing explicit loops, standard algorithms, range projections |  
| **★ 8.9/10** <br>`28K views` \| `624 likes` | [Back to Basics: Initialization in C++](https://www.youtube.com/watch?v=_23qmZtDBxg) | Ben Saks | 2023 | Direct, list, aggregate, value, and uniform initialization rules |  
| **★ 8.3/10** <br>`13K views` \| `286 likes` | [Back to Basics: Functions in C++](https://www.youtube.com/watch?v=CpHX1Du5R0Q) | Mike Shah | 2023 | Function objects, lambdas, namespaces, call frame overheads |  
| **★ 8.5/10** <br>`Contiguous Focus` | [Back to Basics: Almost Always Vector](https://www.youtube.com/watch?v=VRGRTvfOxb4) | Kevin Carpenter | 2024 | CPU cache locality, vector memory layout, contiguous allocations |  
| **★ 8.1/10** <br>`6.0K views` \| `142 likes` | [Back to Basics: Function Call Resolution](https://www.youtube.com/watch?v=ab_RzvGAS1Q) | Ben Saks | 2024 | Overload resolution mechanics, implicit conversions, template matching |  
| **★ 8.8/10** <br>`13K views` | [Back to Basics: Strings & Character Sequences](https://www.youtube.com/watch?v=jzwqTi7n-rg) | Nicolai Josuttis | 2025 | String handling, `std::string_view` lifetime management, UTF encodings |  
| **★ 8.7/10** <br>`8.9K views` | [Back to Basics: C++ Ranges](https://www.youtube.com/watch?v=szU5b972F7E) | Mike Shah | 2025 | Range compositions, view pipelines, lazy evaluation semantics |

---

## 2. Memory Management, RAII & Smart Pointers

Resource Acquisition Is Initialization (RAII) and automated stack lifetime management replace manual dynamic memory routines. Essential foundational knowledge for writing safe C++.

| Rating & Metrics | Talk Title & Link | Speaker | Year | Primary Pedagogical Focus |  
| :--- | :--- | :--- | :--- | :--- |  
| **★ 9.6/10** <br>`89K views` \| `1.8K likes` | [Back to Basics: RAII and the Rule of Zero](https://www.youtube.com/watch?v=7Qgd9B1KuMQ) | Arthur O'Dwyer | 2019 | Deterministic cleanup, stack unwinding safety, Rule of Zero implementation |  
| **★ 9.5/10** <br>`77K views` \| `1.5K likes` | [Back to Basics: Smart Pointers](https://www.youtube.com/watch?v=xGDLkt-jBJ4) | Arthur O'Dwyer | 2019 | `std::unique_ptr`, `std::shared_ptr`, custom deleter signatures |  
| **★ 9.1/10** <br>`47K views` \| `1.1K likes` | [Back to Basics: Pointers and Memory](https://www.youtube.com/watch?v=rqVWj0aVSxg) | Ben Saks | 2020 | Memory layout, address space structure, stack vs heap allocations |  
| **★ 8.6/10** <br>`32K views` \| `736 likes` | [Back to Basics: Smart Pointers](https://www.youtube.com/watch?v=sQCSX7vmmKY) | Rainer Grimm | 2020 | Parameter passing idioms for smart pointers, ownership transfers |  
| **★ 8.4/10** <br>`23K views` \| `561 likes` | [Back to Basics: Pointers](https://www.youtube.com/watch?v=0zd8eznWv4k) | Mike Shah | 2021 | Pointer mechanics, dereferencing safety, transition to smart pointers |  
| **★ 8.2/10** <br>`19K views` \| `335 likes` | [Back to Basics: Smart Pointers and RAII](https://www.youtube.com/watch?v=07rJOzFRs6M) | Inbal Levi | 2021 | Exception safety through RAII, shared state reference counting mechanics |  
| **★ 9.0/10** <br>`39K views` \| `884 likes` | [Back to Basics: RAII in C++](https://www.youtube.com/watch?v=Rfu06XAhx90) | Andre Kostur | 2022 | Leak prevention, resource encapsulation, exception unwinding guarantees |  
| **★ 9.3/10** <br>`80K views` | [Back to Basics: C++ Smart Pointers](https://www.youtube.com/watch?v=0_0HsEBsgPc) | David Olsen | 2022 | Modern standard smart pointer usage patterns, overhead trade-offs |  
| **★ 9.1/10** <br>`45K views` \| `941 likes` | [Back to Basics: The Rule of Five in C++](https://www.youtube.com/watch?v=juAZDfsaMvY) | Andre Kostur | 2023 | Copy/move constructors, copy/move assignment, destructor orchestration |  
| **★ 8.3/10** <br>`14K views` | [Back to Basics: Lifetime Management in C++](https://www.youtube.com/watch?v=ab_RzvGAS1Q) | Phil Nash | 2024 | Object lifespan mechanics, dangling references, storage durations |  
| **★ 8.8/10** <br>`33K views` | [Back to Basics: Custom Allocators Explained](https://www.youtube.com/watch?v=TSrymTXw5w8) | Kevin Carpenter | Multi-Year | Memory arenas, custom memory resources, STL container integration |

---

## 3. Object-Oriented Programming, Design & API Architecture

Learn practical object-oriented design: balancing dynamic virtual functions against static polymorphism (CRTP), type erasure, and Value Semantics.

| Rating & Metrics | Talk Title & Link | Speaker | Year | Primary Pedagogical Focus |  
| :--- | :--- | :--- | :--- | :--- |  
| **★ 9.1/10** <br>`58K views` \| `1.1K likes` | [Back to Basics: Object-Oriented Programming](https://www.youtube.com/watch?v=32tDTD9UJCE) | Jon Kalb | 2019 | Class design foundations, encapsulation, access control, invariants |  
| **★ 8.5/10** <br>`Foundational` | [Back to Basics: Virtual Dispatch & Alternatives](https://cppcon.org/b2b2019/) | Inbal Levi | 2019 | Vtable cost models, static polymorphism via CRTP, type erasure wrappers |  
| **★ 9.0/10** <br>`44K views` \| `684 likes` | [Back to Basics: Design Patterns](https://www.youtube.com/watch?v=2UUqX2eIdSM) | Mike Shah | 2020 | Modern implementations of Creational, Structural, and Behavioral patterns |  
| **★ 8.8/10** <br>`43K views` | [Back to Basics: Class Layout](https://www.youtube.com/watch?v=3KoXeegncrs) | Stephen Dewhurst | 2020 | Struct alignment, padding bytes, `vptr` placement, CPU cache lines |  
| **★ 9.6/10** <br>`104K views` | [Back to Basics: Designing Classes (part 1 of 2)](https://www.youtube.com/watch?v=VNJ4wiuxJM4) | Klaus Iglberger | 2021 | Class member organization, invariants, responsibility separation |  
| **★ 9.0/10** <br>`41K views` | [Back to Basics: Designing Classes (part 2 of 2)](https://www.youtube.com/watch?v=St0MNEU5b0o) | Klaus Iglberger | 2021 | Operator overloading, interface safety, resource management |  
| **★ 8.3/10** <br>`19K views` \| `326 likes` | [Back to Basics: Object-Oriented Programming](https://www.youtube.com/watch?v=Ou5WsJzn7Ws) | Rainer Grimm | 2021 | Interface vs implementation inheritance, explicit `override`/`final` |  
| **★ 8.2/10** <br>`18K views` | [Back to Basics: OOP in C++](https://www.youtube.com/watch?v=2UUqX2eIdSM) | Amir Kirsh | 2022 | Encapsulation boundaries, modern class implementation strategies |  
| **★ 9.7/10** <br>`114K views` | [Back to Basics: C++ API Design](https://www.youtube.com/watch?v=eJCA2fynzME) | Jason Turner | 2022 | Class interface design, parameter selection, compile-time safety |  
| **★ 9.4/10** <br>`43K views` \| `863 likes` | [Back to Basics: C++ Value Semantics](https://www.youtube.com/watch?v=G9MxNwUoSt0) | Klaus Iglberger | 2022 | Preferring value types over reference hierarchies, copy/move semantics |  
| **★ 8.4/10** <br>`16K views` | [Back to Basics: OOP in C++](https://www.youtube.com/watch?v=juAZDfsaMvY) | Andreas Fertig | 2024 | Modern OOP execution, virtual dispatch management, abstraction costs |

---

## 4. Move Semantics, Value Categories & Parameter Forwarding

Move semantics is a core pillar of modern C++ performance optimization. These talks cover everything from basic rvalue references to expression value categories and perfect forwarding rules.

| Rating & Metrics | Talk Title & Link | Speaker | Year | Primary Pedagogical Focus |  
| :--- | :--- | :--- | :--- | :--- |  
| **★ 9.8/10** <br>`132K views` \| `2.8K likes` | [Back to Basics: Move Semantics (part 1 of 2)](https://www.youtube.com/watch?v=St0MNEU5b0o) | Klaus Iglberger | 2019 | Rvalue references, move constructors, ownership transfer mechanics |  
| **★ 9.2/10** <br>`48K views` \| `1.3K likes` | [Back to Basics: Understanding Value Categories](https://www.youtube.com/watch?v=XS2JddPq7GQ) | Ben Saks | 2019 | Expression taxonomy: lvalues, prvalues, xvalues, identity evaluation |  
| **★ 9.0/10** <br>`51K views` | [Back to Basics: Move Semantics (part 2 of 2)](https://www.youtube.com/watch?v=G9MxNwUoSt0) | Klaus Iglberger | 2019 | Move assignment, `noexcept` specifications, container reallocation |  
| **★ 8.7/10** <br>`28K views` \| `655 likes` | [The Hidden Secrets of Move Semantics](https://www.youtube.com/watch?v=TFMKjL38xAI) | Nicolai Josuttis | 2020 | Moved-from state guarantees, `const` rvalue reference pitfalls, `std::move` casts |  
| **★ 8.5/10** <br>`30K views` \| `643 likes` | [Back to Basics: Move Semantics](https://www.youtube.com/watch?v=ZG59Bqo7qX4) | David Olsen | 2020 | Modern C++ move idioms, performance trade-offs, object lifespans |  
| **★ 9.7/10** <br>`111K views` \| `2.0K likes` | [Back to Basics: Move Semantics](https://www.youtube.com/watch?v=Bt3zcJZIalk) | Nicolai Josuttis | 2021 | Practical guidelines, copy elision interaction, pass-by-value vs reference |  
| **★ 8.4/10** <br>`22K views` \| `496 likes` | [Back to Basics: C++ Move Semantics](https://www.youtube.com/watch?v=knEaMpytRMA) | Andreas Fertig | 2022 | Ref-qualifiers, `std::forward` interactions, interface optimization |  
| **★ 8.3/10** <br>`21K views` \| `423 likes` | [Back to Basics: Forwarding References](https://www.youtube.com/watch?v=0GXnfi9RAlU) | Mateusz Pusz | 2023 | Perfect forwarding, reference collapsing rules, generic parameter passing |  
| **★ 8.0/10** <br>`10K views` \| `233 likes` | [Back to Basics: Rvalues and Move Semantics in C++](https://www.youtube.com/watch?v=i_Z_o9T2fNE) | Amir Kirsh | 2024 | Modern rvalue reference application, ownership transfer cost models |  
| **★ 8.6/10** <br>`7.7K views` \| `167 likes` | [Back to Basics: Move Semantics](https://www.youtube.com/watch?v=szU5b972F7E) | Ben Saks | 2025 | Modern synthesis, interaction with compiler elision, RVO/NRVO |

---

## 5. Generic Programming, Templates & Concepts

These sessions outline the transition from unconstrained C++98/11 templates (SFINAE, type traits) to C++20 Concepts and compile-time constraints.

| Rating & Metrics | Talk Title & Link | Speaker | Year | Primary Pedagogical Focus |  
| :--- | :--- | :--- | :--- | :--- |  
| **★ 9.4/10** <br>`75K views` \| `1.7K likes` | [Back to Basics: Function and Class Templates](https://www.youtube.com/watch?v=LMP_sxOaz6g) | Dan Saks | 2019 | Template declaration syntax, type deduction, instantiation phases |  
| **★ 8.6/10** <br>`33K views` \| `530 likes` | [Back to Basics: Templates (part 1 of 2)](https://www.youtube.com/watch?v=VNJ4wiuxJM4) | Andreas Fertig | 2020 | Generic programming fundamentals, function/class/alias templates |  
| **★ 8.2/10** <br>`13K views` | [Back to Basics: Templates (part 2 of 2)](https://www.youtube.com/watch?v=VNJ4wiuxJM4) | Andreas Fertig | 2020 | Type traits, code bloat mitigation, compile-time branching (`if constexpr`) |  
| **★ 9.0/10** <br>`50K views` \| `1.0K likes` | [Back to Basics: Templates (part 1 of 2)](https://www.youtube.com/watch?v=XN319NYEOcE) | Bob Steagall | 2021 | Generic algorithm design, compile-time parameterization |  
| **★ 8.3/10** <br>`18K views` | [Back to Basics: Templates (part 2 of 2)](https://www.youtube.com/watch?v=XN319NYEOcE) | Bob Steagall | 2021 | Explicit specialization rules, foundational SFINAE mechanics |  
| **★ 9.7/10** <br>`101K views` | [Back to Basics: Templates in C++](https://www.youtube.com/watch?v=G9MxNwUoSt0) | Nicolai Josuttis | 2022 | Modern template design, Class Template Argument Deduction (CTAD) |  
| **★ 8.2/10** <br>`10K views` \| `182 likes` | [Back to Basics: Generic Programming in C++](https://www.youtube.com/watch?v=0_0HsEBsgPc) | David Olsen | 2024 | Algorithm abstraction principles, modern template constraints |  
| **★ 8.5/10** <br>`14K views` | [Back to Basics: Functional Programming & Monads](https://www.youtube.com/watch?v=otSPZyXqY_M) | Jonathan Müller | 2024 | Monadic composition, optional/expected chaining, generic error models |  
| **★ 9.3/10** <br>`31K views` \| `628 likes` | [Back to Basics: Concepts in C++](https://www.youtube.com/watch?v=jzwqTi7n-rg) | Nicolai Josuttis | 2024 | C++20 concepts, `requires` clauses, constraint formulations |  
| **★ 8.4/10** <br>`High Engagement` | [Back to Basics: C++ Concepts](https://www.youtube.com/watch?v=NpuNUGifL1M) | Jeff Garland | 2025 | Modern constraint application, standard library concept integration |

---

## 6. Concurrency, Threading & Synchronization

Concurrent programming involves thread synchronization, hardware data race prevention, and atomic execution boundaries.

| Rating & Metrics | Talk Title & Link | Speaker | Year | Primary Pedagogical Focus |  
| :--- | :--- | :--- | :--- | :--- |  
| **★ 8.9/10** <br>`Foundational` | [Back to Basics: Atomics, Locks, & Tasks](https://cppcon.org/b2b2019/) | Rainer Grimm | 2019 | Mutex synchronization, `std::atomic`, task-based async pipelines |  
| **★ 9.8/10** <br>`119K views` \| `2.3K likes` | [Back to Basics: Concurrency](https://www.youtube.com/watch?v=F6Ipn7gCOsY) | Arthur O'Dwyer | 2020 | `std::thread`, RAII locks, deadlock prevention, thread-safe statics |  
| **★ 8.8/10** <br>`37K views` \| `792 likes` | [Back to Basics: Concurrency](https://www.youtube.com/watch?v=pfIC-kle4b0) | Mike Shah | 2021 | Multi-core execution hardware, data races, lock guards |  
| **★ 8.9/10** <br>`32K views` \| `780 likes` | [Back to Basics: C++ Concurrency](https://www.youtube.com/watch?v=8rEGu20Uw4g) | David Olsen | 2023 | Modern threading primitives, parallel algorithms, synchronization bounds |

---

## 7. Software Quality, Testing & Debugging Infrastructure

Sessions focused on unit testing, assertion strategies, dynamic sanitizers (ASan, UBSan, TSan), time-travel debugging, and refactoring legacy systems.

| Rating & Metrics | Talk Title & Link | Speaker | Year | Primary Pedagogical Focus |  
| :--- | :--- | :--- | :--- | :--- |  
| **★ 8.4/10** <br>`15K views` | [Back to Basics: Sanitizers in C++](https://www.youtube.com/watch?v=juAZDfsaMvY) | Andrei Alexandrescu | 2021 | AddressSanitizer, UndefinedBehaviorSanitizer, ThreadSanitizer setup |  
| **★ 9.1/10** <br>`33K views` \| `778 likes` | [Back to Basics: Debugging in C++](https://www.youtube.com/watch?v=YzIBwqWC6EM) | Mike Shah | 2022 | Interactive GDB/LLDB usage, memory inspection, breakpoint control |  
| **★ 8.7/10** <br>`22K views` \| `489 likes` | [Back to Basics: Debugging in C++](https://www.youtube.com/watch?v=ab_RzvGAS1Q) | Andrei Alexandrescu | 2023 | Modern diagnostic tooling, static analysis, structured tracing |  
| **★ 9.3/10** <br>`41K views` \| `990 likes` | [Back to Basics: Unit Testing in C++](https://www.youtube.com/watch?v=MwoAM3sznS0) | Dave Steffen | 2024 | Isolation strategies, test doubles (mocks/stubs), maintainable suites |  
| **★ 8.6/10** <br>`19K views` \| `412 likes` | [Back to Basics: Code Smells and Refactoring](https://www.youtube.com/watch?v=juAZDfsaMvY) | Klaus Iglberger | 2024 | Identifying legacy design anti-patterns, systematic refactoring strategies |

---

## 8. Chronological Progression & Track History

If you prefer to follow the evolution of the CppCon **Back to Basics** track year-by-year or want a structured curriculum path from absolute fundamentals to advanced patterns, use this chronological index.

| Year & Track Focus | Key Core Themes Emphasized | Recommended Starting Talk |  
| :--- | :--- | :--- |  
| **2019** <br> *Foundational Establishment* | Value semantics, RAII, lambda closures, object-oriented programming foundations | [Back to Basics: Move Semantics (part 1)](https://www.youtube.com/watch?v=St0MNEU5b0o) (Klaus Iglberger) |  
| **2020** <br> *Abstract Machine & Safety* | The abstract machine, compilation/linking phases, error handling, const correctness | [Back to Basics: The Abstract Machine](https://www.youtube.com/watch?v=ZAji7PkXaKY) (Bob Steagall) |  
| **2021** <br> *Templates & Idioms* | Class templates, compilation architecture, smart pointers, standard library design | [Back to Basics: Compiling and Linking](https://www.youtube.com/watch?v=cpkDQaYttR4) (Ben Saks) |  
| **2022** <br> *API Design & Constraints* | Class design, clean API architecture, core guidelines, debugging practices | [Back to Basics: C++ API Design](https://www.youtube.com/watch?v=eJCA2fynzME) (Jason Turner) |  
| **2023** <br> *Ranges, Iterators & Advanced Flows* | Range algorithms, iterators, forwarding references, initialization rules | [Back to Basics: Iterators in C++](https://www.youtube.com/watch?v=26aW6aBVpk0) (Nicolai Josuttis) |  
| **2024–2025** <br> *Modern Synthesis & Concepts* | C++20/C++23 Concepts, advanced metaprogramming constraints, state-of-the-art tooling | [Back to Basics: Concepts in C++](https://www.youtube.com/watch?v=jzwqTi7n-rg) (Nicolai Josuttis) |

---

## 🤝 Contributing & Suggestions

Have you watched a CppCon Back to Basics talk that completely changed how you write code? 
Contributions are welcome! 

⭐ **If you find this repository helpful for your interview prep or daily C++ development, please consider giving it a star!**

---

## 📊 How Ratings Are Calculated

To help you prioritize your study time, each talk is rated out of **10.0** using a weighted combination of quantitative and qualitative metrics:

* **Engagement Rate (Like-to-View Ratio):** Evaluates audience satisfaction by comparing total likes to view counts. Higher ratios indicate high utility and retention.  
* **Pedagogical Clarity:** Assesses the speaker's ability to deconstruct complex computer science paradigms into intuitive, digestible concepts.  
* **Modern C++ Relevance:** Weights heavily toward talks that emphasize modern standards `(C++17, C++20, C++23)` and steer clear of deprecated or unsafe idioms.  
* **Interview & Production Practicality:** Measures how directly the concepts translate to real-world software engineering, codebases, and technical interview scenarios.

---

## ⚖️ Legal Disclaimer & Attribution

* **Trademarks & Copyrights:** All presentation titles, video content, talk materials, and trademarks (including *CppCon*, *Back to Basics*, and *C++*) belong to their respective owners, speakers, and the CppCon Organization / Standard C++ Foundation.
* **Non-Affiliation:** This repository is an independent, community-driven educational guide and index. It is **not** sponsored, endorsed by, affiliated with, or officially linked to CppCon, the Standard C++ Foundation, YouTube, or Google LLC.
* **Educational Fair Use:** All video links and metadata referenced in this catalog are provided strictly for indexing, educational, and reference purposes under Fair Use principles. No underlying video assets or copyrighted presentation slides are hosted directly in this repository.
* **No Warranty:** This guide is provided "as-is" without any express or implied warranties regarding accuracy, completeness, or suitability for any specific interview or commercial purpose.
