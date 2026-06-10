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

You can use DOI Quick Search in two ways: the hosted web version or a local downloaded copy.

你可以通过两种方式使用 DOI 快速查询：在线网页版，或下载到本地后使用。

### Option 1: Hosted Web Version / 方式一：在线网页版

Open the hosted version:

打开在线网页版：

**https://doi-quick-search1.vercel.app**

Steps:

步骤：

1. Open the web page in a browser.
2. Paste or type a complete English paper title.
3. Wait briefly for the automatic search, or click the search button.
4. Copy the DOI or open the DOI link from the result panel.

1. 在浏览器中打开网页。
2. 粘贴或输入完整的英文论文标题。
3. 等待页面自动查询，或点击查询按钮。
4. 在结果区域复制 DOI，或打开 DOI 链接。

Advantages:

优势：

- No download or setup required.
- Works on any modern browser.
- Always uses the latest deployed version.

- 无需下载或配置。
- 可在任何现代浏览器中使用。
- 始终使用已部署的最新版本。

### Option 2: Local Download / 方式二：下载到本地使用

Download the repository or just save `index.html`, then open `index.html` directly in your browser.

下载本仓库，或单独保存 `index.html` 文件，然后直接用浏览器打开 `index.html`。

Example title:

示例标题：

```text
Deep Residual Learning for Image Recognition
```

Expected DOI / 预期 DOI：

```text
10.1109/cvpr.2016.90
```

Advantages:

优势：

- Faster for repeated use because the browser cache stays on your local device.
- Can be kept as a lightweight personal tool without opening GitHub or Vercel first.
- No build step, package installation, or server is required.

- 重复查询速度更快，因为浏览器缓存会保存在本地设备中。
- 可以作为轻量的个人工具保存，不需要每次先打开 GitHub 或 Vercel。
- 不需要构建步骤、依赖安装或服务器。

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
