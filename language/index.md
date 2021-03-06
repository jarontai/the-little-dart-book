# 语言

本章主要介绍 Dart 语言的基础知识，包括但不限于：变量、函数、类、泛型、库、异步及并发等。

## 重要概念

在开始之前，先了解几个 Dart 的重要概念

* Dart 中“万物皆对象”，数字、函数甚至`null`也是对象
* Dart 支持顶层变量和函数，Dart 文件执行的入口是顶层的`main`函数
* Dart 的可见性控制是库（library）级别的，而且没有 public/protected/private 等访问控制符
* Dart 1.x 使用可选类型，从 Dart 2.0 开始，类型不再可选（强类型）
* Dart 具备类型推导能力，即使从2.0开始变成强类型语言，在很多场景下还是可以使用`var`来声明变量

---

\* 本书示例代码都假设是在`main`函数中运行（代码中出现了`main`函数的除外）。

\* 本书示例大量使用了 Dart 核心库的`print`函数，用于打印输变量/表达式的内容。

\* 本书示例使用了部分出自游戏《黑暗之魂》(Dark Souls) 的概念和名词。
