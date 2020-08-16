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

- Multi platform SDK
  - ホットリロード等による高い生産性
  - 高度なカスタマイズが可能なUI
  - ネイティブ並みのパフォーマンス
  - 宣言型プログラミングで書きやすい

---

### What’s dart

+++
What's Flutter

- JSの代替言語としてgoogleが開発
- Object oriented programing language、JSの雰囲気が強い
- JITコンパイルとAOTコンパイルでパフォーマンスの最適化

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
