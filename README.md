# Usage

Run "make" in shell and have fun.
Use "<TeX>" "</TeX>" to escape to TeX.

可以在Windows上正常工作，需要安装字体Liberation Mono。Linux和Mac下需要自行改动字体。
建议使用最新版本xeCJK避免代码中英混排的BUG，如果没有条件的话可以加空格解决。

代码全扔src目录里即可，里面可以有子目录，子目录和文件名前面都可以带数字表示顺序。

扔.tex文件进去可以直接include进去。

--------

以上是原版描述，出处貌似[是这里](https://post.icpc-camp.org/d/108-yy)。然而好像都崩了。。这里作下备份，顺便更新下使用说明。

1. 安装[CTex](http://www.ctex.org/CTeXDownload)
2. 安装字体Liberation Mono
3. 在src文件下新建目录作为次级标题，再往次级目录下放代码文件。src目录下放貌似会boom
4. 运行make.bat即可