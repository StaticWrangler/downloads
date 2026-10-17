# StaticWrangler downloads

Public playlist templates and XMLTV guides for T-Rex and Dream 4K. Each provider has its own lineup, channel IDs, groups and programme data.

| Provider | Playlist template | XMLTV guide |
| --- | --- | --- |
| T-Rex | [t-rex.m3u](https://github.com/StaticWrangler/downloads/releases/latest/download/t-rex.m3u) | [t-rex.xml](https://github.com/StaticWrangler/downloads/releases/latest/download/t-rex.xml) |
| Dream 4K | [dream-4k.m3u](https://github.com/StaticWrangler/downloads/releases/latest/download/dream-4k.m3u) | [dream-4k.xml](https://github.com/StaticWrangler/downloads/releases/latest/download/dream-4k.xml) |

The playlists use `DNS/live/USERNAME/PASSWORD/<stream-id>.ts` placeholders. They contain no subscription credentials and are not playable until personalized with your own compatible subscription. Do not upload personalized playlists or credentials to this repository or to an issue.

Updates are checked every 15 minutes. A new release is promoted only after both provider pairs pass validation and all assets finish uploading. These stable links follow the latest release. A failed update retains the last verified release; two previous releases remain available for recovery. Download both files from one versioned release if you need a fixed, matching snapshot.

The [validation record](https://github.com/StaticWrangler/downloads/releases/latest/download/validation.json) contains publication input timestamps, channel and programme counts, and SHA-256 checksums. It contains no private provider URLs, credentials or server configuration.

Guides preserve channel order, logos, rich programme descriptions and sports identities. Some provider artwork may be unavailable, and informational entries do not play video. Provider feed availability can change independently of these downloads.

These are early release artifacts. EPGenius submission, import compatibility and video playback have not been tested. This repository distributes curation and guide data; it does not provide a TV subscription or provider access.
