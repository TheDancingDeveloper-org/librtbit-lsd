# librtbit-lsd

BEP 14 Local Service Discovery for the rtbit BitTorrent client.

**Version:** 0.1.0 | **Edition:** Rust 2024 | **License:** MIT

## This Is a Shared Library

### Consumed By

| App | Via | Tag |
|-----|-----|-----|
| rustTorrent | git | v0.1.0 |
| Arz | git | v0.1.0 |
| NGMS | git | v0.1.0 |

### Depends On

- **librtbit-core** (git, v0.1.0) — for core types (Id20, etc.)
- **librtbit-sha1-wrapper** (git, v0.1.0) — for SHA1 hashing

## BEP Implementations

- BEP 14 — Local Service Discovery via multicast (IPv4 239.192.152.143:6771, IPv6 ff15::efc0:988f:6771)
