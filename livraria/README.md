# Livraria - Script SQL (SQLite)

Arquivos:
- `schema.sql`: criação da tabela `livros`, carga inicial e consultas de verificação.
- `livraria.db`: banco SQLite já gerado a partir do script.

## Como executar
Pelo terminal do VS Code (com sqlite3 instalado):

    sqlite3 livraria.db < schema.sql

Ou use a extensão SQLite (alexcvzz.vscode-sqlite): abra `livraria.db`
com "SQLite: Open Database" e execute as consultas de `schema.sql`.
