COIN TRACKER V13

V13 keeps the V12 recovery/search/grouping/editing/photo functionality and adds live-market architecture plus valuation tools.

UPLOAD TO GITHUB PAGES: index.html, manifest.json, sw.js, icon-180.png

LIVE METALS: the app supports Metals.Dev through the included secure proxy. It also supports a device-only Metals.Dev key for personal testing. The public-site-safe option is the proxy.

LIVE COIN VALUATION: Numista catalogue search and sales records are accessed through the included proxy. The app stores the Numista ID and valuation result fields, not a copy of the catalogue. Numista attribution/N# display requirements apply.

CLOUDFLARE WORKER: deploy worker.js and set secrets NUMISTA_API_KEY and METALS_API_KEY. Put the worker URL into Coin Tracker > Settings & connections.

RECOVERY: V13 attempts to migrate CoinTrackerV12 and CoinTrackerV10 without deleting them. The Version 2 JSON recovery button remains. Do not clear Safari website data.
