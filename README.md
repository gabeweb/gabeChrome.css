# gabeChrome.css

![gabeChrome.css Main window](images/gabechrome-202210-main.png "gabeChrome.css Main window")
<em>gabeChrome.css + [WaveFox](https://github.com/QNetITQ/WaveFox) in Mozilla Firefox Developer Edition 107 and [Better Dark Dracula](https://addons.mozilla.org/en-US/firefox/addon/better-dark-dracula/) theme</em>

Minimal customizations for modern versions of [Mozilla Firefox](https://www.mozilla.org/en-US/firefox/new/) and [LibreWolf](https://librewolf.net/).

## Key Features

![gabeChrome.css and go-buttom in URL bar](images/gabechrome-202210-go_button.png)
<em>gabeChrome.css and `go-buttom` in URL bar, `tab counter` and verify icon in green</em>

- Only show close buttons ❌ on background tabs when hovering with the mouse
- URL bar `go-button` ➡ (as old-school Firefox)
- Tab counter + show tab manager button even when tabs aren't overflowing
- Verify icon gray ⚫ to green 🟢
- Move `Find Bar` above the page (why not?) for Google Chrome `new kids on the Firefox block`
- `Status Panel` in another color
- Hide the email address in the `hamburger menu`
- Grid view for `overflow menu`
- Show percentage download progress (experimental)

![Grid view for overflow pane](images/gabechrome-202210-overflow_pane.png)
<em>Grid view for overflow pane</em>

## Compatibility

- As october 2022: tested in Mozilla Firefox 106+ / LibreWolf 105+
- Can be used with other `userChrome.css` tweaks.

## How-To Apply?

1. Your must enable via `about:config` the `toolkit.legacyUserProfileCustomizations.stylesheets` in Mozilla Firefox or LibreWolf.

2. Save the `gabeChrome.css` file as your `userChrome.css` (if you don't have another `userChrome.css` previously, otherwise you can import it into your actual `userChrome.css` file) and the `gabeChrome-extras.css`file, both in the `chrome` folder of your profile directory: `Roaming\Mozilla\Firefox\Profiles\[User]\chrome` ==> `(%APPDATA%\Mozilla\Firefox\Profiles\` on Windows or go to `about:profiles` in Firefox/LibreWolf and locate the `Roaming` folder of your profile.

> For more details please refer to: *[Firefox advanced customization and configuration options](https://support.mozilla.org/en-US/kb/firefox-advanced-customization-and-configuration#firefox:win10:fx106)* and *[Profiles - Where Firefox stores your bookmarks, passwords and other user data](https://support.mozilla.org/en-US/kb/profiles-where-firefox-stores-user-data)* in the official [Firefox Help](https://support.mozilla.org/en-US/questions).

3. Restart your browser and enjoy.

## Credits

Not for me but the whole [r/FirefoxCSS](https://www.reddit.com/r/firefoxcss/) community always helping to make Firefox (and LibreWolf) our own.
