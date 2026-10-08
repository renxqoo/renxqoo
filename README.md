### Renxqoo · 前端架构 / AI Agent 工程

既能在编译期改造构建链路（Babel AST / 自定义 JSX Runtime / Vite 虚拟模块），也能把 AI Agent 从编排内核做到流式 UI 闭环。

**在做什么**

**通用 AI Agent 项目**（运行时内核 + 双端应用，两层一套产品）
- 🔧 **[x-harness](https://github.com/renxqoo/x-harness)** — 运行时内核：44 个包，覆盖 Agent loop / 子 Agent 分工 / 上下文压缩 / 权限沙箱 / 会话持久化 / 插件体系，394 个测试文件 3,861 个用例
- 🖥 **[pai-code](https://github.com/renxqoo/pai-code)** — 消费内核的双端应用：macOS「AI 干活助手」+ 移动端，Electron + Expo，扫码零配置配对，自研 oxlint 插件在 lint 层强制架构纪律
- 🚪 **[Tillgate](https://github.com/renxqoo/Tillgate)** — 可自托管 LLM API 网关：OpenAI 兼容入口 + 计量计费 + 订阅限额 + 逐请求链路追踪

**技术栈**

`TypeScript` `React 18/19` `Next.js 15` `Node.js` `Bun` `Vite / Rollup` `Babel AST` `Vitest` `Electron` `React Native / Expo`

📍 杭州 
