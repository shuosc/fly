---
title: "通信原理课，最有用的课，最没用的课——20-sjj-通信工程-分流"
date: 2023-06-11T13:01:02+08:00
categories: [分流]
tags: [20级,分流,通信学院,通信工程]
author: 信号 微积分是我永远的痛
draft: false
---

## 0. 省流

sjj认为：

0.1 不推荐通信学院任何专业。通信专业并不是一个“支撑技术专业”，今天其他行业所需的大部分通信知识，都封装在了“计算机网络”这一概念中，可能并不需要“通信”专业的学生提供技术支持。因此通信工程的前景和通信行业的建设需求绑定。

0.2 通信工程和电子信息工程二者，选择通信工程。两专业必修课程几乎相同。目前通信工程分流热度更低，但保研率更高，推得电子信息工程卷度高于通信工程。未来选择哪一者，取决于未来的分流热度和保研率趋势。（大部分企业在用人时清楚电子信息类专业基础技能相似，无需担心专业名问题。）

0.3 不推荐大数据专业。数据库和操作系统压缩为一门课就够让人唠一辈子了，其他前后置课程的sb之处自行了解。

0.4 不推荐光电专业。通信学院的光电专业的建设基础是光纤实验室，以光纤通信以及光纤的衍生应用为主。如对更广范围的光电产品乃至光学工程感兴趣，请选择更合适的专业。

以上观点仅代表sjj个人观点，欢迎指正其中的固有印象。

## 1. 个人情况

- **学校、学院系所、专业**

  上海大学 通信与信息工程学院 通信工程

- **学分成绩及其排名**

  3.04/4.00

  专业排名65.0%

- **分流成绩及其排名**
  
  高考归一化66.10

  学习成绩77.74（绩点2.75）

  排名775

  试读警告*1（微积分3、大学物理2）


- **其他成果**

  CET-4 ：622，CET-6 ：536

  无其他证书，无竞赛，有科研无成果

- **项目**

  均为课程项目

-  **目前规划**

  直接工作，正在找实习，暂无正式offer

## 2.通信工程劝退综述

如开头所述，笔者认为通信工程并不是一个“支撑技术专业”，这是一个专为通信行业裁剪的电子信息专业，是一个典型的“学一堆东西解决一个问题”，而非“学一部分东西就可以解决其他行业中的问题”的专业。以SHU-SCIE为例，其本科课程计划的基本脉络如下：

### 通信工程课程设置

正如标题所说，通信原理课，是整个通信工程四年最有用的课，因为通信的必修课就是在为通信原理课打基础。通信原理课介绍了通信系统如何传输信息。而表示信息的物理量是信号，因此我们有了信号与系统和数字信号处理。为了给信号与系统提供数学基础，我们学习了复变函数与积分变换。而信号的传输有他的物理实体，这个物理实体很多情况下是电路，因此我们学习了电子线路1，学会了如何分析一个电路图。对于FM（广播）这样的模拟通信系统，我们学习了电子线路2（模拟电路）和通信电子线路（高频电子线路）。对于更高频率的有线通信、无线通信、光通信元器件，他们的原理又涉及电磁的相互转换，因此我们需要学习电磁场理论。对于今天最常见的数字通信系统，我们需要知道数字信号如何被处理，因此我们需要学习数字电路。今天的数字通信系统在传输中往往会通过编码合理地控制差错，因此就有了“信息论与编码”“概率论与随机过程”。

但以上只是学习的“物理层”如何运行，即一段二进制编码（数字通信系统）或者一个连续波形（FM等模拟系统）如何在实际的载体中传递。对物理层而言无区别的二进制编码，对于不同的应用，有各不相同的格式规定，因此就有了“计算机网络”。计算机在处理这些不同格式的编码时，又有各种冲突和速度问题，因此我们学习了数据结构与算法基础。一些复杂的算法和程序使用顺序结构去编写易读性差，因此我们学习了面向对象程序设计。储存在计算机中的编码需要被传输到实际的电路中去，因此我们要学习软硬件之间的接口，也就是微机原理。

### 本科就业

到这里，我们已经验证了，这确实是一个专为通信行业裁剪的电子信息专业。但通信行业并没有提供足够的就业岗位，对转行到其他电子信息行业工作的同学们有用的课程则是一些电子信息类专业共有的课程。

对于转行成为硬件工程师的同学，最重要的课程是各种电路课程。

对于转行成为嵌入式软件工程师的同学，最重要的课程显然是微机原理。但这一岗位的发展趋势是更多开发将在rtos（实时操作系统）上进行，通信工程并没有开设任何与操作系统相关的必修或选修，而rtos有关的工作常常涉及操作系统的裁剪和移植。

