# XUIDGrabber
cxkes XUIDGrabber as a POST request

# Usage
 `grabber.js <GamertagToConvert> (--detailed)` (the first time it will require a reload)
 
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

npm is still not supported at the moment 
```
const grabber = require('./grabber.js') 
```
It does have only a function (`getXUID(gamertag)`) that in fact returns a map (if the tokens are available)


**Disclaimer:** This app can break in any moment (if the website changes), so feel free to fork it if you want.


