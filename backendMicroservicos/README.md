# backendMicroservicos
clonar o repositorio com o comando
1 - git glone https://github.com/pacastro666/backendMicroservicos.git
   depois criar a venv
2 - python -m venv venv
 ativar a venv
3 -.\venv\Scripts\activate
instalar as dependencias como comando 
4- pip install -r requirements.txt
rodar a primeira vez o servidor para criar o banco de dados
5- python manage.py runserver
 parar o servidor com CTRL+C e rodar as migracoes
6 -python manage.py migrate
depois so rodar novamente o servidor
7- python manage.py runserver



instalar as dependencias
nao coloquei validacoes de usuarios para nao dar prblema na hora de validar os dados

