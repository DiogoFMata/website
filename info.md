# website
Template HTML CSS with database MYSQL::PDO query Sweet Alert 2 

This a website created for private reasons and because of that i can´t show the database

But still i can show the tables:

Table users;

+-------------+--------------+------+-----+---------+----------------+
| Field       | Type         | Null | Key | Default | Extra          |
+-------------+--------------+------+-----+---------+----------------+
| id          | int          | NO   | PRI | NULL    | auto_increment |
| username    | varchar(10)  | NO   | UNI | NULL    |                |
| password    | varchar(300) | YES  |     | NULL    |                |
| privilegios | varchar(10)  | YES  |     | 2       |                |
+-------------+--------------+------+-----+---------+----------------+
Table Acontecimentos;
+--------------+-------------+------+-----+---------+----------------+
| Field        | Type        | Null | Key | Default | Extra          |
+--------------+-------------+------+-----+---------+----------------+
| id           | int         | NO   | PRI | NULL    | auto_increment |
| requerente   | varchar(90) | YES  |     | NULL    |                |
| residente    | varchar(80) | YES  |     | NULL    |                |
| localobra    | varchar(80) | YES  |     | NULL    |                |
| tipoobra     | varchar(80) | YES  |     | NULL    |                |
| tecnico      | varchar(50) | YES  |     | NULL    |                |
| processo     | int         | YES  |     | 0       |                |
| caixa        | int         | YES  |     | 0       |                |
| entrada      | varchar(20) | YES  |     | NULL    |                |
| aprovacao    | varchar(20) | YES  |     | NULL    |                |
| licenca      | varchar(90) | YES  |     | NULL    |                |
| vistoria     | varchar(80) | YES  |     | NULL    |                |
| observacoes  | varchar(50) | YES  |     | NULL    |                |
| requerimento | varchar(50) | YES  |     | NULL    |                |
| plantaLocal  | varchar(50) | YES  |     | NULL    |                |
| idUser       | int         | YES  | MUL | NULL    |                |
+--------------+-------------+------+-----+---------+----------------+
