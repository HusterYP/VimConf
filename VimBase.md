9. Vim基础操作
> 1. 关于Vim的配置可以参加`Notes`中的`Vim.md`笔记
> 2. 可以在Vim命令模式下(即在终端输入`vim`之后即可),通过输入`:h xxx`,可以查看xxx的所有文档,如查看`ctags`的文档: `:h ctags`
> 3. `:n`可以跳转到指定行
> 4. `Ctl+Shift+n`可以打开新的命令行窗口
> 5. `u`可以撤销上一步操作,`Ctl+r`可以回复上一步被撤销的操作
> 6. `Ctl+o`可以返回上一次编辑位置
> 7. `set foldmethod=indent`,设置函数折叠,还可以有其他折叠方式,[参见博客](http://www.cnblogs.com/abeen/archive/2010/08/06/1794197.html)
> 8. 自定义快捷键的时候,`inoremap`和`vnoremap`等表示的是在不同的模式下起作用(如前面的两个分别是`Insert`模式和`Visual`模式下)
> 9. `gg`可以跳转到文件头,`shift+g`可以跳转到文件末尾,`n+gg`可以跳转到第n行
> 10. 使用`:sp + 文件名`可以水平分割窗口
> 11. 使用`:vs + 文件名`可以垂直分割窗口  
> 12. 对于包含头文件的C/C++项目,可能直接使用快捷键编译运行不行,可以通过命令行`gcc -Wall main.c other.c -o main`或者`g++ -Wall main.cpp other.cpp -o main`
> 13. 对于C/C++的编译和运行,同样对于12的问题,可以直接在Vim窗口中使用`Asycrun gcc -Wall *.c -o  main`来编译和运行;当然,也可以通过自己编写`Makefile`文件来使用make命令来执行,关于make的使用可以[参见博客](http://www.ruanyifeng.com/blog/2015/02/make.html)
> 14. 在Vim中可以通过`:pwd`来查看当前所在目录,同时可以通过`:cd path`来切换路径
> 15. 使用`Ctl+F`可以搜索文件,可以方便的打开其他文件
* 关于折叠: `zr`为打开折叠,`zm`为关闭折叠,都是以当前光标开始处,`zc`为开始折叠,与`zm`对应,同时`zn`可以打开所有折叠;可以通过在vim中使用`:h Folding`来查看折叠的帮助文档;
* 进入vim的可视模式,可以选择文本;`v`可以进入`visual`模式,之后可以逐个字符选择文本;`V`之后可以逐行选择文本;`Ctl+v`可以按照块的方式选择文本
* 关于`Vim`复制粘贴: http://stefan321.iteye.com/blog/1542678
