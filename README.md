# Razi Protocol: Russian for the mods

Russian translations for mods in the Razi Protocol set and our pack that ship none or only part of their Russian locale. Razi Protocol loads this mod as an optional dependency.

The generated translations come from these packs:

| Mod | Version | Author | License |
| --- | --- | --- | --- |
| [russianlocalizationpalnet](https://mods.factorio.com/mod/russianlocalizationpalnet) | 1.0.3 | weydarkend | MIT |
| [ru-planets-and-more](https://mods.factorio.com/mod/ru-planets-and-more) | 1.12.0 | Derneder | MIT |
| [rus-perevod](https://mods.factorio.com/mod/rus-perevod) | 1.11.1 | Severeniys | MIT |
| [RULocale_fromSLL](https://mods.factorio.com/mod/RULocale_fromSLL) | 1.2.0 | S-L-L | The Unlicense |
| [locale_ru](https://mods.factorio.com/mod/locale_ru) | 0.0.19 | KeySiVi | MIT |

Hand-written strings are kept in locale files without a double hyphen in their filenames. Files with a double hyphen are generated from the packs by tools/locale/build-razi-protocol-ru.py. A key is included only when neither Razi Protocol nor the mod provides its Russian translation. Changes to translations belong in the hand-written files.

Optional hidden dependencies make this mod load after mods whose Russian locale it overrides.

## License

This mod is licensed under the [MIT License](LICENSE). Translation pack authors and license notices are listed there.
