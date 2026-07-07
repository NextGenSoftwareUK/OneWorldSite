# One World — The Sequel

**OASIS Omniverse · Unreal Engine 5**

One World is a full 3D open-world MMORPG built on Unreal Engine 5 — the epic sequel to [Our World](../OurWorldSite). Set across ancient Atlantis, Lemuria and the age of the dinosaurs, One World is accessible through portals discovered at real-world GPS locations in parks. Avatar progress, karma and NFT items carry over from the entire OASIS Omniverse.

## The World

| Realm | Setting | Era |
|---|---|---|
| **Atlantis** | Majestic oceanic civilisation at its peak — and its fall | ~10,000 BC |
| **Lemuria** | Ancient spiritual continent of enlightened beings | ~50,000 BC |
| **The Age of Dinosaurs** | Vast prehistoric landscapes with living dinosaurs | ~65 million BC |

Players can travel between realms through ancient portal networks, each discovered via GPS in the real world.

## OASIS Integration

- **Universal avatar** — your OASIS avatar carries into One World directly from OPORTAL
- **Karma rewards** — quests, exploration and positive actions earn OASIS karma
- **NFT items** — weapons, mounts, pets and clothing are NFTs owned on-chain, usable across all OASIS games
- **GeoHotSpots** — portal entrance locations are physical GPS points registered in STARNET
- **Shared quests** — some quests span One World and Our World simultaneously

## Related

- [`OurWorldSite`](../OurWorldSite) — the original Our World flagship experience
- [`OGEngineSite`](../OGEngineSite) — the shared OASIS game engine
- [`STARNET`](../STARNET) — asset and quest registry

## Tech Stack

| Layer | Detail |
|---|---|
| Game Engine | Unreal Engine 5 |
| Site | Single-file `index.html` — inline CSS + vanilla JS |
| OASIS API | `@oasisomniverse/web4-api@2.0.2` via esm.sh |
| Fonts | Orbitron, Rajdhani, Share Tech Mono (Google Fonts) |

## Running the Site Locally

```bash
npx serve .
# or
python -m http.server 8080
```

---

*Part of the [OASIS Omniverse](https://oasisomniverse.one) · Built on Unreal Engine 5*
