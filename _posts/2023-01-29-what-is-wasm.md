---
layout: post
title: "What is wasm"
categories: [blockchain]
image: assets/images/wasm.png
---

WASM has been designed to be an open standard that can be supported by multiple web browsers and other environments. It provides a low-level programming model that is closer to the hardware, enabling developers to write high-performance code that can run efficiently in the browser. This makes it possible to bring existing code and libraries written in other languages to the web, making the development of complex web applications faster and easier.

WASM has been embraced by the web development community, and many libraries and frameworks have been created to make it easier to write and run WASM code. There is a growing ecosystem of tools and development environments that support WASM, making it easier for developers to adopt and use the technology in their work.

Overall, WASM is a promising technology that has the potential to make the web a more powerful platform for a wide range of applications.

An example of using WASM to improve performance in a web application would be a 2D graphics editor. A graphics editor written in JavaScript can be slow and unresponsive when handling large or complex graphics. By using WASM, the performance-critical parts of the application, such as image processing, can be implemented in a lower-level language such as C or C++. The WASM code can then be loaded and run in the browser, providing a significant boost in performance compared to an equivalent implementation in JavaScript.

Another example is a game that is written in a high-performance language such as C++. By compiling the game to WASM, it can be run in the browser without the need for a plugin. This makes it possible to reach a wider audience by eliminating the need for users to download and install native software. The game can be played on a variety of devices, including desktop and mobile, and it can be easily integrated with other web-based services, such as social networks and cloud storage.

Example:

```text
const wasmCode = new Uint8Array([ ... ]); // binary code from the WASM compilation
const wasmModule = new WebAssembly.Module(wasmCode);
const wasmInstance = new WebAssembly.Instance(wasmModule);
const result = wasmInstance.exports.add(40, 2);
console.log(result); // 42
```

In this example, the WASM binary is loaded into a WebAssembly.Module object and then instantiated as a WebAssembly.Instance. The exports property of the instance provides access to the functions defined in the WASM module, in this case the add function. The function can be called just like any other JavaScript function, and the result can be used in the rest of the application.
