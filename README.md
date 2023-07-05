# ChopSpider - Grupo 2 [Seg AppWeb 2023]

<p align=center>

  <img src="https://i.postimg.cc/sD9JxYCy/ezgif-4-607cd28bd6cc.gif"/>

  <br>
  <span>Herramienta para la explotación de Chop Slider 3 [WordPress]</span>
  <br>
  <br>
  <a target="_blank" href="https://www.python.org/downloads/" title="Python version"><img src="https://img.shields.io/badge/python-%3E=_2.7-green.svg"></a>
 </a>
</p>

  


## Instalación

```console
# Clonar el repo
$ git clone https://github.com/Dzukito/ChopSpider.git

# Instalar el modulo requests
$ pip install requests

# Entrar en el directorio del proyecto
$ cd ChopSpider

```


## Uso

```console
$ python chopSpider.py
usage: chopSpider.py [-h] [-u URL] [-db] [-t] [-c COLUMNS] [-du DUMP]

optional arguments:
  -h, --help            show this help message and exit
  -u URL, --url URL     URL raiz de la Web a vulnerar. Ej:
                        http://www.test.com/
  -db, --database       Retorna el nombre de la base de datos del sitio
  -t, --tables          Retorna el nombre de todas las tablas de la base de
                        datos del sitio
  -c COLUMNS, --columns COLUMNS
                        Retorna el nombre de todas las columnas de una tabla
                        de la base de datos del sitio
  -du DUMP, --dump DUMP
                        Retorna los datos o filas de una tabla de la base de
                        datos del sitio
```

Para obtener todos los datos de la tabla de una base de datos:
```
python chopSpider.py -u http://www.test.com --dump <tabla> <database>
```
