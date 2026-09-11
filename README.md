# Take Out Serve 🍔

> 基于 Node.js + Express 的外卖点餐在线系统服务端 RESTful API。

[![Node.js](https://img.shields.io/badge/Node.js->=14-green?style=flat-square&logo=nodedotjs)](https://nodejs.org/)
[![Express](https://img.shields.io/badge/Framework-Express-lightgrey?style=flat-square&logo=express)](https://expressjs.com/)
[![License](https://img.shields.io/badge/license-MIT-blue?style=flat-square)](LICENSE)

---

## 📖 项目简介

**Take Out Serve** 是为外卖点餐平台（Web 端与移动端 App）打造的后端接口服务。提供完整的商品列表查询、商户详情、用户认证、购物车增删查改及下单支付等核心 RESTful API。

---

## ✨ 核心功能与接口

- 🏪 **商家模块**：店铺基本信息、评分公告、配送费规则
- 🍜 **餐品模块**：菜单分类目录、餐品详情、爆款排行
- 🛒 **订单模块**：购物车数据计算、优惠券抵扣、订单提交
- 💬 **评价模块**：用户晒单评价与商家回复

---

## 🚀 启动指引

```bash
# 1. 克隆项目与安装依赖
git clone https://github.com/qqlcx5/take-out-serve.git
cd take-out-serve
npm install

# 2. 启动服务（默认监听端口 4000）
npm start # 或 bash start.sh
```

---

## 📄 接口文档

详细的 API 路由格式、参数规范及返回示例请查看 [API文档.md](API文档.md)。

---

## 📄 开源协议

本项目遵循 [MIT 协议](LICENSE) 开源。
