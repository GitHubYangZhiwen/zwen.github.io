# 玩具之家

一款运行在 GitHub Pages 上的**本地股票分红管理工具**。纯单文件 HTML，数据存于浏览器 localStorage，无需后端、无需登录。

## 功能

- **赠品排行** — 按股息率高低排列，柱状图直观展示，支持自定义达标阈值
- **玩具池** — 添加/编辑/删除自选股票，一键刷新腾讯实时行情
- **布林** — 每只股票的日/周 BOLL 带迷你图，蓝点标记当前价位置
- **撒网捕鱼** — 按股息率 4%~7% 反推目标价，可视化"入网"与"待捕"状态

## 使用

直接访问 [https://githubyangzhiwen.github.io/zwen.github.io/](https://zwen.github.io) 即可。所有数据保存在浏览器本地，建议定期点击右上角 **导出备份** 留存 JSON 快照。

## 技术

- 纯 HTML + CSS + 原生 JavaScript（无框架、无构建步骤）
- 行情数据源：腾讯财经公共接口（`qt.gtimg.cn` / `web.ifzq.gtimg.cn`）
- 持久化：localStorage
