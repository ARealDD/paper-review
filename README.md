# paper-review

### Life Cycles

通过生命周期图和简介，介绍了主流的软件过程模型。

可以参考其生命周期图的画法。

### 一种基于组织实体能力的软件过程建模方法

组织实体可以理解为软件的开发者团队，该方法主要是将组织实体的 目标、技能、知识、生产率、经验、历史数据记录、设备等情况作为其能力的评估，纳入到开发过程中作为参考。

可以参考其工作过程图的画法。

![工作过程图](https://github.com/ARealDD/paper-review/blob/main/img/Snipaste_2021-04-21_21-01-41.jpg)

### 软件过程建模方法研究

软件过程建模的主要目的是建立软件过程的抽象模型，通过对该抽象模型的分析增加对过程本身的理解和认识，从而可以更好地实施软件开发活动。对软件过程建模方法的研究主要是围绕着过程建模语言和以过程为中心的软件工程环境(process-centered  software engineering environment，简称 PSEE)展开的。

本文采用系统评价(systematic review)方法对软件过程建模领域最近 10 年的主要研究进行了概括和分析。主要关注三个问题： 

##### 问题 1:软件过程建模方法主要基于什么范式? 

结论：可以归纳为以下四种： 静态关联的元素、顺序执行的活动 、并发交互的活动 、隐含的并发活动 

##### 问题 2：软件过程建模方法研究的主要目的集中在哪些方面? 

结论：可以归纳为以下四种：文档化、分析、执行、演化

##### 问题 3：软件过程建模方法的研究有哪些新的趋势? 

结论： 分布式或者全球开发、  软件过程技术实施 

本文比较全面地阐述了软件过程模型应该关注的问题，提供了大量可以参考的英文文献及其简介，同时给出了一个形式化定义模型作为参考。

### 基于程序生成的软件过程模型

一篇92年的文章。主题与课题非常接近，定义了一种名为EASYCODE的过程模型。这是一个适用于特定环境（DP/MIS，即付款交单 /信息管理系统）的集成化计算机辅助软件工程（CASE）环境，可以自动生成可执行代码。

区别在于，首先，本文定义了三类描述语言：应用定义语言ADL，结构定义语言SDL和映像定义语言MDL。其特点是面向过程的、具有数学严密性的。

本文的工作更加类似RM2PT的工作内容，可以借鉴的是其对软件过程模型的描述部分，本文采取了与瀑布模型对比的方式，给出了4大优势。

### 支持可执行定义的进化式软件开发模型

本文与其他切实的模型不同，更多的是一种方法论上的指导，属于对一类具体开发模型的抽象。其关注的主要是需求工程问题，且参考了快速原型方法。

本文的特点是比较完整地描述了一个软件开发（过程）模型。文章定义了12种角色：人员、问题、方案、理由、构件、变换、提出、解决、支持、引用、进化、产生和组成；并定义了数条规则和变换类型。

可以借鉴的是本文非常详细的描述方法。本文采用了大量的数学语言和示意图，显得非常专业。

### Towards a New Approach on Software Process Evolution 

本文主要关注的是开发过程中软件过程模型的变化和演化。文章把软件过程用一系列的逻辑规则来表示，只有当一条规则的条件部分被满足时，才会执行规则结论部分所对应的活动。贯彻了软件过程是软件的思想。

可以借鉴的是本文使用描述软件的方法描述软件过程。其将软件过程分为控制流和数据流，将过程中使用的数据和文档充入数据流，将规则的条件部分对应的活动充入控制流。

### A user-centered behavioral software development model 

本文是对敏捷方法的一种拓展，提出用“行为”代替“测试”，使用一种类似自然语言的、包括given、when和then的语言描述场景和用户故事，并自动生成简单测试用例。

本文最值得借鉴的部分是其研究设计模块。由于敏捷方法不依托工具，其方法自由度高，形式化程度低，对新模型的验证是主要关注的问题。本文使用了三角法（ triangulation method ）评估模型，第一阶段包括论文阅读、需求分析和模型提议；第二部分包括模型验证和模型改善。

![研究设计](https://github.com/ARealDD/paper-review/blob/main/img/Snipaste_2021-04-21_21-02-13.jpg)
