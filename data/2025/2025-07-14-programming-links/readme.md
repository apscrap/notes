# Ссылки для изучающих программирование

[![image](../../../data/tags/education/tag_education.png)](../../../data/tags/education)
[![image](../../../data/tags/cpp/tag_cpp.png)](../../../data/tags/cpp)
-----

Коллекция полезных ссылок будет дополняться на регулярной основе.
<br><br>

## C++

[open-std.org](https://open-std.org/) — черновики стандартов: [C++11](https://www.open-std.org/jtc1/sc22/wg21/docs/papers/2012/n3337.pdf), [C++14](https://www.open-std.org/jtc1/sc22/wg21/docs/papers/2014/n4296.pdf), [C++17](https://www.open-std.org/jtc1/sc22/wg21/docs/papers/2017/n4659.pdf), [C++20](https://www.open-std.org/jtc1/sc22/wg21/docs/papers/2020/n4861.pdf), [C++23](https://www.open-std.org/jtc1/sc22/wg21/docs/papers/2023/n4950.pdf).

[cppreference.com](https://en.cppreference.com/w/) — наиболее авторитетный неофициальный справочник по актуальному состоянию языка. Если есть какие-то сомнения относительно внутренней кухни, то тут либо в стандарт, либо сюда.

[cplusplus.com/reference](https://cplusplus.com/reference/) — альтернативный онлайн-справочник, сильно уступающий по объёму и актуальности материалов, но выигрывающий по человечности их представления.

[wandbox.org](https://wandbox.org/) — онлайн-сервис, позволяющий скомпилировать и выполнить программу на одном из множества языков программирования и компиляторов с различными настройками.

[compiler-explorer](https://compiler-explorer.com/), он же [godbolt.org](https://godbolt.org/) — онлайн-дизассемблер, поддерживающий всевозможные версии платформ и компиляторов различных языков.

[cppinsights.io](https://cppinsights.io/) — онлайн-компилятор, позволяющий развернуть весь синтаксический сахар в стандартные конструкции, инстанцировать шаблоны и преобразовать лямбда-выражения.

[quick-bench.com](https://quick-bench.com/) — онлайн-профилировщик, сравнивающий производительность двух функций.

[build-bench.com](https://build-bench.com/) — онлайн-профилировщик времени компиляции проекта.
<br><br>

## Компиляторы

[gcc.gnu.org](https://gcc.gnu.org/) — компилятор **GCC** под Linux.

[clang.llvm.org](https://clang.llvm.org/) — компилятор **Clang** для LLVM под Linux.

[mingw-w64.org](https://www.mingw-w64.org/) — компилятор **Mingw-w64** под Windows ([собранные релизы](https://github.com/niXman/mingw-builds-binaries)).

[winlibs.com](https://winlibs.com/) — готовые билды **GCC+Mingw** под Windows в ассортименте.

[jmeubank.github.io/tdm-gcc](https://jmeubank.github.io/tdm-gcc/) — компилятор **TDM-GCC** под Windows, компилирующий в том числе 32-разрядные программы (Mingw этого не умеет).

[github.com/gcc-mirror/gcc](https://github.com/gcc-mirror/gcc) — зеркало исходников компилятора **GCC**, в том числе: [парсер и семантический анализатор](https://github.com/gcc-mirror/gcc/tree/master/gcc/cp), [общая часть C и C++](https://github.com/gcc-mirror/gcc/tree/master/gcc/c-family), [стандартная библиотека](https://github.com/gcc-mirror/gcc/tree/master/libstdc++-v3) (например, [stl_vector.h](https://github.com/gcc-mirror/gcc/blob/master/libstdc++-v3/include/bits/stl_vector.h) и [vector.tcc](https://github.com/gcc-mirror/gcc/blob/master/libstdc++-v3/include/bits/vector.tcc)).

[openwatcom.org](http://www.openwatcom.org/) — компилятор **Open Watcom** для ценителей ретрокодинга (ограниченная поддержка C++98).
<br><br>

## IDE и редакторы

[geany.org](https://geany.org/) — минималистичная кроссплатформенная среда разработки **Geany**. Под линуксом в связи с отсутствием аналога Notepad++ я её использую ещё и как дефолтный текстовый редактор — настолько она быстрая.

[github.com/Embarcadero/Dev-Cpp](https://github.com/Embarcadero/Dev-Cpp) — отличная среда разработки **Dev-C++** под винду, по умолчанию использует компилятор TDM-GCC. Мне не очень нравятся в ней два момента: во-первых, редактор текста не сравнится по возможностям с Notepad++, во-вторых, указание параметров компиляции разбито по окнам и вкладкам, и мне так не слишком удобно. В остальном всё супер — готовый вариант, что называется, «из коробки».

[codeblocks.org](https://www.codeblocks.org/) — популярная среда разработки **Code::Blocks** под винду. Из недостатков отмечу только громоздкость настроек и некоторую неторопливость работы самой IDE, впрочем, это дело вкуса.

[jetbrains.com/clion](https://www.jetbrains.com/clion/) — мощная кроссплатформенная среда разработки **CLion**. На экосистему JetBrains очень легко подсесть, потому что сделано толково: статический анализатор кода, куча автоматизированных решений, полная интеграция с отладчиком и тулчейном (а в линуксе еще и с valgrind). Вроде как с этого года будет бесплатен для некоммерческого использования, но на семёрке работает только версия 2019.2, поэтому для некоммерческого использования придётся пройти в зелёный магазин под чёрным флагом.

[vim.org](https://www.vim.org/) — кроссплатформенный текстовый редактор **Vim** с собственной уникальной экосистемой и традициями.

[gnu.org/software/emacs](https://www.gnu.org/software/emacs/) — кроссплатформенный текстовый редактор **Emacs** с собственной уникальной экосистемой и традициями.

[github.com/notepad-plus-plus/notepad-plus-plus](https://github.com/notepad-plus-plus/notepad-plus-plus) — самый лучший текстовый редактор **Notepad++** под винду (рекомендую [версию 7.6](https://download.notepad-plus-plus.org/repository/7.x/7.6/)). Ничего даже близко сопоставимого по удобству и мощи среди классических редакторов просто не существует.

[mh-nexus.de/en/hxd](https://mh-nexus.de/en/hxd/) — hex-редактор **HxD** под винду, написанный на ассемблере.

[sourceforge.net/projects/frhed](https://sourceforge.net/projects/frhed/) — старенький, но ещё популярный hex-редактор **Frhed** под винду.
<br><br>

## Отладчики

[sourceware.org/gdb/](https://www.sourceware.org/gdb/) — отладчик **gdb** под Linux/Windows (gcc/mingw).

[x64dbg.com](https://x64dbg.com/) — отладчик **x64dbg** под Windows.

[github.com/NationalSecurityAgency/ghidra](https://github.com/NationalSecurityAgency/ghidra) — кроссплатформенный пакет для реверс-инжиниринга **Ghidra**, разработанный АНБ США.

[cheatengine.org](https://www.cheatengine.org/) — утилита **Cheat Engine** для исследования программ под Windows через оперативную память.

[github.com/scanmem/scanmem](https://github.com/scanmem/scanmem) — консольная утилита **scanmem** и её GUI-надстройка **Game Conqueror** для исследования программ под Linux через оперативную память.

[github.com/AlexanderBagel/ProcessMemoryMap](https://github.com/AlexanderBagel/ProcessMemoryMap) — утилита **ProcessMemoryMap** под винду для просмотра карты памяти процесса ([сайт автора](https://rouse.drkb.ru/)).

[systeminformer.sourceforge.io](https://systeminformer.sourceforge.io/) — утилита **System Informer** (бывший **Process Hacker**) под винду для гибкого мониторинга работы процессов.

[ntcore.com/explorer-suite](https://ntcore.com/explorer-suite/) — утилита **Explorer Suite** под винду для анализа исполняемых файлов.
<br><br>

## Эмуляция и виртуализация

[virtualbox.org](https://www.virtualbox.org/) —  средство создания виртуальных машин **VirtualBox**. Прекрасная виртуалка. Потребует определенного времени для вкуривания настроек, коих при кажущейся простоте на самом деле немало, но в остальном работа с ви-боксом вообще ни разу не доставила мне никаких проблем. Последняя работающая под семёркой версия: [5.2.44-139111](https://download.virtualbox.org/virtualbox/5.2.44/). Очень рекомендую начать освоение как можно быстрее — сейчас я уже и мыслить не могу в категориях жизни без ви-бокса. Стоит ли свеч возня с [VMware Workstation](https://www.vmware.com/products/desktop-hypervisor/workstation-and-fusion) взамест — вопрос открытый. На мой взгляд, нет.

[qemu.org](https://www.qemu.org/) — консольный эмулятор **QEMU**, работающий с разными архитектурами и совместимый с отладчиком GDB.

[dosbox.com](https://www.dosbox.com/) — эмулятор **MS-DOS**.

[pdp-11.org.ru](https://pdp-11.org.ru/) — эмулятор **PDP-11**.
<br><br>

## Алгоритмы и структуры данных

[algorithmica.org](https://ru.algorithmica.org/) — авторский проект Сергея Слотина, посвященный алгоритмам и структурам данных.

[visualgo.net](https://visualgo.net/en) — визуализация работы алгоритмов и структур данных.

[cs.usfca.edu/~galles/visualization](https://www.cs.usfca.edu/~galles/visualization/) — визуализация работы алгоритмов и структур данных.

[algorithm-visualizer.org](https://algorithm-visualizer.org/) — визуализация работы алгоритмов и структур данных.
<br><br>

## Компьютерные сети

[linkmeup.ru/blog/1188](https://linkmeup.ru/blog/1188/) — цикл статей «**Сети для самых маленьких**». Вопреки названию, материал в них совсем не детский. Заслуженно считается одним из лучших свободных учебников по компьютерным сетям.
<br><br>

## Полезный софт

[doublecmd.sourceforge.io](https://doublecmd.sourceforge.io/) — кроссплатформенный панельный менеджер **Double Commander**, полностью совместимый с плагинами к Total Commander. Даже если отвлечься от собственно стандартных функций панельного менеджера, он поистине великолепен при поиске файлов по именам и их содержимому, а также групповом перименовании файлов, потому что умеет в регулярные выражения и скорость работы. Полноценная и современная альтернатива ветерану — Far Manager.

[winmerge.org](https://winmerge.org/) — программа **WinMerge** для сравнения содержимого файлов под винду (рекомендую версию 2.16.42.1).

[angusj.com/resourcehacker](http://www.angusj.com/resourcehacker/) — редактор ресурсов **Resource Hacker** для исполняемых файлов и библиотек под винду (рекомендую версию 3.6.0.92).

[logicnet.dk/DiagramDesigner](https://logicnet.dk/DiagramDesigner/) — редактор разного рода диаграмм и схем **Diagram Designer** под винду (рекомендую версию 1.30). Поможет быстро набросать UML-диаграмму или блок-схему. [Дополнительные библиотеки](https://github.com/meesoft/DiagramDesigner/tree/master/TemplatePalettes) элементов нужно размещать в корневой папке программы (понимает только ANSI-символы в именах файлов, а то там какой-то француз решил блеснуть патриотизмом).
<br><br>

## Нейросети

[chat.deepseek.com](https://chat.deepseek.com/) — единственная заслуживающая внимания бесплатная нейросеть **DeepSeek**. Вопросов будет много, и в 99% случаев она справится лучше, чем гугл: подскажет, поправит, проанализирует код (можно засылать все файлы проекта скопом), посоветует литературу, даст ссылки на пункты стандартов. В среде дедов-красноглазиков пользователи нейросеток приравниваются к электросамокатчикам, но при этом сами деды на помощь что-то как-то не спешат.
<br><br>

