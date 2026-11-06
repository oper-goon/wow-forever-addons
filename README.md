# WoW Forever addon index

A guide to the addons in this personal WoW Forever pack, with the currently installed versions and links to their publishers.

**[Browse the complete addon index →](INDEX.md)**

Snapshot: **November 6, 2026 · Forever 1.60.1 · Interface 16001**. Versions describe the current installation, rather than tracking future releases automatically. Leatrix Plus was intentionally left unchanged. Compatibility was checked against publisher listings and addon manifests; no in-game testing was performed.

## Main addons

| Addon | Version in pack | What it does |
| --- | --- | --- |
| [Questie](https://github.com/Questie/Questie/releases/tag/bundle/v12.6.2+v1.0.11) | 12.6.2 + QuestieDB 1.0.11 | Quest locations, map objectives, and quest tracking; includes required QuestieDB. |
| [Leatrix Plus](https://www.curseforge.com/wow/addons/leatrix-plus/files/9275554) | 1.60.25-forever | Optional faster looting, quest automation, and interface adjustments. |
| [Baganator](https://www.curseforge.com/wow/addons/baganator/files/9473987) | 843 | Categorized bags, sorting, and searching. Requires included Syndicator. |
| [DungeonJournal](https://www.curseforge.com/wow/addons/dungeonjournal/files/9473650) | 1.7.0 | Dungeon boss loot, quests, locations, and rewards. |
| [Auctionator](https://www.curseforge.com/wow/addons/auctionator/files/9162359) | 341 | Auction-house buying, selling, and price tooltips. |
| [EllesmereUI](https://github.com/EllesmereGaming/EllesmereUI/releases/tag/v9.7.8) | 9.7.8 | Modular interface suite for frames, bars, chat, minimap, and more. |
| [Attune](https://www.curseforge.com/wow/addons/attune/files/9473452) | 16001-38 | Tracks attunement chains and dungeon prerequisites. |
| [DialogueUI](https://www.curseforge.com/wow/addons/dialogueui/files/9451752) | 1.0.7 b | Quest conversation interface with camera and gamepad controls. |
| [Spoken](https://www.curseforge.com/wow/addons/spoken/files/9455301) | 3.8.3 | Plays quest, gossip, place, boss, and book narration using audio packs. |
| [OpenMap](https://www.curseforge.com/wow/addons/openmap/files/9299630) | 0.7.5-beta-forever | Seamless world map with zoom and pan, preserving Vanilla art; beta. |
| [GatherLite](https://www.curseforge.com/wow/addons/gatherlite/files/9470583) | 8.3.1 | Gathering node locations, fish catch areas, and farming routes. |

## Installation

1. Close WoW and extract your **Forever Addons.zip** package.
2. Open the extracted folder containing `README.txt` and `Interface`. Back up your existing `Interface` and `WTF` folders if needed.
3. Drag the extracted `Interface` folder into your **Forever client folder**, merging folders and replacing matching addon files.
4. Start WoW and enable the desired addons at character selection.

The resulting layout must be `Interface/AddOns/<addon-folder>/<addon>.toc`. Avoid an extra `Interface/Interface` or `AddOns/AddOns` layer. Keep QuestieDB with Questie, and Syndicator with Baganator.

For an update from the October pack, remove the old `SpokenBooksAudio` and `SpokenZonesAudio` addon folders; their replacements have new author-supplied names. OpenMap is the latest Forever beta, **0.7.5-beta**.

Spoken needs your faction's quest audio plus Shared; both factions are supplied. Gossip, Places/Zones, and Readables/Books add their corresponding narration. EllesmereUI modules are optional; choose which ones you want enabled, particularly where they overlap with Baganator or other interface addons.

## Repository contents

- [INDEX.md](INDEX.md): explanations, pinned versions, official sources, and all 47 addon folders, including bundled modules.
- [manifest.csv](manifest.csv): original archive names, publishers, source URLs, sizes, and SHA-256 checksums.
- [verification.json](verification.json): manifest compatibility evidence and archive checks.

The original installation ZIP is named **Forever Addons.zip**, with `README.txt` and `Interface/AddOns` at its root. It is supplied separately in the Windows Downloads folder. This repository documents the pack and links to the original sources. Addon copyrights and licenses remain with their authors.


## November 6 installation update

The version lists reflect the installed addon updates. The separately supplied **Forever Addons.zip** was not rebuilt and may contain the older November 3 versions. Leatrix Plus remains unchanged. OpenMap remains at 0.7.5-beta; its missing `Data/Changelog.lua` was not repaired by these updates. SavedVariables, Edit Mode layouts, and addon enable/disable selections were preserved. No account or character data is included in this repository.
