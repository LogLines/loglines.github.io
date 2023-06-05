---
sidebar_position: 13
---

# Adding Plugins

Plugins are shipped as node modules and thus installed as such. We will visit below a few plugins that we have installed and that we believe it would be useful for your projects.

## 📦 plugin-google-gtag

The default Global Site Tag (gtag.js) plugin. It is a JavaScript tagging framework and API that allows you to send event data to Google Analytics, Google Ads, and Google Marketing Platform. This section describes how to configure a Docusaurus site to enable global site tag for Google Analytics.

:::tip

You can use [Google's Tag Assistant](https://tagassistant.google.com/) tool to check if your gtag is set up correctly!

:::

## Installation {#installation}

```bash npm2yarn
npm install --save @docusaurus/plugin-google-gtag
```

### Example configuration {#ex-config}

You can configure this plugin through preset options or plugin options.

:::tip

Most Docusaurus users configure this plugin through the preset options.

:::

```js config-tabs
// Preset Options: gtag
// Plugin Options: @docusaurus/plugin-google-gtag

const config = {
  trackingID: 'G-999X9XX9XX',
  anonymizeIP: true,
};
```