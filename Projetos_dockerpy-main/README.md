# Projetos_dockerpy

Projeto de exemplo utilizando **Python**, **Docker** e **pyenv** para gerenciamento de versões.

---

## Tecnologias Utilizadas

- Python (gerenciado com pyenv)
- Docker
- Docker Compose
- Virtualenv (venv)

---

## Pré-requisitos

- Python instalado (recomenda-se usar pyenv)
- Docker
- Docker Compose
- Git

---

## Configuração do Ambiente Python

1. Instale a versão do Python desejada usando **pyenv**:
```bash
pyenv install 3.12.2
pyenv local 3.12.2
## para atualizar tudo use:
pip freeze | tee requirements.txt
ou 
pip freeze > requirements.txt

pip install -r requirements.txt

## Instalar VENV
#criar        >> python3 -m venv env
#ativar       >> source env/bin/activate
#desativar    >> deactivate

# Rodar o projeto
django-admin --version
python manage.py runserver

