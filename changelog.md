Changelog
=========

0.0.44

  * Частично пофикшен #181. См. тесты `spaces.*.yate`.

0.0.43
------

  * Пофикшен #178.

0.0.42
------

  * Пофикшен #172 (вроде бы).

0.0.41
------

  * Fixed #171

0.0.40
------

  * Изменен синтаксис атрибутов с динамическим именем.
    Было:

        @{ .name } = 42
        @{ "data-{ .name }" } = 24

    Стало:

        @{ .name } = 42
        @data-{ .name } = 24

    Т.е. статические куски имени (строковые литералы) не нужно заключать в кавычки.

