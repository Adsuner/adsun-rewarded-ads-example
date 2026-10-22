# Adsun Rewarded Ads — Telegram Mini App example

Minimal plain-HTML Telegram Mini App that shows an Adsun **Reward** ad and grants coins.

## Run

```bash
npx serve .
```
Then open it in a browser (debug) or set the URL as your bot's Mini App in @BotFather.

Replace `YOUR_BLOCK_ID` with the block ID from your Adsun publisher panel.

## Debug mode

`debug: true` shows a test ad: no billing, and the Reward URL is **not** called.
Use it outside Telegram too (otherwise you get `NoUserData`). Remove it before going live.

## Links

- Docs: https://adsun.io/documentation
- Mini App monetization: https://adsun.io/telegram-mini-app-monetization

## License

MIT
