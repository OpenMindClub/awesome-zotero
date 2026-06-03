# awesome-zotero

<!--rehype:style=font-size: 38px; border-bottom: 0; display: flex; min-height: 260px; align-items: center; justify-content: center;-->

[![Awesome](https://awesome.re/badge.svg)](https://github.com/sindresorhus/awesome) [![jaywcjlove/sb](https://wangchujiang.com/sb/lang/english.svg)](README.md) [![jaywcjlove/sb](https://wangchujiang.com/sb/lang/chinese.svg)](README.zh-cn.md)

<!--rehype:style=text-align: center;-->

社区维护的 Zotero 7 生态导航。聚焦高质量、长期稳定的工作流与插件，不再以 Zotero 6 兼容性为目标。

> 如果你刚开始用 Zotero 或刚从 6 升级到 7，可以先看「快速上手」这一节，再按需往下展开。

## 快速上手：2025 推荐工作流

> 默认你使用 Zotero 7. 这一节给出一套信息密度高的「标准增强组合」。

**最小推荐栈 (10 个插件):**

1. **Better BibTeX for Zotero**
   [retorquere/zotero-better-bibtex](https://github.com/retorquere/zotero-better-bibtex)
   稳定生成 citekey, 提供增强的 BibTeX 和 CSL JSON 导出，支持自动刷新文献列表。LaTeX, Markdown, Pandoc 写作的刚需。

2. **Better Notes for Zotero**
   [windingwind/zotero-better-notes](https://github.com/windingwind/zotero-better-notes)
   在 Zotero 内完成文献笔记的拆分、链接与重组，支持模板、子笔记、图谱视图，并可以同步到 Markdown 文件。

3. **Translate for Zotero (Zotero PDF Translate)**
   [windingwind/zotero-pdf-translate](https://github.com/windingwind/zotero-pdf-translate)
   为 PDF, EPUB 和网页提供多引擎翻译，支持划词和整页翻译，中英双向阅读更轻松。

4. **Actions & Tags for Zotero**
   [windingwind/zotero-actions-tags](https://github.com/windingwind/zotero-actions-tags)
   基于标签的自动化工作流中心：为新条目自动打标签，批量移动到集合，修改字段，连通各种批处理脚本。

5. **Linter for Zotero**
   [northword/zotero-format-metadata](https://github.com/northword/zotero-format-metadata)
   清理和统一元数据：修正标题格式，设置期刊缩写，统一语言字段，发现潜在重复条目。

6. **ZotMoov**
   [wileyyugioh/zotmoov](https://github.com/wileyyugioh/zotmoov)
   Zotfile 在 Zotero 7 时代的替代方案，支持将附件移动到 OneDrive, Dropbox, Box 等同步盘，并按规则重命名。

7. **Zotero Add-on Market**
   [syt2/zotero-addons](https://github.com/syt2/zotero-addons)
   插件市场：在 Zotero 内浏览、搜索、安装和更新插件，终端用户找插件的第一站。

8. **Jasminum**
   [l0o0/jasminum](https://github.com/l0o0/jasminum)
   中文文献元数据增强：作者姓名格式，拼音排序，中文期刊信息等，是中文用户几乎必装的插件。

9. **DOI Manager / Zotero ShortDOI**
   [bwiernik/zotero-shortdoi](https://github.com/bwiernik/zotero-shortdoi)
   使用 Crossref 等数据源校验和补全 DOI, 生成 short DOI, 让文献条目更完整更稳定。

10. **去重和附件健康**
    - [ZoteroDuplicatesMerger](https://github.com/frangoud/ZoteroDuplicatesMerger)
      批量合并重复条目，配合 Zotero 内置 Duplicates 视图使用。
    - [Zoplicate](https://github.com/Polygon/zoplicate)
      更智能的重复检测和半自动合并，对大型库很有帮助。
    - [Attachment Scanner](https://github.com/retorquere/zotero-attachment-scanner)
      扫描丢失附件和潜在重复文件，清理磁盘时很好用。

**典型扩展组合：**

- 学术写作 (LaTeX / Markdown / Pandoc)
  - Better BibTeX
  - zotxt 或 MarkDB-Connect
  - Citation Tally 或 Scite 插件 (查看引用情况)

- 知识管理 (Obsidian / Logseq / Roam)
  - Better Notes
  - MarkDB-Connect
  - Zotero2MD 或 Zotero2Readwise
  - Obsidian 插件或 zotero-roam 之类的桥接工具

- Notion 工作流
  - Better BibTeX
  - Notero 将文献同步到 Notion
  - 再配合 Notion 模板管理写作和项目

- AI + Zotero
  - Awesome GPT / PapersGPT / Zotero-TLDR
  - 对单篇或一组文献做摘要，问答和辅助写作
  - 注意隐私和合规，不要上传保密稿件

## Zotero 教程

### 官方资源

- [Zotero 支持文档](https://www.zotero.org/support/)
- [Zotero 论坛](https://forums.zotero.org/discussions)
- [Zotero 更新记录](https://www.zotero.org/support/changelog)
- [快捷键列表](https://www.zotero.org/support/kb/keyboard_shortcuts)
- [插件列表](https://www.zotero.org/support/plugins)
- [Item 类型与字段定义](https://www.zotero.org/support/kb/item_types_and_fields)

### 社区文章与视频

> 许多经典文章写于 Zotero 5 或 6 时期，UI 截图略有差异，但对文献管理与知识管理的理解在 Zotero 7 时代仍然适用。

- 核心概念：BIBFRAME, MARC, DOI, CSL 等
  - Schreur, P. The Evolution of BIBFRAME: from MARC Surrogate to Web Conformant Data Model.
  - Taniguchi, S. Examining BIBFRAME 2.0 from the Viewpoint of RDA Metadata Schema.
  - [MARC standards](https://en.wikipedia.org/wiki/MARC_standards)
  - [BIBFRAME](https://en.wikipedia.org/wiki/BIBFRAME)
  - [Citation Style Language](https://en.wikipedia.org/wiki/Citation_Style_Language)
  - [Zotero Quick Tip: Adding DOI Numbers](https://www.youtube.com/watch?v=ywgTnDIVGsM)

- 阳志平老师的 Zotero 最佳实践系列
  - [Zotero (1): 文献管理软件 Zotero 基础及进阶示范](https://www.yangzhiping.com/tech/zotero1.html)
  - [Zotero (2): 作为知识管理工具的 Zotero](https://www.yangzhiping.com/tech/zotero2.html)
  - [Zotero (3): 平板与社交：再谈研究辅助工具 Zotero 兼配套 App](https://www.yangzhiping.com/tech/zotero3.html)
  - [Zotero (4): Zotfile 插件的使用](https://www.yangzhiping.com/tech/zotero4.html)
  - [Zotero (5): 电子文献管理攻略](https://www.yangzhiping.com/tech/zotero5.html)
  - [Zotero (6): 如何批量下载 PDF](https://www.yangzhiping.com/tech/zotero6.html)

- 数字人文与个人数据库
  - [日码五千字：2019 年我的写作机器](https://sspai.com/post/58872)
  - [一：瓦尔堡的卡片盒子](https://sspai.com/post/58895)
  - [二：牛津文献书目和个人研究方向](https://sspai.com/post/58896)
  - [三：书目作为艺术史研究的方法：Kubikat](https://sspai.com/post/58897)
  - [四：用 Zotero 保存 Kubikat 检索条目](https://sspai.com/post/58898)
  - [五：艺术史的写作：图像的尤利西斯之旅](https://sspai.com/post/58908)
  - [如何勾画文艺复兴艺术史研究的全貌](https://sspai.com/post/62628)

- 中文用户向 Zotero 实践文章 (节选)
  - [文献管理终级神器 Zotero](http://www.hanlindong.com/2018/zotero-citation-manager/)
  - [四步实现自定义 Zotero 参考文献格式](https://zhuanlan.zhihu.com/p/31326415)
  - [用 Zotero + 坚果云搞定多设备文献管理](https://sspai.com/post/64283)
  - [使用 Zotero 在 Markdown 中优雅地处理参考文献](https://sspai.com/post/60825)
  - [Zotero 和它的朋友们：一个文献阅读生态](https://sspai.com/post/57943)

## Zotero 工具与生态

### Citation Style Language (CSL)

- [Chinese-STD-GB-T-7714-related-csl](https://github.com/redleafnew/Chinese-STD-GB-T-7714-related-csl)
  GB/T 7714-2015 相关 CSL 样式合集，覆盖期刊，学位论文等常见需求，中文科研用户的基础设施。

### 编程接口与批处理

- [Pyzotero](https://github.com/urschrei/pyzotero)
  Zotero Web API 与本地 API 的 Python 客户端，支持脚本访问，批量导入导出，查询与修改条目。

- [zotero-cli](https://github.com/dhondta/zotero-cli)
  基于 Pyzotero 的命令行工具，可以按条件筛选条目，输出为 CSV 或 Excel, 用于批量整理与统计。

- [Zotero2MD](https://github.com/e-alizadeh/Zotero2MD)
  从 Zotero 抓取注释与笔记，导出为结构化 Markdown 文件，常用于对接 Obsidian, Logseq 等。

- [Zotero2Readwise](https://github.com/e-alizadeh/Zotero2Readwise)
  将 Zotero 的高亮与笔记同步到 Readwise, 构建外部的阅读复习体系。

- [zotero-javascripts](https://github.com/redleafnew/zotero-javascripts)
  面向高级用户的批处理脚本集合，如批量修改标题大小写，清空特定字段，统一语言等。

### 网页与在线书目

- [Zotsite](https://github.com/plandes/zotsite)
  将本地 Zotero 库导出为可离线浏览的 HTML 网站，适合自建小型书目站点或备份。

- [Kerko](https://github.com/whiskyechobravo/kerko)
  基于 Zotero Web API 的在线书目前端组件，支持筛选，搜索与分类浏览，被多所机构用于公开书目项目。

## Zotero 插件 (Zotero 7)

> 本节只列出对 Zotero 7 有明确支持或广泛实践检验的插件。

### 核心必装套件

- [Better BibTeX for Zotero](https://github.com/retorquere/zotero-better-bibtex)
  稳定的 citekey, 强大的导出和自动更新，是任何涉及 LaTeX, Markdown, Pandoc 的工作流基础组件。

- [Better Notes for Zotero](https://github.com/windingwind/zotero-better-notes)
  把 Zotero 的笔记系统升级到「知识库」级别，支持块级引用，子笔记，大纲视图和 Markdown 同步。

- [Translate for Zotero](https://github.com/windingwind/zotero-pdf-translate)
  为 Zotero 内置阅读器提供翻译服务，尤其适合英文文献阅读和双语写作。

- [Actions & Tags for Zotero](https://github.com/windingwind/zotero-actions-tags)
  用规则和脚本驱动的自动化中枢，可以根据元数据，标签，集合等条件自动触发一系列操作。

- [Linter for Zotero](https://github.com/northword/zotero-format-metadata)
  聚焦元数据质量，一次性修复大量小问题，为后续写作与导出打下干净的基础。

- [ZotMoov](https://github.com/wileyyugioh/zotmoov)
  统一管理附件的存储位置与重命名策略，以云盘为中心搭建多设备阅读与备份方案。

- [Zotero Add-on Market](https://github.com/syt2/zotero-addons)
  插件市场，适合作为发现与升级插件的统一入口。

- [Jasminum](https://github.com/l0o0/jasminum)
  针对中文元数据的增强，解决人名，期刊名，拼音排序等一系列细节问题。

- [Zotero ShortDOI](https://github.com/bwiernik/zotero-shortdoi)
  对 DOI 做自动校验与补全，提高引用链接的持久性与准确性。

- 去重与附件健康
  - [ZoteroDuplicatesMerger](https://github.com/frangoud/ZoteroDuplicatesMerger)
  - [Zoplicate](https://github.com/Polygon/zoplicate)
  - [Attachment Scanner](https://github.com/retorquere/zotero-attachment-scanner)

### 阅读与笔记增强

- [Ethereal Style for Zotero](https://github.com/MuiseDestiny/zotero-style)
  大幅增强界面与阅读体验，包括阅读进度，标签侧栏，高亮样式等，适合重度阅读用户。

- [Ethereal Reference](https://github.com/MuiseDestiny/zotero-reference)
  从 PDF 参考文献中识别文献并匹配到 Zotero 条目，构建更完整的引用网络。

- [Chartero](https://github.com/volatile-static/Chartero)
  提供阅读统计与可视化，构建个人阅读时间线与热力图，对自我管理有需求时可以尝试。

- [zotero-ocr](https://github.com/UB-Mannheim/zotero-ocr)
  为扫描版 PDF 执行 OCR, 生成可检索文本，并可同时生成注释或 hOCR 输出。

### 元数据清理与去重

- [Linter for Zotero](https://github.com/northword/zotero-format-metadata)
- [ZoteroDuplicatesMerger](https://github.com/frangoud/ZoteroDuplicatesMerger)
- [Zoplicate](https://github.com/Polygon/zoplicate)
- [Attachment Scanner](https://github.com/retorquere/zotero-attachment-scanner)

如果你准备大规模整理老库，建议的顺序是：
备份库 → 使用 Linter 统一元数据 → 用 ZoteroDuplicatesMerger 与 Zoplicate 去重 → 用 Attachment Scanner 检查丢失附件与重复文件。

### 评价与科研情报

- [Zotero-IF](https://github.com/qnscholar/zotero-if)
  更新期刊影响因子和中科院分区，支持按年更新，适合中文科研评价使用场景。

- [Citation Tally](https://github.com/syt2/zotero-citation-tally)
  面向 Zotero 7 的引文统计插件，可以为条目批量拉取引用次数并可视化。

- [scite-zotero-plugin](https://github.com/scitedotai/scite-zotero-plugin)
  集成 scite 的支持，反对，提及统计，提供更细粒度的引用质量信息。

- [pubpeer_zotero_plugin](https://github.com/PubPeerFoundation/pubpeer_zotero_plugin)
  将 PubPeer 评论挂在条目下，有助于发现可能存在问题的研究。

- [zotero-inspire](https://github.com/inspirehep/zotero-inspire)
  面向高能物理等领域，深度集成 INSPIRE-HEP, 是该社区的常见工具。

- [arxiv-marker](https://github.com/lelelelelelelelelelelelele/arxiv-marker)
  解析 arXiv 预印本的真实发表会议/期刊、CORE/CCF 等级与引用次数（Semantic Scholar，CS 会议用 DBLP 兜底），并写回为规范的 Zotero 元数据，让 Zotero-IF、Citation Tally、Ethereal Style 等评估类插件能识别它们。原生 Zotero 7/9 插件；确定性解析，写入前逐条预览确认。

### AI 与大模型集成

- [Awesome GPT for Zotero](https://github.com/MuiseDestiny/zotero-gpt)
  在 Zotero 内调用 GPT 模型，对选中文本执行总结，改写，翻译，问答等操作，使用标签或命令驱动工作流。

- [PapersGPT for Zotero](https://github.com/papersgpt/papersgpt-for-zotero)
  以对话形式阅读 PDF, 支持多家 LLM 服务，并通过 MCP 将 Zotero 暴露给其他客户端。

- [Zotero-TLDR](https://github.com/syt2/Zotero-TLDR)
  自动从 Semantic Scholar 获取 TLDR 摘要，提供快速了解文献内容的入口。

- [zotero-chatgpt](https://github.com/kazgu/zotero-chatgpt)
  通过 ChatGPT API 做总结与翻译的轻量插件，适合作为按需尝试的选件。

> 使用这类插件前，请确认自己可以接受相应服务对数据的处理方式，不要把保密稿件与敏感数据直接发送给第三方服务。

### 与其他工具的集成

- [zotxt](https://github.com/egh/zotxt)
  为 Pandoc, Markdown, Emacs Org 等提供本地 HTTP 引用接口，在纯文本写作工作流里非常常见。

- [MarkDB-Connect](https://github.com/daeh/zotero-markdb-connect)
  扫描 Markdown 文件中的 citekey, 在 Zotero 中为对应条目打标签并建立跳转，适合作为 Zotero 与 Obsidian, Logseq, Zettlr 等工具之间的桥梁。

- [Notero](https://github.com/dvanoni/notero)
  将 Zotero 文献同步到 Notion 数据库，配合 Notion 模板可以管理文献，项目与写作任务。

- [zotero-roam](https://github.com/alixlahuec/zotero-roam)
  Roam Research 与 Zotero 的连接器，为 Roam 中的笔记自动注入文献信息与链接。

## Zotero Translators

> Translators 决定了 Zotero 如何从网页和数据库抓取元数据，对中文用户尤其重要。

- [OpenMindClub/awesome-translators](https://github.com/OpenMindClub/awesome-translators)
  开智学堂信息分析课程团队与学员共创的 Translators 集合，包含大量中文站点支持。

- [l0o0/translators_CN](https://github.com/l0o0/translators_CN)
  对中文学术站点提供增强支持的 Translators 集合，包括 CNKI 等。

## 开发资源

> 想写自己的插件或 Translators, 从这里开始。

- [Zotero 插件开发文档](https://www.zotero.org/support/dev/client_coding/plugin_development)
- [Zotero 7 for Developers](https://www.zotero.org/support/dev/zotero_7_for_developers)
- [Translators 开发指南](https://www.zotero.org/support/dev/translators)

插件模板与脚手架：

- [windingwind/zotero-plugin-template](https://github.com/windingwind/zotero-plugin-template)
- [northword/zotero-plugin-scaffold](https://github.com/northword/zotero-plugin-scaffold)
- [retorquere/generator-zotero-plugin](https://github.com/retorquere/generator-zotero-plugin)
- [MuiseDestiny/zotero-addon-template](https://github.com/MuiseDestiny/zotero-addon-template)

## 避免踩坑：不再推荐的插件

> 以下插件在 Zotero 7 中存在兼容性或维护问题，不再作为推荐方案，仅供你识别和迁移旧工作流。

- **Zotfile**
  曾经的附件管理神器，现不再支持 Zotero 7。推荐改用 ZotMoov, 同时使用 Zotero 7 内置的自动重命名功能。

- **Mdnotes for Zotero**
  已归档并停止维护，不兼容 Zotero 7。推荐使用 Zotero 内置 Markdown 导出，Better Notes, Zotero2MD 和 Obsidian 插件等组合替代。

- **Zotero Scihub**
  无法在 Zotero 7 中正常安装，也涉及版权和服务条款风险。公开场合不再推荐该插件。

- **Zotero Storage Scanner**
  仓库已归档，建议改用 Attachment Scanner 等新工具执行附件扫描与清理。

- **Zotero Scholar Citations**
  依赖对 Google Scholar 的抓取，在当前环境下经常不可用，不建议继续使用。引文计量推荐使用 Citation Tally 和 Scite 插件。

- **Report Customizer for Zotero**
  长期未对 Zotero 7 做适配，不建议基于它设计新的报告工作流。

- **Zutilo**
  在 Zotero 7 中仅部分功能可用，且存在不兼容风险。可作为高级用户按需安装的工具，不再视为默认必装。

- **ZoteroQuickLookReload**
  面向 Zotero 6 的附件预览增强，Zotero 7 已有改进的预览体验，一般无需再安装。

## Contribute

欢迎增补与修订。

1. 请先阅读仓库中的贡献指南 (CONTRIBUTING 文件)。
2. Fork 本仓库，按照 Awesome List 的格式添加或修改条目。
3. 提交 Pull Request, 简要说明你的修改动机与使用经验。

## Credits

感谢：

- 阳志平老师与开智学堂，最早系统整理了中文语境下的 Zotero 实践。
- 所有插件作者与维护者，是他们支撑起 Zotero 生态。
- 参与本仓库的所有贡献者，持续帮大家避坑，提升使用体验。

## License

本仓库采用 CC0 许可协议发布。

详情见：

[![CC0][CC0-badge]][CC0-link]

[CC0-badge]: http://mirrors.creativecommons.org/presskit/buttons/88x31/svg/cc-zero.svg
[CC0-link]: https://creativecommons.org/publicdomain/zero/1.0/
