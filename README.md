<h1 align="center">FPGA Tutorial </h1>

本项目旨在**帮助大家进行FPGA的入门，分享FPGA相关的优秀文章，优秀项目**。

[一起为本项目作出贡献](#github)

<h2 align="center">一、入门资料</h2>

<h3>FPGA相关门户网站</h3>

- [Xilinx](https://www.xilinx.com/)
- [Xilinx Forums](https://forums.xilinx.com/)
- [Xilinx Open Hardware](http://www.openhw.org/)
- [Altera](https://www.intel.cn/content/www/cn/zh/products/programmable.html)
- [Digilent 中国](http://www.digilent.com.cn/)
- [米联客](https://www.uisrc.com/portal.php)
- [opencores 开源硬件IP站](https://opencores.org/)

<h3 id="github">每个人都应该会使用GitHub</h3>

- [廖雪峰的Git教程]( https://www.liaoxuefeng.com/wiki/896043488029600 )
- [Github Guides](https://guides.github.com/activities/hello-world/)
- [如何参与到本项目的建设](docs/HowContribute.md)

<h3>数字电路</h3>

数字电路是学习FPGA的前提。

如果没有学习过数字电路，先选择一本数字电路教程(下面的数字电路课本中选一本，或者用手头的数字电路课本),再选择一本Verilog教程。用Verilog实现一遍数字电路里的加法器等等，是很好的入门经历。

- [电子技术基础 数字部分 (康华光.第5版)](http://leiblog.wang/static/FPGA/books/电子技术基础.数字部分.(康华光.第5版).pdf)

<h3>Verilog HDL入门</h3>

> HDL是硬件描述语言(Hardware Design Language)，使用这门语言的时候我们像是在**建模**，这点区别于编程语言，这往往是新手首先需要绕过来的难关！
>
> Xilinx和Altera是我们主要使用到的FPGA芯片厂商，此外还有国产的紫光、安陆等。对我们用户来说，他们的区别主要在于EDA软件的不同，比如Xilinx使用的是Vivado、Altera使用的是Quatus...
>
> 我个人认为Vivado的功能最强大，最好用，但缺点在于综合、生成等步骤的速度慢，你需要一台好的电脑！
>
> 虽然对于学习Verilog来说他们没有差别，但学习FPGA的时候手上最好要有一块板卡，上板验证会有更多的成就感。所以，用什么家的板卡，就用什么软件。

- 经典图书
  - [搭建你的数字积木](https://book.douban.com/subject/30242443/)
    - Xilinx大学计划书目，比较推荐，但是没找到PDF,并且还有配套的Basys3/EGO1例程([仓库地址](https://github.com/xupsh/Digital-Design-Lab))
  - [Verilog数字系统设计教程 夏宇闻](http://leiblog.wang/static/FPGA/books/Verilog数字系统设计教程夏宇闻.pdf)
  - [Verilog经典教程 夏宇闻](http://leiblog.wang/static/FPGA/books/夏宇闻-Verilog经典教程.pdf)
- 网路上生动的大神教程
  - [Artix7修炼秘籍](http://leiblog.wang/static/FPGA/books/00《Artix7修炼秘籍》-MIA701第一季.pdf)
  - [Verilog那些事儿](http://leiblog.wang/static/FPGA/books/Verilog那些事儿/)
    - [驱动篇](http://leiblog.wang/static/FPGA/books/Verilog那些事儿/02Veilog那些事儿-驱动篇I.pdf)
    - [时续篇](http://leiblog.wang/static/FPGA/books/Verilog那些事儿/03Verilog_HDL_那些事儿_时序篇v2.pdf)
    - [建模篇](http://leiblog.wang/static/FPGA/books/Verilog那些事儿/04VerilogHDL那些事儿_建模篇.pdf)
    - [整合篇](http://leiblog.wang/static/FPGA/books/Verilog那些事儿/05VerilogHDL那些事儿-整合篇.pdf)
  - [Xilinx原语的使用方法](http://leiblog.wang/static/FPGA/books/xilinx原语的使用方法.pdf)
  - [FPGA自学笔记-设计与验证](http://leiblog.wang/static/FPGA/books/FPGA自学笔记——设计与验证公开版.pdf)
  - [Verilog开发经验总结](http://leiblog.wang/static/FPGA/books/Verilog开发经验总结.pdf)
- 官方pdf文档
  - [Vivado从此开始](http://leiblog.wang/static/FPGA/books/Vivado从此开始/)
- Xilinx 入门视频
  - [Digilent Basys3 手把手教学](https://space.bilibili.com/511019924/channel/detail?cid=134957)
    - 顺便学一下Vivado如何使用
- Altera 入门视频
  - [正点原子 FPGA教学](https://www.bilibili.com/video/BV1Mb411E7gd?from=search&seid=11737352508875302131)
    - 如果买的是正点原子家的FPGA，可以白嫖很多项目。
    - 别家的FPGA，学习语法、驱动，也是没问题的。
  - [芯航线 FPGA从零到入门](https://www.bilibili.com/video/BV1tW411v78j?from=search&seid=11737352508875302131)

<h3>飞速提升开发效率✈️</h3>

- [VsCode取代Vivado自带编辑器](https://editor.csdn.net/md/?articleId=84668833)
- [使用板卡文件自动配置环境(板卡芯片、DDR等)](https://www.bilibili.com/s/video/BV1zg4y1q7Jd)
- [ModelSim与Matlab搭建图像仿真环境(无需上板即可验证Verilog算法!)](http://leiblog.wang/technicaldetail/5e397c7937a947e1fa893314)

<h3>规范你的工程🌟</h3>

- [华为verilog编程规范](http://leiblog.wang/static/FPGA/books/standard/华为verilog编程规范.pdf)

<h2 align="center">二、进阶资料</h2>

<h3>SOC System on Chip</h3>

> Xilinx系列最全最详细的文档其实是官方提供的 [Xilinx Docnav](https://china.xilinx.com/support/documentation-navigation/overview.html)
>
> https://www.zhihu.com/question/56596019

- [MicroBlaze](https://china.xilinx.com/products/design-tools/microblaze.html)

- ZYNQ
  - [The ZYNQ Book](http://www.zynqbook.com/)
  - [The ZYNQ Book 中文版](http://leiblog.wang/static/FPGA/books/The_Zynq_Book_ebook_chinese.pdf)
  - [MicroZed 300多篇教学博客](http://adiuvoengineering.com/microzed-chronicles/?tdsourcetag=s_pctim_aiomsg)

- [PYNQ](http://www.pynq.io/)
  - [Github](https://github.com/Xilinx/Pynq)
  - [Docs](https://pynq.readthedocs.io/en/v2.5.1/)
  - [DIscuss](https://discuss.pynq.io/)

<h3>HLS High-Level Synthesis</h3>

- [Xilinx 官方教程](http://xilinx.eetop.cn/list-83-1.html)

<h2 align="center">三、优秀项目</h2>

<h3>官方开源项目</h3>

- [ALINX 黑金 官方仓库 (包含OV系列摄像头驱动、DDR驱动等)](https://github.com/alinxalinx)
  - [AC616](https://github.com/alinxalinx/AC616)
  - [AX4010](https://github.com/alinxalinx/AX4010)
  - [AX7035](https://github.com/alinxalinx/AX7035)
  - [AX309](https://github.com/alinxalinx/AX309)
  - [AX7101](https://github.com/alinxalinx/AX7101)
  - [AX7102](https://github.com/alinxalinx/AX7102)
  - [AX7103](https://github.com/alinxalinx/AX7103)
  - [AX7021](https://github.com/alinxalinx/AX7021)
  - [AX7010](https://github.com/alinxalinx/AX7010)
  - [AX301](https://github.com/alinxalinx/AX301)
  - [AX7020](https://github.com/alinxalinx/AX7020)
  - [AX7015](https://github.com/alinxalinx/AX7015)
- [Digilent 官方仓库](https://github.com/Digilent)
  - [vivado-library 很多好用的IP-VGA、HDMI等](https://github.com/Digilent/vivado-library)
  - [vivado-boards Digilent开发板的板卡文件](https://github.com/Digilent/vivado-boards)
    - [使用板卡文件，让你的设计事半功倍](https://www.bilibili.com/s/video/BV1zg4y1q7Jd)
  - [Digilent 大神用户们的项目](http://www.digilent.com.cn/project/all/open.html)
- [赛灵思中文学习资料和开源设计](https://github.com/xupsh)
  - [74LSXX 芯片IP](https://github.com/xupsh/Digital-Design-Reference-Design/tree/dd239f50d5117917479b7a3b51eeb8a0d6945cc9/Library/74LSXX_Lib)

<h3>优秀开源项目 - 初级</h3>

- [带闹钟功能的计数器](https://github.com/LeiWang1999/DigitalAlarmClock)
  - 板卡:`Nexys4 DDR`
  - 功能
    - 支持I2S协议驱动的音响，接入耳机播放闹钟
    - 支持VGA显示剩余时间
    - 支持闹钟计数时钟变速(一倍速和五倍速)
- [搭建你的数字积木 配套工程](https://github.com/xupsh/Digital-Design-Lab)
  - 板卡:`Basys3`|`EGO-1`
  - 配套图书:[搭建你的数字积木](https://book.douban.com/subject/30242443/)

<h3>优秀开源项目 - 中级</h3>

- [基于FPGA的机器博弈五子棋游戏](https://github.com/Starrynightzyq/ZYNQ-PYNQ-Z2-Gobang)
  - 板卡:`PYNQ-Z2`
  - 2018全国大学生FPGA创新设计邀请赛一等奖、最佳创意奖
- [CM3软核 FPGA 车牌识别系统](https://github.com/Starrynightzyq/Nexys4DDR-ARM-M3-Plate-Recognition)
  - 板卡:`Nexys4 DDR`
  - 全国大学生集成电路创新创业大赛参赛作品

<h3>优秀开源项目 - 高级</h3>

- [PYNQ集群 类脑计算](https://github.com/OpenHEC/SNN-simulator-on-PYNQcluster)
  - 板卡:`PYNQ`
  - 全国大学生FPGA创新设计作品