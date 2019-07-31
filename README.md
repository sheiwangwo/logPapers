# log相关文章的简要信息
此处列近两年各个方向较好的会议，和2000年以后四大、四个系统会议上的log相关文章。
---------

 - ASE 18--An Automated Approach to Estimating Code Coverage Measures via Execution Logs
代码覆盖率重要但仅在单元测试和集成测试使用。关注分布式部署和性能开销，使用程序分析技术，从代码中提取log相关的执行路径，在日志文件中检索来评估代码覆盖率。

 - ASE 18--Characterizing the Natural Language Descriptions in Software Logging Statements
关注日志质量和日志语句构建中存在的问题，探究日志中repetitiveness和n-gram model，以及演示日志描述的全局重复性来自动生成日志。

 - ATC 18--Closing the Performance Gap Between Volatile and Persistent Key-Value Stores Using Cross-Referencing Logs
使用cross-referencing logs(CRLs)，对持久内存优化K-V存储的性能。

 - ATC 18--Kernel-Supported Cost-Effective Audit Logging for Causality Tracking
日志在系统中的开销在产生的过程中，传输、存储已经产生。为了提升效率，在内核中设计二级缓存，在不影响取证调查的情况下，防止生成冗余情报。

 - ATC 18--NanoLog: A Nanosecond Scale Logging System
NanoLog通过将工作从运行时热路径转移到应用程序的编译和执行后阶段来实现低延时（8ns）。

 - ATC 18--Troubleshooting Transiently-Recurring Errors in Production Systems with Blame-Proportional Logging
生产系统中暂时性重复问题，很少发生难以检测排除。使用轻量级触发器来识别问题的第一次出现，然后使用它的递归执行过失比例日志记录。

 - CHI 18--Leveraging Community-Generated Videos and Command Logs to Classify and Recommend Software Workflows
复杂软件的用户工作流不是最佳，基于操作视频（带指令）和日志语料库对工作流分类，并进行推荐。

 - FSE-ESEC 18--CloudRaid: Hunting Concurrency Bugs in the Cloud via Log-Mining
分布式并发bug难检测且代价大。提出充分测试的消息排序（部分乱序）可能暴露错误，翻转每一对消息，评估是否可能并行，来测试并行bug。

 - FSE-ESEC 18--Identifying Impactful Service System Problems via Log Analysis
日志数据量大且有分类需求，聚类以及手工验证困难。提出新的层叠聚类算法，通过迭代采样、聚类和匹配日志序列，在保持较高精度的同时，大大节省了聚类时间。

 - FSE-ESEC 18--Using Finite-State Models for Log Differencing
探究不同版本系统的差异性，可以分析已经消除或引入的bug或新功能，以及进行恶意软件的分析。通过日志建立优先状态模型，比较软件版本的差异性。使用2KDIFF比较两个日志之间和nKDIFF输出FSM比较多个日志

 - HPCA 18--Steal but No Force: Efficient Hardware Undo+Redo Logging for Persistent Memory Systems
由于性能和能量开销，在持久内存中采用传统的软件日志记录机制非常昂贵。提出了一个硬件撤销+重做日志记录方案，该方案通过利用商品缓存中使用的写回和写分配策略来维护数据持久性。

 - INFOCOM 18--ADELE: Anomaly Detection from Event Log Empiricism
结合计数器和日志文件，利用机器学习技术，发现系列小故障预警大故障

 - NDSS 18-- Fear and Logging in the Internet of Things
家庭场景物联网攻击调查很重要，日志的设备隔离和设备的各异导致困难。提出了ProvThings，一种以平台为中心的方法来实现物联网中的集中审计，它对物联网应用程序和设备api执行高效的自动化检测得到数据，腿短依赖关系重建事件，最终可面向消费者。

 - NDSS 18--MCI: Modeling-based Causality Inference in Audit Logging for Attack Investigation
提出解决因果分析导致的依赖爆炸，主要依靠插装和修改内核增强收集。不用其他额外操作，直接对日志进行建模，each model is a sequence of system calls that have inter-dependences, some of them caused by memory operations and hence implicit at the system call level.

 - NDSS 18--Towards a Timely Causality Analysis for Enterprise Security
