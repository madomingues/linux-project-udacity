# linux-project-udacity
Projeto de configuração de servidores Linux feito para o o Nanodegree FullStack Udacity

## Endereço de ip e porta ssh
IP: 100.24.44.120

porta ssh:2200

usuário: grader

senha: udacity123


## URL da aplicação WEB
/var/www/FlaskApp/FlaskApp

## Instalação e configuração do Apache
-Instalar apache com o comando sudo apt-get install apache2

-Instalar mod_wsgi sudo apt-get install python-setuptools libapache2-mod-wsgi

-Reiniciar Apache sudo service apache2 restart

## Instalação e Configuração Postgresql
-Instalar postgresql sudo apt-get install postgresql

-logar com o usuario postgres sudo su - postgres

-Entrar no shell usando psql

-Criar banco de dados ,usuário e senha do banco de dados

-Nome do banco de dados: catalog

-Usuário: catalog

-senha: password

## Outros Softwares usados
-Git

-Python

-pip

-psycopg2

-Flask

## Referencias
- https://www.digitalocean.com/community/tutorials/how-to-deploy-a-flask-application-on-an-ubuntu-vps

- Aulas Udacity de Deploy em servidores linux
