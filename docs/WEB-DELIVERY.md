# Web delivery supplement for MIDI library v1.23

Status: prepared locally; the new web-material Release has not been published.
The original v1.23 archive bytes, paths and licences remain authoritative.

The web supplement assigns every one of the 133,667 original MIDI paths to an
immutable SHA-256 content address on the existing mid/zip Pages sites. Both hosts
must be ready and pass actual HTTPS/CORS checks before consumer pages are updated.
Every source record and expanded byte is checked against the frozen original ZIPs.

`web-materials-v1.23-web-r1.json` records the original archive digests and planned
immutable web archives. A complete old-path/new-address migration map is prepared
as a Release attachment. The browser loads a small bootstrap and one hashed path
bucket only when playback or MIDI download is requested.

This changes delivery, not musical data, ownership, attribution, or the licence of
any track. The original dataset archives remain available under their original
version. A bare GitHub Pages host cannot promise permanent redirects for every
historical raw MIDI URL.
