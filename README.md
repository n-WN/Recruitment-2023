# USTC NEBULA 2023 招新安排

      ┌---------------------------------------------------------┐
     ███╗   ██╗███████╗██████╗ ██╗   ██╗██╗      █████╗         │
     ████╗  ██║██╔════╝██╔══██╗██║   ██║██║     ██╔══██╗        │
     ██╔██╗ ██║█████╗  ██████╔╝██║   ██║██║     ███████║        │
     ██║╚██╗██║██╔══╝  ██╔══██╗██║   ██║██║     ██╔══██║        │
     ██║ ╚████║███████╗██████╔╝╚██████╔╝███████╗██║  ██║        │
     ╚═╝  ╚═══╝╚══════╝╚═════╝  ╚═════╝ ╚══════╝╚═╝  ╚═╝        │
      │                                                         │
      │                                      Join us:           │
      │                                                         │
      └---------------------------------------------------------┘

## 目录

- [重要时间节点](#重要时间节点)
- [学习资料与练习平台](#学习资料与练习平台)
    - [通用资料](#通用资料)
    - [逆向 (Reverse)](#逆向-Reverse)
    - [二进制漏洞利用 (Pwn)](#二进制漏洞利用-Pwn)
    - [Web (Web)](#Web-Web)
    - [密码学 (Crypto)](#密码学-Crypto)
    - [杂项 (Misc)](#杂项-Misc)
    - [讨论与求助](#讨论与求助)
- [各方向招新选拔要求](#各方向招新选拔要求)
    - [通用](#通用)
    - [逆向 (Reverse)](#逆向-Reverse-1)
    - [二进制漏洞利用 (Pwn)](#二进制漏洞利用-Pwn-1)
    - [Web (Web)](#Web-Web-1)
    - [密码学 (Crypto)](#密码学-Crypto-1)
    - [杂项 (Misc)](#杂项-Misc-1)
- [附录：联系方式](#附录：联系方式)

---

## 重要时间节点

招新开始时间：北京时间 2023 年 10 月

招新截止时间：北京时间 2023 年 10 月 31 日 23:59:59，有特殊情况可联系说明

---

## 学习资料与练习平台

### 通用资料

- [CTF-wiki](https://github.com/ctf-wiki/ctf-wiki) ( [https://ctf-wiki.org/](https://ctf-wiki.org/) )

- [CTF-All-in-One](https://github.com/firmianay/CTF-All-In-One) ( https://github.com/firmianay/CTF-All-In-One )

- [Nebula-CTFTeam/CTF_101](https://github.com/Nebula-CTFTeam/CTF_101) ( https://github.com/Nebula-CTFTeam/CTF_101 )

    - 供新人参考的新生赛的题解，招新期间我们也会把合适的比赛发到招新群中并在赛后即时发布题解供大家参考学习

> **记得学习 CTF 最重要的是实践而不是看书**
>
> **大家也不要花很多精力去配置各种所谓的“工具集”，重要的还是在做题中积累经验**

---

### 逆向 (Reverse)

建议：多实践，实践到瓶颈就会找到理论学习的方向

书籍：
- 《深入理解计算机系统》（前三章）
- 《加密与解密》（工具书）
- 《逆向工程核心原理》（如果喜欢看书学习）

资料：信安实践逆向教材

题库：https://buuoj.cn/

---

### 二进制漏洞利用 (Pwn)

1. https://pwnable.kr/

2. https://pwnable.tw/

3. 以往比赛题（国内比赛基本可以在 buuctf 练习平台里找到）

4. 安全客、先知、看雪等平台的文章

强烈推荐 pwnable.kr 和 pwnable.tw（tw 题偏难，适合基础掌握后去看），如果觉得都太难了可以做 buuctf 的题

工具：pwntools、gdb (with pwndbg 插件)、IDA Pro、各种 ubuntu 发行版、ROPgadget 等

---

### Web (Web)

需要了解的知识：HTTP 协议、JavaScript、PHP、Python、Flask、Nginx、Apache、SQL等；

工具：浏览器开发者工具、Burpsuite、sqlmap、nmap 等；

常见漏洞：SQL 注入、XSS 跨站脚本、CSRF 跨站请求伪造、文件上传、文件包含、框架安全、PHP 常见漏洞、Python 常见漏洞、代码审计等；

资料：通用资料和 https://websec.readthedocs.io/zh/latest/ ；

---

### 密码学 (Crypto)

工具：Python、SageMath、RsaCtfTool 等，重要的在于积累各种类型题的解题脚本

学习资料：基础部分可以参考上面的通用资料，进阶可以看知名比赛题目的 writeup

练习平台：
- https://crypto.sqrt-1.me/（zzh 前辈搭建的练习平台）

- https://cryptohack.org/

---

### 杂项 (Misc)

Misc 方向内部可以细分为很多领域，如：

- Stego（隐写）
- Forensics（取证）
- Recon（信息搜集，包括 OSINT 等）
- ...

此外，有时 AI Security 和区块链安全也会算在 Misc 方向。

#### 入门

国内一些比赛和国外一些小型 CTF 竞赛对于隐写、取证、信息搜集方面的考查较多，且简单的题目以对工具的使用为主，不涉及繁杂的代码编写。对于基础比较薄弱的同学，可以考虑从这里入手训练。

以下是一些靶场推荐：
- [picoCTF](https://picoctf.org)
- [BUUCTF 在线评测](https://buuoj.cn/)

除此之外，可以参加一些国外的小比赛进行训练。

需要留意的是，这类题目会出现一些被称为“脑洞题”、“套娃题”的低质量题目。

#### 进阶

在困难的国际比赛中，Misc 选手需要具备广博的知识面和快速学习的能力，**任何题目都可能出现在 Misc 分类中**。

以下是一些具体的例子：

- zer0pts CTF 2023：侧信道攻击
- HITCON CTF 2023：逆向工程、二进制漏洞利用、socket 编程
- （某一次比赛，忘了名字）：Android 逆向获取 API，然后 SQL 注入

不过一般而言，这类题目不会像各方向专门的题目一样困难。

---

### 讨论与求助

- 遇到问题首选解决方案是上网搜索；

- 在招新群里问（见附录： 联系方式）；

- 直接问各方向 mentor（见附录： 联系方式）；

- 遇到不会的题目可以搜“题目名称 writeup”，大概率会有别人的 writeup（解题报告），但是一定要自己理解，不能直接照抄;

---

## 各方向招新选拔要求

**注意：**

- 所有选拔标准均不限学院、不限年级、不限成绩（，但是要求是科大在校生）；

- 所有选拔标准均为参考标准，并非绝对，我们会根据实际情况调整；

- 题目不必要独立完成，Google / 群里讨论 / 找 mentor 都是有效的解决方法，但是一定要自己理解后做出，不能直接照抄；

- 提前完成或达到选拔标准的同学，可以主动联系 mentor 提前开始正式队内训练；

- 选拔划分方向仅供不明确自己兴趣爱好的同学参考，如果你对多个方向感兴趣，可以考虑联系战队负责同学。无论通过何种选拔方式进入战队，以后均可自由选择自己感兴趣的方向，没有任何限制；

- 以下各方向完成任意一个即可：

### 通用

Hackergame 校内获奖（包括特别奖项）；

### 逆向 (Reverse)

常识上，你最好：

- 懂科学上网
- 熟悉C语言，尤其是数据类型和指针
- 能独立配置Python环境，知晓如何安装第三方库，能写出20行以上的Python脚本帮助自己解决问题
- 有linux环境（VMware, WSL等）
- 能成功安装IDA Pro 7.5+，并深刻认识到F5的含金量

训练量上，你至少需要：
- 完成[buuoj](https://buuoj.cn/)上reverse方向第一页的32题，可以参考网上的Writeup
- 挑选其中5题写详细的Writeup供mentor考察和指导

训练效果上，你将：
- 能使用IDA Pro静态分析二进制文件
- 能在汇编层面上调试二进制文件（能使用Ollydbg, x64dbg, gdb, windbg的其中至少一种）
- 熟悉逆向中常用的加密或编码方法，并能借助工具或自行写代码解密（RC4, TEA, RSA, AES, base64等）
- 对以下关键词不感到陌生：
  "栈"，"寄存器"，"混淆"，"反调试"，"加壳/查壳/脱壳"，"花指令"

### 二进制漏洞利用 (Pwn)

两项任选其一完成即可:

1. pwnable.tw 任意 2 题（较困难, 建议选择 start 和 calc 两题）

2. `nc pwnable.nebuu.la 80` 任意两题（附件见 attachement 链接）

**并且能够解释自己的 writeup（解题报告）**


### Web (Web)

ctfhub 技能树( https://www.ctfhub.com/#/skilltree ) web 分枝下信息泄露， SQL 注入，XSS ，文件上传几项中共选择 5 题，并简单记录解题过程

### 密码学 (Crypto)

Hackergame 密码学题目（具体列表比赛开始后公布）任意两题

或 https://crypto.sqrt-1.me/ 任意 10 题

或 https://cryptohack.org/ 任意 10 题（前两个分类和问答题除外）

或找 mentor 根据自身基础和兴趣个性化定制任务

请大家保留自己的解题代码，要求大家能够讲清楚解题思路及原理

### 杂项 (Misc)

以下条件满足其一即可：

- Hackergame general 分类校内排名前 30
- picoCTF 练习题 General Skills 和 Forensics 分类共 99 题，完成 25 题
- 如果你有某方面的兴趣或特长，可以找 mentor 定制任务

---

## 附录：联系方式

NEBULA 2023 招新群 QQ：476033823

**如果是一般的题目问题，请直接在群里提问；**

**如果有不方便在群里问的问题，可以联系群管理员中对应方向的 mentor（mentor 有自己的学习科研任务，可能很忙，如果照顾不过来请谅解）；**

（括号内为 QQ 尾号，详见招新群管理员列表）
- Web: 
    - 17*****424 (wy)
    - 12*****716 (danqi)
- Pwn: 
    - 27*****628 (eastXueLian)
    - 10*****394 (lrcno6)
- Crypto: 
    - 11*****972 (brealid)
- Misc:
    - Blockchain: 61*****91 ([hklst4r](https://github.com/hklst4r/))
    - General: 8*****389 ([Crabtux](https://github.com/Crabtux))
    - AISec: 17*****192 (abd)
- Reverse: 
    - 22*****204 (0xd009)
