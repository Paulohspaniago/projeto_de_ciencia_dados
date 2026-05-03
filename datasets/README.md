# datasets

Pasta destinada aos arquivos de dados do projeto.

Organizacao sugerida:

```text
datasets/
├── crimes/
├── educacao/
├── idh/
└── populacao/
```

Boas praticas:

- manter os arquivos brutos sem sobrescrever o original
- usar nomes consistentes por fonte e ano
- documentar a origem de cada arquivo na documentacao do projeto
- evitar salvar aqui arquivos finais tratados

Arquivos tratados e consolidados nao devem ser versionados nesta pasta. A fonte oficial dos dados tratados e o PostgreSQL, principalmente o schema `dw`.
