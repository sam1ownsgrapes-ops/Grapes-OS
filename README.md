# GRAPES OS

GRAPES OS is a web desktop proxy app with a browser, app launcher, game hub, music player, settings, and cloaking controls.

For links or support, join the [Discord Server](https://discord.gg/3EC7UFTWJw).

## Features

- Two proxy choices
- Desktop-style app launcher
- Site support through Ultraviolet and Scramjet
- Cloaking and panic-key settings
- Game hub and app store

## Local Usage

Install dependencies:

```bash
pnpm i
```

Run locally:

```bash
pnpm start
```

GRAPES OS runs locally on `localhost:8080`.

## Cloudflare

Wrangler is included as a dev dependency. Build the app with:

```bash
pnpm build
```

Then deploy the built `dist` folder with Wrangler:

```bash
pnpm deploy
```
