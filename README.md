# DOI Quick Search

A fast, single-page DOI lookup tool for English academic paper titles.

## What It Does

Paste or type an English paper title, and the page searches Crossref for the most likely DOI. It shows the best match first, provides copy/open actions, and lists alternative matches when available.

## Features

- Automatic search after typing pauses
- Direct Crossref metadata lookup
- Local browser cache for repeated searches
- Request cancellation so stale results do not overwrite newer input
- Match confidence indicator
- Copy DOI and open DOI link actions
- Responsive layout for desktop and mobile browsers

## Usage

Open `index.html` in a browser, then enter a paper title such as:

```text
Deep Residual Learning for Image Recognition
```

Expected DOI:

```text
10.1109/cvpr.2016.90
```

## Data Source

This tool uses the [Crossref REST API](https://www.crossref.org/documentation/retrieve-metadata/rest-api/) to retrieve DOI metadata.

## Notes

- Results depend on Crossref metadata and may include multiple candidate records.
- For the best match, enter the full English title and remove author names, journal names, page numbers, or unrelated text.
- Browser caching is local to your device.

## Files

```text
index.html   Static web app
README.md    Project documentation
LICENSE      MIT license
```

## License

MIT
