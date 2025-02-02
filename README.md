
#7DaysOfCode Python desafio 3


# Desafio 3

No desafio de hoje, você vai dar o primeiro mergulho com o framework Django! Ele é muito usado para o back-end com Python.

Para fazer o desafio de hoje, você deverá:

Iniciar um projeto Django com o comando startproject e criar um app (aplicativo)
Fazer as configurações necessárias para registro do app.
Executar o projeto para que a página inicial do Django seja mostrada, conforme abaixo:


O comando para iniciar um projeto no Django é:
```
django-admin startproject <nome_do_projeto>.
```
Substitua “<nome_do_projeto>” para outro que julgar melhor para o desafio. 

Já, para criar o app (aplicação), você pode usar este comando:
```
django-admin startapp <nome_do_app>
```

Para executar, o server, faças as migrações:

```
python manage.py migrate
```
E depois execute:

```
python manage.py runserver
```
Server Django executando `http://127.0.0.1:8000/`

![image/d_3.png](image/d_3.png)
