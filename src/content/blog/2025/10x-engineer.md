---
title: '如何成为十倍工程师'
description: '探讨AI时代如何借助工具提升开发效率，成为十倍工程师'
pubDate: 'Nov 18 2025'
heroImage: '../../../assets/images/2025/10x-engineer/blog-placeholder-2.jpg'
---

### 引言
“十倍工程师”（10x engineer）这个说法，是指那些工作效率远超普通工程师的个人。这个概念最早可以追溯到 20 世纪 60 年代的研究，特别是 Frederick P. Brooks 在他的著作《人月神话》（The Mythical Man-Month）中提到的观点。Brooks 指出，在软件开发领域里，某些程序员的工作效率比其他程序员高出很多，甚至能达到十倍之多。这一观察后来被广泛引用，并逐渐演变成今天我们所熟知的“十倍工程师”的概念。

如今有越来越多的 AI 工具宣传能够提高工程师 10 倍的工作效率，包括但不限于 Anthropic、Trae、Devin 等知名 AI 公司。

<!-- 这是一张图片，ocr 内容为：DEEDY SUBSCRIBE @DEEDYDAS EXCITED TO ANNOUNCE THAT WE AT MENLO VENTURES ARE DOUBLING DOWN ON OUR INVESTMENT WITH ANTHROPIC! $61.5B IS A SMALL PRICE FOR 10X'ING EVERY SOFTWARE ENGINEER. ANNOUNCEMENTS ANTHROPIC RAISES SERIES E AT $61.5B POSTMONEYVALUATION 1 MIN READ MAR 3,2025 -->
![](https://cdn.nlark.com/yuque/0/2025/png/34471378/1763362199687-f2efd5fb-9708-484a-add8-0bfc86ded0f8.png)



<!-- 这是一张图片，ocr 内容为：UNDERSTAND.EXECUTE.DELIVER. TRAE IS YOUR IOX AI ENGINEER WHO CAN INDEPENDENTLY BUILD SOFTWARE SOLUTIONS FOR YOU. EXPLORE SOLO DOWNLOAD TRAE ALL DOWNLOADS -->
![](https://cdn.nlark.com/yuque/0/2025/png/34471378/1763361702879-07f52276-e21f-4a85-97e3-41f74941dec0.png)

我最喜欢的吴恩达老师，也曾发表过长文来探讨 AI 如何使“10x”成为可能。吴恩达认为，随着越来越多的工作受到人工智能的支持，不只是“10 倍工程师”，会有更多的“10 倍市场营销人员”“10 倍招聘人员”“10 倍金融分析师”这样的“10 倍专业人士”出现。

<!-- 这是一张图片，ocr 内容为：ANDREW NG @ANDREWYNG A"10X ENGINEER"-A WIDELY ACCEPTED CONCEPT IN TECH-PURPORTEDLY HAS 10 TIMES THE IMPACT OF THE AVERAGE ENGINEER. BUT WE DON'T SEEM TO TALK ABOUT 10X MARKETERS,10X RECRUITERS,OR 10X FINANCIAL ANALYSTS.AS MORE JOBS BECOME AL ENABLED,I THINK THIS WILL CHANGE, AND THERE WILL BE A LOT MORE"10X PROFESSIONALS." THERE AREN'T ALREADY MORE 10X PROFESSIONALS BECAUSE,IN MANY ROLES, THE GAP BETWEEN THE BEST AND THE AVERAGE WORKER HAS A CEILING.NO MATTER HOW ATHLETIC A SUPERMARKET CHECKOUT CLERK IS, THEY'RE NOT LIKELY TO SCAN GROCERIES SO FAST THAT CUSTOMERS GET OUT OF THE STORE 10X FASTER.SIMILARLY, EVEN THE BEST DOCTOR IS UNLIKELY TO MAKE PATIENTS HEAL 10X FASTER THAN AN AVERAGE ONE (BUT TO A SICK PATIENT,EVEN A SMALL DIFFERENCE IS WORTH A LOT). IN MANY JOBS,THE LAWS OF PHYSICS PLACE A LIMIT ON WHAT ANY HUMAN OR AI CAN DO(UNLESS WE COMPLETELY REIMAGINE THAT JOB). BUT FOR MANY JOBS THAT PRIMARILY INVOLVE APPLYING KNOWLEDGE OR PROCESSING INFORMATION,AL WILL BE TRANSFORMATIVE.IN A FEW ROLES,I'M STARTING TO SEE TECH-SAVVY INDIVIDUALS COORDINATE A SUITE OF TECHNOLOGY TOOLS TO DO THINGS DIFFERENTLY AND START TO HAVE,IF NOT YET 10X IMPACT, THEN EASILY 2X IMPACT.I EXPECT THIS GAP TO GROW. 10X ENGINEERS DON'T WRITE CODE 10 TIMES FASTER.INSTEAD, THEY MAKE TECHNICAL ARCHITECTURE DECISIONS THAT RESULT IN DRAMATICALLY BETTER DOWNSTREAM IMPACT,THEY SPOT PROBLEMS AND PRIORITIZE TASKS MORE EFFECTIVELY,AND INSTEAD OF REWRITING 10,OOO LINES OF CODE (OR LABELING 10.000 TRAINING EXAMPLES)THEY MIGHT FIGURE OUT HOW TO WRITE JUST 100 LINES(OR COLLECT 100 EXAMPLES) TO GET THE JOB DONE. I THINK 10X MARKETERS,RECRUITERS,AND ANALYSTS WILL,SIMILARLY,DO THINGS DIFFERENTLY.FOR EXAMPLE,PERHAPS TRADITIONAL MARKETERS REPEATEDLY WRITE SOCIAL MEDIA POSTS.10X MARKETERS MIGHT USE AL TO HELP WRITE,BUT THE TRANSFORMATION WILL GO DEEPER THAN THAT.IF THEY ARE DEEPLY SOPHISTICATED IN HOW TO APPLY AL-IDEALLY ABLE TO WRITE CODE THEMSELVES TO TEST IDEAS, AUTOMATE TASKS,OR ANALYZE DATA-THEY MIGHT END UP RUNNING A LOT MORE -->
![](https://cdn.nlark.com/yuque/0/2025/png/34471378/1763362262469-b64b06e7-3403-4b15-9db9-995a95aa8506.png)

[https://x.com/AndrewYNg/status/1887919658201960807?s=20](https://x.com/AndrewYNg/status/1887919658201960807?s=20)



如果从 chatGPT 发布（2022 年 11 月 30 日）算起，Gen-AI 的风已经吹了 3 年了，Cursor 发布也已经有 2 年了，AI 真的给我们带来了 10 倍的效率吗？如果目前还没有，那要怎么做，才有机会更接近“十倍工程师”呢？

### 一个真实的案例
我想先从我自身出发，聊聊 AI 到底为我带来了多少效率提升。



在谈效率提升之前，我想先谈一谈如何去衡量效率。我们可以首先给效率下这样一个抽象定义：做同一件事，所花费的时间越短，效率越高。但是这样定义是不够的，这样只规定了“时间”，没有规定“质量”。对于软件工程的效率我觉得可以这样定义：做同一件事，以最小代码量实现并且做到bug free的情况下所花费的时间越短，效率越高。这样定义多了两个额外的要求，避免“垃圾代码”和“有问题的代码”。如果不做这两点规定，“提效”从何谈起呢。



我们在这里讨论的开发特指以团队形式开展的大型软件工程项目，不讨论个人项目或者玩具项目。以我参与的一个开源项目 [Chaterm](https://github.com/chaterm/Chaterm)（一款AI Terminal工具） 为例，这个项目的总计代码量在8W左右。原始项目的复杂度对于评估效率很重要，在10W代码量的项目中添加1K行代码，跟在100W代码量的项目中添加1K代码量难度是完全不一样的。

<!-- 这是一张图片，ocr 内容为： CHATERM GIT:(MAIN) CLOC SRC 386 TEXT FILES. 379 UNIQUE FILES. 12  FILES IQNORED. 1 ERROR: LINE COUNT, EXCEEDED TIMEOUT: SRC/MAIN/AGENT/CORE/PROMPTS/SYSTEM.TS GITHUB.COM/ALDANIAL/CLOC V 2.02 T-1.27 S (297.5 FILES/S, 83311.2 LINES/S) BLANK FILES LANGUAGE CODE COMMENT 46132 7208 279 6784 TYPESCRIPT 2407 4271 VUEJS COMPONENT 34456 56 3 LESS 76 410 2398 JAVASCRIPT 39 4 57 1050 32 SVG 0 0 370 121 29 CSS 200 19 195 MARKDOWN 3 HTML 35 379 84836 SUM : 11555 9754 -->
![](https://cdn.nlark.com/yuque/0/2025/png/34471378/1763367204437-8bb5317c-8ded-4c98-bcf8-0088e9459b43.png)

最近我要开发一个新的需求——支持MCP。为完成这个功能，我前后进行了大约10次commit。其中最关键的是下面这两次提交，这两次提交涉及的功能更新共计5000行有效代码。

[feat:Add MCP support part1:UI & McpHub · chaterm/Chaterm@cc2be7a](https://github.com/chaterm/Chaterm/commit/cc2be7a57cc43fbab201bc40a48ca7c7fdd19094)

[feat:Add MCP support part2:integrate MCP tools into agent · chaterm/Chaterm@44e4b8e](https://github.com/chaterm/Chaterm/commit/44e4b8e0bb901b5d15a8d8c29b667ab54e0891d4)

<!-- 这是一张图片，ocr 内容为：FEAT:ADD MCP SUPPORT #1021 EDIT CODE ZHOUYU123666 MERGED 2 COMMITS INTO CHATERM:MAIN MERGED FROM  DSD2077:MAIN 2 WEEKS AGO 凤 CHECKS 4.828-47  CONVERSATION FILES CHANGED COMMITS 0 42 CONTRIBUTOR DSD2077 COMMENTED 3 WEEKS AGO REVIEWERS NO REVIEWS NO DESCRIPTION PROVIDED. ASSIGNEES NO ONE ASSIGNED DSD2077 ADDED 2 COMMITS 3 WEEKS AGO LABELS NONE YET FEAT:ADD MCP SUPPORT PART1:UR & MCPHUB CC2BE7A PROJECTS FEAT:ADD MCP SUPPORT PART2:INTEGRATE MCP TOOLS INTO AGENT 44E4B8E NONE YET -->
![](https://cdn.nlark.com/yuque/0/2025/png/34471378/1763367858616-b653c704-97cb-40f3-90a0-3b448adc46d8.png)

由于项目已经上线三个星期，并未发现bug，所以我单方面判定这5000行代码为合格的代码（如果感兴趣的朋友也可以点开链接帮我review一下）。如果没有AI的帮助，完成这样一个功能我需要花费多少时间呢？我预计大概要一个月左右，算法很简单，假设手敲代码的情况下一天的有效代码量为200~300行，5000行差不多需要一个月时间。



有了AI帮助，我花了多长时间呢？答案是一个多星期，不到两个星期。所以AI对我的提效大概是两到三倍左右。离十倍工程师还有很远的距离。如果想要做到十倍效率，那么完成这次功能应该只需要花费2~3天的时间。这有可能吗？经过复盘，答案是可能的。



下面我将阐述如何成为“十倍工程师”：

整体上可以分成几块：先选择一个顺手的工具，其次调整编程范式，然后是一些AI coding的小技巧，最后通过长期的刻意练习把这些提升沉淀成长期能力。

### 挑选自己最喜欢的AI工具
正所谓“工欲善其事必先利其器”，成为十倍工程师的第一步就是挑选适合自己的AI工具。如今的AI coding产品真的是琳琅满目、遍地开花。

目前市面上已有的AI coding产品主要分为四大类：

+ IDE：Cursor、Windsurf、Kiro、Trae、CodeBuddy、Lingma
+ CLI：Claude Code、OpenAI Codex
+ IDE 插件：GitHub Copilot、Cline、Agument
+ 网页端：Lovable、Replit

对于工具的选择，适合自己的才是最好的，基本上各家都做出了自己的特色。最好的选择方法是都去试一试，看看哪个用起来最顺手。不要看网上那些大V/媒体一天天在那里吹，Claude Code出来就吹CC，Codex出来又吹Codex。这就像有人告诉你在Vim里编程效率很高一样，得实际体验了才知道。



如果你压根就不习惯在terminal里面“敲代码”，那CLI类的产品就不在你的选项范围内。如果你不是专业开发者，那么网页端的产品可能才是你的最佳选择。就我实际体验下来各家产品之间在AI能力方面压根没有那么大差异，所以选一个你用得最顺手的即可。



就我个人而言，偏爱Cursor，核心原因就一个——Cursor的IDE方便我审查代码。其他家的产品这一点做得并不是很好。最近我发现字节的Trae做得也很不错，而且价格也比Cursor便宜，下个月准备切过去试试。



### 做好代码审查
在谈及AI提效时，如果让我选一个原则的话，那一定是“**做好代码审查**”。这就像在使用辅助驾驶时“不要把你的双手脱离方向盘/不要把你的双眼移开路面”一样，**AI coding时尽量不要完全放弃对代码的最终决定权**。



我知道现在有越来越多的人在使用AI coding时，都不再审查代码。他们的做法通常是这样的：给AI下达指令->AI执行coding->运行项目->查看功能是否实现->然后开始跟AI battle：“我要的是这个，不是那个”、“我想要这种实现，不是那种实现”.....“你是傻逼吗”。如果你是一名AI coding实践者，多半也经历过这样令人崩溃的时刻。这是程序猿/攻城狮驯服AI必然会经历的痛苦过程。



我观察到推荐这种方式写代码的，很多都是非专业背景的开发者，而且主要以个人开发者为主，在推特上做build in public（公开构建）的人尤其推崇这种方式。并且通常伴随着他们的“战绩”：从零开始使用AI coding，在多么短的时间内，推出产品，并且做到了多少MRR（月度经常性收入）。



可是大多人不是在做独立开发，而是在企业里做工程师。这两者不都是敲代码，有什么本质区别吗？这里面的区别可大了，如果你是独立开发，我认为你至少要用50%的时间去“卖产品”，用剩余的50%时间去“做产品”，产品做得好不好只决定了你成功的一半，甚至在我看来不到一半。而如果是在企业里面做工程师，你将用绝大部分的时间来“做产品”，而不太需要关心“卖产品”。并且企业中通常是以团队形式进行工程开发，这就使得“代码审查”变得更加重要。



除了代码的质量问题外，代码审查要格外注意一点：代码复用性。目前AI在这个方面还不算擅长，碰到问题，往往会随手写个新的函数出来，而不会优先去考虑代码中已经有可复用的函数，或者相似的逻辑。如果不够慎重，项目就会变得越来越臃肿，最终沦为shi山。

### Spec编程
在我们最开始接触AI coding时，通常的做法是“给AI下达指令->AI执行coding->运行项目->查看功能是否实现”，不断循环这个过程，直到实现我们想要的效果。在业界有一个专有名词来形容这种编程方式——vibe coding（氛围编程）。



经过几个月的实践，我发现vibe coding并非最佳的AI coding姿势。那么正确的姿势是什么呢？这里给大家介绍最近社区很火的另外一种AI coding 理念/范式——Spec编程。



Spec编程的全称是“Spec-Driven Development”，规范驱动开发，Spec是单词specification的缩写。它的核心思想是：把 “规格（spec / specification）” 作为开发的核心驱动力。



如果你上过大学的软件工程课，一下就明白这是什么意思了。软件工程课的大作业要求小组完成一个项目（通常是xxx管理系统），最后不仅需要提交一份代码，还需要提交4个文档，分别是：需求分析、概要设计、详细设计和测试文档。

<!-- 这是一张图片，ocr 内容为：软件工程案例实验 搜索 名称 种类 大小 修改日期 文件夹 0项目管理 今天18:35 文件夹 1需求分析 2022年1月12日23:20 文件夹 2022年11月10日 13:28 2概要设计 文件夹 3详细设计 2024年1月5日22:50 文件夹 今天18:33 4测试文档 文件夹 2022年2月16日 19:43 5CODE 文件夹 课件 2024年1月 5日 22:50 -->
![](https://cdn.nlark.com/yuque/0/2025/png/34471378/1763375778385-af075643-d6ae-4e13-9dd3-d3b94df04481.png)



开源社区有一个项目[GitHub - github/spec-kit: 💫 Toolkit to help you get started with Spec-Driven Development](https://github.com/github/spec-kit)

专门帮助人们采用SSD进行开发。而亚马逊的Kiro直接将Spec设计为一种模式，Spec模式下，在执行代码之前它会为你生成三个文档：

+ requirements.md
+ design.md
+ task_list.md

<!-- 这是一张图片，ocr 内容为：LET'S BUILD PLAN,SEARCH,OR BUILD ANYTHING SPEC VIBE PLAN FIRST,THEN BUILD.CREATE CHAT FIRST,THEN BUILD.EXPLORE IDEAS AND REQUIREMENTS AND DESIGN BEFORE CODING ITERATE AS YOU DISCOVER NEEDS. STARTS. GREAT FOR: THINKING THROUGH FEATURES IN-DEPTH PROJECTS NEEDING UPFRONT PLANNING BUILDING FEATURES IN A STRUCTURED WAY -->
![](https://cdn.nlark.com/yuque/0/2025/png/34471378/1763377303631-4f8f1425-325b-48a1-91f1-fd33f3fc9064.png)

讲到这你以为我是来向你推销Kiro的？哎，猜错啦！spec编程只是一种理念，可以把这种理念运用在任何一款开发工具上。就像面向对象编程一样，用C语言也可以面向对象编程。



我们再来重看Spec编程，思考一下为什么要先有三个文档？

 

我想用这句话来解释是最贴切的：`Plan first, then build`。文档是一种指导，通过文档，我们可以事先知道后面做的事情是不是符合预期。如果不是就**提前纠正**，如果是就开始执行。至于有没有文档，其实不重要。文档的更新最好是事后的，统一的，而不是事先的，零散的。



下面我将演示如何在Cursor中进行Spec编程。



最近我将Chaterm的AI功能从单任务模式扩展到了多任务模式（也就是同时可以执行多个任务）。重构之后出现了一个bug：回传结果时，无法把结果传回到发起请求的Tab。<!-- 这是一张图片，ocr 内容为：点击重启以更新 查看系统版本 10.60.12.46 2000823 SHUDONG_DENGQUBUNTU-GPU-H200-001:~$ CAT /ETC/OS-RELEASE & 查看系统版本 内核版本三 UNAME &&ECHO"S-- A & ECHOSTNAMECTL PRETTY NAMEUNTU 22 U 22.04.5 LTS" NAME''UBUNTU** 发送命令 我将为您查看系统版本信息,包括操作系统版本,内核版本等 VERSION ID-'22.04 详细信息. VERSION"22.04.5 LTS (JAMMY JELLYFISH)" VERSION_CODENAMEJAMMY ID-UBUNTU 内核版 /ETC/OS-REL ECHO CAT EASE ID LIKEDEBIAN 系统信 HOME URL"HTTPS://WWW.UBUNTU.COM/" 本息 && ECHO -A UNAME SUPPORT_URL"HTTPS://HELP.UBUNTU.COM/" & HOSTNAMECTL SHU BUG REPORT URL-"HTTPS://BUAS.LAUNCHPAD.NET/UBUNTU/" PRIVACY POLICY URL-"HTTPS://WWW.UBUNTU.COM/LEGAL/TERMS-AND-POLICIES/PRIVACY-POLICY" UBUNTU_CODENAMEJAMMY 23 LINES OUTPUT 三内核版本 LINUX UBUNTU-GPU-H200-001 5.15.0-126-QENERIC #136-UBUNTU SMP WED NOV 10:38:22 UTC 2024 X86 PRETTY NAME"UBUNTU 22.04.5 LTS" 64 X86_64 X86_64 GNU/LINUX NAME''UBUNTU" 三系统信息: 回传结果 USER_2000823 VERSIONID22204" STATIC HOSTNAME:UBUNTU-GPU-H200-001 VERSION"22.04.5 LTS (JAMMY JELLYFISH)" ICON NAME:COMPUTER-SERVER VERSION_CODENAMEJAMMY SHUDONG_DENG@INTSLG.NE CHASSIS:SERVER SHUDONGDENG ID-UBUNTU MACHINE ID: 901A3D4B467149D09091658A2EFFDFD0 ID LIKEDEBIAN BOOT ID: BBA13650997249F3940C728F213ED179 HOME_URL"HTTPS://WWW.UBUNTU.COM/" 0PERATING SYSTEM:UBUNTU 22.04.5 LTS SUPPORT_URL"HTTPS://HELP.UBUNTU.COM/" KERNEL:LINUX  5.15.0-126-GENERIC BUG REPORT URL-"HTTPS://BUGS.LAUNCHPAD.NET/UBUNTI ARCHITECTURE: X86-64 PRIVACY_POLICY URL-"HTTPS://WWW.UBUNTU.COM/LEGAL, SHUDONG_DENG@UBUNTU-GPU-H200-001:~$ UBUNTU_CODENAMEJAMMY 三内核版本三 LINUX UBUNTU-GPU-H200-001 5.15.0-126-GENERIC #13( SHUDONG-DEN 三系统信息统信息 STATIC HOSTNAME:UBUNTU-GPU-H200-001 ICON NAME:COMPUTER-SERVER CHASSIS:SERVER MACHINEID:901A3D4B467149D09091658A2EFFDF BOOT ID:BBA13650997249F3940C728F213ED1 0PERATING SYSTEM:UBUNTU 22.04.5 LTS KERNEL:L L:LINUX  5.15.0-126-GENERIC USER_2000823 ARCHITECTURE: X86-64 SHUDONG_DENG@INTSIG.NET 开始新任务 -->
![](https://cdn.nlark.com/yuque/0/2025/png/34471378/1763380978037-4b9c57aa-3895-47a5-a39e-bbf21aa0e102.png)

选择**plan mode**，将问题描述丢给AI。它会给出问题的分析和解决方案。

<!-- 这是一张图片，ocr 内容为：PREVIEW` COMPOSER 1 V INDEX.YUE(1789-1794) V INDEX.VUE(238-245) 当前COMMAND模式存在BUG,点击执行命令直接报错,问题出在HANDLEEXECUTECOMMAND透数的接受参 数. 修复命令执行BUG并支持多TAB结果回传 查看主进程中处理 SSH:SHELL:WRITE 的代码,定位 DATA.TRIM()的调用位置: 问题分析 EXPLORED 2 FILES 2 SEARCHOS 查看命令执行结果的处理机制: 1.BUG根源; SSHCONNECT.VUE 的HANDLEFXECUTECOMAND 函数期空损收字行率参数,但实际收到的是对象( CORNAND EXPLORED 1 FILE 2 SEARCHES A,最终在主进程调用 DATA.TRIM()时报错. STRING,TABID7: STRING >, 导致对象被传递给 SENDMARKEDDATA,最终在主 GREPPED CHATERM:COMMAND IN SSHCONNECT.YUE 2.结果回传缺失:当前 HANDLECOMNANDOUTPUT.发送结果时没有携带 带 TABID,无法将结果回传到发起命令的TAB. SEARCHED HOW ARE MARKED COMMAND OUTPUTS HANDLED AND RETURNED TO THE RENDERERER PROCESS? READ SSHCONNECT.VUE L1765-1814 3.多TAB支持:需要建立MARKER到TABLD的映射关系,确保每个命令的执行结果能正确回传到对应的TAB. 查看命令输出处理逻辑: 修复方案 EXPLORED 2 FILES 1 SEARCH READ SSHCONNECT.VUE L1825-2004 READ INDEX.VUE L1-100 1.修复 NAND 参数处理(SRC/RENDER/SRC/VIEWS/CONPONPONENTS/SSH/SSH/SSHCONNECT.VUE) HANDLEEXECUTECOMMAND GREPPED CHAT TOAI IN INDEX.VUE 修改 HANDLEEXECUTECOMAND 函数,正确提取 COMMAND 字符串和 TABID 查看 CHATTOA1 事件的处理逻辑: 建立 MARKER到 TABID 的映射 (使用MAP 存储) EXPLORED 2 FILES 在发送命令时保存映射关系 已分析问题,制定修复方案: 2.修改命令结果回传逻辑(SRC/RENDER/SSHCOMPONECT.VIEWS/COMPONENTS/SSHCONNECT.VUE) -BUG-TAB.PLAN.MD 修复命令执行BUG并支持多TAB结果回传 修改 HANDLECOMMANDOUTPUT 函数,在发送CHATTOAI 事件时携带对应的 TABID 修复HANDLEEXECUTECOMMAND 参数处理BUG,并实现命令执行结果回传到目标TAB的功能,支持多个TAB同 从MARKER映射中查找对应的 TABID,如果找不到则使用当前连接的 TABLD(向后兼容) 时执行命令, 3.更新事件类型定义(SRC/RENDER/SRC/UTILS/EVENTBUS.TS) 4 TO-DOS O 修复HANDLEEXECUTECOMMAND函数,正确提取COMMAND字持承和TABLD,建立MARKER到TABLD的跃射 确保 CHATTOAI 事件类型定义支持(TEXT:STRING;TABID?:STRING)格式(已存在,无需修改) 添加MARKER到TABLD的映射存储机制.使用REF或MAP 存储 4.兼容性处理 修改 HANDLECOMMANDOUTPUT 函数,在发送CHATTOAI 事件时携带对应的 TABLD 保持对旧格式(字符串)的兼容,确保TERM/INDEX.VUE 等其他监听器仍能正常工作 1MORE 确保当TABID 不存在时,行为与之前一致 VIEW PLAN BUILD 3G4 COMPOSER1, 实现细节 文件修改清单 1.SRC/RENDERER/SRC/VIEWS/COMPONENTS/SSH/SSHCONNECT,VUE STEER THE PLAN,OR ADD MORE DETAILS 修改 HAND LEEXECUTECOMMAND 函数(约539行) &二PLANV COMPOSOR 1` -->
![](https://cdn.nlark.com/yuque/0/2025/png/34471378/1763089333086-170a6603-a805-413e-9bbe-f043aac07b5b.png)

看起来AI分析得没毛病，但如果这个时候直接点build，那就完蛋了。这样还是会陷入之前的“审查代码->否定方案->不断与AI校准”的循环中。这个时候我们可以理解为AI给出了一个“需求文档”，但是压根没有说“实现方案”。要知道AI最擅长**一本正经的胡说八道，**即便模型已经迭代多年，但这样的情况还是经常发生。所以不仅要看它怎么说，还要看它怎么做。这个时候要求AI给出实现方案：

> 给出每一个实现的关键细节
>



在AI给出实现细节之后，不要着急点build。这个时候应该去审查实现细节，现在审查要比修改代码之后再审查容易得多。关键就审查两个方面：首先是**数据结构**和**算法**，只要这两点没有问题，那么程序基本上就不会有什么问题；其次是**代码复用性**，看看AI是不是又写了一堆原本就有的新函数。

<!-- 这是一张图片，ocr 内容为：给出每一个实现的关键细节 IF(PROPS.ACTIVETABID PROPS.CURRENTCONNECTIONID) RETURN AND') / COMMAND 可能是对象 SENDMARKEDDATA( COMMAND, CHATERM:COMMAND') TERMINSTANCE.FOCUS( ) 修复后的代码: COMMAND: STRING; TABID?: STRING }) 三> { (PAYLOAD:STRING 子 CONST HANDLEEXECUTECOMMAND IF(PROPS.ACTIVETABID ID !PROPS.CURRENTCONNECTIONID)RETURN //1.提取 COMMAND 字符串 : TYPEOF PAYLOAD - 'STRING' ? PAYLOAD : PAYLOAD?.COMMAND CONST COMMAND IF(!COMMAND) CONSOLE.WARN('HANDLEEXECUTECOMMAND: COMMAND IS EMPTY') RETURN // 2. 提取 TABID (可能为 UNDEFINED) ; 'STRING' ? UNDEFINED : PAYLOAD?.TABID CONST TABID - TYPEOF PAYLOAD //3.生成唯一 MARKER(包含 CO CONNECTIONID,时间戳,随机字符串) CONST UNIQUEHARKERKER-;(HATEM:COMMAND:S(CONNECTIONID.VALUE):S(OATE:NOW():SFMATH, RANDON(),SUBSTR(2,9) //4.保存映射关系 核心逻辑 COMMANDMARKERTOTABID.VALUE.SET(UNIQUEMARKER, TABID) //5.发送命令(使用唯一 MARKER)  SENDMARKEDDATA(COMMAND, UNIQUEMARKER) TERMINSTANCE.FOCUS() 要点: 支持字符串和对象两种格式(向后兼容) 生成唯一MARKER,避免多TAB冲突 保存MARKER TABLD映射 -->
![](https://cdn.nlark.com/yuque/0/2025/png/34471378/1763090101017-96af3ce1-6eb0-4bdd-8b43-faef8e27b083.png)

<!-- 这是一张图片，ocr 内容为：FIX COMMAND EXECUTION BUG AND RESULT HANDLING 给出每一个实现的关键细节 步骤2:添加映射存储数据结构 文件: SRC/RENDERER/SRC/VIEWS/COMPONENTS/SSH/SSHCONNECT.VUE 位置:第2774行附近(与其他REF定义一起) 添加的代码: ( 在 COMMANDOUTPUT 和 ISCOLLECTINGOUTPUT 定义之后添加(约2775行后) - REF(NEW MAP<STRING, STRING | UNDEFINED>()) COMMANDMARKERTOTABLD CONST 数据结构 REF<STRING NULL>(NULL) CONST CURRENTCON TCOMMANDMARKER UNDEFINED>(UNDEFINED) CONST CURRENTCOMMANDTABRD REF<STRING 三 数据结构说明: COMMANDMARKERTOTABID:MAP<MARKER,TABLD>,存储所有活跃命令的映射关系 CURRENTCOMMANDMARKER:当前正在执行的命令的MARKER(用于清理) CURRENTCOMMANDTABID:当前命令对应的 TABLD (用于回传结果) 步骤3:修改 HANDLESERVEROUTPUT 识别MARKER 文件: SRC/RENDERER/SRC/VIEWS/COMPONENTS/SSH/SSHCONNECT.VUE 位置:第1994-2001行 当前代码: 'CHATERM:COMMAND') { L ELSE IF (RESPONSE.MARKER ISCOLLECTINGOUTPUT.VALUETRUE HANDLECOMMANDOUTPUT(DATA,TRUE) 修改后的代码: 'CHATERM:COMMAND' RESPONSE.MARKER?.STARTSWITH('CHATERM:COMMAND:')) { } ELSE IF (RESPONSE.MARKER ISCOLLECTINGOUTPUT.VALUE TRUE //查找对应的 TABID IT TABID - COMMANDMARKERTOTABID.VALUE.GET(RESPONSE.MARKER) 7? CONST TABI COMMANDMARKERTOTABID.VALUE.GET('CHATERM:COMMAND') 7? UNDEFINED //保存当前命令的 MARKER和TABID -->
![](https://cdn.nlark.com/yuque/0/2025/png/34471378/1763090143035-7d3f3613-2547-487b-8c96-f0694eaaac51.png)

AI的实现细节大体上已经没有问题了，但遗漏了一些细节，就是资源清理。AI每一次发送消息，都会将消息映射关系存下来，最后程序终止时才去销毁。假设用户发起了500次交互，就会保留500条映射关系。这显然是不合理的。

```typescript
// 命令 marker 到 tabId 的映射关系，用于将命令执行结果回传到对应的 Tab
const commandMarkerToTabId = ref(new Map<string, string | undefined>())
```

给出下列指令（指令遵循三段论`做什么？怎么做？为什么要这么做？` ）：

> 映射关系的清理需要提前。每一个消息回传之后，立刻清理。不然会堆积越来越来的映射关系
>



<!-- 这是一张图片，ocr 内容为：FIX COMMAND EXECUTION BUG AND RESULT HANDLING 做什么,怎么做,为什么这么做 映射关系的清理需要提前.每一个消息回传之后,立刻清理.不然会堆积越来的映射关系 更新计划:将映射关系清理提前到消息回传时立即执行,避免堆积. RECEIVED INVALID STRING TO REPLACE IN PLAN RECEIVED INVALID STRING TO REPLACE IN PLAN RECEIVED INVALID STRING TO REPLACE IN PLAN 已更新计划,将映射关系清理提前到消息回传时立即执行.关键修改如下: 关键优化:提前清理映射关系 修改后的 HANDLECOMMANDOUTPUT 函数逻辑 清理时机调整:在检测到命令完成后,立即清理映射关系(在发送事件之前) CONST HANDLECOMMANDOUTPUT - (DATA: STRING, ISINITIALCOMMAND: BOOLEAN) CONST CLEANOUTPUT STRIPANSI(DATA).TRIM() COMMANDOUTPUT.VALUE+CLEANOUTPUTPUT+'\N' CONST PROMPTRE IF (PROMPTREGEX.TEST(CLEANOUTPUT)){ ISCOLLECTINGOUTPUT.VALUE FALSE 立即获取并保存 TABID和MARKER CURRENTCOMMANDTABID,VALUE TABID CONST MARKER CURRENTCOMMANDMARKER.VALUE CONST 立即清理映射关系(在发送事件之前,避免堆积) IF (MARKER) COMMANDMARKERTOTABID.VALUE.DELETE(MARKER) LUE NULL CURRENTCOMMANDMARKER.VALUE CURRENTCOMMANDTABID.VALUE UNDEFINED //后续处理输出和发送事件.. NST LINES COMMANDOUTPUT.VALUE CONST T REPLACE(//N/\R/G,'\N') .SPLIT(\N') .FILTER((LINE) LINE.TRIM()) -->
![](https://cdn.nlark.com/yuque/0/2025/png/34471378/1763091186104-05db2752-50a7-412e-94da-0f5b3cae4918.png)

一切就绪点击build，一把就成功。修复这样一个bug只需要10分钟就搞定。如果不这样做，但凡跟AI 多battle两轮，花费的时间就要成倍增加。并且这样写出来的代码，质量有保障。



看着这里，不知道你有没有感到奇怪，说好的AI干活呢？为啥感觉很多事情都是自己在做？AI给出的方案需要自己来确认，AI做错的地方需要自己来纠正，最后AI给出的代码还要自己来审核。这就对了，“十倍工程师”的瓶颈，很大程度上不在AI，而在于使用AI的人。在我看来AI是一个资质普通，但悟性极高的工程师。只要你能告诉它正确的做法，它就能立刻将其实现。在现实中属于那种一点就透的人。

### 善用User Rules & project rules
目前基本上所有的主流编程软件都支持自定义规则（User Rules 和 Project Rules），这是一个被严重低估的功能。通过在项目中设置明确的编码规范、架构约束、命名规则等，你可以让 AI 在生成代码时自动遵循这些约定。例如,你可以指定特定的设计模式、代码风格、甚至是你团队的最佳实践。这样一来,AI 生成的代码质量会显著提升,减少后期审查和修改的工作量。善用这些规则,相当于给 AI 配备了一个"编码指南",让它更懂你的项目需求。



通常而言，User Rules会被置于最高优先级，例如放在System Prompt的最开头或者结尾。以保证AI尽可能遵循用户指令。所以当我们发现AI的回复不符合我们的预期。通过User Rules加以限制是最佳的解决方式。



我的rules中添加了以下几条限制：

```typescript
请慎重的添加注释，遵循《代码简洁之道》

修复bug时，永远记住：第一步先做分析，待用户确认后，再修改代码

修复bug时，如在两步之内未成功，请在第三步添加日志，通过日志定位问题

永远回复中文

给出每一步行动的解释，为什么要这么做

绝不要创建文件，除非这是实现目标绝对必要的。始终优先编辑已有文件，而不是新建文件。
  
绝不要主动创建文档文件（如 *.md 或 README 文件）。只有在用户明确要求时，才可以创建文档文件。

除非我提出明确要求，否则不要创建测试文件，并执行测试
```



### 善用MCP
MCP（Model Context Protocol）是 Anthropic 推出的一项强大功能，它允许 AI 直接与外部工具、数据库、API 进行交互。通过 MCP，你可以让 AI 访问项目文档、查询数据库、调用第三方服务等。



MCP的使用有许多值得探索的地方，很多人觉得MCP没用。其实用好MCP能够极大的自动化工作流程。后面我会再写一篇文章单独来讲如何用好MCP。



这里，我只举一个非常实用的例子。使用AI coding时，我经常会碰到这样一种情况：AI扩展了我的认知边界，也就是AI解决了一个我都不懂的问题。很多人碰到这种情况，接受了AI的代码之后就算结束了。但其实，这恰恰是深入了解和学习新知识的好机会。<font style="color:rgb(51, 51, 51);">"干中学"是对王阳明“知行合一”理念的很好诠释。有AI这个老师，可以让它把每一行代码拆开来讲解。搞懂了还不算结束，真正的高手总是善于总结。我们不是高手，总结也嫌麻烦，但是现在有了AI这个好帮手。</font>



<font style="color:rgb(51, 51, 51);">通过MCP，让AI把问题总结好，并写入到自己的知识库中。可以使用Notion/语雀/obsidian，这里我使用的是我们自己开发的Confluence MCP server，用于连接企业的知识库。</font>



以后隔一段时间，把笔记拿出来看一看，温故知新。

<!-- 这是一张图片，ocr 内容为：分析自动滚动机制的BUG 将该问题总结,然后使用CONFLUENCEMCP写入 RAN CONFLUENCE_SEARCH RAN CONFLUENCE_SEARCH 查找WORK_NOTES页面: RAN CONFLUENCE_GET_PAGE_CHILDREN 总结问题并创建页面.先生成标题和时间: RAN COMMAND:DATE DATE +SY-SM-SD' 2025-11-17 SUCCESS ASK EVERY TIME 创建问题总结页面: RAN CONFLUENCE_CREATE_PAGE ASK EVERY TIME 已创建问题总结页面. 页面信息: 标题:2025-11-17-CHATERM切换TAB后自动滚动失效问题修复 位置: 的主页>WORK_NOTES页面下 页面ID:1060962382 链接: 页面内容包括: 1.问题描述和现象 2.根本原因分析(状态管理,DOM监听器,滚动时机) 3.解决方案(SESSION级别状态,手动重新初始化,滚动逻辑优化) 关键代码修改示例 5.修复效果 6.相关文件 7.经验总结 可随时查看和编辑. 页面已保存到CONFLUENCE, -->
![](https://cdn.nlark.com/yuque/0/2025/png/34471378/1763447959800-6e99c1f0-9c2f-4095-b5f0-0de5f565cc83.png)

### 反直觉的建议
很多人以为在 AI 时代，工程师应该把精力放在“如何更好地使用 AI 工具”上，比如 Prompt Engineering。PE很重要，但不是根本。真正能让你脱颖而出的，仍然是你作为软件工程师的基本功。

以下这些乍看“反直觉”的建议，才迈向“十倍工程师”的关键：

+ 比以往任何时候都更深入理解你所使用的语言

不是泛泛地“会用”，而是深入到语言的类型系统、运行时机制、内存模型、并发模型等底层细节。  
原因很简单：当 AI 给出一段代码时，你需要有能力判断其是否正确、是否高效、是否踩了底层机制的坑。AI真的太容易写出看似正确的代码了。稍不注意就会被带入坑里。每次纠正它时，它只会说：你说得太对了！

+ 比以往任何时候都更深入理解你所使用的框架

理解框架的运行机制、生命周期、数据流、性能瓶颈，你才能指导 AI 写出“符合框架最佳实践”的代码。如果对框架的理解不够深入，就只能接受AI写出的看似work的代码。这方面也是踩了很多坑。

+ 掌握好数据结构和算法

即使 AI 能写代码，数据结构和算法仍是软件工程的“终极底层逻辑”。  
你需要知道什么结构适合什么场景、复杂度如何。这样你才能判断 AI 是否给了你一个不错的解法，而不是由if else堆砌起来的shi山代码。

+ 熟读设计模式

设计模式本质是一套“如何写出可维护代码”的经验总结。当需求变更、功能增加时，一个结构清晰、职责明确的模式可以让你改动最少的代码，而不是把整个系统拆掉重来。正如我前面所说，AI真的很容易写出if else垃圾代码。AI 能写代码，但 AI 不会替你做架构决策，不会为你考虑项目未来的可扩展性。设计模式正是这种结构性思考的核心能力。未来的工程师角色将会变成：**你负责思考结构，让 AI 去实现细节。**



做这一切为了：更好的审查AI的代码、更好的指导编写代码。终极目标只有一个：成为架构师。未来的开发工作模式就是一个人指导一堆Agent干活。



### 成本
最后我想谈一谈成本。过去一个月，我在 Cursor 上的花费大约是 60~70 刀，还未达到 Cursor 和 Claude 设定的最高档 200 刀。这可能也是我没有成为"十倍工程师"的原因之一——用量没有达到十倍，效率自然也无法达到十倍。



这里说的“用量”，不是为了刷额度而瞎问，而是尽可能让AI多参与真实的工程任务：写代码、查问题、改设计，然后由自己认真审查和纠偏。高用量的本质，其实是你和AI之间形成了高频的反馈循环——你越会用它，它也就越能帮你把效率拉高。



我知道有些很厉害的工程师很早之前就就已经达到200刀配置限制。当时我并没意识到他们对AI的利用已经达到何种程度。大家可以试一下，就算不审查代码，仅以实际运行来判断AI生成代码的可靠性这种方式来使用AI，要达到200刀的使用限额，都是一件非常困难的事。



等到我的用量达到200刀一个月时，我会再写一篇文章阐述我的实践。

### 展望
想要成为“十倍工程师”，不管有没有AI都不是一件容易的事情。但AI的出现确实为我们提供了一种可能,将AI作为放大你能力的杠杆。关键在于,你要先成为一个优秀的工程师,才能借助AI成为"十倍工程师"。再此基础上通过刻意练习，来无限的接近这一目标。



如果你做的是大型软件工程项目，预计在未来三到五年内，可能都无法做到“脱手”让AI自己去干。在这段时间里，我们能做是把AI擅长的发挥到极致，并借此提升自身的能力以适应未来世界对工程师的要求。



拥抱时代的人，永远不会被时代抛弃



完~

作者：dsd2077

时间：2025.11.18  


