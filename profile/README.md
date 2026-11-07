<a href="https://druxtjs.org">
  <img src="banner.svg" alt="@druxt-contrib: Contributed modules for Druxt">
</a>

# @druxt-contrib

[![Druxt](https://img.shields.io/badge/framework-Druxt-00a4d3)](https://druxtjs.org)
[![License](https://img.shields.io/badge/license-MIT-blue)](https://github.com/druxt/druxt.js/blob/develop/LICENSE)
[![Discord](https://img.shields.io/badge/chat-Discord-5865F2?logo=discord&logoColor=white)](https://discord.druxtjs.org)

Modules that extend [Druxt](https://druxtjs.org), the fully decoupled Drupal
framework, beyond what the core packages cover.

Each one pairs a Drupal module with the Vue components that render it,
so a feature your editors already use in Drupal keeps working once the frontend
is Nuxt. They are separate packages: install only the ones you need, alongside
`druxt-site` or a Nuxt project you already have.

## Modules

| Module | Release | Renders |
| ------ | ------- | ------- |
| [druxt-ckeditor](https://github.com/druxt-contrib/druxt-ckeditor) | not yet released | Drupal's own [CKEditor 5](https://www.drupal.org/docs/core-modules-and-themes/core-modules/ckeditor-5-module) build, mounted on a field |
| [druxt-config-pages](https://github.com/druxt-contrib/druxt-config-pages) | [![@druxt-contrib/config-pages on npm](https://img.shields.io/npm/v/@druxt-contrib/config-pages?label=npm&color=00a4d3)](https://www.npmjs.com/package/@druxt-contrib/config-pages) | [Config Pages](https://www.drupal.org/project/config_pages) as Druxt components |
| [druxt-layout-builder](https://github.com/druxt-contrib/druxt-layout-builder) | not yet released | [Layout Builder](https://www.drupal.org/docs/8/core/modules/layout-builder) sections |
| [druxt-layout-paragraphs](https://github.com/druxt-contrib/druxt-layout-paragraphs) | [![druxt-layout-paragraphs on npm](https://img.shields.io/npm/v/druxt-layout-paragraphs?label=npm&color=00a4d3)](https://www.npmjs.com/package/druxt-layout-paragraphs) | [Layout Paragraphs](https://www.drupal.org/project/layout_paragraphs) layouts |
| [druxt-node-preview](https://github.com/druxt-contrib/druxt-node-preview) | [![@druxt-contrib/node-preview dev build on npm](https://img.shields.io/npm/v/@druxt-contrib/node-preview/dev?label=dev&color=7c4dff)](https://www.npmjs.com/package/@druxt-contrib/node-preview/v/dev) | An unsaved node, through [JSON:API Node Preview](https://www.drupal.org/project/jsonapi_node_preview) and [Consumer Node Preview](https://www.drupal.org/project/consumer_node_preview) |

## Install

```sh
npm install @druxt-contrib/config-pages
```

Then add it to `modules` in `nuxt.config.js`, the same way as any other Druxt
module. Each repository's README covers its own options.

A module with a dev build and no stable release installs from the `dev` tag:

```sh
npm install @druxt-contrib/node-preview@dev
```

## Building your own

[module-template](https://github.com/druxt/module-template) is the starting
point, and the reference these modules follow. It ships the structure, tooling
and CI a Druxt module is expected to have, so a new module starts on the same
footing rather than catching up later.

## Links

- [druxtjs.org](https://druxtjs.org) — documentation
- [druxt/druxt.js](https://github.com/druxt/druxt.js) — the framework
- [drupal.org/project/druxt](https://www.drupal.org/project/druxt) — the Drupal module
- [Discord](https://discord.druxtjs.org) — questions and help
