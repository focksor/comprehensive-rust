# Comprehensive Rust 🦀

这个仓库包含了 Comprehensive Rust 🦀 的源码，一个由 Android 团队开发的 4 天 Rust 课程。这个课程涵盖 Rust 从基础语法到泛型和错误处理的所有方面。它还包含了 Android 特有的内容于最后一天。

其他语言版本：[English](README.md), [简体中文](README.zh-CN.md)。

阅读课程于 **https://google.github.io/comprehensive-rust/** 。

（译者注）阅读中文课程于 **https://google.github.io/comprehensive-rust/zh/** 。

## 课程形式和面向受众

该课程在谷歌内部用于向经验丰富的软件工程师教授 Rust。他们通常有 C++ 或 Java 背景。

该课程是在课堂环境中教授的，我们希望它对其他想要向团队教授 Rust 的人有用。这门课对自学来说用处不大，因为你没有经过课堂上的讨论，也看不到问题和答案和我们在代码示例中触发的编译器错误。
我们希望通过
[演讲者备注](https://github.com/google/comprehensive-rust/issues/53) 和
[发布视频](https://github.com/google/comprehensive-rust/issues/52) 改进这一点。


## 构建

这个课程使用 [mdBook](https://github.com/rust-lang/mdBook) 和它的 [Svgbob 插件](https://github.com/boozook/mdbook-svgbob) 构建。
通过以下指令安装这两个工具

```shell
$ cargo install mdbook
$ cargo install mdbook-svgbob
```

然后执行

```shell
$ mdbook test
```

以测试所有包含的 Rust 片段。运行

```shell
$ mdbook serve
```

来启动一个课程的 web 服务器。你可以在 <http://localhost:3000> 找到内容。你可以使用 `mdbook build` 来创建一个静态版本的课程到 `book/` 目录。

## 联系方式

对于问题或评论，请联系 [Martin Geisler](mailto:mgeisler@google.com) 或创建一个 [Github 讨论](https://github.com/google/comprehensive-rust/discussions)。我们会乐于收到你的来信。

