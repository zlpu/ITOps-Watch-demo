<div align="center">

# ITOps-Watch

专为运维团队打造的监控平台

> 本系统原名 ZabbixWatch，2026.3.23 正式更名为 ITOps-Watch

Zabbix & Prometheus 双数据源 · 可视化大屏 · AI 智能巡检 · AI 智能告警 · 动态网络拓扑

零配置接入 · 开箱即用 · Docker 一键部署 · 5 分钟快速上线

[在线演示](https://itops-watch.data-demo.cn/) · [官网](https://itops-watch.data-demo.cn)

</div>

## 项目简介

ITOps-Watch 是一款专为运维团队打造的企业级监控平台，支持 **Zabbix 与 Prometheus 数据源**接入，提供可视化大屏、3D机房可视化、AI+智能巡检、AI+智能告警、自定义大屏、动态网络拓扑等核心功能，实现运维监控的智能化、简单化。

官网：https://itops-watch.data-demo.cn

### 核心功能

- **多数据源智能采集**：支持 Zabbix（5.x/6.x/7.x）与 Prometheus 数据源，可同时接入多个实例统一管理；自动采集 CPU、内存、磁盘、网络等关键指标，支持自定义指标键值映射，灵活扩展监控维度
- **可视化监控大屏**：提供默认可视化大屏与拖拽式大屏编辑器，支持多种图表类型、大屏轮播、地图告警展示、历史数据趋势分析；支持**组件订阅功能**，可自由订阅和配置大屏组件，灵活定制监控视图；可自定义首页展示主机与布局
- **3D机房可视化**：第一视角直观的监控机房、机柜的运行情况，可以在机柜上直观的看到设备运行状态。
- **AI 智能运维**：集成 AI 大模型，支持 AI+告警自定义告警规则、自动分析研判;支持主机、数据库、web站点自动巡检，生成巡检报告、发送巡检报告(pdf、word）；
- **多渠道通知**：微信、钉钉、飞书、邮件多渠道通知，支持告警语音播报及 Webhook 推送告警消息到第三方平台，支持发送巡检报告
- **数据库监控**：监控oracle、mysql、sqlserver、postgresql数据库，支持告警自定义；
- **Web 站点监控**：监控 Web 站点可用性与响应时间，支持 SSL 证书到期监控与提醒，及时发现站点故障与安全风险
- **网络拓扑与扫描**：用户可根据自身环境自定义网络拓扑图，动态展示实时流量及主机数据，支持导入导出；内置多网段 IP 存活扫描，快速发现网络中的活跃设备
- **主机采集管理**：直接在 ITOps-Watch 上管理被监控主机，支持添加、删除、编辑主机信息，修改 Zabbix 监控项及触发器，监控历史数据直观展示
- **导入导出与多语言**：支持监控数据源、网络拓扑、Web 监控站点、自定义看板、扫描网段等数据的批量导入导出；系统支持中英文语言切换
- **Docker 一键部署**：支持 Docker Compose 一键部署，5 分钟快速上线，简化运维部署流程

### 适用场景

IT 运维监控、数据中心可视化、多机房统一监控、运维大屏展示、多数据源统一管理

## 专业版购买套餐(社区版免费，自行部署)

### 套餐说明

> **服务范围**：仅提供 ITOps-Watch 系统及部署服务，包含 AI+巡检、AI+告警、自定义大屏、动态拓扑、数据大屏等全部功能。  
> **特别说明**：如需调整 Zabbix / Prometheus 配置或定制开发，需单独收费。

### 购买流程

1. **咨询沟通** - 添加微信 `pzl960504` 咨询产品详情
2. **选择套餐** - 根据需求选择合适套餐
3. **获取激活码** - 付款后立即提供激活码


### 套餐价格

| 套餐 | 价格 | 功能说明 | 适用场景 |
|------|------|---------|---------|
| **免费试用** | ¥0 / 3天 | 全量功能体验，零成本试用<br>所有核心模块全面开放<br>3天深度体验 | 功能验证、试用评估 |
| **按月购买** | ¥130/月 | 授权期内全量功能无限制使用<br>灵活付费，按需订阅<br>支持随时续费，无压力<br>适合短期项目和快速验证<br>标准技术支持服务 | 短期项目、灵活使用 |
| **半年购买** ⭐ | ¥700/半年 | 授权期内全量功能无限制使用<br>平均 ¥117/月，节省 ¥80<br>🎁 授权期内免费享受所有新版本升级服务<br>标准技术支持服务| 中期项目、性价比优选 |
| **按年购买** ⭐ | ¥1300/年 | 授权期内全量功能无限制使用<br>平均 ¥108/月，节省 ¥260<br>🎁 授权期内免费享受所有新版本升级服务<br>超高性价比，长期合作优选 | 生产环境、长期使用 |
| **永久使用** | ¥3000 | 全量功能永久使用<br>一次付费，终身无忧<br>🎁 免费升级，持续迭代<br>技术支持通道<br>无需续费，最具价值 | 生产环境、长期使用 |
## 联系方式

<p align="center">
  <img src="项目介绍/images/wechat.jpg" width="200">
</p>

- **作者微信**: pzl960504
- **GitHub**: https://github.com/zlpu/ITOps-Watch-demo
- **Gitee**:[ https://gitee.com/root-pu/zabbixwatch-demo](https://gitee.com/root-pu/ITOps-Watch-demo)
- **Email**: 2925006354@qq.com

## 版本历史

> 社区版免费不开源，专业版提供全部高级功能及技术支持
>> 购买方式：https://item.taobao.com/item.htm?ft=t&id=1022330606414 或微信pzl960504

### v7.2 (2026-06-27) - 当前版本
- 3D机房可视化
- 完善数据库监控


### v7.1 (2026-06-07) 
- 数据大屏支持组件订阅模式、自定义调整大屏布局
- 新增支持巡检数据库、web站点
- 修复前面版本的 BUG
- 调整授权机制


### v6.1 (2026-03-24) 

- ZabbixWatch 正式更名为 **ITOps-Watch**
- 全面支持 **Prometheus** 数据源接入，内置常见 PromQL 查询语句
- 重写自定义看板功能
- 修复前面版本的 BUG

### v6.0 (2026-03-01)

- 系统架构调整，解决系统卡顿问题
- Web 监控：支持 SSL 证书监控
- 主机管理和监控历史数据功能合并，直观展示主机资源使用情况

### v5.2 (2026-02-23)

- 网络扫描：支持扫描多个网段 IP 存活状态
- 多语言：系统支持中英文语言切换
- 导入导出功能：网络拓扑、Web 监控站点、自定义看板、扫描网段
- 优化首页展示的指标

### v5.0 (2026-02)

- 主机配置管理：可在系统上管理被监控主机，包括添加、删除、编辑信息
- 告警语音播报：支持在系统页面中进行告警的语音播报
- 新增邮件告警方式
- 优化前端数据加载性能，减少客户端资源消耗

### v4.0 (2026-01-18)

- 支持自定义监控指标键值：用户自行维护指标键值映射关系
- 支持过滤首页展示的主机：可自定义需要在首页展示的主机
- 新增网络拓扑功能：用户可以根据自己的环境自定义网络拓扑，动态展示实时流量及主机数据
- 数据库切换为 MariaDB：解决 MySQL8 适配问题

### v3.0 (2025-12-02)

- 地图告警：大屏新增地图样式告警展示
- 可见名称：全面支持 Zabbix 主机可见名称
- 流程优化：取消数据初始化页面，解决认证失败
- 规则持久化：告警规则配置持久化存储
- 时间筛选：告警信息支持时间范围查询
- 状态判断：在线/离线增加双重判断标准
- 磁盘显示：修复磁盘使用率显示问题

### v2.0 (2025-11-04)

- 零配置接入：直接接入 Zabbix
- 自定义大屏：拖拽式编辑器
- 多数据源：支持多个 Zabbix
- AI 增强：内置大模型
- 大屏优化：流量 TOP10
- 架构重构：模块化设计

### v1.1 (2025-09-14)

- 扩展 Zabbix 版本支持（5.x/6.x/7.x）
- 自定义资产组显示
- 自定义时间段查询
- 简化 Zabbix 配置
- Docker Compose 部署

### v1.0 (2025-08-29)

- 首次发布
- 基础监控大屏
- 历史数据趋势图
- Web 站点监控
- AI + 告警分析
- Webhook 消息通知
- 容器化部署



## 专业版使用教程


#### 1. 首次登录

访问地址: http://your-server:8088
默认账号: admin / watch

注意：首次登录后请立即修改密码

![](项目介绍/images/login.png)

#### 2. 配置数据源

操作路径：右上角系统设置 → 数据源配置

支持两种数据源类型：

**Zabbix 数据源：**
- Zabbix URL: http://your-zabbix-server
- 用户名: Admin（使用实际的账号密码）
- 密码: zabbix

**Prometheus 数据源：**
- Prometheus URL: http://your-prometheus-server:9090
- 认证信息（如有）

点击测试连接，确认连接成功后保存配置。

零配置说明：无需在 Zabbix/Prometheus 端做任何修改，直接配置即可使用。

![](项目介绍/images/datasources.png)

#### 3. 查看监控大屏

操作路径：左侧菜单 → 数据大屏

功能说明：
- 自动加载数据，实时刷新
- 支持自定义资产组显示
- 支持全屏展示（F11 全屏 / ESC 退出）
- 地图告警展示
- 支持组件订阅
<img width="1910" height="995" alt="image" src="https://github.com/user-attachments/assets/aaff21e4-9708-444d-81b8-6282d77fed18" />

操作: 左侧菜单 → 数据大屏-网络拓扑

功能: 自定义网络拓扑图-关联主机实时数据

<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/93124af8-bcb2-421b-8d21-f81446923899" />

操作: 左侧菜单 → 数据大屏- 机房可视化
<img width="1910" height="995" alt="image" src="https://github.com/user-attachments/assets/636084ea-56f2-4fcb-a29e-b5364bb55fb3" />
<img width="1708" height="890" alt="image" src="https://github.com/user-attachments/assets/51134cdb-4310-483f-8959-8c1ee5f08f0c" />


#### 4. 主机管理与历史数据

操作路径：左侧菜单 → 主机管理

功能说明：
- 主机资源使用情况直观展示（CPU、内存、磁盘、网络等）
- 自定义时间段查询（精确到分钟）
- 多指标对比分析
- 支持数据导出

![](项目介绍/images/page_history1.png)
![](项目介绍/images/page_history2.png)

#### 5. Web 监控

操作路径：左侧菜单 → Web 监控

功能说明：
- 实时监控站点状态
- 响应时间分析
- 可用性统计
- SSL 证书到期监控与提醒

![](项目介绍/images/page_web.png)

#### 6. 数据库监控

操作路径：左侧菜单 → 数据库监控

功能说明：
- 实时数据库状态
- 关键指标采集
<img width="1910" height="995" alt="image" src="https://github.com/user-attachments/assets/a80ae53c-a4f5-45aa-8329-f3ff9468a102" />


#### 7. AI+告警

操作路径：左侧菜单 → AI+告警

告警规则配置：
- 主机告警规则
- Web 站点告警规则
- 自定义告警阈值和时间窗口
- AI 自动分析研判告警信息

![](项目介绍/images/page_alert_rules.png)

消息配置：
- 支持微信、飞书、钉钉、邮件
- 支持告警语音播报
- 支持 Webhook 推送告警消息到第三方平台
- 自定义消息模板

![](项目介绍/images/page_alert_msg.png)

AI 模型配置：
- 内置服务商：硅基流动、DeepSeek、OpenAI
- 支持自定义模型 API 地址和 Key

![](项目介绍/images/page_alert_ai.png)

#### 8. AI+智能巡检

操作路径：左侧菜单 → AI+智能巡检

功能说明：
- AI 自动分析监控数据，智能识别异常模式
- 提供运维建议与巡检报告word pdf
- 支持发送 PDF 巡检报告（微信、钉钉、飞书、邮件）
- 可配置定时巡检任务

<img width="1920" height="1040" alt="image" src="https://github.com/user-attachments/assets/71b494e7-33d2-4c9d-b603-12d3a5debc1f" />
<img width="1910" height="995" alt="image" src="https://github.com/user-attachments/assets/c3f8088c-6139-414f-9934-e2947597895b" />
<img width="1920" height="1040" alt="image" src="https://github.com/user-attachments/assets/0d2a449e-2b1f-42bd-96b2-fb9e44b55c40" />
<img width="1910" height="995" alt="image" src="https://github.com/user-attachments/assets/5dfc553b-c2fa-4156-a4a1-f06580552c91" />
<img width="1920" height="1040" alt="image" src="https://github.com/user-attachments/assets/d3015fbe-7c8f-46f3-a2a6-ad84051da4ee" />



#### 9. 主机采集管理

操作路径：左侧菜单 → 主机管理

功能说明：
- 直接在 ITOps-Watch 上管理被监控主机，支持添加、删除、编辑主机信息
- 修改 Zabbix 监控项及触发器
- 监控历史数据直观展示

#### 10. 网络扫描

操作路径：左侧菜单 → 网络扫描

功能说明：
- 支持扫描多个网段 IP 存活状态
- 快速发现网络中的活跃设备
- 支持扫描网段的导入导出

#### 11. 制作自定义大屏

操作路径：左侧菜单 → 制作大屏 → 新建

操作流程：
1. 拖拽组件到画布
2. 调整布局和大小
3. 配置数据源
4. 设置背景和样式
5. 预览效果
6. 保存大屏

![](项目介绍/images/page_bashboard_edit.png)
![](项目介绍/images/page_show.png)

#### 11. 指标管理

操作路径：系统设置 → 指标管理

功能说明：
- 监控指标键值映射管理（Zabbix item key / Prometheus PromQL）
- 首页主机过滤
- Prometheus 自定义 PromQL 查询语句配置

<img width="1840" height="924" alt="image" src="https://github.com/user-attachments/assets/4a893190-8006-4628-add4-aefa46a0d8ad" />
<img width="1856" height="930" alt="image" src="https://github.com/user-attachments/assets/ffa998d4-578e-459b-ab87-5a0ea1618a29" />

#### 12. 系统设置

操作路径：左侧菜单 → 系统设置

功能说明：
- 定义首页大屏标题
- 设置会话有效期
- 配置数据存储时长

![](项目介绍/images/page_setings.png)

#### 13. 导入导出与多语言

功能说明：
- 支持网络拓扑、Web 监控站点、自定义看板、扫描网段等数据的批量导入导出
- 系统支持中英文语言切换（右上角语言切换按钮）

## 部署指南

### 环境要求

- Docker 20.10+
- Docker Compose 1.29+
- Zabbix Server 5.0+ 或 Prometheus
- Linux（CentOS 7+、Ubuntu 18.04+、Debian 10+）

>本系统需要使用宿主机80、8088、3306、3367、5001、5000，请确保这些端口未被其他服务占用。【无法使用环境变量修改端口】

### 一、社区版部署

```bash
# 下载项目
git clone https://github.com/zlpu/ITOps-Watch-demo.git
cd ITOps-Watch-demo/Install-zabbixwatch(Community)

# 启动服务
docker-compose up -d
```
访问：http://your-server-ip:8088  
默认账号：admin / admin123

### 二、专业版部署

```bash
# 下载项目
#x86-64
git clone https://github.com/zlpu/ITOps-Watch-demo.git
## 国内：使用git clone https://github.com/zlpu/ITOps-Watch-demo.git
cd ITOps-Watch-demo/Install-itops-watch-Professional

#arm64
git clone https://github.com/zlpu/ITOps-Watch-demo.git
## 国内：使用git clone https://github.com/zlpu/ITOps-Watch-demo.git
cd ITOps-Watch-demo/install-itops-watch(Professional)/arm64/

# 启动服务
docker-compose up -d
```

访问：http://your-server-ip:8088  
默认账号：admin / watch

**部署完成后需购买授权码进行激活使用**

### 三、服务管理

```bash
# 停止服务（保留数据）
docker-compose stop

# 停止并删除容器（保留数据卷）
docker-compose down

# 完全卸载（删除所有数据）
docker-compose down -v
```



## ⭐️ Star History

如果这个项目对你有帮助，请给我们一个 Star ⭐️

[![Star History Chart](https://api.star-history.com/svg?repos=zlpu/ITOps-Watch-demo&type=Date)](https://star-history.com/#zlpu/ITOps-Watch-demo&Date)

<br>


<div>

### 🌟 如果觉得项目不错，请给个 Star ⭐️

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


<sub>Made with ❤️ by **pzl960504** | Copyright © 2025-2026 ITOps-Watch. All rights reserved.</sub>

**[⬆️ 回到顶部](#itops-watch)**

</div>
