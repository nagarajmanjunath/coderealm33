---
layout: post
title: "System runtime vs Wasm runtime"
categories: [wasm]
image: assets/images/System.jpg
---

System runtime and WebAssembly (Wasm) runtime are two different types of runtime environments, designed to execute different types of code. Here are some of the key differences between these two types of runtime:

1.Programming language: System runtimes are designed to execute code written in system-level languages such as C, C++, and Rust, while Wasm runtimes are designed to execute code written in the Wasm binary format, which can be generated from a variety of programming languages.

2.Security: System runtimes typically provide low-level access to system resources and can pose a security risk if the code running on them is not properly sandboxed or isolated. Wasm runtimes, on the other hand, are designed to execute code in a secure sandboxed environment that isolates the code from the host system's resources and ensures that it cannot perform any unauthorized operations.

3.Portability: System runtimes are platform-specific and require different versions for different operating systems and hardware architectures. Wasm runtimes, on the other hand, are designed to be portable and can be executed on a wide range of platforms, including web browsers, server environments, and even embedded systems.

4.Performance: System runtimes typically provide low-level access to system resources and can be optimized for performance, but this requires a lot of effort and expertise. Wasm runtimes, on the other hand, are designed to be executed in a highly optimized virtual machine that can be run efficiently on a wide range of platforms.

In summary, system runtimes and Wasm runtimes are two different types of runtime environments designed to execute different types of code. While system runtimes provide low-level access to system resources and can be highly optimized for performance, they also pose a security risk and are platform-specific. Wasm runtimes, on the other hand, provide a secure, portable, and efficient way to execute code written in a variety of programming languages.
