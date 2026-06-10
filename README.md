# DOI Quick Search / DOI 快速查询

## Online Web App / 在线网页版

**Use it here / 立即使用：**

**https://doi-quick-search1.vercel.app**

Open the link above in any modern browser, paste an English paper title, and the DOI result will appear automatically.

在现代浏览器中打开上方链接，粘贴英文论文标题后，页面会自动返回 DOI 查询结果。

A fast, single-page DOI lookup tool for English academic paper titles.

一个快速、单页式的 DOI 查询工具，适合根据英文论文标题查找 DOI。

## What It Does / 功能简介

Paste or type an English paper title, and the page searches Crossref for the most likely DOI. It shows the best match first, provides copy/open actions, and lists alternative matches when available.

粘贴或输入英文论文标题后，页面会通过 Crossref 检索最可能匹配的 DOI。工具会优先展示最佳匹配结果，并提供复制、打开 DOI 链接以及查看其他候选结果的功能。

## Features / 功能特性

- Automatic search after typing pauses
- Direct Crossref metadata lookup
- Local browser cache for repeated searches
- Request cancellation so stale results do not overwrite newer input
- Match confidence indicator
- Copy DOI and open DOI link actions
- Responsive layout for desktop and mobile browsers

- 停止输入后自动查询
- 直接调用 Crossref 元数据接口
- 使用浏览器本地缓存，加快重复查询
- 自动取消旧请求，避免慢请求覆盖新结果
- 显示匹配可信度
- 支持复制 DOI 和打开 DOI 链接
- 适配桌面和移动浏览器

## Usage / 使用方法

Open `index.html` in a browser, then enter a paper title such as:

在浏览器中打开 `index.html`，然后输入英文论文标题，例如：

```text
Deep Residual Learning for Image Recognition
```

Expected DOI / 预期 DOI：

```text
10.1109/cvpr.2016.90
```

## Web Usage / 网页版使用说明

How to use:

使用方法：

1. Open the web page in a browser.
2. Paste or type a complete English paper title.
3. Wait briefly for the automatic search, or click the search button.
4. Copy the DOI or open the DOI link from the result panel.

1. 在浏览器中打开网页。
2. 粘贴或输入完整的英文论文标题。
3. 等待页面自动查询，或点击查询按钮。
4. 在结果区域复制 DOI，或打开 DOI 链接。

## Data Source / 数据来源

This tool uses the [Crossref REST API](https://www.crossref.org/documentation/retrieve-metadata/rest-api/) to retrieve DOI metadata.

本工具使用 [Crossref REST API](https://www.crossref.org/documentation/retrieve-metadata/rest-api/) 检索 DOI 元数据。

## Notes / 注意事项

- Results depend on Crossref metadata and may include multiple candidate records.
- For the best match, enter the full English title and remove author names, journal names, page numbers, or unrelated text.
- Browser caching is local to your device.

- 查询结果取决于 Crossref 的元数据，可能会返回多个候选记录。
- 为了获得更准确的结果，建议输入完整英文标题，并删除作者名、期刊名、页码等无关信息。
- 缓存仅保存在当前设备的浏览器中。

## Files / 文件说明

```text
index.html   Static web app / 静态网页应用
README.md    Project documentation / 项目文档
LICENSE      MIT license / MIT 许可证
```

## License / 许可证

MIT
