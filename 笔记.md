#include <iostream>
using std::cout;
using std::endl;

int main(){
    cout<<"hello,world!"<<endl;
    return 0;
}
//总结今天复习了一下基本的Git操作命令
/*
ssh-keygen -t rsa 这个命令是生成SSH密钥对的，分别生成id_rsa和id_rsa.pub文件,分别表示私钥和公钥。
将本地生成的公钥上传到GitHub服务器，以便您可以通过SSH协议连接到您的GitHub仓库，进行代码推送和拉取等操作。
如果不指定生成密钥的邮箱会用本地电脑系统中的用户名和主机名作为电子邮件地址

文件状态复习

未跟踪（Untracked）：表示该文件尚未被纳入版本控制，也就是说 Git 对该文件还没有进行过任何操作。
修改（Modified）：表示该文件已经被修改过，并且这些修改还没有被暂存（Staged）起来。

暂存（Staged）：表示对该文件所做的修改已经被暂存起来了，但尚未提交到本地仓库中。

已提交（Committed）：表示对该文件所做的修改已经被提交到本地仓库中。

上传：
推送（Push） 通俗讲就是把本地仓库的信息上传到远程仓库

下载：
拉取(pull)
拉取就是把远程仓库的更新下载到本地然后立刻进行合并操作
抓取(fetch)
把远程仓库的更新下载到本地仓库不做任何操作
*/