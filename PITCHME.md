### Beginner’s guide to Flutter with DDD

2020/08/25

Masataka Ushijima

---

### Self Introduction

- Name: Masataka Ushijima
- Company: Leverages.inc
- Work: Making native app with Flutter.
- Hobby: [ Traveling, Training, Customize Notion ]
- I lived in gaogao tokyo until 03/2020.

---

### Today's topic

+++

### Flutter with DDD

※Light DDD

---?image=assets/flutter_logo.png&size=contain

### What’s flutter

+++

What's Flutter

> Flutter is Google’s UI toolkit for building beautiful, natively compiled applications for mobile, web, and desktop from a single codebase.

https://flutter.dev/

+++

- Multi platform SDK made by Google
  - Fast Development(Hot Reload, etc)
  - Expressive, beautiful UI
  - Native Performance


---?image=assets/dart.png&size=contain

### What’s dart

+++

What's Dart

> Dart is a client-optimized language for fast apps on any platform

https://dart.dev/

+++

- The programming language made by Google
  - Optimizefor UI
  - Productive Development
  - Fast on all platforms
  - Object oriented programing language like JS/Java

---

### How to develop with Flutter

+++

Directory Structure
- lib/ => We write code in this directory mainly
  - main.dart
- test/
- android/
- ios/
- pubspec.yaml

+++

Conpile dart files for...

- iOS
- Android
- Web browser(JS)

---

### What’s DDD

+++

Domain Driven Design
- The process to design software with OOP
  - Value Object
  - Entity(= Domain Object)
  - Service(Domain Service, Application Service)
  - Repository
  - Factory
  - etc

+++

Architectures

- Layered architecture
- Hexagonal architecture
- Onion arthitecture
- Clean architecture

+++

### Onion arthitecture

+++

- Why choose this architecture
  - Simple directory architecture for beginner
  - A lot of useful infomation

https://qiita.com/little_hand_s/items/ebb4284afeea0e8cc752
https://kabochapo.hateblo.jp/entry/2019/11/01/195130

+++

What’s The Onion Architecture

![height=400](assets/onion.png)

https://dev.to/danielrusnok/onion-architecture-or-how-to-not-make-spaghetti-244b

---

### Directory Structure

+++

- lib/
  - application/
  - domain/
  - infrastructure/
  - presentation/
  - main.dart

+++?image=assets/flow.png&size=contain

+++

application(= usecase)

- application/
  - dto/ => data object transfer
  - service/ => application service

+++

domain

- domain/
  - model/ => entity & repository & value object
  - service/ => domain service

+++

infrastructure

- infrastructure/
  - getit/ => setting instance for DI
  - repository/ => detail repositrotry implementation
  - sqflite/ => setting sqlite database

+++

presentation

- presentation/
  - notifier/ => managing state with provider
  - ui/ => set directory with atomic design
    - atoms/
    - molecules/
    - organisms/
    - pages/
    - template/

---

### Pros and Cons

+++

Pros

+++

Compared to BLoC pattern and MVVM...

- Responsibility becomes clear
 - easy to understand directory structure and code
- Repository pattern is very useful
  - pluggable databases

+++

Cons

+++

- Costly to design
- DDD(= OOP) knowledge required

---

### Thank you!

Let's try flutter with DDD!