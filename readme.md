# vfs-iceland-slot-monitor
🤖️ Used to monitor the availability of Slots for Iceland on the UK VFS visa page: https://visa.vfsglobal.com/gbr/en/isl

### Requirements
`automa`, a browser extension for browser automation: https://www.automa.site/

### Technical analysis
Would not use http requests or Selenium webDriver methods. Because it is too heavy, waste life and would be blocked by Google Recaptcha V3.

### Usage
Import to `Automa` plugin, adjust `Choose your Visa Application Centre` by Automa Element Selector, Change `vfs-iceland1.automa.json` line 672 for notice, recommended use `Bark` or `ServerChan`.

### Notification Preview
![notice.jpg](notice-preview.jpg)