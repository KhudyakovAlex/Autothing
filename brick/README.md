# Brick 1.5 — локальная копия

Перспективная линия **1.5**, сборка **1.5.0-rc.2** (2026-10-07). Финального `v1.5.0` на 2026-10-11 нет; стабильная 1.4 сюда не кладётся.
Источник: <https://github.com/BrickSchema/Brick/releases/tag/v1.5.0-rc2>
Лицензия: BSD-3-Clause, Brick Consortium — `LICENSE`.

SHACL-шейпы внутри `.ttl`, отдельного файла нет.

| Файл | Что внутри |
|---|---|
| `Brick.ttl` | Основной. Brick и REC в одном графе. Снаружи остаются импорты QUDT 3.3.0, BACnet и `recimports`. |
| `Brick-only.ttl` | Только Brick; REC подключается импортом `https://w3id.org/rec`. |
| `Brick+imports.ttl` | QUDT (величины и единицы) и BACnet вшиты в файл. Снаружи остаётся REC. |
| `Brick+extensions.ttl` | Как `Brick.ttl`, плюс расширения, в том числе ASHRAE 223P. |
