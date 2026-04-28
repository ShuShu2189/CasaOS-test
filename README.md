# 🏠 CasaOS-test

[![License](https://img.shields.io/badge/license-MIT-blue.svg)](LICENSE)
[![JMeter](https://img.shields.io/badge/JMeter-5.6+-orange)](https://jmeter.apache.org/)
[![Standard](https://img.shields.io/badge/ISO-IEC%2FIEEE%2029119%3A2021-green)](https://www.iso.org/standard/74517.html)

> 本项目为 **CasaOS 智能家居系统** 提供了一套规范的测试实践，包含可直接运行的 JMeter 测试包以及符合国际标准的测试报告。

---

## 📖 简介

CasaOS-test 致力于帮助开发者、测试人员或智能家居爱好者快速对 CasaOS 系统进行**功能、性能与可靠性测试**。  
测试流程遵循 ISO/IEC/IEEE 29119-3:2021 标准设计测试用例，文档编写符合 ISO 9001:2015 质量管理体系要求。

---

## 📦 内容说明

### 1. JMeter 测试包（`/JMeter`）

- 包含一个**完整打包**的 CasaOS JMeter 测试脚本（`.jmx`文件）及必要的配置文件。
- **可直接导入** Apache JMeter（版本 ≥5.6）运行，无需额外环境配置。
- 测试范围覆盖：
  - 登录/登出流程
  - 设备管理接口
  - 自动化场景触发
  - 并发压力模拟

#### 快速开始
```bash
# 克隆仓库
git clone https://github.com/yourusername/CasaOS-test.git
cd CasaOS-test/JMeter

# 启动 JMeter 并导入 登录测试.jmx
jmeter -t 登录测试.jmx
```
提示：请确保 CasaOS 服务正常运行，并根据你的实际地址修改测试计划中的 服务器名称或IP 和 端口。

### 2. 测试报告（`/测试报告`）
- 一份完整的测试报告（PDF/Markdown 双格式），包含：
 -  测试计划与范围
 -  基于 ISO/IEC/IEEE 29119-3:2021 的测试用例（含正/反向、边界、并发场景）
 -  缺陷统计与风险分析
 -  测试总结与改进建议
- 文档结构严格参照 ISO 9001:2015 对文档控制、审阅、版本管理的要求。

## 🤝 贡献指南
欢迎通过 Issue 或 Pull Request 贡献测试脚本或报告模板。建议贡献时遵循：
- 测试用例更新应附带对应的 ISO 29119 覆盖说明。
- 报告文档修改请保持 ISO 9001 的文档控制要求（版本号、变更记录表）。

## 📫 联系方式
项目维护者：@ShuShu2189
问题反馈：Issues



