# Webdash PWA Manifest

![PWA manifest preview](https://i.imgur.com/deqEgn7.png)

```bash
npm install --save-dev webdash-pwa-manifest
```

## Features

Preview your Web App Manifest on Android:

* Icon on homescreen
* Splash screen
* Status bar theme color

## Configuration

This plugin looks for `manifestPath` in your `webdash.json` configuration file, and defaults to `./src/manifest.json` if it's not set.

You may need to fix your `manifestPath` for this plugin to work.

If you cannot see the icon you set in your `manifest.json`, then you need to adjust `readableAssets` in `webdash.json`.

By default it's set to `"./src/assets/": "/assets/"` which allows webdash to access `./src/assets/` in your project and maps it to routes starting with `/assets/`.

## Enjoying webdash?

Say Hi on Twitter: [@JoubranJad](https://twitter.com/JoubranJad)
