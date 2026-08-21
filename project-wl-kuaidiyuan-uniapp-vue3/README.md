# SL Express 快递员端

基于 Uni-app 和 Vue 3 的快递员作业端，覆盖取件、派件、扫码收款、任务搜索和消息通知等流程。

## 开发与运行

建议使用 HBuilderX 打开当前目录，选择运行到浏览器、模拟器或真机。发布前请在 `manifest.json` 配置自己的应用信息，并确认接口地址指向 SL Express 网关的 `/courier` 路由。

该目录包含 `package.json` 和 `yarn.lock`，如需在命令行安装依赖，可执行：

```bash
yarn install
```

`node_modules`、构建产物和本地临时文件不应提交到 Git。
