# chatgpt-team-helper：AI接手入口

Vue与Node工作区构成的Team账号管理平台Fork，含订单渠道、兑换、后台和外部集成。

1. 读 [项目运行与接手说明](docs/AI_HANDOFF.md)，确认入口、应用目录、依赖和数据边界。
2. 读 [本轮实际验证记录](docs/VERIFICATION.md)，区分已测功能与需要素材/密钥/桌面环境的功能。
3. 读根目录AGENTS.md及下层约定，再按用户本次目标修改。

后端SQLite、JWT_SECRET、渠道授权、机器人Token与浏览器状态不随源码备份。启动会初始化数据库和多个调度器，正式运行前逐项配置。
