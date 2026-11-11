# SIP 500 📈🍺

The drink stock market. Every drink is a stock, and the SIP 500 index tracks the whole bar.

**Play:** https://mcmurrayw4.github.io/sip500/
**TV mode:** https://mcmurrayw4.github.io/sip500/?tv
**Host controls:** https://mcmurrayw4.github.io/sip500/?admin (keep this one to yourself)

## How it works
- Order a drink and tap **+**. You buy one share at the current price.
- That stock goes up 5%, its sector goes up 1.5%, and every other stock dips 0.2%.
- The winner has the best return %, not the most drinks.

## Editing drinks
Edit the `SECTORS` and `STOCKS` lists near the top of the script in `index.html`. Then reset the market from the host page.

Live data runs on a free Firebase Firestore database. Hosting is on GitHub Pages.

Please drink responsibly. 21+.
