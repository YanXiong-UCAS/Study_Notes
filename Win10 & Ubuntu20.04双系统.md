# Win10 & Ubuntu20.04双系统

## 1. 安装先后顺序

- ### Win10  > > >  Ubuntu20.04

## 2. Windows安装教程

- 本教程参照Thinkbook官网指导制作Win10启动盘：[**制作Win10系统安装U盘和安装纯净版Win10的通用教程**](https://iknow.lenovo.com.cn/detail/dc_177365.html)
- 安装前重要提示：
  - 准备8G或8G以上U盘（32G以内）。制作U盘会格式化U盘，此U盘内的数据需要提前备份至其它U盘或移动硬盘。
  - 在格式化、删除分区和重新安装操作系统之前，请提前备份好电脑中的所有数据至U盘或移动硬盘，避免产生任何损失。
  - 预装Office的情况，请提前记录自己激活的Office账户和密码，避免重装系统后忘记账户和密码。
  - 因为安装的Win10是纯净版本的，一般会自驱网卡，这样安装系统之后再去联网，点开系统的自动更新会自动更新系统需要的所有驱动。
  - 如果无法自驱网卡，请至相应的电脑官网下载对应网卡驱动，拷贝过来安装。
  - 因为教程中只说到新建一个系统盘，请安装完系统后，自行到磁盘管理新建分区。
  - 建议优先安装和出厂系统相同的版本。如，预装系统为Win10家庭中文版，请安装Win10家庭中文版。一般会自动联网激活，如果安装其他版本请自行联系微软购买相应的激活密钥。
  - 方案为使用微软官方软件制作纯净优盘安装，但是如果涉及激活之类的版权，需要使用者自行解决。

### ##`操作步骤`##

1. **打开微软下载Win10的网址：[下载 Windows 10 光盘映像（ISO 文件）](https://www.microsoft.com/zh-cn/software-download/windows10)**

   如下图所是，依次"选择版本" >>> "选择产品语言" >>> "选在下载系统位数"，即刻开始下载工具。

   ![img](https://webdoc.lenovo.com.cn/lenovowsi/new_cskb/uploadfile/20180807133709874.png)

2. **找到下载的软件，双击或者管理员运行。如果您同意许可条款，请选择接受。**

   ![img](https://webdoc.lenovo.com.cn/lenovowsi/new_cskb/uploadfile/20190523090017720.png)

3. **选择"为另一台电脑创建安装介质(U盘、DVD或ISO文件)"，然后点击"下一步"。**

   ![img](https://webdoc.lenovo.com.cn/lenovowsi/new_cskb/uploadfile/20190523090045490.png)

4. **选择Windows10的语言、版本和题写结构（64位或32位）。**

   此处去掉左下角的"对这台电脑使用推荐的选项"，然后选择Windows10家庭中文版/64位，如果要装32位选择32位即可，但是建议64位，因为64位支持大于4G的内存。

   ![img](https://webdoc.lenovo.com.cn/lenovowsi/new_cskb/uploadfile/20190523090104551.png)

5. **选择您要使用的介质：**

   - 选择"U盘"，然后点击"下一步"。
   - 选择到您的U盘。然后选择下一步，耐心等待下载和创建介质过程，最后点击完成。（连接至少有5G空间的空白U盘，该U盘上的所有内容都将被删除）。
   - 预安传系统的电脑C盘至少拥有10G左右空余。

   ![img](https://webdoc.lenovo.com.cn/lenovowsi/new_cskb/uploadfile/20210521103443897.png)

   ![img](https://webdoc.lenovo.com.cn/lenovowsi/new_cskb/uploadfile/20190523090220763.png)

   ![img](https://webdoc.lenovo.com.cn/lenovowsi/new_cskb/uploadfile/20190523090236131.png)

6. **系统安装**

   - 制作好U盘之后，把U盘接上需要安装系统的机器，联想台式机或一体机可在开机按F12键调出引导菜单(台式机安装的时候请优先断开网线，防止安装过程中联网卡顿)，笔记本开机按F12或者Fn+F12键调出引导菜单。笔记本也可在关机状态下按一下“一键恢复按钮”或者戳“一键恢复小孔”。一键恢复按钮或小孔位置多在“开机键旁边”或者“电脑左右侧”，如下图：

     ![https://webdoc.lenovo.com.cn/lenovowsi/new_cskb/uploadfile/20170515173903188001.jpg](https://webdoc.lenovo.com.cn/lenovowsi/new_cskb/uploadfile/20180807133204536010.jpg)

   - 出现菜单选项后，选择“Boot Menu”启动菜单回车，选择USB项回车启动开始安装系统。

     ![https://webdoc.lenovo.com.cn/lenovowsi/new_cskb/uploadfile/20170515172845970008.jpg](https://webdoc.lenovo.com.cn/lenovowsi/new_cskb/uploadfile/20180807133205647011.jpg)

     ![https://webdoc.lenovo.com.cn/lenovowsi/new_cskb/uploadfile/20170515172846196009.jpg](https://webdoc.lenovo.com.cn/lenovowsi/new_cskb/uploadfile/20180807133205211012.jpg)

   - 安装系统过程（输入密钥步骤跳过即可，系统版本选择WIN10家庭版安装，若是机器预装WIN10家庭中文版一般联网自动激活，安装非预装的系统版本请联系微软购买激活密钥）：

     ![img](https://webdoc.lenovo.com.cn/lenovowsi/new_cskb/uploadfile/20180807133205383013.png)

     ![img](https://webdoc.lenovo.com.cn/lenovowsi/new_cskb/uploadfile/20180807133205808014.png)

     ![img](https://webdoc.lenovo.com.cn/lenovowsi/new_cskb/uploadfile/20180807133205533015.png)

     ![img](https://webdoc.lenovo.com.cn/lenovowsi/new_cskb/uploadfile/20180807133205921016.png)

     ![img](https://webdoc.lenovo.com.cn/lenovowsi/new_cskb/uploadfile/20210520230338743.jpg)

     ![img](https://webdoc.lenovo.com.cn/lenovowsi/new_cskb/uploadfile/20180807133205644018.png)

     ![img](https://webdoc.lenovo.com.cn/lenovowsi/new_cskb/uploadfile/20180807133206142019.png)

     **注意**：删除分区会导致所有数据删除，如果有重要数据需要备份后再操作。

     ![img](https://webdoc.lenovo.com.cn/lenovowsi/new_cskb/uploadfile/20180807133206277020.png)

     ![img](https://webdoc.lenovo.com.cn/lenovowsi/new_cskb/uploadfile/20181223222736381.png)

     ![img](https://webdoc.lenovo.com.cn/lenovowsi/new_cskb/uploadfile/20180807133206904021.png)

     ![img](https://webdoc.lenovo.com.cn/lenovowsi/new_cskb/uploadfile/20210520230206947.jpg)

     ![img](https://webdoc.lenovo.com.cn/lenovowsi/new_cskb/uploadfile/20180807133206728022.png)

     ![img](https://webdoc.lenovo.com.cn/lenovowsi/new_cskb/uploadfile/20180807133206537023.png)

     ![img](https://webdoc.lenovo.com.cn/lenovowsi/new_cskb/uploadfile/20180807133206816024.png)

     ![img](https://webdoc.lenovo.com.cn/lenovowsi/new_cskb/uploadfile/20180807133206208025.png)

     ![img](https://webdoc.lenovo.com.cn/lenovowsi/new_cskb/uploadfile/20180807133207527026.png)

     ![img](https://webdoc.lenovo.com.cn/lenovowsi/new_cskb/uploadfile/20210520230118681.jpg)

     ![img](https://webdoc.lenovo.com.cn/lenovowsi/new_cskb/uploadfile/20210520230136229.jpg)

     ![img](https://webdoc.lenovo.com.cn/lenovowsi/new_cskb/uploadfile/20210520230045579.jpg)

     ![img](https://webdoc.lenovo.com.cn/lenovowsi/new_cskb/uploadfile/20210520230306688.jpg)

     ![img](https://webdoc.lenovo.com.cn/lenovowsi/new_cskb/uploadfile/20200530013016138.png)

     ![img](https://webdoc.lenovo.com.cn/lenovowsi/new_cskb/uploadfile/20200530013030878.png)

     ![img](https://webdoc.lenovo.com.cn/lenovowsi/new_cskb/uploadfile/20181223223039953.png)

     ![img](https://webdoc.lenovo.com.cn/lenovowsi/new_cskb/uploadfile/20181223223052306.png)

     ![img](https://webdoc.lenovo.com.cn/lenovowsi/new_cskb/uploadfile/20190523095933385.png)

     ![img](https://webdoc.lenovo.com.cn/lenovowsi/new_cskb/uploadfile/20201021191829731.png)

     ～～～**Windows安装完成**～～～


## 3. Ubuntu 安装教程

- 本教程通过尝试各类网络教程，失败多次后经验总结所得，几乎保留了安装过程中所涉及的所有问题，如有其他疑问未涉及需要补充，请留言。
- 安装前重要提示：
  - 准备8G或8G以上U盘（32G以内）。制作U盘会格式化U盘，此U盘内的数据需要提前备份至其它U盘或移动硬盘。
  - 在格式化、删除分区和重新安装操作系统之前，请提前备份好电脑中的所有数据至U盘或移动硬盘，避免产生任何损失。
  - 因为安装的Ubuntu是纯净版本的，一般会自驱网卡，安装过程中便会通过联网自动安装其他各类驱动。
  - 本教程中将Ubuntu系统安装于固态硬盘，占据了整个硬盘，需要保留和新建其他磁盘分区，请读者安装前自行到磁盘管理新建分区。
  - 本教程是针对“双固态硬盘双系统”且双系统分别位于相互独立的两个硬盘。本教程同样是适用于“单固态硬盘双系统，双系统共享单个固态硬盘”的情况。关于“固态硬盘+机械硬盘”由于固态硬盘与机械硬盘启动分区的格式不同（固态：GPT，机械：MBR），因此需要单独设置启动选项，详情望读者另行查询，后期有时间会再行补充。
  - 方案为Ubuntu 20.04官方纯净版U盘安装，但是如果涉及激活之类的版权，需要使用者自行解决。
  - 推荐Ubuntu版本：16.04，18.04，20.04

于开源软件Rufus制作Ubuntu20.04启动盘（选择GPT磁盘格式）

### ##`操作步骤`##

1. **在Windows上创建可启动U盘，参考[Ubuntu官网](https://ubuntu.com/tutorials/create-a-usb-stick-on-windows#1-overview)**

   - 使用可启动的Ubuntu U盘，可以实现：

     - 安装或升级Ubuntu
     - 无需更改您的PC配置即可测试Ubuntu桌面体验
     - 在借来的机器上或网吧启动到Ubuntu
     - 使用U盘上默认安装的工具来修复或修复损坏的配置

     ![图像](https://ubuntucommunity.s3.dualstack.us-east-2.amazonaws.com/optimized/2X/0/0e7183ed04be135ae59671bc64482972f736c270_2_690x353.jpeg)

     ##NOTE##  从 Microsoft Windows 创建可启动的 Ubuntu U 盘非常简单，我们将在接下来的几个步骤中介绍该过程。或者，我们也有教程可以帮助您从[Ubuntu](https://tutorials.ubuntu.com/tutorial/tutorial-create-a-usb-stick-on-ubuntu)和[Apple macOS](https://tutorials.ubuntu.com/tutorial/tutorial-create-a-usb-stick-on-macos)创建可引导的 USB 记忆棒。

   - **安装要求：**

     - 一个 4GB 或更大的 U 盘/闪存驱动器
     - Microsoft Windows XP 或更高版本
     - [Rufus](https://rufus.ie/)，一个免费的开源U盘写入工具
     - 一个 Ubuntu ISO 文件。请参阅[获取 Ubuntu](https://www.ubuntu.com/download)以[获取](https://www.ubuntu.com/download)下载链接

     ![ubuntu-下载-18_04_1](https://ubuntucommunity.s3.dualstack.us-east-2.amazonaws.com/optimized/2X/c/c5fab836b9875ee53735b376584d94d44c160852_2_690x467.png)

     ##NOTE##  记下浏览器保存下载的位置：这通常是 Windows PC 上名为“下载”的目录。不要将 ISO 映像直接下载到 U 盘！如果使用 Windows XP 或 Vista，请下载 Rufus 2.18 版。

   - **USB选择：**

     - 执行以下操作以在 Rufus 中配置您的 USB 设备：
       1. 启动 Rufus
       2. 插入你的 U 盘
       3. Rufus 将更新以在**Device**字段中设置**设备**
       4. 如果选择的**设备**不正确（可能您有多个 USB 存储设备），请从设备字段的下拉菜单中选择正确的设备

     ![windows-rufus3-usb](https://ubuntucommunity.s3.dualstack.us-east-2.amazonaws.com/original/2X/8/809f47a67de94bf6d405a142bc507ed84a397099.png)

     ##NOTE##  通过确保没有连接其他设备，您可以避免从 USB 设备列表中进行选择的麻烦。

   - **引导选择和分区方案**

     - 现在选择 Boot 选项。选择将是*Non bootable*和*FreeDOS*。由于您要创建可引导的 Ubuntu 设备，因此请选择**FreeDOS**。
     - 分区方案 ( *MBR* ) 和目标系统（*BIOS（或 UEFI-CSM）*）的默认选择是合适的（但是如果采用的是固态硬盘，那么建议选择GPT分区方案）。

     ![windows-rufus3-select-usb](https://ubuntucommunity.s3.dualstack.us-east-2.amazonaws.com/original/2X/9/9cd9cac04803e637b25805c0b5968e7b16478627.png)

   - **选择Ubuntu ISO文件**

     - 要选择你之前下载的Ubuntu的ISO文件，单击**选择**“引导选择”的权利。如果这是下载文件夹中存在的唯一 ISO 文件，您将只会看到列出的一个文件。
     - 选择适当的 ISO 文件，然后单击“**打开”**。

     ![windows-rufus3-select-ubuntu_18_04_1](https://ubuntucommunity.s3.dualstack.us-east-2.amazonaws.com/optimized/2X/9/93ebf8b4c6fd98efcac1ae53c93eefe4eb021ca0_2_690x462.png)

   - **编写ISO**

     - 该*卷标*将被更新，以反映选择的ISO。
     - 将所有其他参数保留为默认值，然后单击“**开始”**以启动写入过程。

     ![windows-rufus3-write-iso](https://ubuntucommunity.s3.dualstack.us-east-2.amazonaws.com/original/2X/c/c8d89e0c41f6d31f0a4aa38675020973b43d46c9.png)

   - **额外下载**

     ##NOTE##  您可能会收到警告，Rufus 需要额外的文件才能完成 ISO 的编写。如果出现此对话框，请选择**是**继续。

     ![windows-rufus3-additional-downloads](https://ubuntucommunity.s3.dualstack.us-east-2.amazonaws.com/original/2X/0/0cb88c1c27bccfc6bf73d500313e0f49625e0c27.png)

   - **写警告**

     - 然后你会收到警告，Rufus 已经检测到 Ubuntu ISO 是一个*ISOHybrid 镜像*。这意味着相同的图像文件可以用作 DVD 和 U 盘的源，而无需转换。

     - 保持选择*ISO 映像模式写入，*然后单击**确定**继续。

       ![windows-rufus3-isohybrid-warning](https://ubuntucommunity.s3.dualstack.us-east-2.amazonaws.com/original/2X/f/fbacb96229f3fe51369752a9010a5af6f5586252.png)

     - Rufus 还会警告您，您选择的 USB 设备上的所有数据都将被销毁。这是一个很好的时机，当您确信自己拥有正确的设备时，请在单击“**确定”**之前仔细检查您是否选择了正确的设备。

       ![windows-rufus3-写警告](https://ubuntucommunity.s3.dualstack.us-east-2.amazonaws.com/original/2X/6/6be7f071bb10bec2694b5e4b552742fb5e7747fe.png)

     ##NOTE#  如果您的 U 盘包含多个分区，Rufus 将在单独的窗格中警告您这些分区也将被销毁。

   - **编写ISO**

     - ISO 现在将写入您的 USB 记忆棒，Rufus 中的进度条将向您显示您在此过程中的位置。使用相当现代的机器，这应该需要大约 10 分钟。总经过时间显示在 Rufus 窗口的右下角。

       ![windows-rufus3-write-progress](https://ubuntucommunity.s3.dualstack.us-east-2.amazonaws.com/original/2X/2/2ae0bc900f7dbde497f07adf382fd44a64f372fd.png)

   - **安装完成**

     - 当 Rufus 完成对 USB 设备的写入后，状态栏将变为绿色，中间会出现**READY**字样。选择**CLOSE**完成写入过程。

       ![windows-rufus3-write-complete](https://ubuntucommunity.s3.dualstack.us-east-2.amazonaws.com/original/2X/d/df720a52ca05eb8348856590a6ffc1c1ab27e8ac.png)

       **恭喜！**您现在在 U 盘上安装了 Ubuntu，可启动并准备就绪。

2. **安装Ubuntu桌面**，参考[Ubuntu官网](https://ubuntu.com/tutorials/install-ubuntu-desktop#1-overview)

   - Ubuntu 桌面易于使用、易于安装，并包含运行组织、学校、家庭或企业所需的一切。它也是开源的、安全的、可访问的并且可以免费下载。

     ![仿生桌面](https://ubuntucommunity.s3.dualstack.us-east-2.amazonaws.com/optimized/2X/4/43a6f9ad883ac86ecc11a8170b69b895d8b42e0e_2_690x517.png)

   - **安装要求：**

     - 将您的笔记本电脑连接到电源。
     - 确保您有至少 25 GB 的可用存储空间，或 5 GB 的最小安装空间。
     - 可以访问包含您要安装的 Ubuntu 版本的 USB 闪存驱动器。
     - 确保您有最近的数据备份。虽然不太可能出现任何问题，但您永远不会做好充分的准备。

   - **从U盘启动：**

     - 重启电脑，不断点击Fn+F12（Thinbook为此操作，其它品牌电脑或许稍有不同）选择经由Rufus制作的启动盘启动

   - **选择语言：**

     - 一旦您的计算机启动，您就会看到欢迎窗口，选择需要的语言。(强烈建议系统语言选择英文，输入法选择中文！！！)

       ![欢迎窗口](https://ubuntucommunity.s3.dualstack.us-east-2.amazonaws.com/optimized/2X/a/ad5e454a9fd45fd56d90da951702c2f2224cd32a_2_690x479.png)

   - **准备安装Ubuntu**

     - 首先会要求您选择键盘布局。如果安装程序没有正确猜测默认布局，请使用“检测键盘布局”按钮来运行一个简短的配置过程。

     - 选择*继续后*，系统会询问*您要安装哪些应用程序？*这两个选项是“正常安装”和“最小安装”。第一个相当于旧的默认工具包、应用程序、游戏和媒体播放器——一个适用于任何 Linux 安装的绝佳启动板。第二个占用的存储空间要少得多，并且允许您只安装您需要的东西。

     - 在安装类型问题下方是两个复选框；一个用于在安装时启用更新，另一个用于启用第三方软件。

       - 如果空间充足，我们建议同时启用`Download updates`和`Install third-party software`。
       - 保持与互联网的连接，以便在安装 Ubuntu 时获得最新更新。
       - 如果您未连接到 Internet，系统会要求您选择无线网络（如果可用）。我们建议您在安装期间进行连接，以便我们确保您的机器是最新的

       ![选择安装大小、更新和第三方软件](https://ubuntucommunity.s3.dualstack.us-east-2.amazonaws.com/optimized/2X/3/32da76fd45eb5300065df0491ec85a0ab3e6e380_2_690x418.png)

   - **分配驱动空间**

     - 使用复选框选择您是否希望将 Ubuntu 与另一个操作系统一起安装，删除您现有的操作系统并将其替换为 Ubuntu，或者 - 如果您是高级用户 - 选择“**其他**”选项。建议选择**其他**。

       ![设置存储配置](https://ubuntucommunity.s3.dualstack.us-east-2.amazonaws.com/optimized/2X/4/46e9947d7b4ad3e96487d81cf61c327485d56b5a_2_690x424.png)

     - 初学者建议设置四个分区即可（固态硬盘没有主次分区之分，因此可以都选择“主分区”）：

       - **/efi:** 启动分区，逻辑分区，空间起始位置，分区格式为ext4，通常300-500M。固态硬盘安装双系统，Windows与Ubuntu共享一个efi启动分区，Windows安装过程中已经默认划分了一个启动分区，即使是双硬盘也可以共享一个efi启动分区，切记一定是共享的Windos的efi分区，因此在Ubuntu安装过程中可以省去efi分区的划分。
       - **swap:** 交换分区，逻辑分区，空间起始位置，分区格式为swap。该分区相当于Windows中的“虚拟内存”，如果物理内存小于或等于512MB，建议分配交换分区的大小为物理内存容量的2倍；如果物理内存大于512MB，建议分配交换分区的大小等于物理内存容量；如果您的内存够大也可以不建立交换分区。
       - **/:**  安装系统和软件的默认分区，逻辑分区，空间起始位置，分区格式为ext4。空间一定要大，具体大小根据个人需求而定，建议深度学习用户至少保留50-100G空间大小。
       - **/home:**  桌逻辑分区，空间起始位置，分区格式为ext4。面下载文档等都位于该分区，相当于“我的文档”，可以用于存贮数据，因此建议该空间尽量大，可以将生于所有空间均分配给此空间。

   - **开始安装**

     - 配置存储后，单击“立即安装”按钮。将出现一个小窗格，其中概述了您选择的存储选项，如果详细信息不正确，则有机会返回。

     - 单击`Continue`以修复这些更改并开始安装过程。

       ![将更改写入磁盘](https://ubuntucommunity.s3.dualstack.us-east-2.amazonaws.com/optimized/2X/f/f696c2cfd147a5613f1061cf9104c30f03748344_2_690x418.png)

   - **选择您的位置**

     - 如果您已连接到互联网，系统会自动检测您的位置。检查您的位置是否正确，然后单击“前进”继续。如果您在连接到 Internet 时遇到问题，请使用右上角的菜单选择一个网络。

     - 如果您不确定自己的时区，请输入当地城镇或城市的名称或使用地图选择您的位置。

       ![你在哪](https://ubuntucommunity.s3.dualstack.us-east-2.amazonaws.com/optimized/2X/1/1f7d6ccbc18537a79f4af833d124dc096ef70459_2_690x419.png)

   - **登陆详情**

     - 输入您的姓名，安装程序将自动建议计算机名称和用户名。如果您愿意，这些可以轻松更改。计算机名称是您的计算机在网络上的显示方式，而您的用户名将是您的登录名和帐户名。

     - 接下来，输入一个强密码。安装程序会告诉您它是否太弱。

     - 您还可以选择启用自动登录和主文件夹加密。如果您的机器是便携式的，我们建议禁用自动登录并启用加密。如果机器丢失或被盗，这应该会阻止人们访问您的个人文件。如果您启用主文件夹加密并且忘记了密码，您将无法检索存储在主文件夹中的任何个人数据。

       ![用户名和密码输入](https://ubuntucommunity.s3.dualstack.us-east-2.amazonaws.com/optimized/2X/f/fe3e195347fdb45feab534796348384a41b918e7_2_690x424.png)

   - **后台安装**

     - 安装程序现在将在后台完成，而安装窗口会教你一些关于 Ubuntu 有多棒的信息。根据您的机器和网络连接的速度，安装应该只需要几分钟。

       ![安装程序在后台运行](https://ubuntucommunity.s3.dualstack.us-east-2.amazonaws.com/optimized/2X/2/29ec0f5c3d8c5b51f7b7440c4e2a95cc9f4a0118_2_690x514.png)

   - **安装完成**

     - 安装和配置完所有内容后，会出现一个小窗口，要求您重新启动机器。`Restart Now`出现提示时，单击并移除USB 闪存驱动器。如果您在测试桌面时启动了安装，您还可以选择继续测试。

       ![截屏](https://ubuntucommunity.s3.dualstack.us-east-2.amazonaws.com/original/2X/f/f4e2a592f30424c402346ad872e065491518d5eb.jpg)

     - **恭喜！**您已经成功安装了世界上最流行的 Linux 操作系统！







