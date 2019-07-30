ASE 18--An Automated Approach to Estimating Code Coverage Measures via Execution Logs
代码覆盖率重要但仅在单元测试和集成测试使用。关注分布式部署和性能开销，使用程序分析技术，从代码中提取log相关的执行路径，在日志文件中检索来评估代码覆盖率。

ASE 18--Characterizing the Natural Language Descriptions in Software Logging Statements
关注日志质量和日志语句构建中存在的问题，探究日志中repetitiveness和n-gram model，以及演示日志描述的全局重复性来自动生成日志。

Atc 18--Closing the Performance Gap Between Volatile and Persistent Key-Value Stores Using Cross-Referencing Logs
使用cross-referencing logs(CRLs)，对持久内存优化K-V存储的性能。

Atc 18--Kernel-Supported Cost-Effective Audit Logging for Causality Tracking
日志在系统中的开销在产生的过程中，传输、存储已经产生。为了提升效率，在内核中设计二级缓存，在不影响取证调查的情况下，防止生成冗余情报。

Atc 18--NanoLog: A Nanosecond Scale Logging System
NanoLog通过将工作从运行时热路径转移到应用程序的编译和执行后阶段来实现低延时（8ns）。

ATC 18--Troubleshooting Transiently-Recurring Errors in Production Systems with Blame-Proportional Logging
生产系统中暂时性重复问题，很少发生难以检测排除。

CHI 18--Leveraging Community-Generated Videos and Command Logs to Classify and Recommend Software Workflows
复杂软件的用户工作流不是最佳，基于操作视频（带指令）和日志语料库对工作流分类，并进行推荐。

FSE-ESEC 18--CloudRaid: Hunting Concurrency Bugs in the Cloud via Log-Mining
分布式并发bug难检测且代价大。提出充分测试的消息排序（部分乱序）可能暴露错误，翻转每一对消息，评估是否可能并行，来测试并行bug。

FSE-ESEC 18--Identifying Impactful Service System Problems via Log Analysis
日志数据量大且有分类需求，聚类以及手工验证困难。提出新的层叠聚类算法，通过迭代采样、聚类和匹配日志序列，在保持较高精度的同时，大大节省了聚类时间。

FSE-ESEC 18--Using Finite-State Models for Log Differencing
探究不同版本系统的差异性，可以分析已经消除或引入的bug或新功能，以及进行恶意软件的分析。通过日志建立优先状态模型，比较软件版本的差异性。使用2KDIFF比较两个日志之间和nKDIFF输出FSM比较多个日志

HPCA 18--Steal but No Force: Efficient Hardware Undo+Redo Logging for Persistent Memory Systems
由于性能和能量开销，在持久内存中采用传统的软件日志记录机制非常昂贵。提出了一个硬件撤销+重做日志记录方案，该方案通过利用商品缓存中使用的写回和写分配策略来维护数据持久性。

INFOCOM 18--ADELE: Anomaly Detection from Event Log Empiricism
结合计数器和日志文件，利用机器学习技术，发现系列小故障预警大故障

NDSS 18-- Fear and Logging in the Internet of Things


NDSS 18--MCI: Modeling-based Causality Inference in Audit Logging for Attack Investigation

NDSS 18--Towards a Timely Causality Analysis for Enterprise Security

NSDI Prophecy: Accelerating Mobile Page Loads Using Final-state Write Logs

OSDI 18--The FuzzyLog: A Partially Ordered Shared Log

SIGIR 18--LogCanvas: Visualizing Search History Using Knowledge Graphs

SIGIR 18--Online Job Search: Study of Users' Search Behavior using Search Engine Query Logs

SIGMOD 18--Navigating the Data Lake with Datamaran: Automatically Extracting Structure from Log Datasets

SIGMOD 18--RDSQ: Reliable Queue Protocol over Shared Logs

SIGMOD 18--Splaying Log-Structured Merge-Trees

VLDB 18--An Analytical Study of Large SPARQL Query Logs

VLDB 18--Concurrent LogStructured Memory for ManyCore KeyValue Stores

VLDB 18--FineLine: Logstructured Transactional Storage and Recovery

VLDB 18--Query Fresh: Log Shipping on Steroids

VLDB 18--Scalable Database Logging for Multicores

VLDB 18--SQL Statement Logging for Making SQLite Truly Lite

ATC 10--Mining Invariants from Console Logs for System Problem Detection

ATC 11--In-situ MapReduce for Log Processing

ATC 15--Log2: A Cost-Aware Logging Mechanism for Performance Diagnosis

ATC 16--ParaFS: A Log-Structured File System to Exploit the Internal Parallelism of Flash Devices

ATC 17--Log-Structured Non-Volatile Main Memory

ATC 17-- TRIAD: Creating Synergies Between Memory, Disk and Log in Log Structured Key-Value Stores

CCS 11--Policy Auditing over Incomplete Logs: Theory, Implementation and Applications

CCS 13--LogGC: Garbage Collecting Audit Log

CCS 14--POSTER: Scanning-free Personalized Malware Warning System by Learning Implicit Feedback from Detection Logs

CCS 14--VerSum: Verifiable Computations over Large Public Logs

CCS 16--Poster:Toward Automating the Generation of Malware Analysis Reports Using the Sandbox Logs

CCS 17--DeepLog: Anomaly Detection and Diagnosis from System Logs through Deep Learning

EuroSys 06—Predictive Log-Synchronization

EuroSys 07--Antiquity: Exploiting a Secure Log for Wide-Area Distributed Storage

EuroSys 07--Fine Grained Kernel Logging with KLogger: Experience and Insights

EuroSys 13--RapiLog: Reducing System Complexity Through Verification

EuroSys 15--Scaling Concurrent Log-Structured Data Stores

EuroSys 17--Online Reconstruction of Structural Information from Datacenter Logs

OSDI 02--ReVirt: Enabling Intrusion Analysis through Virtual-Machine Logging and Replay

OSDI 12--Be Conservative: Enhancing Failure Diagnosis with Proactive Logging

SOSP 09--Detecting Large-Scale System Problems by Mining Console Logs

SOSP 13--Tango: Distributed Data Structures over a Shared Log

SOSP 17--Log20: Fully Automated Optimal Placement of Log Printing Statements under Specified Overhead Threshold

SOSP 17--Scaling a file system to many cores using an operation log

Usenix security 09-- Efficient Data Structures for Tamper-Evident Logging