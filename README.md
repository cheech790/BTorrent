https://Torrent.NXL.INK//
========
**[Torrent.NXL.INK]** is a fully-featured **[IPFSWebTorrent]** browser client written in HTML, JS and CSS

[![Join the chat at https://chat.nxl.ink/Nextvid/Torrent.NXL.INK](https://kiwiirc.com/nextclient/#irc://irc.freenode.net/#nextvid,#nextvid_chitchat,#nextid_help)

### Features
- [x] Informative GUI with easy sharing options
- [x] Downloading from an info hash or magnet URI
- [x] Downloading from a .torrent file (Coming Soon)
- [x] Seeding files (Single/multiple files)
- [ ] Seeding CORS-enabled remote files (Coming Soon) 
- [x] Download/Upload speed per torrent
- [x] Download/Upload speed of client (All torrents)
- [x] Removing torrents from the client
- [x] Pause/Resume torrent
- [x] Selecting/Deselecting files (Coming Soon)
- [x] Client Debugging
- [ ] Use custom trackers/rtcConfig

### Built with
- [WebTorrent]
- [AngularJS]
- [Skeleton]
- [Normalize.css]
- [Moment.js]
- [ui-grid]
- [pretty-bytes]
- [ng-file-upload]
- [ng-notify]

Website powered by [jsDelivr] and [CloudFlare]. I use [nginx] in my server.

### HTML5 serving
**You must serve index.html as the default**

For nginx, use this conf:
```
    location / {
        try_files $uri$args $uri$args/ /index.html;
    }
```

### Enable Debugging
Enable βTorrent (Debug logging) and WebTorrent (Logs logging) debug logs by running this in the developer console:
```js
localStorage.debug = '*'
```
Disable by running this:
```js
localStorage.removeItem('debug')
```

### Help βTorrent
- **[Create a new issue](https://github.com/cheech790/Torrent.NXL.INK/issues/new)** to report bugs or suggest new features
- **[Send a PR](https://github.com/cheech790/Torrent.NXL.INK/pull/new/master)** with your changes

### Thanks
- [bostrot](mail::to:bruce@nextvid.io) For the logo and favicon
- [raj](mail::to:raj@nextvid.io) For cleanup and ng-file-upload and other ideas

## Licensing

MIT. Copyright (c) [Nextvid International Ltd.](https://nextvid.io)

The license for this project is defined in a separate document "LICENSE.txt"
Nextvid's FOSS IPFS Torrent also contains the following code:

- icu   - Copyright (c) 1991-2019 Unicode, Inc. All rights reserved. https://www.unicode.org/copyright.html.

[Product]: https://Torrent.NXL.INK//
[WebTorrent]: https://webtorrent.io
[AngularJS]: https://angularjs.org/
[jsDelivr]: https://www.jsdelivr.com/
[CloudFlare]: https://www.cloudflare.com/
[nginx]: http://nginx.org/
