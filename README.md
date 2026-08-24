<div align="center">

# 🔐 网络安全知识共享平台

**收集 · 整理 · 共享全球网络安全漏洞挖掘会议 PPT / PDF**

*Security Conference Slides Archive — vulnerability research & bug bounty talks since 2017*

[![GitHub stars](https://img.shields.io/github/stars/bmgfl/security-conference-slides?style=social)](https://github.com/bmgfl/security-conference-slides)
[![GitHub forks](https://img.shields.io/github/forks/bmgfl/security-conference-slides?style=social)](https://github.com/bmgfl/security-conference-slides)
[![License](https://img.shields.io/github/license/bmgfl/security-conference-slides)](https://github.com/bmgfl/security-conference-slides)
[![GitHub last commit](https://img.shields.io/github/last-commit/bmgfl/security-conference-slides)](https://github.com/bmgfl/security-conference-slides)

</div>

---

## 📖 简介

本仓库是一个**网络安全知识共享平台**，系统性收集、归档从 **2017 年至今**全球网络安全漏洞挖掘相关会议、沙龙、SRC 活动的议题 **PPT / PDF** 资料，并按 **「会议 → 年份」** 两级目录组织，方便安全研究者、白帽、SRC 漏洞猎人快速检索与学习。

> 💡 适合人群：渗透测试工程师、漏洞挖掘爱好者、SRC 平台白帽、安全研究员、安全方向学生。

---

## 📂 目录结构

每个会议一个顶层目录，内部按 **年份** 分子目录：

```
security-conference-slides/
├── DEFCON/                  # 世界黑客大会（2017-2025）
│   ├── 2017/ ...
│   └── 2025/
├── BlackHat/                # 黑帽大会（US/Asia/Europe）
├── HITCON/                  # 台湾骇客年会
├── ISC互联网安全大会/        # 中国互联网安全大会
├── KCon/                    # 知道创宇黑客大会
├── 补天沙龙/                 # 补天漏洞平台沙龙
├── 先知白帽大会/             # 阿里先知白帽大会
├── 看雪安全开发者峰会/
├── JSRC京东SRC沙龙/          # 京东安全应急响应中心
├── VSRC唯品会SRC沙龙/        # 唯品会安全应急响应中心
├── WiFi万能钥匙SRC沙龙/
├── 唯品会安全峰会/
├── 京东安全峰会/
├── 携程信息安全沙龙/
├── SSC安全峰会/
├── 网络安全生态峰会/
├── FIT互联网安全大会/
├── OWASP/
├── DEFCON GROUP 010/
├── 饿了么安全峰会/
├── 网络安全分析与情报大会/
├── Hexacon/                 # 法国 Hexacon
├── OffensiveCon/            # 德国 OffensiveCon
└── REcon/                   # 加拿大逆向工程大会
```

---

## 🗂️ 收录会议一览

| 会议 | 类型 | 年份范围 | 说明 |
| --- | --- | --- | --- |
| **DEF CON** | 国际黑客大会 | 2017 – 2025 | 全球最大黑客大会，漏洞挖掘与利用 |
| **BlackHat** | 国际安全大会 | 2017 – 2026 | US / Asia / Europe 三大会场 |
| **HITCON** | 台湾骇客年会 | 2012 / 2016 | 亚洲知名安全会议 |
| **ISC 互联网安全大会** | 国内大会 | 2014 – 2019 | 中国互联网安全大会 |
| **KCon** | 国内大会 | 2012 – 2021 | 知道创宇主办，聚焦攻击技术 |
| **补天沙龙** | 国内 SRC 沙龙 | 2017 | 补天漏洞响应平台 |
| **先知白帽大会** | 国内 SRC | 2017 | 阿里巴巴先知 |
| **JSRC / VSRC 沙龙** | 大厂 SRC 沙龙 | 2013 – 2017 | 京东 / 唯品会安全应急响应中心 |
| **看雪安全开发者峰会** | 国内峰会 | 2017 | 看雪论坛主办 |
| **Hexacon / OffensiveCon / REcon** | 国际会议 | 2023 – 2025 | 逆向、漏洞利用方向 |

> ⚠️ 部分国内 SRC 沙龙（补天、白帽、大厂沙龙）主办方未公开批量下载入口，资料来自社区整理镜像，欢迎补充。

---

## 🚀 如何使用

```bash
# 克隆仓库（体量较大，建议使用 --depth 1 浅克隆）
git clone --depth 1 https://github.com/bmgfl/security-conference-slides.git

# 按会议与年份浏览
cd security-conference-slides/DEFCON/2025/
```

> 💡 若只想下载某个会议某一年份，可访问 GitHub 网页端按目录逐一下载，或使用 `git sparse-checkout` 选择性检出。

---

## ⚠️ 免责声明

- 本仓库所有资料均来自**公开网络**，版权归原作者 / 主办方所有，仅供**学习研究**用途。
- 若您是内容版权方，认为某些资料不应收录，请提 **Issue** 或联系我们，我们将在第一时间删除。
- 请勿将本仓库资料用于任何违法违规用途。

---

## 🤝 贡献指南

欢迎补充、纠错、更新：

1. **Fork** 本仓库
2. 按 `会议名称/年份/` 结构添加资料
3. 提交 **Pull Request**

也欢迎通过 **Issue** 提交你想收录的会议或失效链接。

---

## 📊 Star 趋势

如果你觉得本仓库有帮助，欢迎点亮 ⭐ **Star**，让更多安全同行看到！

---

<div align="center">

**Made with ❤️ by [akihi](https://github.com/bmgfl) · 白帽攻防录**

*漏洞挖掘 · 技术共享 · 共同成长*

</div>
