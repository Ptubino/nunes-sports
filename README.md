Prerequisitos:
[Python 3.x](https://www.python.org/downloads/)
[pip](https://pip.pypa.io/en/stable/installation/)


Para rodar o programa, depois de baixar, rode os seguintes comandos no path do projeto: 
python manage.py makemigrations
python manage.py migrate
python manage.py runserver

Dai você pode acessar a lista de produtos:
(http://localhost:8000/api/products/) para acessar a lista e adicionar produtos
(http://localhost:8000/api/products/<id>) para editar ou deletar o produto do id escolhido

