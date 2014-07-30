## 28 июля, понедельник
Скачал методичку, посмотрел задание. Запустил на тестовом файле (57 кб) FastQC, посмотрел отчеты. Начал разбираться с fastq_quality_trimmer.

## 29 июля, вторник
Разбирался с fastq_quality_trimmer, фильтровал реальные данные. Сравнил отчеты от FastQC до и после фильтрации.
Сделал выравнивание. Индекс хранится здесь `/home/chipseq3/real_data/chromFa/`
Выровненный файл `/home/chipseq3/real_data/chromFa/assembled.sam`
Сконвертил SAM файл в BAM, и сделал дополнительную фильтрацию с помощью SAMTools, файлы (последовательно)
 `/home/chipseq3/real_data/chromFa/assembled.bam`
 `/home/chipseq3/real_data/chromFa/assembled_after_rmdup.bam`
 `/home/chipseq3/real_data/chromFa/filtered_asseble.bam`
Запустил визуализацию BAM файла на ноутбуке, не посмотрев в настройках что UGENE может занять всю память.

## 30 июля, среда
Начал разбираться детальнее с UGENE и  наконец закоммитился.
