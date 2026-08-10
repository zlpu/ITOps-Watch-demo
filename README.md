<div align="center">

# ITOps-Watch

面向运维团队的一体化监控与智能运维平台

> 本系统原名 ZabbixWatch，2026.3.23 正式更名为 ITOps-Watch

多数据源监控 · 可视化大屏 · AI+告警 · AI+巡检 · 网络拓扑 · 3D 机房

统一入口 · 快速部署 · 灵活扩展 · x86-64 / ARM64

[官网](https://itops-watch.data-demo.cn) · [GitHub](https://github.com/zlpu/ITOps-Watch-demo) · [Gitee](https://gitee.com/root-pu/ITOps-Watch-demo)

<img width="1910" height="995" alt="image" src="https://github.com/user-attachments/assets/5170cc87-2e62-4591-9594-be9d5ba986dd" />

</div>

## 项目简介

ITOps-Watch 是一款面向企业运维团队的综合监控平台，用于统一管理基础设施、网络设备、业务接口、数据库、告警和巡检任务。

平台可接入 Zabbix 与 Prometheus，将分散的监控数据汇总到统一界面，通过数据大屏、告警地图、网络拓扑和 3D 机房等方式直观呈现运行状态。同时结合 AI 分析、自动巡检和多渠道通知，帮助运维人员更快发现问题、判断影响并完成日常巡检。

ITOps-Watch 不替代现有监控系统，而是在其基础上补充统一展示、业务关联、智能分析和运维协同能力。

## 能做什么

### 统一管理监控数据

- 接入并管理多个 Zabbix、Prometheus 数据源。
- 设置默认数据源，并在不同监控环境之间快速切换。
- 统一维护常用监控指标，适配不同监控模板和采集方式。
- 不同数据源的数据、配置和大屏布局相互隔离。

### 建设企业监控大屏

- 通过组件库组合主机、网络、数据库、业务接口和告警数据。
- 展示资源使用率、运行状态、TOP 排名和趋势变化。
- 支持按数据源保存大屏布局，满足不同环境的展示需求。
- 支持大屏轮播和静默刷新，适用于值班室、机房和运维中心。

### 在地图上查看资源与告警

- 提供世界、中国、省级和市级地图。
- 支持标准地图与卫星地图展示。
- 将主机、数据库和 Web 业务的告警关联到实际位置。
- 汇总节点状态、告警趋势及告警恢复情况。

### 管理主机与网络设备

- 集中查看主机状态、资源指标和历史趋势。
- 为主机维护位置、类型、业务关系和软件资产信息。
- 将网络设备从普通主机中独立分类管理。
- 展示网络接口状态、接口流量、VLAN 流量和设备资源情况。
- 同时适配 Zabbix 与 Prometheus 监控场景。

### 监控业务接口与数据库

- 监控 Web 站点和业务接口的可用性、响应时间、状态码及 SSL 证书。
- 根据实际业务设置离线判断规则。
- 支持 MySQL、MariaDB、PostgreSQL、SQL Server、Oracle 和 Oracle 11G。
- 查看数据库连接状态、关键性能指标和历史趋势。
- 可按数据库类型扩展自定义监控指标。

### AI+告警与 AI+巡检

- 为主机、Web 和数据库统一配置告警规则。
- 支持告警等级、恢复判断、规则预设和批量管理。
- 可选用 AI 对告警进行分析，辅助定位问题。
- 支持主机、Web、数据库的手动巡检和定时巡检。
- 自动生成 Word、PDF 巡检报告。
- 通过企业微信、飞书、钉钉、邮件或 Webhook 发送消息和报告。

### 可视化业务关系

- 自定义网络拓扑，关联主机、网络设备、Web 和数据库对象。
- 在拓扑中查看对象状态、流量和历史数据。
- 管理机房、机柜和 U 位资产，通过 3D 场景查看设备运行情况。
- 通过业务关联快速了解主机承载的数据库、应用和软件资产。

### 系统管理与审计

- 管理用户、数据源、指标、AI 服务和语音告警。
- 查看登录日志和重要操作记录。
- 支持中英文界面。
- 提供 Docker Compose 部署和独立 ARM64 版本。

## 适用场景

- 企业 IT 基础设施统一监控。
- 多数据源、多机房集中展示。
- 运维值班室和监控中心大屏。
- 网络设备与接口流量管理。
- 业务接口和数据库可用性监控。
- 自动巡检、报告生成和告警通知。
- 数据中心机房与资产可视化。

## 产品展示

### 1. 登录与数据源管理

登录后直接进入监控大屏。首次使用时，管理员先在系统设置中添加并启用数据源。


### 2. 数据大屏与告警地图

数据大屏集中展示监控对象、关键指标、告警和运行趋势，可根据实际环境选择所需组件。

<img width="1910" height="995" alt="image" src="https://github.com/user-attachments/assets/aaff21e4-9708-444d-81b8-6282d77fed18" />

### 3. 网络拓扑

通过拓扑关系展示主机、网络设备、Web 和数据库对象，并关联状态、流量和历史数据。

<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/93124af8-bcb2-421b-8d21-f81446923899" />
<img width="1723" height="924" alt="image" src="https://github.com/user-attachments/assets/d5064de6-09a4-4d56-ad61-47546f37abae" />


### 4. 3D 机房可视化

支持机房、机柜、U 位资产和设备状态管理，适合数据中心资产展示和日常巡查。

<img width="1910" height="995" alt="image" src="https://github.com/user-attachments/assets/636084ea-56f2-4fcb-a29e-b5364bb55fb3" />

### 5. 主机管理

统一查看主机状态、资源使用、历史数据、位置、分类和业务关系。


### 6. Web 业务监控

用于掌握站点和业务接口的可用性、响应速度、证书状态及历史变化。


### 7. 数据库监控

统一管理数据库连接和运行指标，并支持按数据库类型扩展监控内容。


### 8. AI+告警

告警规则覆盖主机、Web 和数据库，支持统一管理、恢复判断和告警分析。



消息中心用于维护通知渠道、告警模板和恢复模板。


AI 配置可接入主流大模型或兼容服务，用于告警分析和巡检报告生成。


### 9. AI+巡检

支持创建主机、Web 和数据库巡检任务，定时生成结果和巡检报告。

<img width="1920" height="1040" alt="image" src="https://github.com/user-attachments/assets/71b494e7-33d2-4c9d-b603-12d3a5debc1f" />
<img width="1910" height="995" alt="image" src="https://github.com/user-attachments/assets/c3f8088c-6139-414f-9934-e2947597895b" />
<img width="1920" height="1040" alt="image" src="https://github.com/user-attachments/assets/0d2a449e-2b1f-42bd-96b2-fb9e44b55c40" />
<img width="1910" height="995" alt="image" src="https://github.com/user-attachments/assets/5dfc553b-c2fa-4156-a4a1-f06580552c91" />
<img width="1920" height="1040" alt="image" src="https://github.com/user-attachments/assets/d3015fbe-7c8f-46f3-a2a6-ad84051da4ee" />


### 10. 指标管理

通过统一的指标配置适配不同监控模板，为大屏、告警、巡检和设备面板提供数据基础。


### 11. 系统设置

系统设置用于管理平台基础信息、用户、数据源、AI、会话、数据保留和日志。



## 快速部署

### 环境要求

- Linux x86-64 或 ARM64。
- Docker 20.10+。
- Docker Compose v2，或兼容的 Docker Compose 1.29+。
- 可访问的 Zabbix 或 Prometheus 数据源。

> 当前部署使用 host 网络模式，请提前确认相关端口未被占用。

### 部署包联系电话18288669701 或微信 pzl960504


部署完成后访问地址：`http://your-server-ip:8088`

首次初始化账号：

- 用户名：`admin`
- 密码：`itops-watch1`

> 首次登录后请立即修改密码。

### 常用命令

```bash
# 查看日志
docker compose logs -f

# 停止服务
docker compose stop

# 更新并重启
docker compose pull
docker compose up -d
```

ARM64 环境请使用对应的 ARM64 部署包和镜像。

## 版本历史

### v7.5 (2026-08) - 当前版本

- 完善多数据源管理、默认数据源和切换体验。
- 升级大屏组件、数据库与业务接口监控概览。
- 重构告警地图，支持更多区域和卫星模式。
- 增加网络设备分类、接口识别和流量面板。
- 完善数据库自定义指标、告警规则和巡检能力。
- 增强业务关联、坐标管理、日志审计和 ARM64 部署。

### v7.2 (2026-06)

- 增加 3D 机房可视化。
- 完善数据库监控。

### v7.1 (2026-06)

- 数据大屏支持组件订阅和布局调整。
- 巡检范围增加数据库和 Web 站点。

### v6.1 (2026-03)

- ZabbixWatch 正式更名为 ITOps-Watch。
- 增加 Prometheus 数据源支持。

### 早期版本

- 持续完善主机监控、网络拓扑、Web 监控、指标管理、告警通知和容器化部署。

## 使用说明

- 卫星地图需要访问在线地图服务；网络不可达时会自动使用标准地图。
- 数据源是平台业务数据的基础，首次使用需由管理员完成配置。
- AI 功能需要单独配置可用的大模型服务，未配置时不影响普通监控和告警。
- 不同版本和授权包含的功能可能有所不同，请以实际交付版本为准。

## 联系方式

- 官网：https://itops-watch.data-demo.cn
- GitHub：https://github.com/zlpu/ITOps-Watch-demo
- Gitee：https://gitee.com/root-pu/ITOps-Watch-demo
- 作者微信：`pzl960504`
- 联系电话：`18288669701`

## Star History

如果 ITOps-Watch 对你的运维工作有帮助，欢迎 Star 并提交问题反馈。

[![Star History Chart](https://api.star-history.com/svg?repos=zlpu/ITOps-Watch-demo&type=Date)](https://star-history.com/#zlpu/ITOps-Watch-demo&Date)

<br>

<div align="center">

<table>
<tr>
<td align="center" width="50%">
<a href="https://github.com/zlpu/ITOps-Watch-demo">
<img src="https://img.shields.io/github/stars/zlpu/ITOps-Watch-demo?style=for-the-badge&logo=github&color=yellow" alt="GitHub stars">
<br>
<b>GitHub 仓库</b>
</a>
</td>
<td align="center" width="50%">
<a href="https://gitee.com/root-pu/zabbixwatch-demo">
<img src="https://gitee.com/root-pu/zabbixwatch-demo/badge/star.svg?theme=dark" alt="Gitee stars" height="28">
<br>
<b>Gitee 仓库</b>
</a>
</td>
</tr>
</table>

<sub>Copyright © 2025-2026 ITOps-Watch. All rights reserved.</sub>

**[回到顶部](#itops-watch)**

</div>
