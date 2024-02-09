# Конвертер new.dat.br to img
[English README](https://github.com/cardinalnsk/repack-util-android/blob/main/README_EN.md)

Этот проект представляет собой консольное приложение, написанное на Java, которое распаковывает архив с OTA обновлением и  конвертирует файлы `*.new.dat.br` в `*.img`.

## Зачем это нужно?

Этот проект был создан для автоматизации процесса распаковки файлов `*.new.dat.br`, которые часто используются в разработке Android, в файлы `*.img`. Это может быть полезно для разработчиков, которые работают с разделами Android.

## Для кого?

Этот проект предназначен для энтузиастов, кто работает с разделами Android.

## Как установить или собрать?

Чтобы собрать и установить проект, выполните следующие шаги:

1. Клонируйте репозиторий:
```bash
git clone https://github.com/cardinalnsk/repack-util-android
```

2. Перейдите в директорию проекта:
```bash
cd repack-util-android
```

3. Собрать проект с помощью Maven:
```bash
mvn clean install
```


## Как использовать?

Чтобы использовать приложение, вам понадобится в командной строке ввести команду:

Запуск утилиты без дополнительных флагов:
```bash
java -jar repack-util-android.jar your-ota-update-with-brotli-files.zip

Результат выполнения будет помещен в папку ./UnpackFirmware
```


---

Пример использования с флагом:
```bash
java -jar repack-util-android.jar your-ota-update-with-brotli-files.zip -o /path/to/output/directory

Результат выполнения будет помещен в папку /path/to/output/directory
```


---
