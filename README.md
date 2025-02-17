# WebVM

This repository hosts the source code of for [https://webvm.io](https://webvm.io), a Linux virtual machine that runs in your browser.

<img src="assets/welcome_to_WebVM_slim.png" width="70%">

WebVM is a server-less virtual environment running fully client-side in HTML5/WebAssembly. It's designed to be Linux ABI-compatible. It runs an unmodified Debian distribution including many native development toolchains.

WebVM 是在 HTML5/WebAssembly 中完全在客户端运行的无服务器虚拟环境。它被设计为与 Linux ABI 兼容。它运行一个未经修改的 Debian 发行版，包括许多本地开发工具链。


WebVM is powered by the CheerpX virtualization engine, and enables safe, sandboxed client-side execution of x86 binaries on any browser. CheerpX includes an x86-to-WebAssembly JIT compiler, a virtual block-based file system, and a Linux syscall emulator. 

WebVM 由 CheerpX 虚拟化引擎提供支持，可在任何浏览器上实现 x86 二进制文件的安全、沙盒客户端执行。 CheerpX 包括一个 x86-to-WebAssembly JIT 编译器、一个基于虚拟块的文件系统和一个 Linux 系统调用模拟器。


# How to: general usage

- go to [https://webvm.io](https://webvm.io)
- use the provided terminal environment
- have fun!

# How to: enable networking

- go to [https://webvm.io](https://webvm.io)
- click "Tailscale Login" in the top right corner
- log in to Tailscale (create an accout if you don't have one)
- if you want to access the public internet, you need an Exit Node. See [here](https://tailscale.com/kb/1103/exit-nodes/) for how to set one up. If you just want to access a machine in your Tailscale Network, you don't need it
- depending on your network speed, you may need to wait a few moments for the Tailscale Wasm module to be downloaded
- log in with your Tailscale credentials
- go back to the WebVM tab. You will see your IP address in the top right
- start firing network requests!

# Bugs and Issues

Please use [Issues](https://github.com/leaningtech/webvm/issues) to report any bug.
Or come to say hello / share your feedback on [Discord](https://discord.leaningtech.com).

# Browsers support

WebVM and CheerpX are compatible with any browser, both Desktop and Mobile, provided support for [SAB](https://caniuse.com/sharedarraybuffer), [IndexedDB](https://caniuse.com/indexeddb), and the device having enough memory.

# More links

- [Do: WebVM](https://webvm.io)
- [Read: WebVM](https://leaningtech.com/webvm-server-less-x86-virtual-machines-in-the-browser/)
- [Read: WebVM + Tailscale networking](https://leaningtech.com/webvm-virtual-machine-with-networking-via-tailscale/)
- [Learn: WebVM](https://leaningtech.com/webvm)
- [Watch: WebVM at GitNation](https://www.youtube.com/watch?v=VqrbVycTXmw)

# Thanks to... 
This project depends on:
- CheerpX, made by [Leaning Technologies](https://leaningtech.com) for the virtualization part
- xterm.js, [https://xtermjs.org/](https://xtermjs.org/), for providing the Web-based terminal emulator
- [Tailscale](https://tailscale.com/) for the networking component
- [lwIP](https://savannah.nongnu.org/projects/lwip/) for the TCP/IP stack, compiled to the Web by [Cheerp](https://github.com/leaningtech/cheerp-meta)

# License
Copyright (c) Leaning Technologies Limited. All rights reserved.
# cowsay "thanks you"
 
- thanks you -
-------------
        \   ^__^
         \  (oo)\_______
            (__)\       )\/\
                ||----w |
                ||     ||
