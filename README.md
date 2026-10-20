# LisoftKassa — установщики

Рабочее место кассира LisoftKassa (LISOFT, Казахстан). Здесь лежат только готовые файлы выпусков,
исходный код закрыт. Последняя версия — **Releases → Latest** справа.

| ОС | Файл | Как ставить |
| --- | --- | --- |
| Windows 10/11 x64 | `LisoftKassa_<версия>_x64-setup.exe` — базовый установщик (WebView2 докачивается из интернета); `LisoftKassa_<версия>_x64-offline-setup.exe` — для кассы без интернета | запустить от имени администратора |
| Linux x64 (Ubuntu 24.04, Linux Mint 22, Debian 13) | `LisoftKassa_<версия>_amd64.deb` | `sudo apt install ./LisoftKassa_<версия>_amd64.deb` |
| macOS 11+ | `LisoftKassa_<версия>_aarch64.dmg` (Apple Silicon), `LisoftKassa_<версия>_x64.dmg` (Intel) | открыть dmg, перетащить в «Программы» |

`latest.json` и файлы `.sig` — служебные, для автообновления кассы на Windows. Контрольные суммы SHA-256 — в описании
выпуска.
