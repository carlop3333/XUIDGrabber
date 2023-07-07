# XUIDGrabber
cxkes XUIDGrabber as a POST request

# Usage
 `app.js <GamertagToConvert> (--detailed)`
 
For example:

`app.js Carlop3333` returns `2535449879825318`

(Detailed returns a lot of information, like account tier, gamerscore, and other things)

Example (using `app.js Carlop3333 --detailed`):
```
name: Carlop3333
xuid-dec: 2535449879825318
xuid-hex: 000901FA6D6ECBA6
real-name: not-shared     
gamerscore: 2,095
account-tier: Silver
followers: 27
following: 43
```
### Known issues
- The detailed grabber can break if the user has a public name.

### API

You can use `require` to import the grabber to your project
```
const grabber = require('XUIDGrabber')
```

**Disclaimer:** This app can break in any moment (if the website changes), so feel free to fork it if you want.


