# oscript-config

Пакет для работы с настройками oscript (содержимое oscript.cfg рядом с oscript.exe или запускаемым скриптом).

Основной сценарий работы - вызов консольного приложения oscript-config с параметрами:
```sh
> oscript-config get lib.system
C:\Program Files (x86)\OneScript\lib

> oscript-config set lib.additional "./oscript_modules"
```

Планируется:
* чтение настроек
* установка настроек
* разделение на режим работы глобальный (конфиг в Program Files) и локальный (в CWD)
* работа в режиме подключаемой библиотеки
