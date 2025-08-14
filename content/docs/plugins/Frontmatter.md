---
{"publish":true,"title":"Frontmatter","created":"2025-08-14T17:29:12.201+02:00","modified":"2025-08-14T17:29:12.201+02:00","tags":["plugin/transformer"],"cssclasses":""}
---


This plugin parses the frontmatter of the page using the [gray-matter](https://github.com/jonschlinkert/gray-matter) library. See [[docs/authoring content#Syntax]], [[docs/features/Obsidian compatibility]] and [[docs/features/OxHugo compatibility]] for more information.

> [!note]
> For information on how to add, remove or configure plugins, see the [[docs/configuration#Plugins\|Configuration]] page.

This plugin accepts the following configuration options:

- `delimiters`: the delimiters to use for the frontmatter. Can have one value (e.g. `"---"`) or separate values for opening and closing delimiters (e.g. `["---", "~~~"]`). Defaults to `"---"`.
- `language`: the language to use for parsing the frontmatter. Can be `yaml` (default) or `toml`.

> [!warning]
> This plugin must not be removed, otherwise Quartz will break.

## List

Quartz supports the following frontmatter:

- title
  - `title`
- description
  - `description`
- permalink
  - `permalink`
- comments
  - `comments`
- lang
  - `lang`
- publish
  - `publish`
- draft
  - `draft`
- enableToc
  - `enableToc`
- tags
  - `tags`
  - `tag`
- aliases
  - `aliases`
  - `alias`
- cssclasses
  - `cssclasses`
  - `cssclass`
- socialDescription
  - `socialDescription`
- socialImage
  - `socialImage`
  - `image`
  - `cover`
- created
  - `created`
  - `date`
- modified
  - `modified`
  - `lastmod`
  - `updated`
  - `last-modified`
- published
  - `published`
  - `publishDate`
  - `date`

## API

- Category: Transformer
- Function name: `Plugin.Frontmatter()`.
- Source: [`quartz/plugins/transformers/frontmatter.ts`](https://github.com/jackyzha0/quartz/blob/v4/quartz/plugins/transformers/frontmatter.ts).
