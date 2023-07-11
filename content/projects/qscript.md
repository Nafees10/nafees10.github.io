---
title: "QScript"
date: 2023-07-11T11:37:06+05:00
tags: [ "projects", "qscript" ]
---

QScript is a Simple Scripting Language, written in the D Programming Language.

The entire compiler pipeline (lexer, parser, code generation) has been written
as part of the project. The compiler outputs bytecode which is executed using
`NaVM` (see below).

The goal is to be fast enough while also being simple and fun to write and read.
Currently, it is being re-written under a redesigned spec.

The new spec includes:

* modules
* public / private module members
* first class functions
* lambda functions
* reference data types
* compile time function execution
* conditional compilation
* metaprogramming
