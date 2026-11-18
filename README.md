安全研究员，SRC 猎人（EDUSRC / 补天 / CNVD）。黑盒渗透和白盒审计都做，近一年在把挖洞方法论整理成 AI Agent 能直接加载的技能库。重复劳动会写成工具，实战复盘发在博客上（90+ 篇技术笔记）。

Blog [xycovo.com](https://xycovo.com) · Mail xuyichen2025@outlook.com

## 项目

| 项目 | 说明 |
|------|------|
| [acumen](https://github.com/Kur1sulab/acumen) | 鉴微 Acumen：小而精的本地漏扫。填目标 → 开扫 → 命中入账 → 复验 → 导 MD / CSV，绿色版自带扫描引擎，双击就跑。每条命中带证据与复现命令，勾几条点「复验」就用同一个模式重跑一遍确认还在不在（仍存在 / 已消失 / 无法判定）。只监听 `127.0.0.1`，不联网、零第三方依赖 |
| [atlas](https://github.com/Kur1sulab/atlas) | 资产测绘引擎：子域枚举、端口、指纹识别、敏感路径、API 未授权、JS 端点。Go 单文件内核 + Python 编排，零第三方依赖，EDUSRC 实战在用 |
| [blackbox](https://github.com/Kur1sulab/blackbox) | 黑盒安全测试技能集，144 个渗透 playbook，按攻击链组织 |
| [whitebox](https://github.com/Kur1sulab/whitebox) | 白盒代码审计技能集，38 个源码审计、逆向、密码分析 playbook |
| [pentest-ops](https://github.com/Kur1sulab/pentest-ops) | 渗透作战指挥台。把渗透情报档案渲染成可视化作战看板，有桌面插件、Web dashboard、静态页三种形态 |

## 技术栈

Burp Suite、sqlmap、nuclei、Nmap、Metasploit、Yakit。开发主要用 Python、Go、PHP，也写 TypeScript 和 Bash。方向是 Web 漏洞挖掘、Java 白盒审计、LLM/Agent 安全。

---

所有安全测试均在授权范围内进行，漏洞已按流程报送至对应 SRC / CNVD。
