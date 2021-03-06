# 更新日志

## 0.3.1 (2018-11-24)

### :bug: Bug 修复:

- 修复子进程（blinksocks）启动失败导致 CPU 占满的问题

### 从 0.3.0 更新到 0.3.1

```
$ npm install -g blinksocks-gui@0.3.1 blinksocks@3.x
```

## 0.3.0 (2018-05-14)

### :rocket: 新功能和改进

- 日志查看器新增地图（基于 Google Map）模式 :sparkles:
- 将 blinksocks 依赖改为 peerDependency，可以选择使用不同的版本
- 图表改为自动刷新
- 选项卡标题增加动态内容

### :bug: Bug 修复:

- 修复子进程（blinksocks）报错退出时主进程（blinksocks-gui）崩溃的问题
- 修复免安装版本无法再 Windows 平台下使用的问题
- 修复 server 模式下无法修改密钥的问题
- 修复无法通过强制刷新进入次级页面的问题
- 修复日志查看器没有显示目标地址的问题

### 从 0.2.1 更新到 0.3.0

```
$ npm install -g blinksocks-gui@0.3.0 blinksocks@3.x
```

## 0.2.1 (2018-04-11)

### :bug: Bug 修复:

- 修复保存系统用户设置时的报错

### 从 0.2.0 更新到 0.2.1

```
$ npm install -g blinksocks-gui@0.2.1
```

## 0.2.0 (2018-04-11)

### :rocket: 新功能和改进

- 服务日志查看器
  - 实时查看每个连接的源地址、目的地址、存活时间和对应状态
  - 历史日志下载
- 服务运行日志统一存放在 runtime/logs 下
- 调整 RPC 超时时间从 10s 到 30s
- 服务名称修改功能现集成到 card 菜单中
- 重新安排了配置项的展示顺序和高级分类
- 增加配置服务自动重启的功能

### :bug: Bug 修复:

- 修改服务名称判空处理
- 登录密码非明文存储

### 从 0.1.0 更新到 0.2.0

```
$ npm install -g blinksocks-gui@0.2.0
```

## 0.1.0 (2018-04-04)

### :rocket: 特性

- 三大平台支持（Windows、Linux、macOS）
- 双端图形化界面
- 单机服务多开
- 远程服务配置、启动/停止
- 实时监控图表（CPU、内存、上下行速度、网络连接数、网络流量）
- 日志查看和搜索

### 安装

```
$ npm install -g blinksocks-gui@0.1.0
```
