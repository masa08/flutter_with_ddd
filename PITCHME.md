### Beginner’s guide to Flutter with DDD

2020/08/25

Masataka Ushijima

---

### Self Introduction

- Name
  - Masataka Ushijima
- Company
  - Leverages.inc
- Work
  - Making native app with Flutter.
- Hobby
  - Traveling
  - Training
  - Customize Notion

---

### Today's topic

+++

### Flutter with DDD

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

+++

Example Code

[WIP]宣言的にウィジェットを重ねてアプリを構築することがわかるような資料


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

+++

Example Code

Object oriented programing language like JS

[WIP]dartの特徴がわかるクラスのコードを書く

---

### How to develop with Flutter

+++

Directory Structure
- lib/
  - We write code in this directory mainly
- test/
- android/
- ios/
- pubspec.yaml

+++

Conpile dart files for...

- iOS
- Android
- Web browser

---

### What’s DDD

+++

Domain Driven Design
- The process to design software with OOP
  - Entity
  - Value Object
  - Service
  - Repository
  - Factory

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

[WIP]各層で何をしているのかを完全に理解する

+++

- application/
  - dto/
  - service/

+++

- domain/
  - model/
  - service/

+++

- infrastructure/
  - getit/
  - repository/
  - sqflite/

+++

- presentation/
  - notifier/
  - ui/
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

[WIP]他の設計と比較した時にDDDの何がいいのかを語る

+++

Cons

+++

[WIP]他の設計と比較した時にDDDの何がいいのかを語る

---

### Thank you!
