## Title
Thank you for attending this presentation.
Today, I would like to talk about "Beginner’s guide to Flutter with DDD"

## Self Intoroduction
At first, let me introduce myself.
My name is Masataka Ushijima and I am software engineer.
I work at Leverages, HR company in Tokyo, Japan.
Recently I have made native app with flutter in my job.
In my free time, I like traveling around the world, training, and customize notion.
I lived in gaogao tokyo until 03/2020.

## Today's topic
So, Today's topic is flutter with DDD.
I started learning about flutter and DDD two month ago.
Today, I would like to share my knowledge with you.

[TODO][低]目次

## What's Flutter
At first, What is flutter.

The official site defines as follows:

"Flutter is Google's UI toolkit for building beautiful,
natively compiled applications for mobile, web,
and desktop from a single codebase"

It means that flutter is toolkit for making native app.

The benefits of using flutter are
- fast development, for example, you can use hot reload
- expressive, beautiful UI
- native performance

## What's Dart
So, next, what's dart.

The official site defines as follows:
"Dart is client-optimized language for performance fast apps on any platform."

The benefits of using dart are
- optimize for UI
- productive development
- fast on all platforms
- OOP like JS

If you use dart with flutter, you can make native apps fastly.

Today's topic is DDD, so if you want to know about dart and flutter more, let's visit official site. It's very easy to understand.

## How to develop with Flutter
Initial directory looks like this.
We mainly write codes in lib directory.
In this directory, you can make directory and files freely.
you should make structure of ddd in this directory.

When you compile files, you can use app in ios, android, web browser.

## what' ddd
DDD is the process to design software with Object oriented programming.
I think it is almost Object oriented design.
There are a lot of concept like this.

We can choose architecture when I use DDD.

This project, I chose onion architecture.

because
- simple directory architecture for begineer
- a lot of useful infomation on website

This image shows how onion architecture works.
Domain is center, and presentation, infrastructure depends on application, and application depends on domain. it's unidirectional.

## Directory structure
In my flutter project, directory structure looks like this.
I would like to introduce this structure.

Call flow begin from presentation like this image.
Ui calls notifier
notifier calls application service
application service calls domain service
domain service calls repository

Data flow begin from concrete databases like this image.
[WIP]
Infrastructure implements repository and called by domain service

Let's see this architecture in detail.

At first application directory.
There are two directory
[WIP]
Dto is making data object for ui.
Service is usecase.

Second domain directory.
There are two directory.
[WIP]
Model includes entity, repository and value object.
Service is domain service.

Third infrastructure directory.
There are three directory.
Getit is for di container and make repository as singleton object.
Repository is detail repository implementation
Sqflight is setting database for sqlite.

Last presentation diretory.
There are two directory
Notifier is for managing state with provider pattern.
Ui is for view directory with atomic design.

## Pros and Cons
At last, I would like to share Pros and Cons.

Pros is as follows:
- Responsibility becomes clear
  - it is easy to understand directory structure and codes

Cons is as follows:
- It consumes time and energy to design
- DDD(= OOP) knowledge is required

## thank you
This is all for my presentation.
Thank you.
