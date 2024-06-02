# FAT32-parser
Cкрипт, написанный на Python, представляет собой анализатор файловой системы FAT32, который позволяет анализировать и парсить файловые системы FAT32.
## Options
```
 -h, --help                               - Print out the help menu
       -i, --image  IMAGE                       - Enter the path to the file system raw image
       -m, --mbr                                - Parse Master Boot Record (MBR) only
       -p, --partition                          - Select the partition number (from 1 to 4) for which you would like to retrieve the boot sector information.
       -v, --verbose                            - Print out a quick documentation of every parsed field
```
## Usage

**Парсинг MBR:**
```
$ python3 --image /path/to/image --mbr
```

**Подробный вывод:**
```
$ python3 --image /path/to/image --mbr --verbose
```

**Парсинг указанного образа:**
```
$ python3 --image /path/to/image
```

## Пример работы программы:

![test](https://github.com/exc3pti0on/FAT32-parser/assets/162144988/533be0e3-280e-47a9-a7c7-74ed6d8fd966)
