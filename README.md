# Vote For Bad Eye - 前端

这是一个基于 Vue 3 和 Element Plus 的在线投票应用的前端部分。用户可以注册、登录、投票选举“本周烂眼儿”，并查看投票结果和历史排名。

## ✨ 功能特性

- **用户认证**: 支持用户注册和登录功能。
- **头像上传**: 用户可以上传自定义头像。
- **投票系统**:
    - 用户可以从候选人列表中选择最多三位进行投票。
    - 投票前有确认提示，防止误操作。
    - 用户在一个投票周期内只能提交一次投票。
- **结果展示**:
    - **本周排名**: 实时展示本周得票数最高的“烂眼儿”排名。
    - **历史总计**: 展示所有候选人的累计得票总数排名。
- **响应式设计**: 适配桌面和移动设备，提供良好的用户体验。

## 🚀 技术栈

- **Vue 3**: 用于构建用户界面的渐进式 JavaScript 框架。
- **Element Plus**: 一套为开发者、设计师和产品经理准备的基于 Vue 3.0 的桌面端组件库。
- **Vue CLI**: Vue.js 开发的标准工具。
- **Axios**: 一个基于 promise 的 HTTP 库，用于发送网络请求。
- **lodash**: 一个一致性、模块化、高性能的 JavaScript 实用工具库。
- **mitt**: 一个小巧的事件发射器/总线库。

## 📦 安装与设置

1.  **克隆项目**
    ```bash
    git clone https://github.com/your-username/vote4badEye.git
    cd vote4badEye
    ```

2.  **安装依赖**
    ```bash
    npm install
    ```

## 🛠️ 使用方法

### 开发环境

启动开发服务器，支持热重载。

```bash
npm run serve
```

### 生产环境

编译和压缩代码，用于生产部署。

```bash
npm run build
```

### 代码检查

检查和修复代码中的格式问题。

```bash
npm run lint
```

## 📁 项目结构

```
vote4badEye/
├── public/
│   └── index.html
├── src/
│   ├── assets/         # 静态资源 （图片，字体等）
│   ├── components/     # Vue 组件
│   │   ├── HeaderPanel.vue
│   │   ├── ResultPanel.vue
│   └── │   └── VotePanel.vue
│   ├── utils/          # 工具函数
│   │   ├── common.js
│   │   └── event-bus.js
│   ├── App.vue         # 根组件
│   └── main.js         # 应用入口文件
├── .gitignore
├── babel.config.js
├── package.json
├── README.md
└── vue.config.js
```

## 🤝 贡献

欢迎提交问题和合并请求。对于重大更改，请先打开一个问题进行讨论。
