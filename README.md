# Beamer Template for the Central South University

## 欢迎使用中南大学Beamer幻灯片模板

本示例模板是应用中南大学（非官方）LaTeX 文档类 CSUBeamer 的一个完整实现。演示了排版中常用的例子，包括公式、表格、参考文献等。 用户可以参考或者直接基于此示例文档制作Beamer。

请注意 CSU_Beamer目前仅支持 XeTeX 引擎，字符编码仅支持 UTF-8。

## Instructions of using
1. 下载并安装 MikTex或者protext；
2. 下载本模板文件（使用 ```git``` 命令或在[这里下载](https://github.com/HexaMPA/CSU_Beamer/releases)）；
3. 编写 ```.tex``` 文件；
4. 使用 ```XeLaTeX``` 编译（当前仅支持 ```XeLaTeX``` 方式编译，已在 ```Win10 + MikTex 2.9 ```和 ```MacOS Catalina + MacTex 2021``` 平台上测试）。在Mac上使用时需要更换字体。

## Acknowledgment

- 感谢[CSUThesis](https://github.com/ChaoYan/CSUThesis)项目提供了图片和表格代码和thesis.bib文件
- 感谢[SEUBeamerTemplate](https://github.com/njustwh2014/SEUBeamerTemplate)提供了图文混排的解决思路
- 感谢[CCNU_BeamerTemplate](https://github.com/K-JW/CCNU_BeamerTemplate)提供的sty文件
- 感谢中南云麓谷提供的校徽蓝ppt模板



## 模板使用

如果你不熟悉 LaTeX 的编译流程，请**不要**直接使用编译器进行编译。

### VSCode 用户

安装“LaTeX Workshop”插件后，选择“Recipe: latexmk (latexmkrc)”编译。您可以在插件设置中设置

```
{
  "latex-workshop.latex.recipe.default": "lastUsed"
}
```

从而在每次保存时自动使用这个 Recipe 进行编译。

### TexStudio用户

使用XeLaTex-BibLaTex-XeLaTex-XeLaTex编译



## 软件许可证

中南大学校徽校名图片（`logo.png` 等）的版权归中南大学所有。

 `biblatex-gb7714-2015` 样式文件使用 [LPPL](https://www.latex-project.org/lppl.txt) 授权。

字体使用开源字体，使用SIL授权。

其他部分使用 [MIT](https://github.com/HexaMPA/CSU_Beamer/blob/main/LICENSE) 授权。

## 更新日志
* 2021-7-9 :
  * v1.0 
    * 第一版发布在 GitHub 上

