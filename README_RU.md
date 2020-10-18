<p align="center">
    <img src="https://raw.githubusercontent.com/SecondThundeR/DokiDoki-RenPy/your-reality/ddlc_logo_ru.png?token=AIXISSJGRHDVOOJOWNOJ2SS7SWGJ6" width="256px" height="256px" alt="DDLC-Logo">
</p>

# Декомпилированный Doki Doki Literature Club (Для использования в Ren'Py Launcher)

> **Внимание! Эти файлы содержат много спойлеров *(очевидно)*. Если вы еще не играли в DDLC по каким-либо причинам, я рекомендую вам для начала сыграть в эту игру, чтобы получить истинные эмоции от прохождения *(Поверьте, оно того стоит)***

Этот репозиторий содержит декомпилированные исходные файлы последней версии Doki Doki Literature Club (1.1.1) для использования в Ren'Py Launcher *(например, создание модификаций для DDLC)*

Декомпилированные исходные файлы предоставляются только для личного использования, анализа файлов с целью получения опыта в создании игр на Ren'Py и создания модификаций для DDLC. Создание самостоятельных проектов, используя исходные файлы DDLC, запрещено Team Salvato [*(см. раздел "Fan Games" в руководстве по интеллектуальной собственности Team Salvato)*](http://teamsalvato.com/ip-guidelines/)

**Для просмотра README на английском языке, пройдите [по этой ссылке](https://github.com/SecondThundeR/DokiDoki-RenPy/blob/your-reality/README.md)**

## Как использовать исходные файлы

1. Откройте Ren'Py Launcher
2. Создайте новый проект с любым названием
3. Откройте папку проекта и удалите все файлы в ней
4. Переместите файлы из папки `ddlc-renpy-project` в папку проекта
5. Запустите проект в лаунчере
6. Убедитесь, что игра запускается без предупреждений и ошибок
7. Декомпилированный DDLC теперь готов к использованию

## Как включить инструменты разработчика

Чтобы включить инструменты разработчика, перейдите в файл `definitions.rpy` в папке `game` и измените значение у `config.developer` с `False` на `True` *(Не забудьте сменить обратно `False` перед компилированием готового проекта)*

## За что отвечает каждая папка

### Папка репозитория

- `characters` - папка с файлами персонажей *(Вынесено из папки `game`, чтобы игра могла видеть эти файлы и манипулировать ими)*

- `game` - главная папка проекта на Ren'Py *(и компилированной игры тоже)*

### Папка game

- `bgm`, `sfx`, `gui/sfx` - папки с музыкой, SFX и окружающими звуками

- `gui` - изображения для UI *(Интерфейса пользователя)* *(Содержит несколько картинкок, которые не подходят для людей с неустойчивой психикой. Картинки со спойлерами также присутствуют)*

- `images` - images of game *(Содержит много картинкок, которые не подходят для людей с неустойчивой психикой. Картинки со спойлерами также присутствуют)*

- `python-packages` - папка библиотек и пакетов для Python *(Содержит библиотеку `singleton` от которой зависит работоспособность игры)*

## Как скомпилировать мод и применить его в оригинальном DDLC

1. Откройте Ren'Py Launcher
2. Нажмите кнопку `"Построить дистрибутивы"`
3. Выберите ОС на которую вы хотите собрать модификацию
4. Ожидайте окончания компиляции
5. После того, как откроется папка с архивом игры, распакуйте архив и перейдите в папку `game`
6. Перенесите все файлы с расширением .rpa из вашего мода в файлы DDLC и согласитесь со всеми изменениями файлов
7. Откройте игру и проверьте совместимость ваших изменений в исходных файлах

## Информация по распространению модов для DDLC

В соответствии с [руководством по интеллектуальной собственности Team Salvato](http://teamsalvato.com/ip-guidelines/), модификации должны распространяться в виде файлов с расширением .rpa и содержать только те файлы, которые необходимы для установки мода *(В большинстве случаев это лишь файл scripts.rpa или же другие файлы (Если вы заменили графику/шрифты/аудио в игре))*. Любые модификации **НЕ** должны распространяться как полноценная игра и должны быть установлены только на существующую официальную игру DDLC, установленную на компьютере пользователя

## Скриншоты

<p align="center">
    <img src="https://raw.githubusercontent.com/SecondThundeR/DokiDoki-RenPy/your-reality/readme_screenshots/screenshot1.png?token=AIXISSKNI27DT32MFTEGPBS7SWGL6" alt="DDLC with edited name">
</p>

<p align="center">
    <img src="https://raw.githubusercontent.com/SecondThundeR/DokiDoki-RenPy/your-reality/readme_screenshots/screenshot2.png?token=AIXISSOCY4EUZZYORZMQNIK7SWGMA" alt="Developer Tools Screenshot">
</p>

<p align="center">
    <img src="https://raw.githubusercontent.com/SecondThundeR/DokiDoki-RenPy/your-reality/readme_screenshots/screenshot3.png?token=AIXISSN557XEIKENO54IVOC7SWGME" alt="Image Location Picker Screenshot">
</p>

## Лицензия

Эти исходные файлы распространяются под [лицензией MIT](https://github.com/SecondThundeR/DokiDoki-RenPy/blob/your-reality/LICENSE) и предоставляются "КАК ЕСТЬ" без каких-либо гарантий.

Все права принадлежат студии Team Salvato, которая создала DDLC

Также спасибо [Ren`Py](https://github.com/renpy/renpy), [unrpa](https://github.com/Lattyware/unrpa), [unrpyc](https://github.com/CensoredUsername/unrpyc) за замечательные инструменты