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
