# Changelog

## 1.3.0

- `feat` 新增配置项 usePrivateIp，为 true 时 injectInfo 使用 private ip 而非 local ip。

## 1.2.2

- `fix` inject 接口监听 0.0.0.0，避免 localhost 和 127.0.0.1 没有匹配的情况

## 1.2.1

- `refactor` 删除无用 console
- `fix` inject 模式下，为配置 openUrl 的情况下，打开 lowcode-engine demo。

## 1.2.0

- `feat`  在 inject 模式下不使用 miniCssExtract

## 1.1.0

- `feat` 支持配置 library

## 1.0.9

- `fix` openUrl 配置在组件状态下不生效

## 1.0.8

- `fix` 删除无用逻辑，去除 style-loader 依赖，解决构建报错问题

## 1.0.7

- `fix` 修复 wsl 环境下 watch 失败的问题 

## 1.0.6

- `feat` 支持 plugin 开发时 lcMeta 的注入，生成 lcMeta 的逻辑默认开启

## 1.0.5

- `feat` 本地调试兼容性依赖 lowcode-engine

## 1.0.3

- `feat` 适配内置插件的新用法，支持本地调试内置插件 

## 1.0.2

- `fix` 本地调试 setter 内置调试组件不渲染

## 1.0.2

- `fix` 本地调试依赖陈旧 & 预览 schema 获取不对

## 1.0.0

- `feat` first version