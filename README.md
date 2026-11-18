# Razi Protocol: Russian for the mods

Russian translation for the mods of the Razi Protocol modpack that ship no Russian locale or only part of it. Razi Protocol lists this mod as an optional dependency: install it to play the pack in Russian.

## Where the strings come from

Most strings are taken from five Russian translation packs on the mod portal:

| Pack | Version | Author | License |
| --- | --- | --- | --- |
| [russianlocalizationpalnet](https://mods.factorio.com/mod/russianlocalizationpalnet) | 1.0.3 | weydarkend | MIT |
| [ru-planets-and-more](https://mods.factorio.com/mod/ru-planets-and-more) | 1.12.0 | Derneder | MIT |
| [rus-perevod](https://mods.factorio.com/mod/rus-perevod) | 1.11.1 | Severeniys | MIT |
| [RULocale_fromSLL](https://mods.factorio.com/mod/RULocale_fromSLL) | 1.2.0 | S-L-L | The Unlicense |
| [locale_ru](https://mods.factorio.com/mod/locale_ru) | 0.0.19 | KeySiVi | MIT |

A string is included only when neither the mod itself nor Razi Protocol has its own Russian for it, so translations that ship with the mods always come first. Strings that none of the packs cover are translated by hand.

## Files

| File | Contents |
| --- | --- |
| `locale/ru/<pack>--<file>.cfg` | strings from a pack, generated; overwritten on every rebuild |
| `locale/ru/<mod>.cfg` | hand-written strings; they replace a pack's string for the same key |

Hidden optional dependencies `(?)` in `info.json` make this mod load after the mods whose Russian it completes, so its strings take effect.

A wrong or missing translation: [open an issue](https://github.com/GreenTech-Solutions/razi-protocol-ru/issues).

## License

[MIT](LICENSE). The licenses and copyright notices of the translation packs are in the same file.
