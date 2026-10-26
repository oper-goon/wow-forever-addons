# WoW Forever addon index

A guide to the addons in this personal WoW Forever pack, with the exact downloaded versions and links to their publishers.

**[Browse the complete addon index →](INDEX.md)**

Snapshot: **October 25, 2026 · Forever 1.60.1 · Interface 16001**. Versions describe this pack, rather than tracking future releases automatically. Compatibility was checked against publisher listings and addon manifests; no in-game testing was performed.

## Main addons

| Addon | Version in pack | What it does |
| --- | --- | --- |
| Questie | 12.2.0 | Shows quest locations and objectives on your maps and helps you track quest progress. |
| Leatrix Plus | 1.60.25-forever | Optional quality-of-life features such as faster looting, quest automation, and interface adjustments. |
| Baganator | 838 | Organizes bags into categories or a single view, with searching and sorting. Requires Syndicator. |
| DungeonJournal (ExehnTV) | 1.6.5 | Displays dungeon boss loot, dungeon quests, quest locations, and rewards. |
| Auctionator | 341 | Simplifies auction-house buying and selling and records item prices for tooltips. |
| EllesmereUI | 9.6.8 | A modular interface suite with movable elements, action bars, frames, chat, minimap, and other optional modules. |
| Attune | Forever 16001-34 | Tracks attunement quest chains and dungeon prerequisites, including progress shared by guildmates using the addon. |
| DialogueUI | 1.0.6 | Reworks quest conversations with camera controls and gamepad support. |
| Spoken | 3.5.1 | Reads quests, NPC dialogue, place lore, and books aloud using the included English audio packs. |

## Installation

1. Close WoW and extract your **WoW-Forever-Drag-and-Drop.zip** package.
2. Open its `WoW-Forever-Addons` folder. Back up your existing `Interface` and `WTF` folders if needed.
3. Drag the extracted `Interface` folder into your **Forever client folder**, merging folders and replacing matching addon files.
4. Start WoW and enable the desired addons at character selection.

The resulting layout must be `Interface/AddOns/<addon-folder>/<addon>.toc`. Avoid an extra `Interface/Interface` or `AddOns/AddOns` layer. Keep QuestieDB with Questie, and Syndicator with Baganator.

Spoken needs your faction's quest audio plus Shared; both factions are supplied. Gossip, Places/Zones, and Readables/Books add their corresponding narration. EllesmereUI modules are optional; choose which ones you want enabled, particularly where they overlap with Baganator or other interface addons.

## Repository contents

- [INDEX.md](INDEX.md): explanations, pinned versions, official sources, and all 43 addon folders, including bundled modules.
- [manifest.csv](manifest.csv): original archive names, publishers, source URLs, sizes, and SHA-256 checksums.
- [verification.json](verification.json): manifest compatibility evidence and archive checks.

The multi-gigabyte installation ZIP and third-party addon files remain in your previously supplied downloads. This repository documents the pack and links to the original sources. Addon copyrights and licenses remain with their authors.
