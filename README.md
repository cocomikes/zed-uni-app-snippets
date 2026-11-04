# uni-app Snippets for Zed

为 Zed 提供 [uni-app](https://uniapp.dcloud.net.cn/) 基本能力代码片段，内容参考并同步自 [`uni-app-snippets-vscode`](https://github.com/uni-helper/uni-app-snippets-vscode)。

## 已支持的语言

- Vue / HTML
- CSS / Less / SCSS / Sass / Stylus
- JavaScript / TypeScript
- JSON with Comments（`jsonc`，可用于 `pages.json`）

## 安装（本地开发）

将本目录放入 Zed 的扩展开发目录，或在 Zed 中使用 **Install Dev Extension** 指向本目录：

```text
/Users/mikes/projects/Zed/extension/zed-uni-app-snippets
```

安装后，在对应语言文件中输入片段前缀即可触发补全。Zed 当前只使用每个片段 `prefix` 数组中的第一个前缀，因此扩展保留 VS Code 片段的第一个前缀作为主触发词。

## 说明

本扩展不包含运行时代码，仅提供 snippets。原始片段及其文档、许可证归 [`uni-app-snippets-vscode`](https://github.com/uni-helper/uni-app-snippets-vscode) 项目及其作者所有。
