# 2026 秋 · 人机交互组招新考核 · 解题仓库

本仓库用于存放《2026 秋人机交互组-设计/前端方向-招新考核》笔试的全部解题文件。
仓库目录结构按照考核文档中的"提交要求"组织，便于逐题对照与评审。

## 目录结构

```
├── README.md                              # 仓库说明（本文件）
├── .gitignore                             # 忽略 node_modules 等依赖与临时文件
├── T02/
│   ├── Multimodal Video Visualization.md  # 文献总结（标题为所选研究领域）
│   └── reference/                         # 参考文献原文 PDF 文件夹
├── T03/
│   ├── README.md                          # 设计说明文档
│   └── design.png                         # 完整设计图
├── T04/
│   ├── README.md                          # 代码实现思路及说明文档
│   ├── .gitignore                         # 前端工程依赖忽略规则
│   ├── src/                               # 项目源码文件夹
│   └── build/                             # 编译后的项目文件（可直接浏览）
└── T05/
    └── README.md                          # AI 工具使用情况与感受
```

## 任务清单与进度

| 编号 | 任务 | 交付物 | 状态 |
| --- | --- | --- | --- |
| 1.1 | GitHub 与 Markdown 基础 | 本仓库及目录结构 | 已完成 |
| 1.2 | 研究总结（选题：Multimodal Video Visualization） | `T02/Multimodal Video Visualization.md`、`T02/reference/`（5 篇原文已归档） | 进行中（提纲已就绪，正文待撰写） |
| 1.3 | 【设计方向必做】可视化系统设计 | `T03/README.md`、`T03/design.png` | 待完成 |
| 1.4 | 【前端方向必做】可视化设计实现（增强雷达图） | `T04/README.md`、`T04/src/`、`T04/build/` | 待完成 |
| 1.5 | AI 工具使用总结 | `T05/README.md` | 待完成 |

## 选题说明

研究总结部分选择的方向为 **Multimodal Video Visualization（多模态视频可视分析）**，
该方向的参考论文为 *Anchorage: Visual Analysis of Satisfaction in Customer Service Videos Via Anchor Events*
(IEEE TVCG, 2024)。文献总结正文见 `T02/Multimodal Video Visualization.md`，
目前为提纲状态，五篇文献分别见 `reference/` 下的原文 PDF。

## 文献总结的添加规范

考核要求：文献总结的文件名即为所选研究领域，参考文献原文放在同级的 `reference/` 文件夹中。因此新增文献时按以下规则操作：

1. **正文**：写在 `T02/Multimodal Video Visualization.md` 中，每篇按统一体例给出——基本信息、问题与动机、方法与可视化设计、主要贡献与创新点、评估与局限；同时在其"横向对比"表中补一行。
2. **原文 PDF**：放入 `T02/reference/`，文件名保持论文标题的原始英文写法，便于与正文中的参考文献条目对应。
3. **参考文献**：在正文第 6 节按出现顺序编号；若某篇只是相邻领域参考、不计入本方向的五篇，需在该条后标注"（相邻领域）"。
4. **数量要求**：本方向至少 5 篇，正文提纲中已按 5 篇预留小节（见文档第 2 节）。
5. **提交**：新增或修改后执行 `git add .` → `git commit -m "..."` → `git push`，保持仓库与本地一致。

## 本地浏览方式

- T02 / T03 / T05 均为 Markdown 文档，可直接在 GitHub 或任意 Markdown 阅读器中查看。
- T04 若提供构建产物，可直接打开 `T04/build/index.html` 浏览；源码运行方式见 `T04/README.md`。

## 提交信息

- 仓库链接：`<在此填写你的 GitHub 仓库地址>`
- 联系方式：`<可选：姓名 / 邮箱>`
