Утилита [Sqoop](../../data-proc/operations/sqoop-usage.md) позволяет импортировать базы данных в кластер {{ dataproc-name }}. В зависимости от конфигурации кластера {{ dataproc-name }} вы можете выполнить импорт в:

* бакет {{ objstorage-full-name }};
* директорию HDFS;
* Apache Hive;
* Apache HBase.

Чтобы импортировать базы данных кластера-источника с помощью Sqoop в кластер-приемник {{ dataproc-name }}:

1. [Подготовьте кластер-источник](#prepare).
1. [Выполните импорт](#import).
1. [Проверьте корректность импорта](#check).

Если созданные ресурсы вам больше не нужны, [удалите их](#clear-out).

{% include [No Sqoop in DataProc v2.0](../../_includes/data-proc/no-sqoop-in-dataproc2.md) %}
