# Семинар 1. Использование ЭВМ и доступ к ним, установка, настройка программ и сред

## План семинара
- Обсуждение различных операционных систем. Работа в командной строке. Рабочие станции, сервера, кластеры, системы хранения данных. Экскурсия к вычислительному кластеру.
- Подключение к кластеру по SSH. Использование PuTTY для Windows. Криптоключи (для самостоятельной работы - объяснить суть).
- X11 forwarding
- X2GO
- bash и основные команды
- Запуск программ в командной строке
- Переменные среды, PATH
- Запуск Python-скриптов в командной строке.
- Компиляторы, компиляция простейших программ.
- Управление модулями командой module
- Менеджер пакетов conda
- Git и GitHub.

## Справочные материалы
- [SSH](https://github.com/intbio/IntBioEdu/blob/master/ITcc.md)
- [Conda](https://github.com/intbio/IT_notes/blob/master/conda.md)
- [Git](https://github.com/intbio/IT_notes/blob/master/git.md)

## Самостоятельная (домашняя) работа.

- На своем локальном компьютере установите менеджер пактов conda.
- С помощью него установите программу Pymol из репозитория Anaconda.
- Зарегистрируйтесь на GitHub. 
- Создайте свой репозиторий, добавить туда файлы.
- Клонируйте репозиторий на кластер Newton в свою рабочую директорию.
- Создайте пару криптоключей, которые позволят вам подключаться к кластеру без пароля.
- Создайте на Newton conda environment `wsh1`.
- Установите программу STRIDE из Anaconda,
- Закрузите, скомпилируйте и проверьте работоспособность программы STRIDE http://webclu.bio.wzw.tum.de/stride/
- Сравните результаты анализа двух версий программы с помощью команды `diff`

### Оцениваемый результат
- Отчет о проделанной работе со скриншотами, в который видено Ваше имя пользователя.

### [Запись семинара](https://distant.bioeng.ru/playback/presentation/2.0/playback.html?meetingId=4578ef0cf123b710b7e95fdbfa8fbcc844ec6bc3-1612794728048)

### [Презентация семианра](workshop_1.pdf)

