# Как сохранить зрение при чтении с экрана

[![Screenshot](../../../data/tags/win7/tag_win7.png)](../../../data/tags/win7)
[![Screenshot](../../../data/tags/linux/tag_linux.png)](../../../data/tags/linux)
[![Screenshot](../../../data/tags/good/tag_good.png)](../../../data/tags/good)
[![Screenshot](../../../data/tags/education/tag_education.png)](../../../data/tags/education)
[![Screenshot](../../../data/tags/med/tag_med.png)](../../../data/tags/med)
-----

При необходимости ежедневного чтения книг и документов с экрана монитора и телефона совершенно естественным образом начинаешь задумываться о сохранении зрения. Безответственное отношение к своему здоровью рано или поздно приводит к неутешительному выводу: или ты становишься на путь сохранения того немногого, что осталось, или окончательно становишься инвалидом. А инвалидом по зрению лучше не становиться — это основной канал получения информации об окружающей действительности.

В эпоху кибернетики довольно быстро стало понятно, что типографский книжный стандарт печати чёрного текста на белом фоне, оптимальный по яркости и контрасту для бумажного носителя, совершенно не подходит для компьютерных мониторов: большинство старых ЭЛТ-мониторов, начиная с допотопных монохромных, всё-таки предполагали светлый текст на тёмном фоне: чёрно-белый, чёрно-жёлтый, чёрно-зелёный. И по сей день мягкий серый (не белый!) цвет текста на чёрном фоне является признанным стандартом работы в консольном режиме.

С появлением высококачественных ЖК-мониторов нагрузка на зрение в любых режимах существенно снизилась по сравнению с их ЭЛТ-прародителями, но всё же достаточно полчаса посидеть в ворде с белым фоном подложки в условиях недостаточной освещённости в помещении, как глазам станет несладко.

Умеренный оптимизм внушает тот факт, что люди стали больше задумываться о комфорте для глаз при чтении с экрана, и это очевидно как по растущему количеству «ночных» тем оформления сайтов и программ, так и по растущему числу пользователей этих тем.

Мой личный опыт говорит о том, что наиболее сбалансированными режимами для глаз являются:

Светлый текст `#C0C0C0` на чёрном фоне `#000000`:

