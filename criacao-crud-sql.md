# Comandos SQL - Para CRUD (Referência)

## Resumo
C -> Create (Insere dados)
R -> Read (Ler dados)
U -> Update (Atualizar dados)
D -> Delete (Deletar dados)

<!-- ____________________________ -->

## Insert
## Fabricantes

```sql
INSERT INTO fabricantes (nome) VALUES('Alus');
INSERT INTO fabricantes (nome) VALUES('Dell');
INSERT INTO fabricantes (nome)
VALUES ('Apple'),('LG'),('Samsung'),('Brastemp');

```

<!-- ____________________________ -->

## Insert
## Produtos

```sql
INSERT INTO produtos (nome, descricao, preco, quantidade, fabricante_id) VALUES(
'Ultrabook',
'Ultrabook Asus Intel Core i9',
6500.99,
7,
1
);
INSERT INTO produtos (nome, descricao, preco, quantidade, fabricante_id) VALUES(
'Geladeira',
'FrostFree com acesso a internet',
8500.99,
10,
6 -- Brastemp
);
INSERT INTO produtos (nome, descricao, preco, quantidade, fabricante_id) VALUES(
'Tablet Android',
'Tablet 10 polegadas com 250gb de armazenamento',
4999,
3,
5 -- Samsung
);
INSERT INTO produtos (nome, descricao, preco, quantidade, fabricante_id) VALUES(
'Iphone 14 Pro Max',
'Processador Bionic 15 com 512gb de armazenamento',
9999.97,
3,
3 -- Apple
);
INSERT INTO produtos (nome, descricao, preco, quantidade, fabricante_id) VALUES(
'Ipad mini',
'Tablet com tela de retina 4k com 512gb de armazenamento',
5000,
3,
3 -- Apple
);

```

<!-- ____________________________________________________________________ -->

## Insert
## Fabricantes

```sql

INSERT INTO fabricantes (nome)
VALUES('Positivo'),('Microsoft');


```

<!-- ____________________________________________________________________ -->

## Insert
## Produtos

```sql

INSERT INTO produtos (nome, descricao, preco, quantidade, fabricante_id) VALUES(
'Xbox',
'Console de última geração...',
2500,
6,
8
);
INSERT INTO produtos (nome, descricao, preco, quantidade, fabricante_id) VALUES(
'Ultrabook',
'AMD Ryzen 5 16gb RAM...',
4500.97,
12,
7
);


```
