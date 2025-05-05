# HTTP Exit Script # html #javascript # Security 

This simple script checks if a website is being accessed via `http://` instead of `https://`, and automatically exits or redirects the user.
## Support the project
https://www.donationalerts.com/r/techjacket1022

## How It Works

When the page is opened in a browser, the JavaScript code checks the protocol. If the site is loaded using `http://`, it redirects to a blank page.

```javascript
if (location.protocol === 'http:') {
    window.location.href = 'about:blank';
}
