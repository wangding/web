# 第 12 章：JavaScript 概述

## 阅读参考资料

- [JavaScript 概述](https://developer.mozilla.org/zh-CN/docs/Web/JavaScript/Guide/Introduction)

## 掌握 Chrome Snippets 用法

要求：
- 打开 Chrome 浏览器
- 打开开发者工具（快捷键：F12），将开发者工具窗口脱离停靠，并将窗口最大化
- 在开发者工具中选择 Sources 选项卡
- 观察开发者工具的界面，分三栏：左侧导航窗格，中间代码编辑窗格，右侧代码调试窗格
- 左侧导航窗格切换到 Snippets 窗格
- 在 Snippets 窗格中，添加一个 Snippet（点击：+ New snippet）
- 将 Snippet 改名为 hello-world（在 Script Snippet #n 上点击鼠标右键，点击 Rename... 菜单项）
- 在中间的代码编辑窗口，输入代码：`console.log('hello world');`，保存代码（快捷键：Ctrl+S）
- 运行这个 Snippet（快捷键 Ctrl+Enter），运行结果在下方的 Console 窗格，运行代码会自动保存代码
- 运行 Snippet 后，焦点在 Console 窗口，清除 Console 窗口内容的快捷键：Ctrl+L
- 焦点在 Console 窗口时，Ctrl+Enter 会再次运行 Snippet，ESC 快捷键会隐藏 Console 窗格
- 在左侧窗格，鼠标右击 Snippet 名称，浮动菜单中，可以将 Snippet 另存为，本地代码文件（扩展名为：js）
- 左侧导航窗格切换到 Filesystem 窗格
- 在 Filesystem 窗格中，打开保存的本地代码文件，这里只能查看代码，不能运行代码
- 如果没有特殊说明，后续 JavaScript 练习，都在 Snippet 环境中编写、运行和调试
