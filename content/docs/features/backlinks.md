---
{"publish":true,"title":"Backlinks","created":"2025-08-14T17:29:12.152+02:00","modified":"2025-08-14T17:29:12.152+02:00","tags":["component"],"cssclasses":""}
---


A backlink for a note is a link from another note to that note. Links in the backlink pane also feature rich [[docs/features/popover previews]] if you have that feature enabled.

## Customization

- Removing backlinks: delete all usages of `Component.Backlinks()` from `quartz.layout.ts`.
- Hide when empty: hide `Backlinks` if given page doesn't contain any backlinks (default to `true`). To disable this, use `Component.Backlinks({ hideWhenEmpty: false })`.
- Component: `quartz/components/Backlinks.tsx`
- Style: `quartz/components/styles/backlinks.scss`
- Script: `quartz/components/scripts/search.inline.ts`
