# oscript-config

Пакет для работы с настройками oscript (содержимое oscript.cfg рядом с oscript.exe или запускаемым скриптом).

Основной сценарий работы - вызов консольного приложения oscript-config с параметрами:
```sh
> oscript-config get lib.system
C:\Program Files (x86)\OneScript\lib

> oscript-config set lib.additional "./oscript_modules"
```

Возможности:
* чтение настроек
* установка настроек
    * глобально - в файл oscript.cfg в OneScript/bin
    * локально - в файл oscript.cfg в CWD