[![Screenshot](https://github.com/apscrap/data-01/blob/main/2025-06-10-pdf-readers/pic/console_dark_mini.png)](https://github.com/apscrap/data-01/blob/main/2025-06-10-pdf-readers/pic/console_dark.png)

Чёрный текст `#000000` на светлом фоне `#C0C0C0`:

[![Screenshot](https://github.com/apscrap/data-01/blob/main/2025-06-10-pdf-readers/pic/console_light_mini.png)](https://github.com/apscrap/data-01/blob/main/2025-06-10-pdf-readers/pic/console_light.png)

Для чтения литературы в форматах `pdf`, `djvu` и `fb2` я хотел бы порекомендовать несколько прекрасных программ, в которых настройка комфортного режима не занимает много времени и сил, а пользоваться ими удобно и приятно, в отличие от множества популярных «читалок» от **Acrobat Reader** до **WinDjView**, где вообще не поддерживается гибкая настройка цветовых решений.

## Okular

Открывает наш маленький хит-парад кроссплатформенный проект [Okular](https://okular.kde.org/download/).

Несмотря на нескромный размер дистрибутива почти в `70 Мб`, это гибкий, удобный, всеядный и быстрый инструмент. Изначально разработанный для **KDE**, окуляр быстро набрал популярность и теперь по умолчанию входит практически в каждый приличный репозиторий.

В стандартном варианте мы увидим типичную картину при открытии pdf-файла — белый фон и чёрный текст.

[![Screenshot](https://github.com/apscrap/data-01/blob/main/2025-06-10-pdf-readers/pic/okular_1_mini.jpg)](https://github.com/apscrap/data-01/blob/main/2025-06-10-pdf-readers/pic/okular_1.jpg)

Но достаточно лишь зайти в меню `Настройка` -> `Настроить Okular` и в блоке `Специальные возможности` выбрать цветовой режим, а также привязанные к нему цвета.

[![Screenshot](https://github.com/apscrap/data-01/blob/main/2025-06-10-pdf-readers/pic/okular_settings_mini.jpg)](https://github.com/apscrap/data-01/blob/main/2025-06-10-pdf-readers/pic/okular_settings.jpg)

А после этого в меню `Настройка` -> `Панели инструментов` добавить кнопку переключения цветового режима на тулбар.

[![Screenshot](https://github.com/apscrap/data-01/blob/main/2025-06-10-pdf-readers/pic/okular_toolbar_mini.jpg)](https://github.com/apscrap/data-01/blob/main/2025-06-10-pdf-readers/pic/okular_toolbar.jpg)

И станет возможным переключение режима в один клик, что очень удобно. Если же у документа есть какая-то текстурная подложка, она будет представлена в оттенках серого. На скриншотах этот переключатель находится справа на тулбаре.

[![Screenshot](https://github.com/apscrap/data-01/blob/main/2025-06-10-pdf-readers/pic/okular_2_mini.jpg)](https://github.com/apscrap/data-01/blob/main/2025-06-10-pdf-readers/pic/okular_2.jpg)
[![Screenshot](https://github.com/apscrap/data-01/blob/main/2025-06-10-pdf-readers/pic/okular_3_mini.jpg)](https://github.com/apscrap/data-01/blob/main/2025-06-10-pdf-readers/pic/okular_3.jpg)

Из дополнительных возможностей может имеется режим управления потреблением оперативной памяти, что может быть полезно при работе с очень большими документами.

Также нужно отметить, что с форматом `fb2` окуляр работает с несколько странным форматированием, и лучше для него пользоваться следующей программой в нашем списке.

## STDU Viewer

Легкий, быстрый и всеядный [STDU Viewer](http://www.stdutility.com/stduviewer.html) работает только под виндой, но делает это хорошо.

[![Screenshot](https://github.com/apscrap/data-01/blob/main/2025-06-10-pdf-readers/pic/stdu_1_mini.jpg)](https://github.com/apscrap/data-01/blob/main/2025-06-10-pdf-readers/pic/stdu_1.jpg)

Настройка цвета доступна в меню `View` -> `Setting`, где регулятором `Brightness` можно сделать подложку серой. Забавно, что при включении опции `Invert colors` для снижения яркости цвета текста на чёрном фоне регулятор `Brightness` нужно двигать вправо.

[![Screenshot](https://github.com/apscrap/data-01/blob/main/2025-06-10-pdf-readers/pic/stdu_settings_mini.jpg)](https://github.com/apscrap/data-01/blob/main/2025-06-10-pdf-readers/pic/stdu_settings.jpg)

С форматом `fb2` программа работает идеально.

[![Screenshot](https://github.com/apscrap/data-01/blob/main/2025-06-10-pdf-readers/pic/stdu_2_mini.jpg)](https://github.com/apscrap/data-01/blob/main/2025-06-10-pdf-readers/pic/stdu_2.jpg)
[![Screenshot](https://github.com/apscrap/data-01/blob/main/2025-06-10-pdf-readers/pic/stdu_fb2_mini.jpg)](https://github.com/apscrap/data-01/blob/main/2025-06-10-pdf-readers/pic/stdu_fb2.jpg)

## ReadEra

Ну и нельзя обойти вниманием мобильные платформы.

На мой взгляд, лучше программы для чтения документов под ведроидом, чем великолепная [ReadEra](https://readera.org/ru), попросту нет. В комплекте скорость работы, всеядность, удобный интерфейс и удобная регулировка яркости.

[![Screenshot](https://github.com/apscrap/data-01/blob/main/2025-06-10-pdf-readers/pic/readera_dark_mini.png)](https://github.com/apscrap/data-01/blob/main/2025-06-10-pdf-readers/pic/readera_dark.png)
[![Screenshot](https://github.com/apscrap/data-01/blob/main/2025-06-10-pdf-readers/pic/readera_settings_mini.png)](https://github.com/apscrap/data-01/blob/main/2025-06-10-pdf-readers/pic/readera_settings.png)

Берегите зрение, друзья!
