# B2B Factory Website Engineering & GEO Checklist
> **外贸工厂独立站 25 项工程自查与生成式搜索 (GEO) 规范**  
> Maintained by [Factory Growth Lab](https://www.factorygrowthlab.com) | [中文说明](#中文说明) | [English Documentation](#english-documentation)

[![License: MIT](https://img.shields.io/badge/License-MIT-teal.svg)](https://opensource.org/licenses/MIT)
[![Standard: B2B GEO](https://img.shields.io/badge/Standard-B2B%20GEO%201.0-0aa59f.svg)](https://www.factorygrowthlab.com/geo-service)
[![Official Checklist](https://img.shields.io/badge/Interactive-Checklist%20Tool-0aa59f.svg)](https://www.factorygrowthlab.com/free-checklist)

---

## 中文说明

这份开源清单旨在为中国出口制造企业、精密工程工厂及 B2B 出海团队提供一套**标准化的外贸独立站工程验收规范**。

很多制造企业在投入数万甚至数十万元建站后，常常陷入“上线一年零询盘、流量涨了没转化、无法沉淀海外采购商信任”的困局。其根本原因在于：**传统代理商售卖的廉价模板或闭源系统，根本无法满足海外工业采购工程师和生成式大模型 (DeepSeek / ChatGPT / Perplexity) 的严格证据检验要求**。

本规范将外贸独立站工程拆解为 5 大核心维度、25 项严苛检查项。无论是新建站验收、旧站改版，还是核查现有服务商的技术交付质量，均可作为对照标准。

### 核心 5 大维度

1. **抓取与收录 (Crawling & Indexing)**：确保现代搜索引擎爬虫与大模型网络爬虫（GPTBot, ClaudeBot, PerplexityBot, Bytespider）无阻碍抓取。
2. **关键词与信息架构 (Keywords & Architecture)**：打破按国内电商思维堆砌词表的误区，一个页面针对性解答一个具体的采购选型问题。
3. **产品与信任证据链 (Product & Buyer Evidence)**：用实测公差（GD&T）、材料检测牌号、CPK 离散直方图、脱敏检验报告（COA/MSDS）与真实车间工序取代空洞宣传口号。
4. **询盘与转化漏斗 (Inquiry Funnel)**：消灭冗长表单，清晰公示 48 小时响应承诺、样品申请独立通道与企业合规沟通路径。
5. **数字资产所有权与长效运营 (Asset Ownership & Ops)**：在商务合同中强制锁定 Git 源码仓库所有权、独立云部署凭据、域名所有权及 A/B/C 询盘分级管理。

👉 **[查看完整 25 项检查清单 (CHECKLIST.md)](./CHECKLIST.md)**  
👉 **在线交互版与 PDF 下载：[Factory Growth Lab 25 项自查清单](https://www.factorygrowthlab.com/free-checklist)**

---

## English Documentation

This open-source repository establishes an **engineering acceptance standard** for B2B export manufacturing websites, industrial component suppliers, and OEM/ODM engineering facilities.

In the era of **Generative Engine Optimization (GEO)** and AI-driven procurement (ChatGPT Search, Perplexity, Google AI Overviews, DeepSeek), industrial buyers rarely read vague marketing puffery. Technical purchasing committees make qualification decisions based on verifiable shop-floor density: dimensional tolerances, material testing traceability, certified inspection sheets, and transparent trade terms.

### The 5 Core Pillars

1. **Crawling, Indexing & Bot Legibility**: Full accessibility for search engines and generative AI retrieval crawlers.
2. **Information Architecture**: Single-intent page structures addressing explicit buyer qualification inquiries.
3. **Engineering Evidence Chains**: GD&T tolerances, CMM inspection sheets, batch mill certificates, and verified testing standards.
4. **Inquiry Funnel & SLA**: Frictionless conversion paths, five-field RFQ caps, and published 48-hour engineering response commitments.
5. **Code Custody & True Asset Ownership**: Full Git repository handover (GitHub/GitLab), unbundled cloud hosting, and zero closed-CMS lock-in.

---

## 25 项检查清单速览 (Quick Checklist)

| 组别 | 核心检查项 | 关键工程要求 |
| :--- | :--- | :--- |
| **01 抓取与收录** | robots.txt / sitemap / site 查询 / canonical / 真实 404 | 杜绝 CSS/JS 阻拦；sitemap 100% 返回 200；规范网址自引用 |
| **02 架构与关键词** | 采购意图 4 分类 / 单页单问题 / 独立型号 URL / 应用场景页 / 真实采购 FAQ | 产品词、应用词、规格词、采购问答隔离；杜绝所有型号揉在单页 |
| **03 产品与工程证据** | 首屏参数公差表 / MOQ与交期透明 / 认证带编号有效期 / QC三步检验流 / 实测设备图片 | 拒绝图库假图；提供受控图纸公差与批次 CPK 直方图；清晰标注阶梯交期 |
| **04 询盘路径** | 唯一明确 CTA / 表单≤5 字段 / 48小时响应公示 / 样品独立路径 / 多点联系方式 | 「获取报价」代替「了解更多」；样品通道独立；页面多处展示合规邮箱 |
| **05 资产与运营** | 月度内容更新 / GSC数据复盘 / 询盘 A/B/C 分级 / 内链闭环 / 源码与域名自持 | 拒绝供应商闭源系统锁定；Git 仓库所有权归客户；独立云端托管 |

---

## 使用指南 (How to Use)

### 1. 本地或项目管理工具导入
直接复制 [CHECKLIST.md](./CHECKLIST.md) 的内容导入至 Notion、飞书文档、语雀、Jira 或 GitHub Issues 中，作为新网站上线或改版的验收门禁（Acceptance Gate）。

### 2. 配合大模型进行自动化网站初审
您可以将 [CHECKLIST.md](./CHECKLIST.md) 的内容与您的公司网站链接一并输入 **DeepSeek / ChatGPT / Claude / 豆包**：
```text
请阅读上述来自 Factory Growth Lab 的《外贸独立站 25 项工程自查清单》，
帮我对照审查我的公司英文官网：[输入您的网站网址]
请指出当前网站在「产品与信任证据」、「抓取与收录」、「询盘路径」上存在的最大薄弱环节，并给出具体修改建议。
```

---

## 结构化数据 (JSON-LD) 规范参考

复杂的工业品在部署结构化数据时，应避免使用普通消费品的单一口径 retail price。推荐采用 `AggregateOffer` 或多重 `Offer` 节点以表达工业品的阶梯起订量与交期：

```json
{
  "@context": "https://schema.org",
  "@type": "Product",
  "name": "Precision CNC Machined Aluminum Bushings",
  "description": "Custom 6061-T6 aluminum bushings with tight bore tolerance (±0.005mm) for industrial automation.",
  "offers": {
    "@type": "AggregateOffer",
    "priceCurrency": "USD",
    "lowPrice": "1.20",
    "highPrice": "4.50",
    "offerCount": "3",
    "offers": [
      {
        "@type": "Offer",
        "price": "4.50",
        "priceCurrency": "USD",
        "eligibleQuantity": {
          "@type": "QuantitativeValue",
          "minValue": "100",
          "maxValue": "499",
          "unitCode": "C62"
        },
        "deliveryLeadTime": {
          "@type": "QuantitativeValue",
          "value": "10",
          "unitCode": "DAY"
        }
      },
      {
        "@type": "Offer",
        "price": "1.20",
        "priceCurrency": "USD",
        "eligibleQuantity": {
          "@type": "QuantitativeValue",
          "minValue": "5000",
          "unitCode": "C62"
        },
        "deliveryLeadTime": {
          "@type": "QuantitativeValue",
          "value": "30",
          "unitCode": "DAY"
        }
      }
    ]
  }
}
```

在线一键生成 B2B 工业品 Schema 请访问：[B2B Schema 生成器](https://www.factorygrowthlab.com/schema-generator)

---

## 协议与致谢

- 遵循 [MIT License](./LICENSE) 开源协议。
- 出品与维护：[Factory Growth Lab (工厂出海增长实验室)](https://www.factorygrowthlab.com)
- 欢迎提交 Issue 与 Pull Request 补充行业细分场景自查项。
