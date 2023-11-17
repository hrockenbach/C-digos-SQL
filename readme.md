# Comando SQL
* Para executar os comandos pressione CTRL + ENTER
```
Criar database
```
* Create database NOME_DATABASE;
```
Definir a database de uso
```
* use NOME_DATABASE;
```
Criar tabela de usuário
```
* create table usuarios(
	id int not null auto_increment,
    nome varchar(120) not null,
    email varchar(120) not null,
    senha varchar(120) not null, 
    dt_nascimento date,
    primary key (id)
);

```
Inserir dados
```

* select * from usuarios;

* INSERT INTO usuarios(nome, email, senha, dt_nascimento)

* VALUES ('Renato Gaucho', 'renato@gmail.com', 'secreta', '2000-05-15');

```
* Not null = nao nulo (campo obrigatorio)
* Varchar = texto
* Date = data