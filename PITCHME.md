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

+++?image=assets/flutter_logo.png&size=contain

### Flutter with DDD

---

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


---

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

[WIP]The process to compile flutter code to native code

+++

プロジェクト構成

- libのmain.dartが読み込まれる
- lib以下に自由にディレクトリを構成してアプリケーションを作成していく

---

### What’s DDD

+++

Domain Driven Development
- ドメインの知識に焦点を当てた設計手法
- [WIP]各用語の説明

+++

ドメイン駆動設計を実現するための多くのアーキテクチャが存在

- ヘキサゴナルアーキテクチャ
- オニオンアーキテクチャ
- クリーンアーキテクチャ

+++

今回はオニオンアーキテクチャを採用
- 選定理由
  - 設計初心者にもわかりやすいディレクトリ構成
  - 小規模アプリの開発だったので、クリーンアーキテクチャレベルのディレクトリ訳は必要なかった

---

### What’s The Onion Architecture

+++

[WIP]Explain Architecture
- 図を用いながら各層について説明

---

### Directory Structure

+++

[WIP]図を表示しながら各層について説明
- application
- domain
- infrastructure
- presentation

+++

- application
  - dto
  - service

+++

- domain
  - model
  - service

+++

- infrastructure

+++

- presentation
  - notifier
  - ui
    - atoms
    - molecules
    - organisms
    - pages
    - template

---

### Pros and Cons

+++

Pros

+++

Cons

---

### Thank you!
