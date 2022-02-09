![](./titlepage.png)

# SteamTradingSiteTracker

Steam 挂刀行情站 —— 全天候更新的 BUFF & IGXE & C5 挂刀比例数据

## 访问地址：[https://www.iflow.work/](https://www.iflow.work/)

🚧 **Status: In Development** 🚧

站点开发进行中，服务器可能不定时停机维护，但会尽可能保证可用性。目前 Web 服务器架设在香港，大部分地区可以正常访问。如站点无法连接 (e.g., `ERR_CONNECTION_RESET`)，请更换网络环境后重试。

**24小时持续更新物品比例数据**，受服务器成本限制，目前仅追踪 **BUFF & IGXE & C5** 三个主要平台 售价 10 ~ 300 元 的 **CSGO & DOTA2** 饰品皮肤（列表动态更新，当前约 9600 个）。目前重点物品数据约 1.5h 完整更新一次，后期可能进一步提高更新频率。

为了服务器的正常运行，请不要在短时间内连续访问站点。

## 开发计划

### 数据更新

- [x] 优化更新调度算法，计算物品**寄售比例**与**求购比例**（时效性更强，权重更高）的加权和，设置分层优先级，提高重点物品的更新频率
- [x] 每小时多进程更新一次加权比例前100的物品，确保重点物品更新时间不超过1h
- [ ] 增加站点监控功能，服务器离线或更新停止时发出通知 

### UI

- [x] 前端支持其他排序/筛选方法
- [ ] 增加表格 `thead` 的底部阴影，使其在滚动时更美观
- [ ] 前端美化

### 后端

- [x] 进一步完善排序/筛选方法

### 其他

- [x] 支持 DOTA2
- [x] 支持 IGXE
- [x] 支持 C5

