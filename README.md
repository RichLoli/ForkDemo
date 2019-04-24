# 多人协作测试仓库
# Fork
先对本仓库进行Fork

![image](https://github.com/RichLoli/ForkDemo/blob/master/1.PNG?raw=true)

fork后 进入到个人仓库

![image](https://github.com/RichLoli/ForkDemo/blob/master/3.PNG?raw=true)

在仓库列表中查找fork的仓库名称

![image](https://github.com/RichLoli/ForkDemo/blob/master/4.PNG?raw=true)

可以看到fork的仓库上有一行标题"Forked From owenma/parent "
说明这个仓库是从"owenma/parent"fork过来的 这个"owenma/parent"就是仓库名称
随后单击进入这个仓库

点击Clone or download

![image](https://github.com/RichLoli/ForkDemo/blob/master/5.PNG?raw=true)

获取到SSH地址后就可以clone该仓库了

在本地创建好目录后使用`clone`命令克隆该仓库

![image](https://github.com/RichLoli/ForkDemo/blob/master/6.PNG?raw=true)

clone成功后就可以开始对这个仓库进行修改了（学习测试 请你们编写一个文本文档名称任意、内容任意）
修改成功后还是死亡命令三件套
```
#添加文件到暂存区
git add
#提交到本地版本库
git commit -m "提交信息"
#提交到远程仓库
git push -u origin master
```
完成后 再到本仓库中(这里指的是原仓库，不是你fork之后从自己的仓库列表中打开后的仓库)

点击pull request

![image](https://github.com/RichLoli/ForkDemo/blob/master/8.PNG?raw=true)

随后需要填写更新日志(就是你在本次提交中都改了什么的描述)

再点击Create pull request

这时只需要坐等仓库的作者同意你的提交之后，你的提交就会在该仓库中正式生效
