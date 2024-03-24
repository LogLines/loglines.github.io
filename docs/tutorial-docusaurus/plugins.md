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

### Installation {#installation}

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

## SEO plugins

There are several plugins available for Docusaurus that can help improve SEO. These plugins provide additional features and functionalities specifically designed to enhance the search engine optimization of your Docusaurus project. Here are a few popular SEO plugins for Docusaurus:

1) @docusaurus/plugin-sitemap: This plugin generates a sitemap for your Docusaurus site, which helps search engines discover and index your content more effectively.

2) @docusaurus/plugin-ideal-image: This plugin optimizes images on your Docusaurus site by generating and serving ideal-sized responsive images based on device capabilities. Optimized images can improve page load times, which is beneficial for SEO.

3) @docusaurus/plugin-google-analytics: Adding Google Analytics to your Docusaurus project enables you to track website traffic, user behavior, and other metrics. This information can help you understand your audience and make data-driven decisions to improve your site's SEO.

4) @docusaurus/plugin-google-gtag: Similar to the Google Analytics plugin, this plugin allows you to integrate Google Global Site Tag (gtag.js) with your Docusaurus project. It enables you to track website analytics and conversions using Google Analytics or other supported services.

5) @docusaurus/plugin-robots-txt: This plugin generates a robots.txt file for your Docusaurus project, which provides instructions to search engine crawlers on which pages to crawl and index.

These are just a few examples, and there might be more plugins available in the Docusaurus ecosystem. To explore and find additional SEO plugins, you can visit the official Docusaurus website (docusaurus.io) or the Docusaurus plugins repository on GitHub (github.com/topics/docusaurus-plugin). Make sure to review the documentation and instructions provided with each plugin to understand how to install, configure, and use them effectively for SEO optimization.

By leveraging these plugins, you can enhance the SEO capabilities of your Docusaurus project and improve its visibility in search engine results.