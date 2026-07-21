# 殷刚 · 作品集 / Portfolio

> **自动化测试系统研发工程师** · 9 年工作经验 · 坐标武汉
> 专注工业上位机、高速数据采集、多协议通信与后端微服务架构

<p>
  <a href="mailto:wygk163@163.com"><img src="https://img.shields.io/badge/Email-wygk163@163.com-red?style=flat-square&logo=gmail&logoColor=white" alt="Email"></a>
  <img src="https://img.shields.io/badge/Phone-188 2751 8603-blue?style=flat-square&logo=whatsapp&logoColor=white" alt="Phone">
  <img src="https://img.shields.io/badge/City-武汉-green?style=flat-square&logo=googlemaps&logoColor=white" alt="City">
  <img src="https://img.shields.io/badge/经验-9年-orange?style=flat-square" alt="Experience">
</p>

---

## 👋 个人简介

9 年 C#/.NET 全栈研发经验，擅长**工业自动化测试系统**与**上位机软件**的从 0 到 1 独立研发。
从需求分析、架构设计到编码、联调、验收交付具备完整闭环能力，同时具备 C/C++ 高性能算法封装与
后端微服务架构落地经验。曾独立主导多个工业级项目，并带领小型团队完成 MES、WMS 等系统的建设与推广。

- 🎯 **求职意向**：自动化测试系统研发工程师（期望城市：武汉）
- 🧩 **核心方向**：上位机开发 · 高速数据采集 · 多协议通信驱动 · 数字孪生可视化 · 微服务架构
- 🛠 **工作方式**：独立主导 + 团队协作，注重代码规范与 CI 流程建设

---

## 🧰 技术栈

**编程语言**

