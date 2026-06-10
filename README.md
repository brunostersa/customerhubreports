# Customer Hub Reports

Hub estático de relatórios de performance por cliente (PSA Palestras / clientes de gestão de tráfego).

## Estrutura

```
index.html              ← página inicial com lista de clientes
clientes/
  busta-amaral/
    index.html          ← relatório Busta & Amaral Advogados (Jan–Jun/2026)
```

## Adicionar um novo cliente

1. Crie a pasta `clientes/<nome-do-cliente>/`
2. Coloque o relatório como `index.html` dentro dela
3. Adicione um link para ele na lista em `index.html` da raiz

## Deploy

Site estático — basta conectar o repo ao Vercel sem configuração adicional.
