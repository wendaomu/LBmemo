#Debug

##如何debug?(有很多方法，这只是其一)

使用vivado进行debug时,在需要观察的信号前添加/*mark_debug = "true"/*(/*代表星号哦)，之后进行synthesis,执行结束后，打开synthesized Design,点击set up debug,(这里需要注意的是clock domain,这里设置不好，在hardware manager下会显示there is no debug core)保存之后会发现xdc文件发生了变化,在最下方出现了create_debug_core, 再执行implementation, generate bitstream,正常操作就可以了。