![C#](https://img.shields.io/badge/C%23-.NET%20%2F%20.NET%20Core-512BD4?style=flat-square&logo=csharp&logoColor=white)
![C++](https://img.shields.io/badge/C%2FC%2B%2B-高性能算法-00599C?style=flat-square&logo=cplusplus&logoColor=white)
![Python](https://img.shields.io/badge/Python-熟悉-3776AB?style=flat-square&logo=python&logoColor=white)
![LabVIEW](https://img.shields.io/badge/LabVIEW-自动化测试-FFDB00?style=flat-square)

**上位机 / 桌面开发**

![WinForm](https://img.shields.io/badge/WinForm-GDI%2B%20%2F%20DevExpress-512BD4?style=flat-square&logo=dotnet&logoColor=white)
![WPF](https://img.shields.io/badge/WPF-桌面开发-0078D6?style=flat-square&logo=windows&logoColor=white)
![VTK](https://img.shields.io/badge/VTK-三维可视化-8A2BE2?style=flat-square)

**通信协议 / 硬件接口**

`串口` · `TCP/IP` · `UDP` · `Modbus RTU/TCP/UDP` · `CAN / CANFD（周立功、广成）` · `PLC（西门子 S7）` · `熟悉 EtherCAT 总线架构`

**图像采集 / 处理**

`工业相机 / 摄像头图像采集` · `OpenCV（二维码识别等图像处理）`

**后端 / 架构 / 中间件**

![Nginx](https://img.shields.io/badge/Nginx-负载均衡-009639?style=flat-square&logo=nginx&logoColor=white)
![Ocelot](https://img.shields.io/badge/Ocelot%2BConsul-微服务网关-5C2D91?style=flat-square)
![Kafka](https://img.shields.io/badge/Kafka-消息队列-231F20?style=flat-square&logo=apachekafka&logoColor=white)
![RabbitMQ](https://img.shields.io/badge/RabbitMQ-消息队列-FF6600?style=flat-square&logo=rabbitmq&logoColor=white)
![Docker](https://img.shields.io/badge/Docker%2FK8S-容器化-2496ED?style=flat-square&logo=docker&logoColor=white)

**数据库 / 存储**

![MySQL](https://img.shields.io/badge/MySQL-主从%2F分库分表%2FSQL优化-4479A1?style=flat-square&logo=mysql&logoColor=white)
![SQLServer](https://img.shields.io/badge/SQL%20Server-精通-CC2927?style=flat-square&logo=microsoftsqlserver&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-缓存-DC382D?style=flat-square&logo=redis&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-熟练-47A248?style=flat-square&logo=mongodb&logoColor=white)
![Elasticsearch](https://img.shields.io/badge/Elasticsearch-熟练-005571?style=flat-square&logo=elasticsearch&logoColor=white)

**其他**：多线程 / 委托 / 反射 / 队列 / 内存管理 · Apollo 配置中心 · SkyWalking 链路追踪 · ELK

---

## 🚀 重点项目经历

### 【项目一】高速数据采集与自动化测试软件
`C# / C++ / WinForm / 多协议通信` · `2022.10 — 至今` · **独立开发者**

> 面向工业自动化测试场景的高速数据采集系统，支持多种工业通信协议，实现采集配置、实时解析显示与后处理分析。负责从架构设计到交付的全部工作。

- 设计多协议通信驱动层（串口 / TCP / UDP / Modbus RTU/TCP/UDP / CAN / CANFD），统一设备接入接口，支持 10+ 类型设备即插即用
- 对接 PLC（西门子 S7）读写与工业相机/摄像头图像采集，集成 OpenCV 实现二维码识别，实现设备参数配置、实时监控与联动
- 实现生产者-消费者多线程采集架构（队列 + 委托），解决高速数据场景下的零丢包与实时刷新问题
- 开发数据后处理模块：波形回放、数据筛选、异常标记与统计分析报表导出，显著提升测试效率
- 封装 C++ 高性能信号处理算法，通过 P/Invoke 集成至 C# 主程序，处理性能提升 60%+

---

### 【项目二】结构健康监测数字孪生平台
`C# / VTK / LUNA / TDS / ANSYS` · `2023.05 — 2024.06` · **C# 侧唯一开发者**

> 基于数字孪生技术，将 LUNA、TDS 等物理传感设备的实时数据与三维模型可视化融合，并与 ANSYS 仿真结果动态比对，用于结构健康监测与模型参数持续修正。

- 完成 VTK 三维模型加载与渲染方案设计，在模型表面标记测点，实现应力/应变空间直观展示
- 完成与 LUNA 光纤传感设备、TDS 数据采集仪的通信协议解析与联调，实时接入应变、温度等多通道数据
- 开发动态数据映射模块，将实时采集值叠加渲染至三维模型测点，支持颜色云图 + 数值标注双模式
- 构建 ANSYS 仿真数据导入解析管道，仿真场与实测数据在同一三维空间对比可视化，辅助模型验证
- 设计参数反演迭代流程，基于实测与仿真偏差持续修正材料参数与边界条件，提升仿真模型置信度
- 实现历史数据回放功能，按时间轴重现结构状态演变，辅助故障溯源与寿命预测

---

### 【项目三】民航自动气象观测系统
`C# / C / C++ / WPF / TCP + 串口` · `2018.03 — 2022.10` · **独立承担全部开发**

> 采集气象站、能见度仪、云高仪、天气现象仪等设备信号，为塔台、观测、预报多端提供实时监测、分析、预警及报文编发（符合民航标准）。

- 设计串口多线程采集架构，按设备分表持久化存储，确保高频采集下数据完整性与可追溯性
- 完成 WPF + 多线程 + TCP/IP + SQL Server 的多客户端并发通信架构，支持塔台/观测/预报三端实时推送
- 实现民航 METAR / SPECI 报文自动生成与预警联动机制，报文格式符合民航行业标准
- 独立负责全项目需求分析、架构设计、数据库设计及所有功能模块开发，按期高质量交付

---

### 【项目四】工业 MES 自动化管理系统
`.NET Core / 微服务 / Kafka / Docker` · `2019.06 — 2022.07` · **架构师兼主程**

> 面向制造企业的生产信息自动化管理系统，涵盖设备数据采集与分析、生产调度、品质管理、物料管理、绩效考核、自动报表等模块，推广至益海嘉里 / 劲酒 / 张裕等 13 个工厂。

- 输出微服务架构方案：`Nginx（转发）+ Ocelot + Consul + JWT + Apollo + Kafka + Redis + MySQL 主主 + ELK + Docker`
- 主导中间件集群搭建，完成 MySQL 分库分区分表及读写分离，封装 MySQL/Redis/Kafka/ES 访问类库
- 设计并实现分布式事务方案（本地消息表 + Kafka + MySQL），解决跨服务数据一致性难题
- 主导设备信号采集链路：实时数据写入 Kafka → Logstash → ES，支撑生产现场实时搜索与图表分析，覆盖 13 个工厂、数十台设备

---

## 💼 工作经历

| 时间 | 公司 | 职位 |
| --- | --- | --- |
| 2022.10 — 至今 | 武汉普创数据科技有限公司 | 上位机 / 自动化测试系统开发工程师 |
| 2017.06 — 2022.10 | 北京巴特系统工程有限责任公司 | .NET 开发工程师（架构师） |

**核心贡献**

- 作为项目核心/独立开发者，主导多个工业自动化测试软件的架构设计与全流程研发，按时高质量交付
- 独立设计并实现高速数据采集软件全套模块，支持 10+ 路设备并发采集
- 主导团队代码规范与 CI 流程建设，指导初级工程师成长
- 带队完成 MES 系统从零建设并推广至 13 个工厂；独立开发 WMS 仓库管理系统与追溯查询系统，服务益海嘉里、可口可乐、伊利等大型客户

---

## 🎓 教育经历

| 时间 | 学校 | 学历 · 专业 |
| --- | --- | --- |
| 2016 — 2020 | 武汉科技大学 | 本科 · 行政管理 |
| 2015 — 2018 | 襄阳职业技术学院 | 大专 · 计算机应用技术 |

---

## 📜 资格证书

- **NCIE 全国信息化工程师证书**（高级软件工程师）

---

## 📫 联系方式

- 📧 Email：**wygk163@163.com**
- 📱 电话：**188 2751 8603**
- 📍 城市：武汉

---

<p align="center"><sub>本作品集由 Markdown 编写，通过 GitHub Pages 发布。</sub></p>
