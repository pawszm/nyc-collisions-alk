# Analiza danych dotyczących wypadków samochodowych w New York

Projekt korzysta z języka programowania Python i środowiska jupyter notebook.
Zalecany system operacyjny w którym będzie uruchaminany projekt dodwolna dystrybucja Linux.
W folderze jupyter znajduje się dokument ny.ipynb w którym opisuję i przeprowadzam analizę danych.
Folder jupyter/data zawiera:
- plik nypd-motor-vehicle-collisions.csv, zawierający dane dotyczące wypadków samochodowych w mieście Nowy Jork

## Instalcaj środowiska

Zainstalować interpreter języka python w wersji 3.9.2 lub wyższej moduł venv do tworzenia środowiska wirtualnego python oraz menadżer pakietów pythona np. `pip` lub `conda`.
Sposób instalacji interpretatora języka python, modułu venv i menadżera pakietów python zależy od systemu operacyjnego.

Przykład instalacji modułu venv i menadżera pakietów python w systemie operacyjnym Linux Debian:
```bash
apt install python3.9-venv python3-pip
```

Sklonować repozytorium https://github.com/pawszm/nyc-collisions-alk.git do dowolnego folder pleceniem:\
```bash
git clone https://github.com/pawszm/nyc-collisions-alk.git
```

Przejść do folderu nyc-collisions-alk i utworzyć katalog venv w którym będzie umieszczone środowisko wirtualne pythona wraz z wymaganymi modułami. Folder venv wraz z zawartością jest ignorowany przez repozytorium git.

Przykład utworzenia środowiska wirtualnego w OS Linux Debian:
```bash
$ cd nyc-collisions-alk
$ mkdir venv
$ python3 -m venv venv/
$ source venv/bin/activate
```
W środowisku wirtualnym zainstalować wymagane pakiety pythona.\
Przykład instalacji pakietów przy pomocy menadzęra `pip`:
```shell
(venv)$ pip install -r requirements.txt
```

Środowisko wirtualne opuszczamy poleceniem `deactivate`
```shell
(venv)$ deactivate
```

Ponowne uruchomienie środowiska wirtualnego nie wymaga instalacji. Przechodzimy do folderu `nyc-collisions-alk` i aktywujemy środowisko wirtualne:
```bash
$ cd nyc-collisions-alk
$ . venv/bin/activate
(venv)$
```
