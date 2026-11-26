# Your Project's Title...
Your project's description...

## Environments
- Preview: https://main--eds-2026--Shehzad1399.aem.page/
- Live: https://main--eds-2026--Shehzad1399.aem.live/

## Documentation

Before using the aem-boilerplate, we recommend you to go through the documentation on https://www.aem.live/docs/ and more specifically:
1. [Developer Tutorial](https://www.aem.live/developer/tutorial)
2. [The Anatomy of a Project](https://www.aem.live/developer/anatomy-of-a-project)
3. [Web Performance](https://www.aem.live/developer/keeping-it-100)
4. [Markup, Sections, Blocks, and Auto Blocking](https://www.aem.live/developer/markup-sections-blocks)

## Installation

```sh
npm i
```

## Linting

```sh
npm run lint
```

## Local development

1. Create a new repository based on the `aem-boilerplate` template
1. Add the [AEM Code Sync GitHub App](https://github.com/apps/aem-code-sync) to the repository
1. Install the [AEM CLI](https://github.com/adobe/helix-cli): `npm install -g @adobe/aem-cli`
1. Start AEM Proxy: `aem up` (opens your browser at `http://localhost:3000`)
1. Open the `eds-2026` directory in your favorite IDE and start coding :)

## Session 2

The `/session-2` page uses `EDS Enablement Block (session-two, session-practice)`
in DA. Add an image and text in separate cells, following the
[Columns pattern](https://www.aem.live/developer/block-collection/columns).
Missing or extra cells are kept. `session-two` adds a border;
`session-practice` adds padding and a light background.

The page title is `session-2 setup first page`. The root `metadata` sheet uses
`URL` and `Title` columns with `**` / `session-2 setup` as the site default.
The page title overrides that default. Preview and publish both documents.

Run `aem up` and check `http://localhost:3000/session-2`.
Merge the PR to release code, then publish content with Sidekick.

The DA Preview tab uses the `dapreview` integration.
See [live-preview limitations](https://docs.da.live/authors/reference/live-preview#limitations)
and check the branch preview and live page before calling it done.
