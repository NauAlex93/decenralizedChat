## Build and deploy app

1. This app works best with `window.ipfs`. Install the IPFS Companion web extension:

    <a href="https://addons.mozilla.org/en-US/firefox/addon/ipfs-companion/" title="Get the add-on"><img width="86" src="https://blog.mozilla.org/addons/files/2015/11/AMO-button_1.png" /></a> <a href="https://chrome.google.com/webstore/detail/ipfs-companion/nibjojkomfdiaoajekhjakgkdhaomnch" title="Get the extension"><img width="103" src="https://developer.chrome.com/webstore/images/ChromeWebStore_BadgeWBorder_v2_206x58.png" /></a>

2. Install dependencies `yarn install`
3. Build and start app `yarn watch`
4. Deploy `ipfs add -r dist/`
