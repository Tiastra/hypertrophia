# hypertrophia
App para gerenciar evolução na academia


### Getting started

Para rodar o projeto localmente precisa ter o python instalado. Clone o projeto HypertrophIA.
Dentro da pasta do projeto, siga os passos abaixo:

1 - Criar ambiente virtual:
python -m venv venv

2 - Ativar o ambiente virtual (windows):
no Git Bash: source venv/Scripts/activate,
no powershell: .\venv\Scripts\activate

3 - Instalar as libs necessárias:
pip install -r requirements.txt

4 - Rodar o servidor do projeto:
python manage.py runserver

5 - Comando makemigrations para inicializar o DB:
python manage.py makemigrations

6 - Comando migrate para rodas migrations inclusive as do Django:
python manage.py migrate

7 - Comando para criar um superUser do Django:
python manage.py createsuperuser
