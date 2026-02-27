# Backported fixes for Create 6.0.8 for MC 1.20.1
[![Modrinth](https://img.shields.io/badge/1.1.0-green?logo=modrinth&label=Modrinth&color=%2300AF5C)](https://modrinth.com/mod/create-6.0.8-schematicannon-dupe-fix)
[![Static Badge](https://img.shields.io/badge/1.1.0-orange?logo=curseforge&label=CurseForge)](https://www.curseforge.com/minecraft/mc-mods/create-6-0-8-schematicannon-dupe-fix)


This is a basic mod that fixes a few bugs in Create 6.0.8 for MC 1.20.1. These bugs have been fixed already in Create 6.0.9,
but that version will unfortunately not be released for MC 1.20.1. The bugs fixed are:

- **[Create#9511 - Item requirement is bad when a schematic contains placards](https://github.com/Creators-of-Create/Create/issues/9511)**:
This bug makes it possible to use the Schematicannon to place blocks that contain other blocks, without requiring those blocks as an ingredient
(essentially a dupe/item generation bug). The fix for this is based on
[this commit](https://github.com/TerraFirmaGreg-Team/Core-Modern/pull/246/commits/9b03ea6f0d79cd9293f07de2239931eddd3fd900)
from the [TerraFirmaGreg-Core mod](https://github.com/TerraFirmaGreg-Team/Core-Modern).
- **[Create#9414 - Train map in Xaeros World Map is not scaled properly](https://github.com/Creators-of-Create/Create/issues/9414)**:
This bug makes the train UI render incorrectly when using Xaero's World Map. The fix is for this is based on
[this commit](https://github.com/TerraFirmaGreg-Team/Core-Modern/pull/323/changes/ac7f647ac93850b02035b61ab8ea759459b4459e)
from the [TerraFirmaGreg-Core mod](https://github.com/TerraFirmaGreg-Team/Core-Modern).