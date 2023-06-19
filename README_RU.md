### [English Version](./README.md)<br>[Презентация PowerPoint](./documentation/presentation/Diploma_RU.pptx)

<br>
<span><img width="450" src="./documentation/readme/Logo.png"/></span><br>

# Редактор Уровней Plants vs. Zombies 2

**Редактор Уровней Plants vs. Zombies 2**, также упоминаемый как **Редактор Уровней**, **PvZ2: LE** или просто **LE** — утилита для Windows для создания уровней для PvZ2.
Утилита написана на C++ при помощи SFML и предоставляет базовую функциональность для создания уровней.

## 🛠 Состояние Разработки
<a name="Development"></a>

Данный проект был заархивирован после завершения и ныне доступен как часть портфолио. В данном репозитории две ветки:

* [``2.0.x``](https://github.com/blazingzephyr/level-editor/blob/2.0.x/README_RU.md) ветка представляет собой стабильную версию утилиты.
* [``2.1.x``](https://github.com/blazingzephyr/level-editor/blob/2.1.x/README_RU.md) ветка содержит незаконченное крупное обновление LE. Однако, обновление было отменено, из-за чего код незакочен и нестабилен.

## 📝 Цели
<a name="Goals"></a>

Изначально, начиная этот проект, я преследовал следующие цели:

* Переделать старую утилиту, которую я сделал в 2020 (Также известную как ``1.0``).
* Улучшить свои навыки C++.
* Изучить новую мультимедиа-библиотеку, в данном случае SFML.
* (Далее) сделать собственный UI на SFML без сторонних библиотек.

## 📃 Возможности
<a name="Features"></a>

Список возможностей, представленных утилитой:

* Базовые возможности, такие как экспорт JSON.
* Настройки персонализации:
  * Полноэкранный и Оконный режимы с широкоэкранными разрешениями (320:180, 640:360, 1280:720, 1920:1080).
  * Поддержка настраиваемого макета UI (ограниченно; только Стандартный макет включён).
  * Поддержка перевода UI (Английский и Русский переводы включены).
  * Поддержка тем UI ('Новая' и 'Старая' темы включены).
  * Дополнительные вторичные настройки:
    * Настройка громкости музыки и звуков.
    * Расположение папки экспорта.
    * и т.д.

## 🛡 Скачать
<a name="Download"></a>

Вы можете скачать последний скомпилированный релиз [здесь](https://github.com/blazingzephyr/level-editor/releases/tag/2023.01.27-stable).

## 📂 Установка
<a name="Installation"></a>

Если Вы скачали скомпилированный релиз, то для установки будет достаточно распаковать архив.

## ⚙ Сборка Исходников
<a name="Build"></a>

Также, Вы могли бы собрать исходники самостоятельно при помощи VS2022.

## 💡 Автор
<a name="Author"></a>

* ZaBlazzingZephyrus ([@blazingzephyr](https://github.com/blazingzephyr))

## 💼 Контрибьюторы
<a name="Contributors"></a>

* MysteriousPersona ([@MysteriousPersona](https://www.youtube.com/@MysteriousPersona))
* Seferiso
* liledix4 ([@liledix4](https://github.com/liledix4))
* BP The Mega Gatling Pea ([@BMegaGPea990](https://github.com/BMegaGPea990))

## 📜 Лицензия
<a name="License"></a>

Утилита и её исходный код распространяются под [MIT лицензией](https://opensource.org/license/mit/). Посмотрите [LICENSE](https://github.com/blazingzephyr/level-editor/blob/2.0.x/LICENSE). Внешние библиотеки, использующие Редактор Уровней, распространяются под собственными лицензиями.

Вкратце, Вам разрешено использовать эту утилиту для личных и коммерческих целей, однако, Вам не предоставляются никакие гарантии.

## 🧾 Внешние Библиотеки
<a name="Libraries"></a>

* [SFML](https://github.com/SFML/SFML) распространяется под [zlib Лицензией](https://github.com/SFML/SFML/blob/master/license.md)
* [minijson_reader](https://github.com/giacomodrago/minijson_reader) распространяется под [MIT Лицензией](https://github.com/giacomodrago/minijson_reader/blob/master/LICENSE.txt)
* [minijson_writer](https://github.com/giacomodrago/minijson_writer) распространяется под [MIT Лицензией](https://github.com/giacomodrago/minijson_writer/blob/master/LICENSE.txt)

## 📸 Скриншоты
<a name="Screenshots"></a>

| <img width="450" src="./documentation/readme/Title_Screen.png"/> |     <img width="450" src="documentation/readme/Main1.png"/>      |
|:----------------------------------------------------------------:|:----------------------------------------------------------------:|
| Главный Экран                                                    | Создание Уровня — Страница 1                                     |
|     <img width="450" src="./documentation/readme/Main2.png"/>    |     <img width="450" src="documentation/readme/Main3.png"/>      |
| Создание Уровня — Страница 2                                     | Создание Уровня — Страница 3                                     |