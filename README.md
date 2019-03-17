#   Blog-api

Blog e uma api do tipo REST que retorna mesagens no padrão json.

## Instalação 

Este projeto requer [python3](https://www.python.org/downloads/), [pip](https://pypi.org/project/pip/) e [virtualenv](https://virtualenv.pypa.io/en/latest/installation/).

``` bash
$ apt-get install python3
$ apt-get install python3-pip
$ pip3 install virtualenv
```
Crie um ambiente dedicado à aplicação e instale as dependências necessárias. 

``` bash
$ cd blog-api
$ cd virtualenv -p python3.6 env
$ ./env/bin/pip install -r requirements.txt
```

## Uso

Altere as informações do arquivo *.env-example* e renomeie para *.env*.

```bash
$ ./env/bin/python3.6 application.py
```