# Seismic Auto Bot

一个基于 Node.js 的工具，用于在 Seismic 开发网络上部署 ERC-20 兼容代币，并自动将代币转移到随机地址以进行测试和空投模拟。

## 领水

https://faucet-2.seismicdev.net/

## 功能

- 一键在 Seismic 开发网络上部署代币
- 自动将代币转移到多个地址
- 实时交易状态更新
- 简单的交互式提示界面

## 先决条件

- Node.js（v14 或更高版本）
- npm 或 yarn
- 在 Seismic 开发网络上拥有 ETH 的钱包

## 安装

```bash
# 克隆仓库
git clone https://github.com/airdropinsiders/Seismic-Auto-Bot.git

# 进入项目目录
cd Seismic-Auto-Bot

# 安装依赖
npm install
```

## 配置

在根目录下创建一个 `pk.txt` 文件，并填写你的私钥：

```
pk1,
pk2,
...
```

> ⚠️ **安全警告**: 切勿分享你的私钥或将 pk.txt 文件提交到 GitHub。

## 使用

运行工具：

```bash
node index.js
```

脚本将自动完成以下步骤：

1. 代币创建（名称、符号、总供应量）
2. 将代币部署到 Seismic 开发网络
3. 可选：自动将代币转移到随机地址

## 代币合约

该脚本部署了一个标准的 ERC-20 兼容代币合约，具有以下功能：

- 代币名称、符号和小数位数
- 地址余额跟踪
- 转移和批准功能
- 标准 ERC-20 事件

## 网络信息

该工具连接到：
- 网络：Seismic 开发网络
- 链 ID：5124
- RPC URL：https://node-2.seismicdev.net/rpc
- 浏览器：https://explorer-2.seismicdev.net/

## 贡献者

- 空投内幕团队

## 许可证

MIT 许可证

## 支持

如有任何问题或需要支持，请在本仓库中提交问题或联系空投内幕团队。
