##### PREPARANDO A MÁQUINA DE BANCO DE DADOS

~~~bash
apt install mysql-server
sudo mysql_secure_installation
sudo mysql -u root -p
~~~
~~~sql
GRANT ALL PRIVILEGES ON nome_do_banco.* TO 'novo_usuario'@'localhost';
FLUSH PRIVILEGES;
~~~

