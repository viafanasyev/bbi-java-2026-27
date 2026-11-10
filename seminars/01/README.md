## План семинара №1

1. Установка JDK **21**.
    * В зависимости от ОС:
        * Windows: При помощи [установщика](https://www.oracle.com/java/technologies/downloads/#java21) (x64 Installer).
        * Linux (Debian-based): `sudo apt install openjdk-21-jdk` в терминале.
        * Linux (non-Debian-based): Либо из пакетного менеджера, либо из [tarball](https://www.oracle.com/java/technologies/downloads/#java21). После установки проверьте, что Java добавилась в `PATH`.
        * MacOS (с использованием [Brew](https://brew.sh/)): `brew install openjdk@21` в терминале.
    * После установки удостоверьтесь, что при вводе `java --version` в терминале/командной строке/Powershell выводится версия 21.
2. Установка IntelliJ IDEA.
    * [Ссылка на скачивание](https://www.jetbrains.com/ru-ru/idea/download/).
    * Ссылка может быть недоступна из России (ошибка 451). Способ обхода:
      1. Переходим на вкладку ["Другие версии"](https://www.jetbrains.com/ru-ru/idea/download/other/).
      2. Находим версию 2025.2 (для наших нужд её будет достаточно).
      3. Выбираем "**Community** Edition".
      4. Выбираем нужную операционную систему и файл.
      5. Загружаем.
3. Создание первого проекта в IDEA. Разбираемся с его структурой.
   * Не забываем, что при настройке IntelliJ IDEA и проектов в ней выбираем версию Java **21**, а не выше или ниже!
4. Пишем "Hello, World!".
5. Запускаем программу через IDEA.
6. Компиляция программы через утилиту `javac`. Запуск при помощи утилиты `java`.
7. Выходные файлы и их формат.
    * Опционально: используем утилиту `javap` или `Show Bytecode` в IDEA для просмотра `class`-файлов.
