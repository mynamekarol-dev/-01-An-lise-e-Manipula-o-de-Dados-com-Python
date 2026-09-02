# Store 1 — Análise e Manipulação de Dados com Python

## 📌 Sobre o projeto

Este projeto foi desenvolvido durante a formação em Análise de Dados da TripleTen.

O objetivo foi trabalhar com dados de clientes de uma empresa fictícia de comércio eletrônico, a **Store 1**, utilizando Python para realizar tarefas de manipulação, transformação e análise de dados.

Durante o projeto, foram trabalhados conceitos fundamentais da linguagem Python e algumas técnicas importantes para quem está começando na área de dados.

## 🎯 Objetivos

* Identificar problemas na qualidade dos dados;
* Corrigir e transformar informações;
* Trabalhar com strings e listas;
* Converter tipos de dados;
* Utilizar estruturas condicionais;
* Trabalhar com ciclos `for` e `while`;
* Utilizar tratamento de erros com `try/except`;
* Calcular valores utilizando funções como `sum()`, `min()` e `max()`;
* Trabalhar com listas aninhadas;
* Filtrar informações de usuários;
* Realizar cálculos a partir de dados de clientes.

## 🛠️ Tecnologias e ferramentas

* Python
* Jupyter Notebook
* Git e GitHub

## 📚 Principais conceitos praticados

### Manipulação de strings

Foram utilizados métodos como:

* `strip()`
* `replace()`
* `split()`
* `lower()`

Esses métodos foram utilizados para limpar e padronizar informações dos usuários.

### Conversão de tipos

Foi praticada a conversão de dados utilizando, por exemplo:

```python
int()
```

Também foi utilizado o tratamento de exceções com:

```python
try:
    ...
except ValueError:
    ...
```

### Listas e List Comprehension

O projeto trabalhou com listas simples e listas aninhadas, além de **list comprehensions** para transformar os dados de forma mais eficiente.

Exemplo:

```python
fav_categories_low = [cat.lower() for cat in fav_categories]
```

### Estruturas de repetição

Foram utilizados:

* `for`
* `while`

Essas estruturas permitiram percorrer informações dos usuários e simular novas compras.

### Condições

Também foram utilizadas estruturas condicionais com `if` para encontrar usuários de acordo com critérios específicos, como idade, categoria de compra e valor total gasto.

### Funções para cálculos

Foram utilizadas funções como:

```python
sum()
max()
min()
```

para calcular valores totais, máximos e mínimos de gastos.

## 📊 Principais análises realizadas

Durante o projeto foram realizadas análises como:

* Cálculo da receita total da empresa;
* Identificação de clientes com menos de 30 anos;
* Identificação de clientes com menos de 30 anos e gastos superiores a US$ 1.000;
* Identificação de clientes que compraram roupas;
* Cálculo dos valores totais, mínimos e máximos gastos por categoria;
* Padronização das categorias favoritas dos usuários.

## 💡 Aprendizados

Este projeto foi importante para desenvolver minha base em Python e entender como a programação pode ser utilizada para trabalhar com dados.

Também pude praticar a identificação e correção de problemas de qualidade dos dados, além de aprender a utilizar estruturas de repetição, condições, listas e tratamento de erros.

Um dos principais aprendizados foi perceber que, na análise de dados, é importante não apenas executar o código, mas também entender a estrutura e a qualidade das informações antes de utilizá-las em uma análise.

## 🚀 Próximos passos

Pretendo continuar desenvolvendo meus conhecimentos em Python e avançar para projetos envolvendo:

* Pandas;
* NumPy;
* Análise exploratória de dados;
* Visualização de dados;
* SQL;
* Projetos mais completos de análise de dados.

## 📝 Observação

Este projeto faz parte da minha jornada de aprendizado em Análise de Dados e representa uma etapa inicial dos meus estudos em Python.
