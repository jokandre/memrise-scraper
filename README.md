# memrise-scraper

Simple memrise scraper


## Usage:
Tags:

--url or -u < url>

--json or -j <True/False> :: default = True

--pinyin or -p <True/False> :: default = True


### On Windows:
```
py -3 memrise.py -u /course/68063/topik-in-30-days-intermediate-vocabulary/  >output.csv
```

### On Linux:

```
python3 memrise.py -u /course/68063/topik-in-30-days-intermediate-vocabulary/ | sort -u
```

```
python3 memrise.py -url /course/184712/practical-audio-visual-chinese-book-2-2/ > unit2.csv

python3 memrise.py -url /course/196005/practical-audio-visual-chinese-book-3/ > unit3.csv

python3 memrise.py -url /course/471083/practical-audio-visual-chinese-book-4-2/ > unit4.csv

python3 memrise.py -url /course/408617/all-top-8829-traditional-mandarin-no-typing/ > mostfrequent.csv
```

### Json



