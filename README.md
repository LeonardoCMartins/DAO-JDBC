# Projeto de Exemplo - Sistema de Gerenciamento de Vendedores e Departamentos
Este é um projeto de exemplo que demonstra um sistema simples de gerenciamento de vendedores e departamentos. O projeto foi desenvolvido em Java e utiliza o padrão DAO (Data Access Object) para acessar os dados do banco de dados.

## O projeto utiliza as seguintes tecnologias:

<p>Java</p>
<p>JDBC (Java Database Connectivity)</p>
<p>MySQL (ou outro banco de dados relacional)</p>
<p>Design Patterns: DAO</p>

## Funcionalidades
O sistema possui as seguintes funcionalidades:

Consulta de vendedores por ID
Consulta de vendedores por departamento
Listagem de todos os vendedores
Inserção de novos vendedores
Atualização de dados de vendedores
Exclusão de vendedores
Consulta de departamentos por ID
Listagem de todos os departamentos
Inserção de novos departamentos
Atualização de dados de departamentos
Exclusão de departamentos

## Configuração do Banco de Dados
Para executar o projeto, é necessário configurar um banco de dados MySQL e criar as tabelas necessárias, além de configurar as conexões com o banco de dados utilizado no arquivo "db.properties". O script SQL para criação das tabelas pode ser encontrado no diretório sql na raiz do projeto.

## Executando o Projeto
Para executar o projeto, basta rodar as classes application.Main para a conferir a tabela de vendedores (seller) e application.Main2 para a tabela de departamentos (department).

## Considerações Finais
Este é um projeto simples que demonstra o uso de DAOs para acesso a um banco de dados relacional em Java. Ele pode ser expandido e melhorado para atender a requisitos mais complexos em um ambiente real de desenvolvimento de software.
