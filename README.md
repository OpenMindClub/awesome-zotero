# awesome-zotero

<!--rehype:style=font-size: 38px; border-bottom: 0; display: flex; min-height: 260px; align-items: center; justify-content: center;-->

[![Awesome](https://awesome.re/badge.svg)](https://github.com/sindresorhus/awesome) [![jaywcjlove/sb](https://wangchujiang.com/sb/lang/english.svg)](README.md) [![jaywcjlove/sb](https://wangchujiang.com/sb/lang/chinese.svg)](README.zh-cn.md)

<!--rehype:style=text-align: center;-->

Community-maintained navigation to the Zotero 7 ecosystem. Focused on high-quality, long-term stable workflows and add-ons, and no longer targeting Zotero 6 compatibility.

> If you're just starting with Zotero or have just upgraded from 6 to 7, start with the "Quick Start" section and then expand as needed.

## Quick Start: Recommended 2025 workflow

> We assume you're using Zotero 7. This section provides a dense "standard enhancement bundle".

**Minimal recommended stack (10 add-ons):**

1. **Better BibTeX for Zotero**
   [retorquere/zotero-better-bibtex](https://github.com/retorquere/zotero-better-bibtex)
   Stable citekey generation, enhanced BibTeX and CSL JSON export, and automatic bibliography refresh. Essential for writing with LaTeX, Markdown, and Pandoc.

2. **Better Notes for Zotero**
   [windingwind/zotero-better-notes](https://github.com/windingwind/zotero-better-notes)
   Split, link, and recombine literature notes entirely inside Zotero. Supports templates, child notes, graph view, and syncing notes to Markdown files.

3. **Translate for Zotero (Zotero PDF Translate)**
   [windingwind/zotero-pdf-translate](https://github.com/windingwind/zotero-pdf-translate)
   Multi-engine translation for PDFs, EPUBs, and web pages. Supports selection-based and full-page translation, making bilingual reading much easier.

4. **Actions & Tags for Zotero**
   [windingwind/zotero-actions-tags](https://github.com/windingwind/zotero-actions-tags)
   A tag-based automation hub: automatically tag new items, batch-move them to collections, modify fields, and connect to various batch-processing scripts.

5. **Linter for Zotero**
   [northword/zotero-format-metadata](https://github.com/northword/zotero-format-metadata)
   Clean up and standardize metadata: fix title formatting, set journal abbreviations, unify language fields, and discover potential duplicate items.

6. **ZotMoov**
   [wileyyugioh/zotmoov](https://github.com/wileyyugioh/zotmoov)
   A Zotfile replacement for the Zotero 7 era. Moves attachments to sync folders such as OneDrive, Dropbox, and Box, and renames them according to custom rules.

7. **Zotero Add-on Market**
   [syt2/zotero-addons](https://github.com/syt2/zotero-addons)
   An add-on marketplace: browse, search, install, and update add-ons inside Zotero—the first stop for end users discovering extensions.

8. **Jasminum**
   [l0o0/jasminum](https://github.com/l0o0/jasminum)
   Enhances metadata for Chinese-language items: author name formatting, Pinyin sorting, Chinese journal information, and more. Almost a must-have for Chinese users.

9. **DOI Manager / Zotero ShortDOI**
   [bwiernik/zotero-shortdoi](https://github.com/bwiernik/zotero-shortdoi)
   Uses Crossref and other data sources to validate and complete DOIs, generate short DOIs, and make your items more complete and robust.

10. **De-duplication and attachment health**
    - [ZoteroDuplicatesMerger](https://github.com/frangoud/ZoteroDuplicatesMerger)
      Batch-merge duplicate items; use together with Zotero's built-in Duplicates view.
    - [Zoplicate](https://github.com/Polygon/zoplicate)
      More intelligent duplicate detection and semi-automatic merging, very helpful for large libraries.
    - [Attachment Scanner](https://github.com/retorquere/zotero-attachment-scanner)
      Scans for missing attachments and potential duplicate files; very useful when cleaning up disk space.

**Typical extension bundles:**

- Academic writing (LaTeX / Markdown / Pandoc)
  - Better BibTeX
  - zotxt or MarkDB-Connect
  - Citation Tally or Scite add-on (for inspecting citation counts)

- Knowledge management (Obsidian / Logseq / Roam)
  - Better Notes
  - MarkDB-Connect
  - Zotero2MD or Zotero2Readwise
  - Obsidian plug-ins or bridge tools such as zotero-roam

- Notion workflows
  - Better BibTeX
  - Notero to sync Zotero items into a Notion database
  - Combine with Notion templates to manage writing and projects

- AI + Zotero
  - Awesome GPT / PapersGPT / Zotero-TLDR
  - Summarize, run Q&A, and assist writing based on one or a group of papers
  - Be mindful of privacy and compliance—do not upload confidential manuscripts

## Zotero tutorials

### Official resources

- [Zotero documentation](https://www.zotero.org/support/)
- [Zotero forums](https://forums.zotero.org/discussions)
- [Zotero changelog](https://www.zotero.org/support/changelog)
- [Keyboard shortcuts](https://www.zotero.org/support/kb/keyboard_shortcuts)
- [Add-ons list](https://www.zotero.org/support/plugins)
- [Item types and fields](https://www.zotero.org/support/kb/item_types_and_fields)

### Community articles and videos

> Many classic posts were written for Zotero 5 or 6. The UI screenshots will differ slightly, but the ideas about literature and knowledge management still fully apply in the Zotero 7 era.

- Core concepts: BIBFRAME, MARC, DOI, CSL, etc.
  - Schreur, P. *The Evolution of BIBFRAME: from MARC Surrogate to Web Conformant Data Model.*
  - Taniguchi, S. *Examining BIBFRAME 2.0 from the Viewpoint of RDA Metadata Schema.*
  - [MARC standards](https://en.wikipedia.org/wiki/MARC_standards)
  - [BIBFRAME](https://en.wikipedia.org/wiki/BIBFRAME)
  - [Citation Style Language](https://en.wikipedia.org/wiki/Citation_Style_Language)
  - [Zotero Quick Tip: Adding DOI Numbers](https://www.youtube.com/watch?v=ywgTnDIVGsM)

- Yang Zhiping's Zotero best-practice series (Chinese)
  - [Zotero (1): 文献管理软件 Zotero 基础及进阶示范](https://www.yangzhiping.com/tech/zotero1.html)
  - [Zotero (2): 作为知识管理工具的 Zotero](https://www.yangzhiping.com/tech/zotero2.html)
  - [Zotero (3): 平板与社交：再谈研究辅助工具 Zotero 兼配套 App](https://www.yangzhiping.com/tech/zotero3.html)
  - [Zotero (4): Zotfile 插件的使用](https://www.yangzhiping.com/tech/zotero4.html)
  - [Zotero (5): 电子文献管理攻略](https://www.yangzhiping.com/tech/zotero5.html)
  - [Zotero (6): 如何批量下载 PDF](https://www.yangzhiping.com/tech/zotero6.html)

- Digital humanities and personal databases (Chinese)
  - [日码五千字：2019 年我的写作机器](https://sspai.com/post/58872)
  - [一：瓦尔堡的卡片盒子](https://sspai.com/post/58895)
  - [二：牛津文献书目和个人研究方向](https://sspai.com/post/58896)
  - [三：书目作为艺术史研究的方法：Kubikat](https://sspai.com/post/58897)
  - [四：用 Zotero 保存 Kubikat 检索条目](https://sspai.com/post/58898)
  - [五：艺术史的写作：图像的尤利西斯之旅](https://sspai.com/post/58908)
  - [如何勾画文艺复兴艺术史研究的全貌](https://sspai.com/post/62628)

- Zotero practice articles for Chinese users (selection)
  - [文献管理终级神器 Zotero](http://www.hanlindong.com/2018/zotero-citation-manager/)
  - [四步实现自定义 Zotero 参考文献格式](https://zhuanlan.zhihu.com/p/31326415)
  - [用 Zotero + 坚果云搞定多设备文献管理](https://sspai.com/post/64283)
  - [使用 Zotero 在 Markdown 中优雅地处理参考文献](https://sspai.com/post/60825)
  - [Zotero 和它的朋友们：一个文献阅读生态](https://sspai.com/post/57943)

## Zotero tools and ecosystem

### Citation Style Language (CSL)

- [Chinese-STD-GB-T-7714-related-csl](https://github.com/redleafnew/Chinese-STD-GB-T-7714-related-csl)
  CSL style collection for GB/T 7714-2015, covering journals, theses, and other common citation needs—foundational infrastructure for many Chinese researchers.

### Programming interfaces and batch processing

- [Pyzotero](https://github.com/urschrei/pyzotero)
  Python client for the Zotero Web API and local API. Supports scripted access, batch import/export, querying, and modifying items.

- [zotero-cli](https://github.com/dhondta/zotero-cli)
  Command-line tool built on Pyzotero. Filter items by criteria and export to CSV or Excel for batch cleanup and statistics.

- [Zotero2MD](https://github.com/e-alizadeh/Zotero2MD)
  Fetches annotations and notes from Zotero and exports them as structured Markdown files, commonly used to integrate with Obsidian, Logseq, etc.

- [Zotero2Readwise](https://github.com/e-alizadeh/Zotero2Readwise)
  Syncs Zotero highlights and notes to Readwise, helping you build an external system for review and spaced repetition.

- [zotero-javascripts](https://github.com/redleafnew/zotero-javascripts)
  A collection of batch-processing scripts for advanced users, e.g., bulk-change title case, clear specific fields, or normalize language fields.

### Web and online bibliographies

- [Zotsite](https://github.com/plandes/zotsite)
  Export a local Zotero library as an offline-browsable HTML site. Suitable for small self-hosted bibliographic sites or backups.

- [Kerko](https://github.com/whiskyechobravo/kerko)
  A front-end component for online bibliographies powered by the Zotero Web API. Supports filtering, search, and faceted browsing; used by many institutions for public bibliographies.

## Zotero add-ons (Zotero 7)

> This section only lists add-ons that explicitly support Zotero 7 or have been widely tested with it.

### Core must-have bundle

- [Better BibTeX for Zotero](https://github.com/retorquere/zotero-better-bibtex)
  Stable citekeys and powerful export/auto-update features—the foundation of any workflow involving LaTeX, Markdown, or Pandoc.

- [Better Notes for Zotero](https://github.com/windingwind/zotero-better-notes)
  Upgrades Zotero's notes into a full "knowledge base": supports block-level references, child notes, outline view, and Markdown syncing.

- [Translate for Zotero](https://github.com/windingwind/zotero-pdf-translate)
  Translation service integrated into Zotero's built-in reader—especially useful for reading English papers and writing in two languages.

- [Actions & Tags for Zotero](https://github.com/windingwind/zotero-actions-tags)
  A rule- and script-driven automation hub. Trigger sequences of actions based on metadata, tags, collections, and other conditions.

- [Linter for Zotero](https://github.com/northword/zotero-format-metadata)
  Focuses on metadata quality, fixing a large number of small issues in one go to prepare clean data for writing and export.

- [ZotMoov](https://github.com/wileyyugioh/zotmoov)
  Centralizes attachment storage locations and renaming strategies. Helps you build a cloud-drive-centered, multi-device reading and backup setup.

- [Zotero Add-on Market](https://github.com/syt2/zotero-addons)
  Add-on marketplace that acts as a unified entry point for discovering and upgrading add-ons.

- [Jasminum](https://github.com/l0o0/jasminum)
  Enhances metadata for Chinese items, handling names, journals, Pinyin sorting, and many details in between.

- [Zotero ShortDOI](https://github.com/bwiernik/zotero-shortdoi)
  Automatically validates and completes DOIs to improve persistence and accuracy of links.

- De-duplication and attachment health
  - [ZoteroDuplicatesMerger](https://github.com/frangoud/ZoteroDuplicatesMerger)
  - [Zoplicate](https://github.com/Polygon/zoplicate)
  - [Attachment Scanner](https://github.com/retorquere/zotero-attachment-scanner)

### Reading and note-taking enhancements

- [Ethereal Style for Zotero](https://github.com/MuiseDestiny/zotero-style)
  Greatly enhances UI and reading experience, including reading progress, tag sidebar, highlight styles, and more—excellent for heavy readers.

- [Ethereal Reference](https://github.com/MuiseDestiny/zotero-reference)
  Extracts references from PDF reference lists and matches them to Zotero items, building a more complete citation network.

- [Chartero](https://github.com/volatile-static/Chartero)
  Provides reading statistics and visualizations, building a personal timeline and heatmap of your reading—useful for self-tracking.

- [zotero-ocr](https://github.com/UB-Mannheim/zotero-ocr)
  Runs OCR on scanned PDFs to generate searchable text, with optional annotations or hOCR output.

### Metadata cleanup and de-duplication

- [Linter for Zotero](https://github.com/northword/zotero-format-metadata)
- [ZoteroDuplicatesMerger](https://github.com/frangoud/ZoteroDuplicatesMerger)
- [Zoplicate](https://github.com/Polygon/zoplicate)
- [Attachment Scanner](https://github.com/retorquere/zotero-attachment-scanner)

If you're planning a large-scale cleanup of an old library, a recommended sequence is:
Back up the library → use Linter to normalize metadata → use ZoteroDuplicatesMerger and Zoplicate for de-duplication → use Attachment Scanner to detect missing attachments and duplicate files.

### Evaluation and scholarly intelligence

- [Zotero-IF](https://github.com/qnscholar/zotero-if)
  Updates journal impact factors and CAS divisions, with yearly updates—fits many Chinese research evaluation scenarios.

- [Citation Tally](https://github.com/syt2/zotero-citation-tally)
  Citation statistics add-on for Zotero 7 that pulls citation counts for items in bulk and visualizes them.

- [scite-zotero-plugin](https://github.com/scitedotai/scite-zotero-plugin)
  Integrates scite's support/contradict/mention statistics, providing more fine-grained information on citation quality.

- [pubpeer_zotero_plugin](https://github.com/PubPeerFoundation/pubpeer_zotero_plugin)
  Displays PubPeer comments on items, helping you identify potentially problematic research.

- [zotero-inspire](https://github.com/inspirehep/zotero-inspire)
  Deep integration with INSPIRE-HEP for high-energy physics and related fields; a common tool in that community.

- [arxiv-marker](https://github.com/lelelelelelelelelelelelele/arxiv-marker)
  Resolves the real publication venue, CORE/CCF tier, and citation count of arXiv preprints (Semantic Scholar, with a DBLP fallback for CS conferences) and writes them back as proper Zotero metadata, so evaluation add-ons such as Zotero-IF, Citation Tally, and Ethereal Style recognize them. Native Zotero 7/9 plugin; deterministic, with every change reviewed before writing.

### AI and large-language-model integration

- [Awesome GPT for Zotero](https://github.com/MuiseDestiny/zotero-gpt)
  Call GPT models directly inside Zotero to summarize, rewrite, translate, and answer questions about selected text. Uses tags or commands to drive workflows.

- [PapersGPT for Zotero](https://github.com/papersgpt/papersgpt-for-zotero)
  Enables conversational reading of PDFs. Supports multiple LLM providers and exposes Zotero via MCP to other clients.

- [Zotero-TLDR](https://github.com/syt2/Zotero-TLDR)
  Automatically fetches TLDR-style summaries from Semantic Scholar to give you a quick overview of a paper.

- [zotero-chatgpt](https://github.com/kazgu/zotero-chatgpt)
  Lightweight add-on for summarization and translation via the ChatGPT API—good for occasional use.

> Before using these add-ons, make sure you're comfortable with how the underlying services process your data. Do not send confidential manuscripts or sensitive data to third parties.

### Integration with other tools

- [zotxt](https://github.com/egh/zotxt)
  Provides a local HTTP citation interface for Pandoc, Markdown, Emacs Org-mode, and similar tools—very common in plain-text writing workflows.

- [MarkDB-Connect](https://github.com/daeh/zotero-markdb-connect)
  Scans Markdown files for citekeys, tags corresponding items in Zotero, and creates back-links. Acts as a bridge between Zotero and tools like Obsidian, Logseq, and Zettlr.

- [Notero](https://github.com/dvanoni/notero)
  Syncs Zotero items to a Notion database, which you can then manage with Notion templates for literature, projects, and writing.

- [zotero-roam](https://github.com/alixlahuec/zotero-roam)
  Connector between Roam Research and Zotero, automatically injecting bibliographic information and links into Roam notes.

## Zotero Translators

> Translators determine how Zotero grabs metadata from websites and databases. They are particularly important for Chinese-language sites.

- [OpenMindClub/awesome-translators](https://github.com/OpenMindClub/awesome-translators)
  A collection of Translators co-created by the OpenMind Club information analysis course team and students, covering many Chinese sites.

- [l0o0/translators_CN](https://github.com/l0o0/translators_CN)
  Enhanced Translators for Chinese academic sites, including CNKI and more.

## Developer resources

> If you want to build your own add-ons or Translators, start here.

- [Zotero plug-in development documentation](https://www.zotero.org/support/dev/client_coding/plugin_development)
- [Zotero 7 for Developers](https://www.zotero.org/support/dev/zotero_7_for_developers)
- [Translators development guide](https://www.zotero.org/support/dev/translators)

Add-on templates and scaffolds:

- [windingwind/zotero-plugin-template](https://github.com/windingwind/zotero-plugin-template)
- [northword/zotero-plugin-scaffold](https://github.com/northword/zotero-plugin-scaffold)
- [retorquere/generator-zotero-plugin](https://github.com/retorquere/generator-zotero-plugin)
- [MuiseDestiny/zotero-addon-template](https://github.com/MuiseDestiny/zotero-addon-template)

## Avoiding pitfalls: add-ons no longer recommended

> The following add-ons have compatibility or maintenance issues with Zotero 7. They are no longer recommended as solutions and are listed only so that you can recognize them and migrate away from old workflows.

- **Zotfile**
  Once the go-to attachment manager, it no longer supports Zotero 7. Recommended alternative: ZotMoov, combined with Zotero 7's built-in automatic renaming.

- **Mdnotes for Zotero**
  Archived and unmaintained, not compatible with Zotero 7. Recommended alternatives: Zotero's built-in Markdown export, Better Notes, Zotero2MD, and Obsidian plug-ins.

- **Zotero Scihub**
  Cannot be installed in Zotero 7 and also involves copyright and terms-of-service risks. It is no longer recommended in public or shared workflows.

- **Zotero Storage Scanner**
  Repository has been archived. Use Attachment Scanner and other newer tools instead for attachment scanning and cleanup.

- **Zotero Scholar Citations**
  Relies on scraping Google Scholar and is frequently broken in current environments. For citation metrics, use Citation Tally and the Scite add-on instead.

- **Report Customizer for Zotero**
  Has not been adapted for Zotero 7 for a long time. Avoid designing new reporting workflows around it.

- **Zutilo**
  Only partially compatible with Zotero 7 and may cause issues. Treat it as an optional tool for advanced users, not part of a default must-have stack.

- **ZoteroQuickLookReload**
  Built for enhanced attachment previews in Zotero 6. Zotero 7 already has an improved preview experience, so this is generally unnecessary.

## Contribute

Contributions and improvements are welcome.

1. Please first read the contribution guidelines in this repository (the `CONTRIBUTING` file).
2. Fork this repository and add or modify entries following the Awesome List format.
3. Submit a Pull Request with a brief explanation of your motivation and experience with the changes.

## Credits

Thanks to:

- Yang Zhiping and OpenMind Club, for some of the earliest systematic Zotero practice in the Chinese context.
- All add-on authors and maintainers, who together support the Zotero ecosystem.
- All contributors to this repository, who continuously help users avoid pitfalls and improve their workflows.

## License

This repository is released under the CC0 license.

For details, see:

[![CC0][CC0-badge]][CC0-link]

[CC0-badge]: http://mirrors.creativecommons.org/presskit/buttons/88x31/svg/cc-zero.svg
[CC0-link]: https://creativecommons.org/publicdomain/zero/1.0/
