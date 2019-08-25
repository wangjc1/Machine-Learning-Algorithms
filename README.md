

## Jupyter使用

* 1. 先安装Jupyter环境
* 2. 修改默认工作路径
```
   1）先确定配置文件的路径，通过jupyter notebook --generate-config命令
   2）修改参数c.NotebookApp.notebook_dir = '存放的代码根路径'
```
* 3. 修改Jupyter样式
   jt -t grade3 -f fira  -fs 13 -ofs 11 -dfs 11 -cellw 88% -T
   jt -t grade3 -f fira  -fs 14 -ofs 13 -dfs 13 -T


* 4. Jupyter快捷键
   在当前位置前插入 a
   在当前位置后插入 b
   保存 ctrl+s
   执行 shift+enter
   转化成Markdown  m
   删除一行 ctrl+d
   删除一段 dd
   代码帮助 tab+shift
   帮助文档 method?+tab