日志因果分析的时效性要求高，之前却被忽视。提出前向后向因果追踪，并在攻击图的构建调查中引入优先级（基于因果关系图的稀疏性和拓扑特征计算因果关系优先级），时间上提升两个数量级。

 - NSDI 18-Prophecy: Accelerating Mobile Page Loads Using Final-state Write Logs
移动设备浏览网页耗费较多带宽和电量，需要移动页面加速技术。通过服务器返回的“write-log”预测提前生成web页面的结构数据，来优化移动页面加载的时间、能源和带宽。

 - OSDI 18--The FuzzyLog: A Partially Ordered Shared Log
The FuzzyLog is a partially ordered shared log abstraction. FuzzyLog applications obtain the benefits of an underlying shared log – extracting strong consistency, durability, and failure atomicity in simple ways.

 - SIGIR 18--LogCanvas: Visualizing Search History Using Knowledge Graphs
一个用于用户搜索历史可视化的平台,帮助用户重新构建搜索活动之间的语义关系，其知识图由每个搜索查询发现的最重要的概念或实体及其关系组成。有助于信息的重新查找，搜索历史记录还有助于协作搜索。

 - SIGIR 18--Online Job Search: Study of Users' Search Behavior using Search Engine Query Logs
利用搜索引擎查询日志，探讨了在线求职的不同特点及其与一般搜索的不同之处。我们的实验结果表明，工作搜索具有特定的属性，可以被搜索引擎用来提高搜索结果的质量。

 - SIGMOD 18--Navigating the Data Lake with Datamaran: Automatically Extracting Structure from Log Datasets
企业积累的大量日志数据成为数据池。未使用、非结构化和未解释的状态，随着它们的积累，使得它们变得不可管理。提出一个从半结构化日志数据集中提取结构的工具，不需要人工监视，将结构化部分（根据不同部分的字段和记录端点得到统一的部分日志，并提取其中的值进行结构化）从非结构化噪声或格式中分离出来。

 - SIGMOD 18--RDSQ: Reliable Queue Protocol over Shared Logs
随着面向消息的中间件作为分布式系统中组件间通信的解决方案的日益普及，在进程崩溃和网络分区等故障场景下设，本文设计并实现一个共享消息队列协议，利用了共享日志服务提供的通信和复制协议。该协议具有高度一致性和持久性，能够容忍客户机故障。

 - VLDB 18--Query Fresh: Log Shipping on Steroids
热备份的安全（需要备份）和最新（需要快速更新重放）的需求一直冲突。提出高效的日志传送方案，它利用NVRAM和RDMA的异步特性，轻松地将网络I/O和重放排除在关键路径之外。并追加存储，设计并行重放方案。保持高性能同时，保持最新。

 - VLDB 18--Scalable Database Logging for Multicores
中央日志存储中的缓冲日志最近面临着一个严重的多核可伸缩性问题，日志刷新受到同步I/O延迟的挑战。设计并实现了一种快速且可伸缩的日志记录方法ELEDA，它可以平稳地将大量事务日志从易失性内存转移到稳定的存储，而不会带来原子性和持久性的风险。ELEDA的核心是一个高度并发的数据结构

 - VLDB 18--SQL Statement Logging for Making SQLite Truly Lite
SQLite由于其轻量在移动设备中受欢迎，但其中的写IO成本，由于logging策略，并不是轻量级的。首先利用非易失性内存(NVM)使逻辑日志实现其全部潜力的工作:可以使用字节寻址的NVM快速编写细粒度逻辑日志，而不需要标准I/O堆栈的开销。结合其他策略将日志性能提高一个数量级。

 - WWW 18--Detecting Absurd Conversations from Intelligent Assistant Logs by Exploiting User Feedback Utterances
为了提高智能助手的转换能力。从日志中提取一些荒谬/可理解的对话，从而训练一个会话分类器，将日志中记录的所有对话分类为荒谬或不荒谬。

 - WWW 18--Discovering Progression Stages in Trillion-Scale Behavior Logs
