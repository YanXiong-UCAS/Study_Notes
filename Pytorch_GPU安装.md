# Pytorch_GPU安装

## #涉及的内容：

### #Ubuntu安装流程

1. 首先安装Win10
2. 安装Ubuntu，不需要efi和boot分区，可以与Win10共用一个efi启动分区，这样子不用在用其他软件来分别启动，只需要重启的时候在"performance MOK management"中一次选择"enroll mok-continue-yes-输入密码-reboot"即可。
3. 更新系统所有驱动，以及默认更新，是系统所有软件均处于最新版本状态。
4. 安装几个基本软件：Typora，Chrome，方便后续查看文件等。
5. 查看显卡驱动状态，以及目前有几个显卡。
6. NVIDIA驱动更新，附加驱动中如果无法更新，则采用命令行默认更新为推荐驱动版本。建议将原来的旧版本显卡卸载，然后在安装新的驱动，对比后面的参考方法，最好二合一得到一个最好的方法。参考：https://juejin.cn/post/6844903908691673096 和 https://www.jianshu.com/p/158ae8fcdb4a
7. 如果NVIDIA显卡不是主显卡，则将其更改为主显卡，通过查看"设置-关于"可以了解当前主显卡版本。
8. 下载Anaconda，然后按照官网指导步骤进行安装，默认路径，无需修改，以防后续问题，参考：https://docs.anaconda.com/anaconda/install/linux/
9. 更新Anaconda，保持最新状态，避免后续的问题，参考：http://showteeth.tech/posts/52735.html
10. 检查是否已经安装gcc，版本是多少？如果没有，则安装gcc，安装多个版本，以便后续的切换需要，参考：https://docs.nvidia.com/cuda/cuda-installation-guide-linux/index.html 和 https://zhuanlan.zhihu.com/p/186077141。需要找到对应的pytorch和cuda与gcc版本之间的关系，确定到底哪个版本支持？？？似乎与gcc版本无关系，应该是python版本和pytorch有联系，pytorch目前支持python3.6，因此需要将python版本降级到3.6
11. CUDA安装及测试，测试的时候，需要安装make，这是个什么命令？？？参考：https://blog.csdn.net/qq_42779103/article/details/108754887
12. CUDNN安装及测试，参考：https://blog.csdn.net/qq_42779103/article/details/108754887
13. Pytorch官网下载安装测试，参考：https://pytorch.org/

