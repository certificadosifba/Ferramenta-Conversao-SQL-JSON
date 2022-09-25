# Ferramenta-de-Conversao-SQL-JSON

Projeto desenvolvido para o Trabalho de Conclusão de Curso, do Curso Superior em Sistemas
de Informação do Instituto Federal de Educação, Ciência e Tecnologia da Bahia campus Vitória da
Conquista.

O intuito do projeto é permitir a migração de uma base de dados SQL para MongoDB, para isso, através de consultas SQL a uma determinada base de dados, os resultados obtidos serão retornados em formato JSON, permitindo uma posterior inserção no banco não relacional.

A ferramenta desenvolvida permite a migração de qualquer base de dados SQL para o formato JSON, podendo mais tarde ser inserido no MongoDB, contudo, não há uma forma única de utilização, visto que cada base de dados atende uma determinada demanda, e a depender da proposta de modelagem do MongoDB será necessário o ajuste da lógica.
<br><br>

# Tecnologias utilizadas

- ### [PHP](https://www.php.net/)
- ### [SQL](https://dev.mysql.com/downloads/mysql/)
- ### [MongoDB](https://www.mongodb.com/try/download/community)

# Instruções de uso

A ferramenta está dividida em duas, uma irá retornar uma migração em vários documentos, a outra em único documento.

A instrução básica de uso é entender a estrutura que se quer obter e a partir disso manipular a lógica da ferramenta para que esta atenda a proposta requerida, modificando as consultas SQL e a estrutura dos <i>for's</i> que geram os arrays e documentos.

Os seguintes passos podem ser seguidos para execução da ferramenta.
<br>

1. Clonar o repositório;

```bash
$ https://github.com/certificadosifba/Ferramenta-Conversao-SQL-JSON.git
```

2. Iniciar o servidor PHP;

```bash
php -S localhost:8080 nome_do_arquivo.php
```

3. Executar o servidor PHP no navegador.

```bash
localhost:8080
```
