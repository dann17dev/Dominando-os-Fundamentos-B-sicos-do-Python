# Desafio: Recomendação de Plano de Internet

## Descrição

Este projeto foi desenvolvido para uma empresa de telecomunicações que deseja oferecer uma solução que recomenda o plano de internet ideal para seus clientes, com base no consumo mensal de dados. A aplicação solicita ao cliente que insira o consumo médio de dados e, de acordo com o valor informado, retorna o plano adequado utilizando uma função em Python com estruturas condicionais.

## Planos Oferecidos

- **Plano Essencial Fibra - 50Mbps**: Recomendado para um consumo médio de até 10 GB.
- **Plano Prata Fibra - 100Mbps**: Recomendado para um consumo médio acima de 10 GB até 20 GB.
- **Plano Premium Fibra - 300Mbps**: Recomendado para um consumo médio acima de 20 GB.

## Requisitos

- O usuário deve informar o consumo médio mensal de dados em formato `float`.
- O programa deve verificar o consumo e retornar o plano adequado com base na seguinte lógica:
  - Até 10 GB: **Plano Essencial Fibra - 50Mbps**
  - Acima de 10 GB e até 20 GB: **Plano Prata Fibra - 100Mbps**
  - Acima de 20 GB: **Plano Premium Fibra - 300Mbps**

## Exemplo de Entrada e Saída

### Entrada 1
