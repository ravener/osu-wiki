# Написание сценариев

![Скриншот сценария сториборда, открытого в "Code - OSS"](img/osb-example.png "Пример сценария сториборда (.osb)")

**Скриптинг** (англ. *storyboard scripting*) — процесс создания [сторибордов](/wiki/Storyboard) путём редактирования файлов [`.osb`](/wiki/Client/File_formats/Osb_(file_format)) и [`.osu`](/wiki/Client/File_formats/Osu_(file_format)). В этих файлах описываются изображения и эффекты, которые [клиент osu!](/wiki/Client) должен отрисовать во время игры.

Скриптинг — отличная альтернатива [встроенному редактору сторибордов](/wiki/Client/Beatmap_editor/Design), когда требуется точность или повышенная сложность. С помощью текстовых редакторов — например, [блокнота](https://ru.wikipedia.org/wiki/Блокнот_(программа)), [Notepad++](https://www.notepad-plus-plus.org/) или [Visual Studio Code](https://code.visualstudio.com/), — сторибордеры могут вписывать точные параметры [объектов](Objects) и [команд](Commands) вместо того, чтобы накликивать их в визуальном редакторе. Кроме того, многие сторибордеры [пишут собственные программы](https://ru.wikipedia.org/wiki/Программирование) для генерации сторибордов, которые было бы крайне сложно сделать вручную.

*Внимание: старайтесь не редактировать сториборд [карты](/wiki/Beatmap), которая в это время открыта в [редакторе](/wiki/Client/Beatmap_editor). При сохранении карты в редакторе ваши изменения, сделанные в блокноте, могут быть стёрты.*

## Концепции и формат файла

См. конкретные статьи:

- [Общие принципы](General_Rules)
- [Объекты](Objects)
- [Команнды](Commands)
- [Составные команды](Compound_Commands)
- [Работа с аудио](Audio)
- [Флаги в файлах `.osu`](osu!_File_Toggles)
- [Переменные](Variables)
- [Сокращённые команды](Shorthand)
- [Шпаргалка](Cheat_Sheet)

## Инструменты от сообщества

В сообществе osu! есть собственные инструменты, скрывающие низкоуровневый код сторибордов и позволяющие перейти к более абстрактным конструкциям — например, [storybrew](https://github.com/Damnae/storybrew) от ::{ flag=FR }:: [Damnae](https://osu.ppy.sh/users/989377).
