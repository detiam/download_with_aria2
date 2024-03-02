## About
- This is a browser extension for [Google Chrome](https://www.google.com/intl/en-US/chrome/), [Microsoft Edge](https://www.microsoft.com/edge), [Mozilla Firefox](https://www.mozilla.org/firefox/), and so like browsers
- Download links or images, capture browser downloads, and manage downloads with aria2c via the JSON-RPC protocol

## Install the extension
- Google Web Store
    - None
- Microsoft Edge Addons
    - [https://microsoftedge.microsoft.com/addons/detail/cgoonbdaiddmlpnneceehfamhjmkbmec](https://microsoftedge.microsoft.com/addons/detail/cgoonbdaiddmlpnneceehfamhjmkbmec)
- Firefox Browser Add-ons
    - ~~[https://addons.mozilla.org/firefox/addon/downwitharia2/](https://addons.mozilla.org/firefox/addon/downwitharia2/)~~ **Obseleted**
    - [https://addons.mozilla.org/firefox/addon/download-with-aria2/](https://addons.mozilla.org/firefox/addon/download-with-aria2/) Provider: [@ivysrono](https://github.com/ivysrono)

## User Manual
- [Screenshot](//github.com/jc3213/download_with_aria2/wiki/Screenshot)
- [How to use](//github.com/jc3213/download_with_aria2/wiki)
- [How to build](//github.com/jc3213/download_with_aria2/wiki/HowToBuild)
- [Feed back](//github.com/jc3213/download_with_aria2/issues/new/)

## Main Functions
- Context menus
    - Download this link
    - Download this image
    - Download all images on this page
- Capture browser downloads
    - Capture downloads via [downloads](https://developer.chrome.com/docs/extensions/reference/downloads) API
    - Capture downloads via [webRequest](https://developer.chrome.com/docs/extensions/reference/webRequest) API
        - *Firefox only*
    - Forward downloads request headers
- Backup/Restore options for this extension and aria2 json-rpc
- Prompt a new window before sending downloads to Aria2
- Notification when downloads start/complete
