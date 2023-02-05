---
layout: post
title: "What is wasm"
categories: [blockchain]
image: assets/images/wasm.png
---

WASM has been engineered as an open system that can be utilized in many different web browsers and other contexts. This provides a low-level programming structure that is close to the hardware, allowing coders to write efficient code that can be deployed in the browser. This makes it feasible to import existing code and libraries written in other languages to the web, which shortens the development of complex web applications. 

The web development sector has accepted WASM, and a number of libraries and frameworks have been built to facilitate the composition and operation of WASM code. There is a progressing ecosystem of tools and development settings that assist WASM, making it easier for developers to incorporate and utilize the technology in their work.  

In summary, WASM is a promising technology that could make the web a much more potent platform for a wide variety of applications.

A demonstration of how WASM can advance the speed of a web application is a 2D graphics editor. If the editor was written in JavaScript, it could be slow and sluggish when managing intricate or voluminous graphics. By utilizing WASM, the performance-critical portions of the program, such as image manipulation, can be executed in a lower-level language such as C or C++. The WASM code can then be uploaded and executed on the browser, supplying a considerable gain in execution compared to an identical implementation in JavaScript.

Another example is a game that is written in a high-performance language like C++. By transforming the game to WASM, it can be run in the browser without the requirement for a plugin. This makes it feasible to reach a broader audience by getting rid of the need for users to download and install native software. The game can be played on a variety of devices, including desktop and mobile, and it can be easily integrated with other web-based services, like social networks and cloud.

Example:

```text
const wasmCode = new Uint8Array([ ... ]); // binary code from the WASM compilation
const wasmModule = new WebAssembly.Module(wasmCode);
const wasmInstance = new WebAssembly.Instance(wasmModule);
const result = wasmInstance.exports.add(40, 2);
console.log(result); // 42
```

In this particular situation, the WASM binary is imported into a WebAssembly.Module item and then initiated as a WebAssembly.Instance. The exports property of the instance gives the ability to access the functions defined in the WASM module, which in this case is the add feature. This function can be implemented in the same way as any other JavaScript function and the output can be used in the rest of the program.