对于转行成为软件工程师的同学，通信工程的课程只提供了使用编程语言的实现通信系统中所需的各种算法的机会，来锻炼你的编程能力。你需要自己学习成为一个合格的软件工程师所需要的基础知识和工具（比如通信工程没有和数据库有关的理论课程）。

而本科寻求本专业对口就业的同学，一般有：

通信设备企业，如路由器开发相关。本科可应聘的岗位同上，主要是进行设备相关的软硬件开发。另外还有一部分同学从事天线/射频相关的工作，但通信学院波导、射频相关课程没有要求学习使用电磁场仿真软件（如hfss），而无电磁仿真的经验则无法投递任何与天线射频相关的岗位。

运营商（通信建设、通信服务企业）。往届毕业生往往选择三大运营商作为三方协议的保底选项。但从23春季招聘的情况来看，无法预测24秋招运营商还能否为本校层次的毕业生提供足够的岗位；运营商提供的大部分岗位与通信底层技术无关，比如有些岗位是负责运营商订单系统的管理和操作；因此运营商的许多岗位并不只招收通信专业毕业生，许多岗位欢迎其他电子信息专业如自动化的毕业生应聘。

另有网络运维、网络技术等岗位，但由于这类岗位并不涉及通信底层原理，有计算机网络相关经验的同学均参与竞争。

综上，如果不清楚本科就业时去往哪一行业，掌握一些通用性较高的软硬件技能，会强于四年只学了一些通信专业的理论和相关实现的同学。

由于笔者主要考虑从事硬件和嵌入式相关的工作，对转码等方向的情况并不十分了解，欢迎各位已经就业的学长学姐补充。

### 研究生方向

转行去一些更加细分的岗位，比如图形算法工程师和FPGA工程师，需要研究生时期的研究方向与相关岗位匹配，本节将简单介绍通信学院研究生的主要方向。由于笔者暂不打算考研，本节内容可能出现差错。

从通信官网上的硕导名单我们可以知道，通信学院的研究生主要分为一下四个方向：通信与信息系统、电磁场与微波技术、电路与系统和信号与信息处理。

