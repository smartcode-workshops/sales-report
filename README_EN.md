# Develop a sales report using Copilot

[中文版](./README.md) | English

## Overview
Processing data is the most important part in most business applications. Data often represents specific business objects, such as users, products, orders, and sales amounts. The business logic in business applications is also directly related to data. The ability of Copilot to understand and process data is directly related to the practical value of generative AI in business development scenarios. 

## Project Background
In this example, we will take the "sales report system" as an example and use Copilot to complete the code generation for several links such as data structure modeling, sample data generation, data statistics, and data display. Through this example, developers can understand the key practices and techniques of using Copilot to handle business data and business logic. We will use the code completion and Chat capabilities in different joints to complete different code generation tasks and ultimately build a clear and readable sales report. 

## Requirements 
You need to prepare the following environment in order to successfully complete this experiment: 
- Windows 10/11 or MacOS
- Git version 2.45 or above and the Git client you are familiar with 
  - https://git-scm.com/
- Visual Studio Code 1.90 or above
  - https://code.visualstudio.com/
- GitHub Copilot and GitHub Copilot Chat extensions
  - https://marketplace.visualstudio.com/items?itemName=GitHub.copilot
- The.Net 7.0 development environment and the basic understanding of the C# programming language 
  - https://dotnet.microsoft.com/en-us/download/dotnet/7.0
  - Please download the SDK version on the corresponding operating system 
  - Use the SDK instead of the Runtime 
- C# Dev Kit Extension
  - https://marketplace.visualstudio.com/items?itemName=ms-dotnettools.csdevkit
- Be familiar with classes, methods, variables and logical statements 

> Note on the development language: Although this example uses the C# language, it is also applicable to developers with any programming language background. Since GitHub Copilot supports basically any mainstream development language, the various operations and techniques demonstrated in this example are applicable to any development language environment. 

## Prepare the development environment 
Once you install the basic software as per the environmental requirements, you can obtain the code repository and configure the development environment. 

```shell
git clone https://github.com/smartcode-workshops/auto-suggest-csharp
```

Obtain the code and start the development environment by following the following operations 
1. Open Visual Studio Code and then click "Clone GitHub Repository" under the "Start" menu. 
2. In the "Clone from GitHub" field, enter the code repository address and then click "Clone from URL": 
3. In the pop-up window, create a new folder and select it as the repository destination. 
4. Wait for the project to be downloaded completely and then open the project. 
5. It may be necessary to confirm that you trust the author of the project in order to make the project run. 
6. Expand the TrieDictionary folder and open Program.cs. 

## Contact
If you encounter any problems in the process of using ** AI Coding Assistant **, or if you have any suggestions and feedback, please feel free to contact us. You can contact us in the following ways:

    website: https://leansoftx.com
    email: info@leansoftx.com
    wechat channel: DevOps
