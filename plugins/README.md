# Folder information

This folder only contains **active mods**. I check weekly for mod updates or new interesting mods.

For now all mods are currently updated to the **latest version** and **compatible** with the latest game version.

All mods are taken from the website: https://thunderstore.io/c/repo/

---

## Folder structure

- `MoreHead/`, `RepoCasino/`, `WesleysEnemies/`, ... - these folders contain: the main mod file mod1.dll and additional files needed for the mod to work correctly

- `Mimics.dll`, `NoDamageInShop.dll`, ... - these are files for other mods that don't require additional files

Mods like `MenuLib.dll`, `REPOConfig.dll`, etc., are **required** for some mods—without them, most mods won't work!

---

### Mod Categories

Mods are divided into two types: **ModLib** and **Mod**. The **Mod** type is further split into two: **AllPlayers** and **OnlyHost**.

This folder has exactly 5 mods of the **ModLib** type:
- `KeybindLib.dll`
- `MenuLib.dll`
- `REPOConfig.dll`
- `REPOLib.dll`
- `TextUpgradesUIScale.dll`

The remaining mods are of the **Mod** type and depend on the required **ModLib** mod being installed!

As mentioned, the **Mod** type splits into **AllPlayers** and **OnlyHost**.

There's only one such mod in this folder:
- `SharedUpgrades.dll`

All others must be installed by **all players**, or you won't be able to play in the same lobby!

---

## Installation (manual)

1) Download the `plugins/` folder.
2) Copy this folder and paste it here, replacing files: `Disk:\...\Steam\steamapps\common\REPO\BepInEx`.
3) Launch the game.

If done correctly, the BepInEx console will show how many mods are loaded.

---

# Информация о папке

В этой папке хранятся только **активные** моды. Каждую неделю я проверяю на наличие обновлений для модов или на наличие новых интересных модов.
В данный момент все моды обновлены до **последней версии** и **совместимы** с последней версией игры.

Все моды взяты с сайта: https://thunderstore.io/c/repo/

## Структура папки `plugins/`

- `MoreHead/`, `RepoCasino/`, `WesleysEnemies/`, ... - в этих папках находятся: основной файл мода mod1.dll и дополнительные файлы, которые нужны для корректной работы мода

- `Mimics.dll`, `NoDamageInShop.dll`, ... - это файлы других модов, для которых не нужны дополнительные файлы

Моды `MenuLib.dll`, `REPOConfig.dll` и т.д. являются **обязательными** для некоторых модов, без них большинство модов не будут работать!

### Разделение модов

Моды разделяются на два типа: **ModLib** и **Mod**, в свою очередь тип **Mod** разделяется ещё на два: **AllPlayers** и **OnlyHost**.

В этой папке всего 4 мода принадлежащих типу **ModLib**:
- `KeybindLib.dll`
- `MenuLib.dll`
- `REPOConfig.dll`
- `REPOLib.dll`
- `TextUpgradesUIScale.dll`

Остальные моды принадлежат типу **Mod** и зависят от того, установлен ли нужный им мод из типа **ModLib**!

Как я уже упомянул тип Mod разделяется на два типа: **AllPlayers** и **OnlyHost**.

В этой папке существует только один такой мод:
- `SharedUpgrades.dll`

Остальные **должны** быть у всех игроков, в противном случае вам не удастся сыграть в одном лобби!

## Установка (инструкция)

1) Скачайте папку `plugins/`.
2) Скопируйте эту папку и перенесите по такому пути с заменой файлов: `Диск:\...\Steam\steamapps\common\REPO\BepInEx`.
3) Запустите игру.

Если вы сделали все правильно, то в консоли BepInEx вы увидите сколько модов у вас загружено.
