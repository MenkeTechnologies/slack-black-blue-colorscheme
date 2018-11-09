# slack-black-blue-colorscheme

![screenshot](/screen.png)

# Installing into Slack

Find your Slack's application directory.

* Windows: `%homepath%\AppData\Local\slack\`
* Mac: `/Applications/Slack.app/Contents/`
* Linux: `/usr/lib/slack/` (Debian-based)

Copy the code in `ssb-interop.js` from

```javascript
let dark_css = `
```
to end of file.

Open up the most recent version (e.g. `app-2.5.1`) then open
`resources\app.asar.unpacked\src\static\index.js` and paste the code.

For versions after and including `3.0.0` the same code must be added to the following file
`resources\app.asar.unpacked\src\static\ssb-interop.js`


reference @ [original dark colorscheme and readme](https://github.com/widget-/slack-black-theme)

# created by MenkeTechnologies
