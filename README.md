Задание 

Реализовать приложение, позволяющее искать некоторый набор запрещенных слов в файлах. Пользовательский интерфейс приложения должен позволять ввести или загрузить из файла набор запрещенных слов. При нажатии на кнопку «Старт», приложение должно начать искать эти слова на всех доступных накопителях информации (жесткие диски, флешки). Файлы, содержащие запрещенные слова, должны быть скопированы в заданную папку. Кроме оригинального файла, нужно создать новый файл с содержимым оригинального файла, в котором запрещенные слова заменены на 7 повторяющихся звезд (*******). Также нужно создать файл отчета. Он должен содержать информацию о всех найденных файлах с запрещенными словами, пути к этим файлам, размер файлов, информацию о количестве замен и так далее. В файле отчета нужно также отобразить топ-10 самых популярных запрещенных слов. Интерфейс программы должен показывать прогресс работы приложения с помощью индикаторов (progress bars). Пользователь через интерфейс приложения может приостановить работу алгоритма, возобновить, полностью остановить. По итогам работы программы необходимо вывести результаты работы в элементы пользовательского интерфейса (нужно продумать, какие элементы управления понадобятся). Программа обязательно должна использовать механизмы многопоточности и синхронизации! Программа может быть запущена только в одной копии.
