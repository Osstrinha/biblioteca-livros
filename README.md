# Biblioteca de Livros

Este repositório contém dados sobre minha biblioteca pessoal, incluindo informações sobre os livros e seus tipos.

## Finalidade

A finalidade do projeto era a criação e estruturação relacional de uma base de dados, mediante uso do PostgreSQL, à partir de um estoque real.

## Estrutura dos Dados

1. **Tabela Principal (`biblioteca.csv`)**
   - Contém os dados principais dos livros, como título, autor, ano de publicação, e um ID que referencia o tipo de livro.

2. **Tabela Auxiliar (`genero.csv`)**
   - Mapeia os IDs de `id_genero` para os gêneros literários dos livros.
  
3. **Tabela Auxiliar (`status.csv`)**
   - Mapeia os IDs de `id_status` para o status dos livros.

4. **Tabela Auxiliar (`tipo.csv`)**
   - Mapeia os IDs de `id_tipo` para os nomes descritivos dos tipos de livros.

## Exemplo de Relacionamento
- O livro com `id_tipo = 3` na tabela principal (`biblioteca.csv`) refere-se ao tipo "Brochura" na tabela auxiliar (`tipo.csv`).

## Uso
Os arquivos podem ser importados para qualquer banco de dados relacional para análise e visualização.
