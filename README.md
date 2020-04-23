# HelloWorld
前一阵儿，在公司同步github代码到本地的时候，爆出了这样的一个错误ssh: connect to host github.com port 22: Connection refused。根据英文可以看出，ssh端口号被拒绝了，应该是被公司的网给禁掉了。

总结下如何换一种方式解决。

git 远程仓库两种协议
在解决问题之前，先要了解git远程仓库的两种协议连接

ssh协议连接github
在windows下的git客户端
