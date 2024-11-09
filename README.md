# QDict
Приложение для Android с открытым исходным кодом, для работы со словарями формата `stardict`.

Установить / скачать APK:

[<img src="https://fdroid.gitlab.io/artwork/badge/get-it-on.png"
     alt="Get it on F-Droid"
     height="80">](https://f-droid.org/packages/com.annie.dictionary.fork/)

### Инструкция по установке словарей:

По умолчанию словари размещаются на `Внутреннем общем накопителе (/storage/emulated/0)` в папке `QDict/dicts/[имя словаря]`. Папка будет создана после первого запуска программы, или её можно создать заранее самому.

Для каждого словаря нужно делать отдельную папку с любым именем (в отличие, например, от GoldenDict, где все словари можно размещать в одной папке). Имя папки значения не имеет, т.к. имя словаря всё равно считывается из самого словаря.

Каждый словарь в формате `StarDict` состоит из трёх файлов, имеющих одинаковое имя, но разные расширения:

1. idx (индекс)
2. ifo (информация)
3. dz (словарь, сжатый zip)

Все три файла нужно поместить в папку словаря, после чего в QDict открываем панель слева, нажимаем `Select dictionary (Выбрать словарь)`, и ставим галочку на нужном словаре.

![Screenshot_20241109-145536_QDict](https://github.com/user-attachments/assets/c2af1985-2c26-40bc-9999-254a4f10b737)
![Screenshot_20241109-145545_QDict](https://github.com/user-attachments/assets/6cf9eee2-2f35-4997-8525-0eff5037a5fd)

После этого можно искать слова, нажав на значок лупы в правом нижнем углу.

---

## Fork information
This fork of [the original application](https://github.com/namndev/QDict) was created to incorporate patches,
which were not responded to by the upstream and so as to make it possible to include the application in the [F-Droid repository](https://f-droid.org).

The fork is not actively developed, i.e. no new features or bugfixes are planned,
however, all PRs are welcome and will be reviewed.

## Using dictionaries
QDict support 3 ways to search:  `Glob-style pattern matching`,  `Fuzzy query` and `Full-text` search.

Stardict dictionaries are not included in the application and should be obtained separately.

Dictionaries should be placed in `/sdcard/QDict/dicts`.
Each dictionary should be placed into a separate subfolder, for instance `/sdcard/QDict/dicts/dict-name`.
It's recommended to only use alphanumeric filenames.

## Donations
Original app creator: [![Donate](https://img.shields.io/badge/Donate-PayPal-blue.svg)](https://www.paypal.com/paypalme/namndev) \
Fork maintainer: [![Donate](https://img.shields.io/badge/Donate-PayPal-blue.svg)](https://www.paypal.com/donate/?hosted_button_id=K2W284SBN9GFU)
