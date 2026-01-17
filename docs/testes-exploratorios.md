# Testes Exploratórios – SauceDemo

## Objetivo
Realizar testes exploratórios para identificar comportamentos inesperados ou possíveis falhas na aplicação.

## Escopo
- Login
- Listagem de produtos
- Carrinho
- Checkout

## Sessão 1 – Login

- Ação: tentar login sem preencher senha
- Resultado: sistema exibiu mensagem de erro
- Observação: comportamento esperado

## Sessão – Checkout sem produtos

- Ação: acessar o carrinho sem produtos e clicar em "Checkout"
- Resultado: sistema permite avançar para a tela de preenchimento de dados
- Observação: comportamento permitido pelo sistema, porém pode gerar fluxo sem sentido do ponto de vista do usuário

