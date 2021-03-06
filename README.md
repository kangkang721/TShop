# 代码使用教程

这个仓库的提交历史被我精心设置为与所介绍的功能顺序一致。使用这份代码时，我建议你从最早的提交开始，顺着本教程内容的进度，向前推移查看提交列表。另外，你还可以 从 GitHub 上下载每次提交代码后得到的 ZIP 或 TAR 文件。

如果你决定使用 Git 操作源码，那么首先要安装 Git 客户端(可以从 http://git-scm.com/ 下 载)。下述命令就使用 Git 下载示例代码:
```bash
$ git clone https://github.com/yll2wcf/TShop.git
```
git clone 命令从 GitHub 上下载源码，安装到当前目录下的 TShop 文件夹中。这个文件夹中不仅有源码，还有一个包含了程序修改完整历史的 Git 仓库。

仓库代码的标签是和教程对应的，比如第一篇文章会要求你签出程序的初始发布版本，然后在适当的时候指示你需要向前推进查看提交历史。切换提交历史的Git命令是`git checkout`。下面举个例子:
```bash
$ git checkout 1a
```
上述命令中的 1a 代表一个标签(tag)，是项目中某次提交历史的名字。这个仓库的标签根据本教程文章顺序命名，因此本例中的 1a 表示第 1 篇文章使用程序的初始版本。

除了签出程序源码的不同版本，你可能还需要进行一些设置。例如，你有时需要安装额外的第三方包。需要执行这些操作时，我会提醒你。


# 教程

文章教程要比代码更新的慢，对我来说，写一篇易懂的文章比写代码困难的多，有能力的先看代码。

[零、React Native电商项目实战——开篇](https://blog.csdn.net/yulianlin/article/details/80580701)

[一、React Native 电商项目实战——1.创建项目](https://blog.csdn.net/yulianlin/article/details/80670139)

[二、RN 电商项目实战——2.组件的State](https://blog.csdn.net/yulianlin/article/details/80808275)