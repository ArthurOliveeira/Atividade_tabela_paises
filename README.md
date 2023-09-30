# Atividade_tabela_paises

## Questão 01
```sql
select * from tabela_paises;
```
## resultado esperado:
![Captura de Tela (3)](https://github.com/ArthurOliveeira/Atividade_tabela_paises/assets/117039722/e29f5c7b-1ec0-4222-b0ae-0642be634fc2)

## Questão 02
```sql
select cidade from tabela_paises where pais = 'Brazil';
```
## resultado esperado:
![Captura de Tela (2)](https://github.com/ArthurOliveeira/Atividade_tabela_paises/assets/117039722/d14ee77d-abf2-44ab-8efb-2065e44fa6a9)

## Questão 03
```sql
select cidade from tabela_paises where regiao = 'Ceará';
```
## resultado esperado:
![Captura de Tela (5)](https://github.com/ArthurOliveeira/Atividade_tabela_paises/assets/117039722/a2445003-494e-4a79-9b7d-868bef0997bc)

## Questão 04
```sql
select regiao, count(regiao) from tabela_paises where pais = 'China' group by regiao;
```
## resultado esperado:
![Captura de Tela (7)](https://github.com/ArthurOliveeira/Atividade_tabela_paises/assets/117039722/458acc9e-0b89-475f-b066-8d89e020e203)

## Questão 05
```sql
select regiao, count(distinct regiao) from tabela_paises where pais = 'Canada' group by regiao;
```
## resultado esperado:
![Captura de Tela (8)](https://github.com/ArthurOliveeira/Atividade_tabela_paises/assets/117039722/45fbcc2c-6276-4b58-aba3-c66c57e2286f)

## Questão 06
```sql
select pais, count(distinct pais) from tabela_paises group by pais;
```
## resultado esperado:
![Captura de Tela (9)](https://github.com/ArthurOliveeira/Atividade_tabela_paises/assets/117039722/b752a4b8-6441-49be-adb4-df44cdb013c7)

## Questão 07
```sql
select cidade, count(distinct cidade) from tabela_paises where pais = 'Canada' group by cidade;
```
## resultado esperado:
![Captura de Tela (10)](https://github.com/ArthurOliveeira/Atividade_tabela_paises/assets/117039722/7495700e-b834-4782-98a8-29bf05a37f4f)

## Questão 08
```sql
select pais, count(regiao) from tabela_paises group by pais;
```
## resultado esperado:
![Captura de Tela (11)](https://github.com/ArthurOliveeira/Atividade_tabela_paises/assets/117039722/f3e0fdd0-6c26-4e61-894d-f3dd9d05be62)

## Questão 09
```sql
select count(nome) as quant_João from tabela_paises where nome like 'João%';
```
## resultado esperado:
![Captura de Tela (14)](https://github.com/ArthurOliveeira/Atividade_tabela_paises/assets/117039722/8b5230b6-58b0-4cf4-8a43-9af06e9d22f5)

## Questão 10
```sql
select nome from tabela_paises where nome like 'John%' group by nome;
```
## resultado esperado:
![Captura de Tela (15)](https://github.com/ArthurOliveeira/Atividade_tabela_paises/assets/117039722/386990ad-a480-41ea-9446-1e5ee64f41c4)

## Questão 11
```sql
select pais from tabela_paises group by pais order by pais asc;
```
## resultado esperado:
![Captura de Tela (16)](https://github.com/ArthurOliveeira/Atividade_tabela_paises/assets/117039722/e93718af-398d-44a3-92e0-1f3bd629cc80)














