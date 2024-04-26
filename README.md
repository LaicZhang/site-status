# site-status

一个基于 UptimeRobot API 的在线状态面板

## 特色

- 站点状态总览
- 流畅的动画
- 数据获取失败提醒
- 移动端适配
- 移除原版中字体CDN以避免Firefox中跨域问题

## 事先准备

- 在[UptimeRobot](https://uptimerobot.com/dashboard) 添加站点监控，并在老版界面中的`My Settings` 获取 类型为 `Read-Only API Key` 的 `API Key`

## 如何使用

## 部署

### 安装依赖

```bash
# 编辑.env 文件
vi .env

# 若没有 pnpm
npm install pnpm -g

# 安装依赖
pnpm install
```

### 开发

```bash
pnpm dev
```

### 打包

```bash
pnpm build
```

## 鸣谢

- [uptime-status](https://github.com/yb/uptime-status)
- [site-status](https://github.com/imsyy/site-status) 基于此项目进行修改