研究入户在web服务中的行为阶段，提出概率模型，有利于制定业务策略。模型中的每个阶段的特征是操作类型、操作频率和下一步移动的概率分布。并且可在MapReduce框架中处理pb级别数据和万亿次操作。

 - ATC 10--Mining Invariants from Console Logs for System Problem Detection
一种用于异常检测的非结构化日志分析技术，提出了一种自动发现日志中程序不变量的新算法。程序不变量可以从系统的各个方面定义，包括系统度量值(例如CPU和网络利用率)和程序变量（如job id），对其计数建立线性关系检测异常。

 - ATC 11--In-situ MapReduce for Log Processing
处理商用点击日志，机器和日志规模巨大。转移数据到单独的HDFS集群运行MapReduce作业，有IO和时间上的巨大花费求。分析转移到日志服务器本身的就地MapReduce(iMR)体系结构可节约上述，但服务器又其他任务，分析资源受限延迟不可保障。使用连续MapReduce model，有损MapReduce 处理，架构上分布式流处理器、子窗口或者panes。

 - ATC 15--Log2: A Cost-Aware Logging Mechanism for Performance Diagnosis
开发人员预先定义了允许日志记录的资源预算（日志带宽），在运行时日志系统决定是否进行日志记录。两段过滤：一评分（如差异性）删除条目，二评分动态调整输出。

 - CCS 11--Policy Auditing over Incomplete Logs: Theory, Implementation and Applications
设计并实现了一种算法reduce，用于检查审计日志是否符合丰富的隐私和安全策略。reduce对以一阶逻辑表示的策略进行操作，该逻辑允许在无限域上进行有限的量化；对于日志的不完备性，多次迭代，在每个迭代中，可以证明它在当前日志上检查了尽可能多的策略，并输出了一个仅当日志包含额外信息时才可以检查的剩余策略。

 - CCS 13--LogGC: Garbage Collecting Audit Log
审计日志的取证的一个关键挑战是生成的日志文件的大小。一个关键的观察:审计日志中的许多事件条目可以删除，而不会影响将来的法医分析(如因果图)。开发了一个基本的GC算法，它直接作用于审计日志，获取当前的审计日志并生成一个新的和减少的审计日志。

 - CCS 14--POSTER: Scanning-free Personalized Malware Warning System by Learning Implicit Feedback from Detection Logs
传统的反恶意软件系统通过扫描文件系统来检测此类恶意软件，并为用户提供安全的环境。缺点:耗时;某些设置未检测到;警告系统可以在不扫描的情况下检测到未受感染的恶意软件，并具有很高的感染风险。提出了一种基于检测日志和协同过滤(CF)算法的恶意软件检测方法。

 - CCS 14--VerSum: Verifiable Computations over Large Public Logs
计算外包需要可验证性。VERSUM客户机通过比较来自多个服务器的输出来确保输出是正确的。关键思想：将计算表示为一个函数程序，允许对以前的结果进行记忆；将功能程序的评估轨迹记录在计算历史中，识别服务器出错；引入一种新的经过身份验证的数据结构。

 - CCS 16--Poster:Toward Automating the Generation of Malware Analysis Reports Using the Sandbox Logs
恶意软件的新例子不断增加，日志报告语义不可读。ReGenerator通过使用安全公司发布的现有报告，自动生成将沙箱日志生成相近于公司报告的可读内容。

 - CCS 17--DeepLog: Anomaly Detection and Diagnosis from System Logs through Deep Learning
数据众多，且异常检测越来越有挑战性。提出利用长短时记忆(LSTM)对系统日志进行自然语言序列建模的深度神经网络模型DeepLog。使用日志键和其他度量值，小数据训练，可实时反馈调整。

 - EuroSys 06—Predictive Log-Synchronization
为了简化并发数据结构的设计，提出了预测日志同步作为软件事务内存处理的替代模式。它可以通过显著降低并发操作之间的协调开销来提高只读吞吐量，并提供了一种简化并发数据结构的方法。

 - EuroSys 07--Antiquity: Exploiting a Secure Log for Wide-Area Distributed Storage
