# **Projeto Conceitual de Banco de Dados para Oficina Mecânica**

## **Objetivo**
Este projeto visa criar o esquema conceitual para um sistema de controle e gerenciamento de ordens de serviço (OS) em uma oficina mecânica, com base na narrativa fornecida.

## **Narrativa**
O sistema destina-se ao controle e gerenciamento da execução de ordens de serviço em uma oficina mecânica. O fluxo de trabalho descrito é o seguinte:

### - Recepção de Veículos: 
  - Clientes levam seus veículos à oficina para consertos ou revisões periódicas.

### - Designação de Equipe: 
  - Cada veículo é atribuído a uma equipe de mecânicos, que identifica os serviços a serem executados e preenche uma ordem de serviço (OS) com a data de entrega prevista.

### - Cálculo de Custos: 
  - A partir da OS, calcula-se o valor de cada serviço, consultando-se uma tabela de referência de mão-de-obra. O valor das peças necessárias também é adicionado à OS.

### - Autorização: 
  - O cliente autoriza a execução dos serviços.

### - Execução dos Serviços: 
A mesma equipe que avaliou os serviços executa os trabalhos necessários.

## **Estrutura do Projeto**
O projeto será estruturado utilizando um modelo de entidade-relacionamento (ER), com diagramas que representem claramente as entidades, seus atributos e os relacionamentos entre elas.
