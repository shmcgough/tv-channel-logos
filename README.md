# tv-channel-logos

Channel logos for a self-hosted live TV setup (Tunarr channels shown in Plex).
Static PNGs only.

They live in a public repo because Plex's Android TV app only draws guide
channel logos from public HTTPS URLs. Logos served from a LAN address show as
empty boxes there, even though Plex Web displays them.

Each filename carries a content hash, because Plex caches thumbnails by URL
and a redrawn logo needs a new one. A file is never renamed or deleted while a
channel still points at it.
