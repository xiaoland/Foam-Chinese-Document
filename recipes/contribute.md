# 贡献指南
- Foam是开源的，并且欢迎任何形式的贡献（包括但不限于代码、文档、想法和反馈）
- 这里有一些关于如何对Foam做出贡献的提示&方法
  - 1、你可以在自己使用Foam的过程中找出需要改进的地方
  - 2、查看[Roadmap](../foam/roadmap.md)了解计划中的内容
  -  3、阅读[Principles](principles.md「原理」来了解Foam的理念与发展方向
  - 4、阅读[Contribution Guide](../recipes/contribution_guide.md)「贡献指南」来了解如何为Foam作出贡献
  - 5、通过[Github iuuses](https://github.com/foambubble/foam/issues)「Github意见」来向我们提供有关新功能的反馈和想法
  - 6、请阅读并遵守我们的[Code of Conduct](../foam/code_of_conduct.md)「行为准则」
  - 7、Foam的代码和文档都可以在[foambuble/foam](https://github.com/foambubble/foam/)下找到
    - [/docs]（已失效），请查看[Recipes](../index.md)
    - [/packages/foam-vscode](https://github.com/foambubble/foam/tree/master/packages/foam-vscode)「Foam的vscode插件」
    - [/packages/foam-core](https://github.com/foambubble/foam/tree/master/packages/foam-core)「在所有平台上增强Foam的核心功能」
  - 但这里面没有：
    - [foambubble/foam-template](https://github.com/foambubble/)「Foam入门模板」
    - 而且其它的推荐扩展都位于它们各自的库中
  
## 为vscode扩展作贡献
- 如果你有兴趣为vscode上的foam扩展作出贡献（又叫做foam-vscode），那么本指南将帮助你在本地对其作出设置
  - 1、将本库克隆到本地：git clone https://github.com/fomabubble/foam.git（也可以用Github Desktop进行克隆，这样管理起来更方便）
  - 2、在根目录下运行这条命令安装依赖：yarn workspace foam-cre build
  - 3、这个项目使用[Yarn workspace](https://classic.yarnpkg.com/en/docs/workspaces/)「Yarn工作区」
    - foam-vscode依赖foam-core，这意味着我们需要在进行任何开发之前对其进行编译，因此，请从根目录运行命令：yarn workspace foam-core build
  - 4、现在，我们将使用.vscode/launch.json中定义的启动配置来启动一个新的vscode扩展主机
  - 5、在新的vscode扩展主机中，打开一个Foam工作区（如您的个人Foam工作区）。不过严格来说，这不是必须的，但这个扩展不会自动运行，除非该扩展位于带有.vscode/foam.json文件的工作区中
  - 6、测试一下命令以确保其能正常运行。打开vscode的命令面板「输入Crtl+Shift+P或View>Command Palette」，然后输入并找到后选择"Foam: Update Markdown Reference List"。如果你没有遇到任何错误，那你就可以开始开发了！
- 有关于vscode扩展的更多信息，请查看：[教程：向vscode扩展添加新命令](https://foambubble.github.io/foam/tutorial-adding-a-new-command-to-the-vs-code-extension)（不是很想翻译，你们喜欢就翻译一下吧，谢谢啦！）