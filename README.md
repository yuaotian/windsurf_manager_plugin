# Windsurf 账号管理助手

> Windsurf IDE 多账号无感切换管理工具

## Features

- 🔐 邮箱密码登录，自动换取 API Key
- 📱 支持手动录入 API Key
- 🔄 一键切换已保存账号
- ⏭ 支持快捷切换下一个账号
- 📊 查询每日 / 每周配额与模型级配额
- 📋 复制完整账号信息
- 🔍 搜索、分组和批量管理账号
- 🔧 重置 Machine ID
- 🚀 启动时自动导入当前登录账号
- ⚙️ 可配置切换后是否自动刷新窗口
- ⚡ 一键向本地 Language Server 注入 Pro 状态
- 📦 支持本地 VSIX 打包
- 🤖 支持 GitHub Actions 自动打包、自动 Release、自动版本回写


## Usage

1. 在 Windsurf / VS Code 中安装生成的 VSIX
2. 打开左侧“账号管理”面板
3. 添加账号（登录模式或手动模式）
4. 点击账号进行切换
5. 使用配额按钮查询配额
6. 需要时执行 Pro 注入

## Tech Stack

- TypeScript
- VS Code Extension API
- Firebase Auth REST API
- Windsurf Web Backend API
- sql.js
- GitHub Actions

## Notes

> ⚠️ 需要代理 / VPN 才能访问部分 Google Firebase 接口

- 首次切换账号可能触发补丁应用并要求重启 Windsurf
- Windsurf 更新后可能需要重新应用补丁
- Pro 注入为运行时行为，Windsurf 重启后需要重新注入

## License

[MIT](LICENSE.txt)


https://github.com/yuaotian/windsurf_manager_plugin

