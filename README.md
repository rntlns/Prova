# Prova
Código Da Prova

Este projeto foi desenvolvido em Python para auxiliar no controle de atendimento de uma barbearia.

O sistema permite cadastrar clientes, organizar uma fila de espera, registrar os serviços escolhidos, realizar atendimentos e gerar relatórios de faturamento.
- Como o sistema funciona

- Cadastro de clientes

O cliente informa seu nome e escolhe um ou mais serviços disponíveis.

Após o cadastro, ele é adicionado ao final da fila de espera junto com o horário de entrada.

- Fila de espera

A fila funciona por ordem de chegada.

O primeiro cliente que entra na fila é o primeiro que será atendido.

- Atendimento

Ao selecionar a opção de atendimento, o sistema mostra o próximo cliente da fila e os serviços escolhidos.

Quando o atendimento é finalizado:

* O valor total é calculado.
* O faturamento é atualizado.
* O cliente é removido da fila.
* O cliente é registrado como atendido.

- Relatórios

O sistema gera um relatório contendo:

* Total de clientes atendidos.
* Quantidade de cada serviço realizado.
* Faturamento por serviço.
* Valor total arrecadado pela barbearia.

- Estruturas utilizadas

Durante o desenvolvimento foram utilizados:

* Listas para armazenar a fila e os atendimentos.
* Dicionários para armazenar serviços, preços e faturamento.
* Estruturas de repetição (`while` e `for`).
* Estruturas condicionais (`if`, `elif` e `else`).
* Tratamento de erros com `try` e `except`.

* PROVA FEITA EM DUPLA POR: RENATA LINS MARINHO DOS SANTOS E GABRIELA ARAUJO

- Objetivo

O objetivo do projeto foi praticar conceitos básicos da linguagem Python, como manipulação de listas, dicionários, laços de repetição e estruturas condicionais, aplicando-os em uma situação real de gerenciamento de clientes.
