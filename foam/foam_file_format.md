# Foam文件格式标准
- [本页面](https://foambubble.github.io/foam/foam-file-format)就是一个有效的Foam文件示。当然，从本质上来看，这只是个markdown文件，并且对mediawiki样式[[wiki-links]]有一些额外的支持。
- 这里有些限制，主要是因为我们的工具有些零散。而其中的大多数都应在最后时被取消，因为我们的要求应该只是“有[[wiki-links]]的markdown”
- 接下来，就是关于Foam文件的格式了。

## 正文
- 首先，每个Foam文件必须有一个最顶级标题：# Heading
  - 这将会被用作一个文章的标题
- 第二，文件名不应有空格的存在：foam-file-format.md才是一个有效的名字，而不是foam file format.md
  - 其实这是个临时的限制，它将在之后的版本中被取消
  - 从技术上讲，你已经可以将空格包含在文件名中，但为了避免一些您不想处理的极端状况，我们不推荐您这么做
- 第三，文件名后缀应为.md或.markdown
  - 这也是个临时限制，在将来的版本中，它将会被取消
  - 在未来，至少将支持.mdx，但在理想情况下，我们希望能够支持任何能在vscode中映射为markdown语言的文件
- 最后，除了常规的markdown链接外，您还可以使用如[[media-links]]这样的链接。
  - 更多详细信息，请参考[Wiki Links](foam/wiki_links.md)「维基链接」