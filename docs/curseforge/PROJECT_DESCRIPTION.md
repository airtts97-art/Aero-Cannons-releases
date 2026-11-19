# Aero Cannons

Aero Cannons adds armor, damage and vehicle support systems for Create Big Cannons and Create Aeronautics.

## Features

- Six armor materials, material-aware copycat armor and vehicle mass adjustments.
- Persistent block damage, repair tools, and integrations for cannon penetration, spalling and impact marks.
- Ship flooding, drainage, buoyancy and compartment diagnostics.
- Surface painting and decals that follow Sable vehicles.
- Additional crew and carrier-aircraft controls when Nepheria Gloud is installed, including aircraft setup, command maps and a flight-training mission.
- Game rules for optional combat features. `aeroTerminalBallistics` can delegate ordinary block impacts to the original projectile logic while retaining assembled Create structure damage.

## Installation

Minecraft **1.21.1**, **NeoForge**, **Java 21**. Install Aero Cannons on both the client and server. Back up existing worlds before upgrading.

Required: **Create**, **Create Big Cannons**, **Create Aeronautics**, **Sable**, and **TFMG**. Install the dependencies required by those projects as well. Use matching versions; compatibility patches can be version-specific.

Optional integrations include **CBC Terminal Ballistics**, **CBC Military Supplement**, **Shaolib**, **Sable Photomancy**, and **Nepheria Gloud**. Cannon damage and cracks described above require the supported Terminal Ballistics version. Crew features require Nepheria Gloud; this mod does not provide its own NPC entity. Schematic painting support requires the supported Sable Schematic API version. See the file notes for the observed versions.

Remove the original **Nation Industry** JAR before installing Aero Cannons; their overlapping features are incompatible. Aero Cannons was separated from the author's Nation Industry project and does not include its nation, economy or infantry-weapon systems. Existing Nation Industry worlds are not automatically converted.

## Beta status

Aircraft automation depends on each aircraft's configured controls and flight characteristics. It is experimental. Separate server tests have checked flight-training completion and the current penetration hooks; they do not establish reliable autonomous operation for every aircraft. The public artwork update preserves all v14 class files unchanged. A minimal-dependency client installation and a fresh in-game screenshot of the new artwork have not yet been verified.

## 日本語

Aero CannonsはCreate系の船舶・航空機向けに、装甲、損傷と修理、浸水・浮力、塗装・デカールを追加します。Nepheria Gloud導入時は乗員・艦載機指揮や訓練任務も使えます。

Minecraft 1.21.1 / NeoForge / Java 21用です。前提MODは別途導入し、更新前にワールドをバックアップしてください。元のNation Industryとの同時導入・ワールド自動変換には対応しません。機体自動操縦は試験的な機能です。

## Credits and support

Create, Create Big Cannons, Create Aeronautics, Sable, TFMG and the supported integration mods are developed by their respective authors. Aero Cannons is an independent addon; none of those mods are bundled in this file.

Source and issue tracker: https://github.com/airtts97-art/Aero-Cannons
