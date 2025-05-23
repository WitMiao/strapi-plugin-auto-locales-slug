# Auto Locales Slug Strapi Plugin

![ Auto Locales Slug Strapi Plugin](https://i.ibb.co.com/Z18jqb1F/strapi-plugin-auto-locales-slug.gif)

## Description

This plugin automatically adds a locale to the end of the slug.

## How It Works

This plugin checks at the database level whether the slug is available. It operates by appending a locale to the end of a slug. It specifically works with fields named 'title' or 'name'. The plugin retrieves the value from these fields and applies it according to the pattern specified in the plugin's basic settings. You must select either 'title' or 'name' in the pattern option for the plugin to function correctly.

## Features

- Automatically appends locale information to slugs.
- Supports multiple locales.
- Easy integration with existing projects.
- No need extra configuration.

## Installation

To install the plugin, follow these steps:

Using npm:

```bash
npm install auto-locales-slug
```

Using yarn:

```bash
yarn add auto-locales-slug
```

## Compatibility

- **Required Strapi Version:** 5.x.x

## Bug Report

If you encounter any issues or bugs, please report them at our [GitHub Issues page](https://github.com/livealvi/strapi-plugin-auto-locales-slug/issues).
