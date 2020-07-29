# 维基链接
- Foam允许您使用[[file-name]]的形式（如：[[media-wiki]]）来将页面连接在一起
- 也就是各个文件之间的链接，反向链接则是一个文件内的（盲猜）

## 详细内容
- 输入"[["然后输入文件名，等待自动完成
  - 请注意，你输入的文件名应该记录在lower-dash-case.md中，并且你的维基链接应该完全引用文件名[[lower-dash-case]]，而不是[[Lower Dash Case]]
  - 请查阅[Link Formatting and Autocompletion](link_formatting_and_autocompletion.md)「链接的格式和自动完成」来了解更多信息。如：如何设置你的链接自动完成功能并以此使操作变得更加容易
- 通过Crtl/Cmd + Click(单击)一个文件名来导航到这个文件（如果你的光标在文件名上，你也可以按F12）
- 但如果你使用此方法点击了一个不存在的文件名，那么它将会被创建

## 示例
- 所谓的维基链接其实就是"[[xxxxx]]"这样的一串文字，"xxxx"就是链接到的文件的文件名!!!注意不要加扩展名!!!
- 通过Crtl+单击就可以对这样的链接进行操作，存在则导航，不存在则创建
- 我个人认为上面说的那一段「要记录在lower-dash-case.md中」是不必要的（其实是无法理解怎么做，但似乎也没有影响）

## Markdown兼容性
- Foam将会自动在文件的底部生成[Link Reference Definitions](link_reference_definitions.md)「链接的参考定义」，并以此使维基链接来兼容Markdown工具和解释器

## 要求的扩展
- [Markdown Notes](https://marketplace.visualstudio.com/items?itemName=kortina.vscode-markdown-notes)「Markdown笔记」
- [Foam for VSCode](https://marketplace.visualstudio.com/items?itemName=foam.foam-vscode)「vscode上的Foam」

## 查看更多
- [Foam File Format](foam_file_format.md)「Foam的文件格式标准」
- [Link Formatting and Autocompletion](link_formatting_and_autocompletion.md)「链接的格式和自动完成」
- 查看[Link Reference Definition Improvements](https://foambubble.github.io/foam/link-reference-definition-improvements)来为当下的问题和解决方案进行讨论（懒得翻译了，大家喜欢就翻译一下吧(๑•ᴗ•๑)）