# Artwork and packaging audit

## Findings
The previous block and material generators explicitly embedded masks copied from Create and TFMG images. These old outputs are not retained in the v15 JAR. All 22 gameplay PNGs were regenerated using tools/generate_aerocannons_public_assets.py, which imports no image, existing mask, font or game assets. The 400x400 project icon is also new procedural artwork. The preview image is a texture contact sheet, not an in-game screenshot.

The JAR contains only com/aerocannons class entries and assets/aerocannons resources, not dependency JARs. The 495 class files are byte-for-byte identical to v14. NeoForged MDK template notice is preserved. All Rights Reserved remains the existing project license; dependency licenses are not changed.

These structural checks are not a certification of the provenance of every code line. Any separate author permission already held should be preserved with the project records. No third-party permission request has been sent.

## Source references
- Create license: https://github.com/Creators-of-Create/Create/blob/mc1.21.1/dev/LICENSE.md
- CurseForge moderation: https://support.curseforge.com/support/solutions/articles/9000197279
- Local evidence: tools/generate_block_textures.py and tools/generate_material_icons.py comments.

## Verification limits
JAR CRC, model/resource references, JSON, UTF-8 TOML, new PNG inventory and unchanged class bytes passed. These tests do not replace a client startup with only advertised dependencies. No new in-game screenshot has been captured. OBSERVED_INSTANCE_MODS.json records the local full instance, not a tested minimum or recommended upgrade list.
