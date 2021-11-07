# ProceedSmiling - Generics without Type Erasure in Javali

## Purpose
This repository contains the main project of the ETH course 'Advanced Compiler Design' from the Computer Science Master's curriculum.
The project's goal was to extend the compiler of a subset of Java, called Javali, by a new language feature.
We extended Javali's compiler with support for generics without type erasure.
The source code is not publicly available but might be requested from the [ETH Laboratory of Software Technology](https://www.lst.inf.ethz.ch/).

## Abstract
Generics as in Java and C# or templates in C++ parlance are
a powerful language feature in many common object oriented
programming languages. We introduce generics with
syntax and semantics inspired by Java’s generics to Javali,
a programming language used in the Bachelor’s Compiler
Design course at ETH Zurich. Our implementation features
new symbol types enabling type checking in the presence of
generic types, as well as a type inference facility that greatly
enhances the usability of generics. Moreover, in contrast to
Java, we do not use type erasure. Instead, we consider each
generic instantiation a separate type and present a novel
approach called runtime type tracking allowing us to emit
code of a generic class or method only once, independent of
the number of instantiations
