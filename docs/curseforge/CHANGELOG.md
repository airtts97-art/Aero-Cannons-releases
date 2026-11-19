# v2026.11.19-15 - publication candidate

- Replaced all 22 bundled gameplay texture PNGs with new, independently drawn geometric artwork.
- Added a 400x400 project icon and bundled template license / attribution notices.
- Retained all v2026.11.19-14 class files byte-for-byte. No gameplay balance or protocol changes from v14.
- Includes v14 native CBC big-cannon slope correction: half the extra slope resistance; autocannons and addon shells are excluded.
- Includes v13 `aeroTerminalBallistics` game rule. Default true; false delegates ordinary impacts to CBC/addon logic. Create structure integrity is retained.
- Includes the carrier training mission UI and prior deck-service / learned-steering changes.

Validation: unchanged class hashes, new texture inventory, PNG dimensions, JSON and UTF-8 TOML parsing, JAR integrity and no nested dependency JARs. v14 was cold-started in a separate server and its native CBC / Terminal Ballistics hooks were checked at multiple angles. v15's resource-only artwork changes have not yet been viewed in a running game. Live penetration counts were not measured in the v14 hook test. This is a Beta candidate.
