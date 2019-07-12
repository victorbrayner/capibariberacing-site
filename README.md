# Site Capibarib-E Racing

Repositório do site do Capibarib-E Racing.

## Primeiros Passos

Siga estes passos caso queira ter uma cópia do projeto configurada e executando no seu host local para propósitos de desenvolvimento e testes.

### Pré-requisitos

```
* Python3;
* Pip;
* Virtualenv;
```

### Instalação

* Instale as dependências listadas na seção acima caso não as possua:

```
sudo apt install python python3 python-pip virtualenv
```

* Dentro da pasta do projeto, rode o comando:

```
python -m venv env
```

* Ative o ambiente virtual:
#### Windows

```
env\Scripts\activate
```

#### Linux

```
source env/bin/activate
```

* Instale o Django:

```
pip install django
```

* Verifique se os requerimentos batem com os atuais usando:

```
pip freeze
```

* Para rodar, na pasta onde há o manage.py use:

```
python manage.py runserver
```

* Para rodar, na pasta onde há o manage.py use:

```
python manage.py runserver
```