# 使用GitHub Copilot开发销售报表系统

[English](./README_EN.md) | 中文版

## 概述
处理数据是大多数商业应用中最重要的部分，数据往往代表某种特定的业务对象，比如：用户，产品，订单，销售额。商业应用中的业务逻辑也和数据直接相关。Copilot 理解和处理数据的能力直接关系到 生成式AI 在业务开发场景中的实战价值。

## 项目背景
在本示例中，我们将以 销售报表系统 为例，利用 Copilot 完成数据结构建模，样例数据生成，数据统计和数据展示这几个环节的代码生成。通过这个示例，开发者可以了解使用 Copilot 处理业务数据和业务逻辑的关键实践和技巧。
我们将在不同的关节中使用 代码补全 和 Chat 能力来完成不同的代码生成任务，最终构建一份清晰可读的 销售报表

## 环境需求
你需要准备以下环境以便可以顺利的完成此实验：
- Windows 10/11 或者 MacOS
- Git 2.45 以上版本以及你所熟悉的Git客户端
  - 下载地址：https://git-scm.com/
- Visual Studio Code 1.90 版本以上
  - 下载地址：https://code.visualstudio.com/
- GitHub Copilot 和 GitHub Copilot Chat 扩展 更新到最新版本。
  - 下载地址：https://marketplace.visualstudio.com/items?itemName=GitHub.copilot
- .Net 7.0 开发环境和对 C# 编程语言的基本了解
  - 下载地址：https://dotnet.microsoft.com/en-us/download/dotnet/7.0
  - 请下载对应的操作系统上的SDK版本
  - 必须安装和使用SDK而不是Runtime
- C# Dev Kit 扩展
  - 下载地址：https://marketplace.visualstudio.com/items?itemName=ms-dotnettools.csdevkit
- 熟悉类、方法、变量和逻辑语句

> 关于开发语言的特别说明：虽然本示例采用C#语言，但是同样适用于任何编程语言背景的开发人员。由于GitHub Copilot支持基本上任何主流的开发语言，因此本示例中所展示的各种操作和技巧适用于任何开发语言环境。

## 配置开发环境
一旦您按照 环境需求 安装好基础软件，就可以获取代码库并配置开发环境了。

```shell
git clone https://github.com/smartcode-workshops/sales-report
```

按照以下操作获取代码并启动开发环境
1. 打开 Visual Studio Code，然后在“开始”菜单下单击“克隆 GitHub 存储库”。
2. 在“从 GitHub 克隆”字段中，输入 代码库地址，然后单击“从 URL 克隆”：
3. 在弹出窗口中，创建一个新文件夹，并选择其作为存储库目标。
4. 等待项目下载完成，然后打开该项目。
5. 可能需要确认你信任项目的作者才能使该项目运行。
6. 展开 sales-report 文件夹并打开 Program.cs。

## 联系我们

如果您在使用 AI编码助手 的过程中遇到任何问题，或者您有任何建议和反馈，请随时联系我们。您可以通过以下方式联系我们：

    网址 https://leansoftx.com
    电子邮件 info@leansoftx.com
    微信公众号 DevOps
