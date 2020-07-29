# 如何使Foam正确地自动补全你的链接
- Foam的文件自动补全功能由[Markdown Notes](https://marketplace.visualstudio.com/items?itemName=kortina.vscode-markdown-notes)提供。Markdown Notes在默认情况下会建议你在文件名末尾添加.md后缀，如下图：
- ![sample_img](https://foambubble.github.io/foam/assets/images/md-notes-autocomplete-with-extension.png)
- 要更改这个行为，请在.vscode/setting.json中添加如下内容：
  - "vscodeMarkdownNotes.noteCompletionConvention": "noExtension"
- 更改之后，你的键入建议就会如下图所示：
- ![sample_img](https://foambubble.github.io/foam/assets/images/md-notes-autocomplete-no-extension.png)
  
## 注意事项
- 如果你是在2020/7/27号之后使用官方的[foam-template](https://github.com/foambubble/foam-template)「Foam模板」创建的，那么这个设置应该已经设置好了