![image](https://github.com/KYShek/fly/assets/52855847/b0baa46e-9020-4623-bf9b-948dd285150c)

其中信号与信息处理主要是一些图像处理、雷达信号处理、声信号处理、视频编码等领域有关的导师。这些导师的研究方向，计算机学院和机自学院也有许多导师研究。笔者认为这一方向可以视为一种半转行。这些方向的学生会进入各行各业继续进行各种细分领域的信息处理系统的相关工作，各细分领域的行情差异较大，供需变动很快，在此不详细讨论。

官网列出的电磁场和电路系统方向的导师主要和微波、天线、射频有关。该方向招生名额较少（考研学硕名额一共10个），不详细讨论。

通信与信息系统方向的导师主要为光纤以及其他通信系统的算法、设备、网络、应用相关的导师。笔者认为相当比例的光纤方向研究（尤其是那些导师学历背景为物理学的）出现了很强的材料学研究特征，友善提醒各位同学小心。另外，整个行业最翘楚的人才才会从事通信新协议新算法研发的岗位，请对自己的能力上限进行评估。

通信与信息系统学硕、电子信息专硕名额也可用于招收电路、电磁场、信号与信息处理方向的学生。

四个学硕专业初试专业课2均为**信号与系统+模拟电路**。电子信息专硕初试专业课2为**模拟电路**。本学院各专业**不接受调剂**。（不想细说，甚至不应该明确写出来，外院外校最好一直注意不到这件事。）

## 3. 学业压力与课程项目

由于分流时绩点较低，保研无望，笔者对绩点完全不焦虑，能够很自如地项目放飞自我、上课开摆、期末速成。

太过于放飞自我的后果就是每个学期都不得不第十周刚刚开始学习。笔者认为如果只以及格为目的，第十周开始，只速读ppt，2-5天速成一门课完全无问题。（其实任何专业任何课都可以，只是大一的时候还没有学会如何速读ppt，才把微积分和大物玩炸了。）

因此该部分将主要讨论通信学院特色的课程项目。

通信工程专业几乎所有必修课，很大一部分选修课都有课程项目。必修课中没有项目的几门则要提交自学报告，当然通信学院的自学报告限制页数，因此主要压力来自于项目。

大部分课程的项目一般在第四周左右确定组员和选题，第九周周末左右验收。之所以我们能看到第八周第九周熬夜赶工的景象，主要是因为大家都有拖延症。

往年大家往往听到的是对课程项目的抱怨。但今年笔者想给课程项目说点好话。

大一以来，笔者一直在思考大学应该如何更好地培养一个工程师。通信学院几乎每个课程都开设课程项目，才应该是一种普遍的正常状态。（当然，目前笔者认为，这些项目并不足以培养一个能力合格的工程师。）同学校其他学院，甚至更好学校的相近专业才是有问题的。关于大学工科教育的问题，一位成电老师的文章可能阐述的更清楚。[“有技无工”——目前大学工科教育的一些问题兼论如何学习SoC设计](https://zhuanlan.zhihu.com/p/598683182)

笔者认为工程能力有以下几个方面：技能、解决问题/获得技能的方法论、进度控制能力、团队合作能力、对复杂系统的理解。最后一项对本科毕业生比较困难，主要谈谈前四项。

大家常常会抱怨课程项目和理论课程学习进度不匹配，这也是许多人将课程项目拖到最后的原因。1.实践和理论学习是可以先分开进行的，实际上笔者的许多项目做完了，才刚刚开始看ppt。（笔者除了工教高之外，还修了嵌入式项目设计，都是完全没有理论学习，纯做项目的课。）2.这种拖延一部分可以视为一种做题思维，把课程项目当成了某种课后练习题，因此要等到课上学完了，才开始做。3.项目有时只涉及这门课程的某一小块，学习这一小块的知识点并不需要太多时间。4.期末速成才花几天时间，开学的时候对课程内容形成印象需要的时间并不长。（笑死，小学初中拿新书的的时候才干得出这种事。）

大家还会抱怨项目所需知识和课程内容不完全重合。有几门课程确实有这个问题。主要是电子线路1项目不得不使用之后课程才会学到的元件（当然这些元件掌握起来并不难，当年这些元件问世的时候就是集成化元件，而不需要完全搞清楚内部原理），也没有明确电路板的评分标准（为什么要从19级开始取消工教初！），还有信号与系统2课程项目可能需要用到机器学习，通信原理项目用到Verilog语言，但一半同学工程教育没有选修Verilog。这个问题笔者比较能接受，确确实实锻炼了解决问题、自学技能的能力，又不是理论课的前置课程缺失。

总结两年来的项目经历，笔者认为想要在课程项目中获得真正的工程能力，理想情况应该是：开学第一周先对每门课的各章内容和相互之间的联系建立初步印象，第四周至第五周完全完成理论设计，有初步的分工，第五周至第八周完成，第九周当作冗余。当然实际操作中这种情况完全没有可能，因为人有惰性，组员也不互相熟悉。但是只有这样，才能获得解决问题的方法论和进度控制能力。

十分建议大家在选课时就确定小组成员，整组一起选绩点最低的同学能选上的老师，比较方便评估组员的工作能力和分工。固定的小组成员也比较容易形成一套合适的进度控制方法。

当然，期末赶工项目也是一种选择，通信学院的神·bughht就是这么干的。但是期末赶工时解决问题的流程就完全不一样了。

以上碎碎念均是由于笔者工教高（综合工程设计）烂完了很后悔，可以不听，因为对大家来说工教高可能只是一门课而已。笔者曾希望自己的工教高的工作成果能更好一些。近两周反思后认为，无论是进度控制和项目分解，都可以做的远好些。

下面讲讲项目和就业的关系。

1.往届有许多学长学姐靠工教高项目单刷秋招。（这也是为什么笔者会把工教高的工作成果看得如此重要。）当然今年开始就业明显恶化，不具有参考价值。

2.简历上课程项目多确实有一些优势。但是就业形势恶化下，简历匹配度可能更有用。一个和岗位相关的大项目比罗列课程项目更有用些。

3.可以借课程项目机会稍扩展出去掌握一些技能。比如数电项目可以试着画个pcb。（笔者直到工教高做完都没有画过一块pcb，蛮可惜的。数电项目元件多，但布线规则不复杂，很适合练习布线。）

## 4. 遗憾&广告两则

大二没能抓住机会加入翔英大楼408无人机实验室，是笔者在通信最大的遗憾。虽然没能加入，感谢无人机实验室jj、lcs、hht、tsh提供的项目和理论学习上的帮助，以及大三春最后一周借用了几天无人机实验室的工位。给他们打个广告吧，欢迎掌握（但不限于）pcb板设计、单片机开发、无人机飞控等技能中的一项的22级同学，选择分流到通信工程专业并报名加入无人机实验室。虽然该实验室在通信学院，但在电赛-自动控制组居然获得了不错的成绩。

广告2：本人还曾担任通信学院人工智能社学术部部长，但是这个社团在摆烂，蛮可惜的，如果你们有开展这方面的学术活动的兴趣，欢迎加入。人工智能社成员可优先提名华为“智能基座”奖学金。

## 5. 结语

这是个专为了培养通信行业所需电子信息人才开设的专业，但是通信行业容不下那么多才俊，因此大家学了个专为通信领域裁剪的电子信息专业。如需转行，请提前完成技能点数分配。