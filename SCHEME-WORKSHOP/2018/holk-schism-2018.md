# [Schism: A Self-Hosting Scheme to WebAssembly Compiler](holk-schism-2018.pdf)

By Eric Holk

## Abstract

Schism is a small, self-hosting compiler from a subset of R6RS Scheme
to WebAssembly, a new portable low-level binary format primarily
targeting Web applications. The compiler was under one thousand lines
of code when it first became self-hosting, and has since grown to
support additional Scheme features. While currently far from a
complete Scheme, Schism supports basic control flow, most basic data
types and first class procedures. Schism provides an example of a
small implementation of a language targeting WebAssembly and
demonstrates techniques that may be useful to other languages
implementors. As a dynamically typed functional programming language,
Scheme is markedly different than languages with good WebAssembly
support, like C and C++, and thus shows that WebAssembly has achieved
its goal of being able to support a variety of languages. Still,
Schism would greatly benefit from new capabilities in WebAssembly such
as a proper tail call instruction and garbage collection. Given
Schism’s small size, it is well-positioned to provide early
implementation experience to the WebAssembly standardization process
for these new features. In this paper we will discuss the design and
implementation of Schism, including compromises made to enable a quick
and small implementation, as well as plans for future development on
Schism and influence on the WebAssembly standard.

## Keywords

- Web Assembly
