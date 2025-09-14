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
# 1. Ative a virtual environment (se ainda não estiver ativa)
#criar        >> python3 -m venv env
#ativar       >> source env/bin/activate
#desativar   só em caso de necessidade >> deactivate 

# 2. Entre na pasta do projeto Django
cd src

# 3. Rode o servidor de desenvolvimento
python manage.py runserver

python manage.py runserver

# Atualizando o git
git add .
git commit -m "Atualização do projeto: ajustes finais"
git push origin main   >>>> enviar os arquvos