设计假定所有服务器最终都会失败，并尝试在这些失败的情况下维护数据。ancient使用安全日志来维护数据完整性，在多个服务器上复制每个日志，以确保持久性，并使用动态拜占庭故障olerant quorum协议来确保副本之间的一致性。

 - EuroSys 07--Fine Grained Kernel Logging with KLogger: Experience and Insights
系统的复杂性、并行性，已难以令人理解。KLogger利用框架可以使用事件配置文件专门针对特定的子系统，从而在内核编译时生成特定于事件的代码。得到细粒度的、可伸缩的、高度灵活的内核日志程序。帮助开发者理解系统的运行。

 - EuroSys 17--Online Reconstruction of Structural Information from Datacenter Logs
数据中心管理和诊断的任务中，事务重构的需求，却面对大规模脱机文件，需要定制代码等难题。提出大型数据中心日志记录基础设施中实时恢复结构信息(会话、跨度、调用图、事务树等)的系统TS，它具有低延迟，仅使用少量计算资源。流程：重新排序，重构会话，统计利用模版，实时数据流建图。

 - OSDI 02--ReVirt: Enabling Intrusion Analysis through Virtual-Machine Logging and Replay
ReVirt通过将目标操作系统移动到虚拟机并在虚拟机下面进行日志记录，从而消除了对目标操作系统的依赖。还能够重播虚拟机的完整的逐条指令执行，即使执行依赖于非确定性事件。日志程序与操作系统在不同的域中运行，修改主机内核来记录虚拟机。

 - OSDI 12--Be Conservative: Enhancing Failure Diagnosis with Proactive Logging
在5个系统的调查中发现超过一半的故障中没有记录可检测到的错误，缺少故障相关的错误会导致时候调查费时费力。自动化在代码中插入主动日主语句，以强化故障诊断。它通过在源代码中机械地搜索表5中的七个通用异常模式来识别潜在的异常。

 - SOSP 09--Detecting Large-Scale System Problems by Mining Console Logs
控制台日志未能充分运用，其特点large、 unstructed，需要自动化处理检测异常。结合代码，将控制台日志结构化，选取时间和对象的特征，进行异常检测。代码生成模板，tostring函数填入，与log进行检索得到structured log，时间特征和对象识别建立向量，pca异常检测，将结果可视化为可理解的判断树结构

 - SOSP 13--Tango: Distributed Data Structures over a Shared Log
分布式系统缺少用于存储和访问元数据的类似抽象。为开发人员提供了由共享日志支持的复制的内存数据结构(如映射或树)的抽象。通过简单的附加和读取操作复制共享日志上的状态，而不是复杂的分布式协议;在此过程中，它们从共享日志中获得线性化、持久性和高可用性等特性。

 - SOSP 17--Log20: Fully Automated Optimal Placement of Log Printing Statements under Specified Overhead Threshold
在指定数量的性能开销的约束下，确定代码中日志打印语句的接近最优位置。优选取上，位置在程序所采用的不同执行路径之间的区分能力来度量它的信息化程度，消除路径歧义方面。指标为信息熵（如果路径越不可预测，那么熵也就越大）和运行路径统计频率。

 - SOSP 17--Scaling a file system to many cores using an operation log
文件系统中同时实现多核可伸缩性和高磁盘吞吐量是一个具有挑战性的问题。使用每个内核的操作日志将内存中的文件系统与磁盘上的文件系统解耦。这种设计便于为内存表示使用高度并发的数据结构，它允许交换操作在没有缓存冲突的情况下进行，因此可以完美地伸缩。

 - Usenix security 09-- Efficient Data Structures for Tamper-Evident Logging
日志的真实可用性在很多场景是强需求。开发了一种新的篡改明显的日志设计，它基于一种新的Merkle树数据结构，允许日志记录器生成其正确行为的简洁证明。提出了Merkle aggregation，它允许以可验证的方式将这些属性从叶子聚合到树的根。
