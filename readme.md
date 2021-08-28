## 关于模板库

[PDF 下载](https://github.com/onglu1/template/blob/gh-pages/template.pdf)

forked from [F0RE1GNERS/template](https://github.com/F0RE1GNERS/template)

自动生成pdf，上传markdown就行了。 

## 代码特性

+ 优先保证代码简洁和可读性，其次是常数
+ 代码尽量用 `namespace` 封装
+ 轻度压行
+ 使用 `template` 来复用代码
+ 代码符合 C++11 标准，且至少需要 C++11


## 关于 PDF

+ 使用 pandoc 和 LaTeX 生成
+ 代码高亮使用 minted

## 使用方法  
+ 更改workflows中的相关链接，改成自己的仓库地址。  
+ 在Setting - Secrets中加入一个ACCESS_TOKEN秘钥，是自己的Personal access tokens。  
+ 更改master分支之后，会自动创建action在/template/tree/gh-pages下生成template.pdf文件  
