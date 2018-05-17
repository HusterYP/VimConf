# Vim配置
1. 实际情况是,在尝试了自己配置vim效果不佳之后,使用了[开源配置](https://github.com/amix/vimrc)
> 1. `~/.vim_runtime`目录下即其文件,关于其更多的快捷键可以参见[文档后半部分](https://github.com/amix/vimrc),但是有些被自己更改了哦
> 2. 有时候下载的插件有其对应的`xxx.vim`配置文件,此时好像应该加到`~/.vimrc`文件中,否则好像没有用,即应该使用`source ~/.vim_runtime/vimrcs/xxx.vim`的形式添加到`.vimrc`文件中
> 3. 自定义vim快捷键的时候,`<leader>`代表的是自定义的,[参见博客](https://blog.csdn.net/zgqxiexie/article/details/72973662)
> 4. `let:g`中`g`好像是`global`的意思
2. NerTree
> 1. 当使用vim打开一个文件夹的时候,默认会打开Nertree
> 2. `F2`可以打开侧边窗口
> 3. `,+f`可以跳转到侧边窗口选择文件
> 4. 在不同的标签之间切换,用命令`:tabn`和`:tabp`,查看所有标签用`tabs`
> 5. 更多快捷键,[参考博文](http://yang3wei.github.io/blog/2013/01/29/nerdtree-kuai-jie-jian-ji-lu/)
> 6. 在NerTree中选中目录后按下`ma`后可以新建目录或文件
> 7. 在目录下按下`m`,之后会出现几个选项,然后可以对选中文件进行操作,需要注意的是,使用`move`操作也可以重命名文件
3. MRU
> 1. 记录最近打开和编辑文件,[参见文档](https://github.com/vim-scripts/mru.vim)
> 2. 输入`:MRU`即可
> 3. 输入上2中命令并选择好文件后,可以通过输入`o`在新窗口打开文件;`v`可以以只读打开文件
> 4. `Ctl+ww`可以在左右窗口之间跳转,`Ctl+j`与`Ctl+k`可以上下切换窗口,`Ctl+wr`移动当前窗口的布局位置
4. Goyo
> 1. 即进入全屏模式,[文档](https://github.com/junegunn/goyo.vim)
> 2. 使用`:Goyo`进入(快捷键为`,+z`),`:Goyo!`退出(也可以用`:q`)
> 3. 还可以自定义全屏高度和宽度,具体见文档
5. ack
> 1. 主要用于项目内搜索,比如搜索某个函数,[文档](https://github.com/mileszs/ack.vim)
6. YankStack
> 1. [文档](https://github.com/maxbrunsfeld/vim-yankstack)
> 2. 用于将粘贴的文本存入一个栈中
> 3. 具体使用为快捷键`Ctl+p`与`Ctl+n`
7. vim-multiple-cursors
> 1. 多光标使用,[文档](https://github.com/terryma/vim-multiple-cursors)
> 2. 输入`MultipleCursorsFind xxx`即可找到所有的`xxx`,之后按下`c`来先删除再进入编辑,或者输入`u`后输入`i`进入编辑模式,此时不会删除原来的,而是在前面插入
8. ALE
> 1. 在错误代码之间跳转,快捷键`,+a`
