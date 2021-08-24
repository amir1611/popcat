## Let's fight for Malaysia's Popcat world ranking 🇲🇾

This is a JS auto-click script for <a href="https://popcat.click/" target="_blank">PopCat challenge</a> with anti-spam prevention (bypass bot detection).

The script accesses the PopCat's Vue app instance directly and manipulate the key variables which contributes to click counter, spam counter and API call, so to ensure that:

1. You hit the max 800 clicks per 30s (according to the API rate limit)
2. You won't get marked as bot


## About Popcat Rules

- API rate limit = 800 clicks per 30 seconds (So far I can't bypass this)....
- If you send 800 clicks or above, system will only record 800 clicks & spam score +1
- If you hit 10 spam scores, system will mark you as bot & no further clicks will be sent to API

```diff
- Only allow 1 browser per device. API rate limit is enforced per IP address.
```

**See the file: popcat-App.html**

## About Clickbot script V2

- Directly send clicks via the Popcat's API.
- Send 800 clicks per 30 seconds
- Clear spam scores automatically

**See the file: clickbot-v2.js**

## How to Use (Simple)

1. Copy all content of the file "clickbot-v2.min.js"
2. Visit <a href="https://popcat.click/" target="_blank">https://popcat.click/</a>
3. Tap `F12` to open browser devtool & navigate to "Console" tab
4. Tap `Ctrl` + `v` to paste all content into console
5. Tap `Enter` to run the script

*Navigate to "Network" tab to check if your API request accepted or rejected (in red text)*


## How to Use (Advanced - Python version)

1. Make sure you have install Python3 with PIP (Python package manager)
2. Install selenium package via PIP
3. Double click to run **clickbot-v2.py**

## Disclaimer

The author is not responsible for any loss or damage of your personal assets including your laptops, PCs and brain XD
