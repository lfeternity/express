# SL Express 管理后台

基于 Vue 2、Vue CLI 和 Element UI 的物流运输管理后台，面向运营人员提供组织、车辆、线路、订单、运单和运输任务等管理功能。

## 开发环境

- Node.js 14.x（项目包含旧版 Vue CLI 和 `node-sass` 依赖）
- npm 6+ 或 Yarn 1.x
- 可访问后端网关的本地或测试环境

## 本地运行

```bash
npm install
npm run dev
```

默认开发环境配置位于 `.env.development`。请将 API 地址改为自己的网关地址，不要在仓库中提交真实密钥。

## 常用命令

```bash
npm run lint       # ESLint 检查
npm run build:prod # 生产构建
npm run test:unit  # 单元测试
```

## 目录提示

- `src/api`：后端接口封装
- `src/views`：业务页面
- `src/router`：路由与权限控制
- `src/store`：全局状态
- `src/components`：通用组件

接口通过网关的 `/manager` 路由访问，具体地址以环境文件为准。
