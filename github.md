github 学习
1. 远程库与本地库
本地库可以通过 git clone 命令将远程库克隆至本地库
工作台中代码通过使用push命令将代码推入远程库。

2.SSH密钥配置
 GITHUB中项目有两个地址:HTTP以及SSH.使用http地址在每次通过git提交时都要输入用户名和密钥，使用SSH只需一次配置后便可直接通过git提交。

 如何设置SSH密钥：1、打开git bash。
2、使用cd ~/.ssh可以查看是否已配置SSH。
3、执行生成公钥和私钥的命令ssh-keygen -t rsa 并按回车3下（为什么按三下，是因为有提示你是否需要设置密码，如果设置了每次使用Git都会用到密码，一般都是直接不写为空，直接回车就好了）。会在一个文件夹里面生成一个私钥 id_rsa和一个公钥id_rsa.pub。（可执行start ~命令，生成的公私钥在 .ssh的文件夹里面
![](https://github.com/withjiang/Git-Github-notes-for-study/blob/master/1600954247.png)

