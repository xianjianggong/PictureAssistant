# 第三方许可证 / Third-Party Licenses

本项目在 `screenshot-tool/fabric.min.js` 中包含了 Fabric.js 库。

## Fabric.js

- 版本：5.3.0（cdnjs 分发版本；注意该文件内部 `fabric.version` 常量误标为 `5.1.0`，已核实内容确为 5.3.0）
- 官网：https://fabricjs.com/
- 仓库：https://github.com/fabricjs/fabric.js
- 许可证：MIT License

依据 MIT 许可的要求，随分发一并提供 Fabric.js 的许可证全文如下：

~~~text
MIT License

Copyright (c) 2008-2015 Printio (Juriy Zaytsev, Maxim Chernyak)

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
~~~

> ⚠️ 升级提醒：Fabric.js **6.0 及以上版本**许可证变更为 **MIT + OFL-1.1 双许可**（引入了字体相关代码，字体部分采用 SIL Open Font License）。本项目使用的 5.x 为纯 MIT，可自由打包分发；若将来升级到 6.x，请重新审查许可证要求。
