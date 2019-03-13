# Lexikon der Kulturellen Unterschiede
Lexikon der  Kulturellen Unterschiede 是一部整理记录了中德文化差异的小册子。主要使用xeLatex排版引擎，分为中德文两本。更多内容在本项目的[Wiki](http://118.25.137.24:8080)页面呈现。

###生成册子

1.**软件需求**：**Texlive** (推荐2017版以上）

-  [官方站点](http://mirror.ctan.org/systems/texlive/Images/texlive2018.iso) 
- [清华大学镜像站](https://mirrors.tuna.tsinghua.edu.cn/CTAN/systems/texlive/Images/texlive2018.iso) 
- [中国科技大学镜像站](https://mirrors.ustc.edu.cn/CTAN/systems/texlive/Images/texlive2018.iso)

2.**生成pdf文档**

- **使用make**  (only Linux)

	中文：
	
			$ make cn
			$ make clean
			
	Deutsch:
	
			$ make de
			$ make clean
			
-  **xeLatex**:

	中文：		
	
			xelatex Lexikon_der_kulturellen_Unterschiede_CN.tex
	
	Deutsch：
	
			xelatex Lexikon_der_kulturellen_Unterschiede_CN.tex