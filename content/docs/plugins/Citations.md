---
{"publish":true,"title":"Citations","created":"2025-08-14T17:29:12.194+02:00","modified":"2025-08-14T17:29:12.195+02:00","tags":["plugin/transformer"],"cssclasses":""}
---


This plugin adds Citation support to Quartz.

> [!note]
> For information on how to add, remove or configure plugins, see the [[docs/configuration#Plugins\|Configuration]] page.

This plugin accepts the following configuration options:

- `bibliographyFile`: the path to the bibliography file. Defaults to `./bibliography.bib`. This is relative to git source of your vault.
- `suppressBibliography`: whether to suppress the bibliography at the end of the document. Defaults to `false`.
- `linkCitations`: whether to link citations to the bibliography. Defaults to `false`.
- `csl`: the citation style to use. Defaults to `apa`. Reference [rehype-citation](https://rehype-citation.netlify.app/custom-csl) for more options.
- `prettyLink`: whether to use pretty links for citations. Defaults to `true`.

## API

- Category: Transformer
- Function name: `Plugin.Citations()`.
- Source: [`quartz/plugins/transformers/citations.ts`](https://github.com/jackyzha0/quartz/blob/v4/quartz/plugins/transformers/citations.ts).
