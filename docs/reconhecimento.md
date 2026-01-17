# Reconhecimento do Sistema – SauceDemo

## Visão Geral do Sistema
O sistema SauceDemo é uma aplicação web utilizada para simular um e-commerce. 
Ela permite que usuários realizem login e visualizem uma lista de produtos disponíveis para compra, além de interagir com um carrinho de compras.

O principal objetivo do sistema é permitir que o usuário navegue pelos produtos e realize um fluxo básico de compra.

---

## Funcionalidades Identificadas

### Tela de Login
- Campo de usuário (username)
- Campo de senha (password)
- Botão de login
- Mensagem de erro para credenciais inválidas

### Listagem de Produtos
- Exibição de produtos com nome, descrição e preço
- Botão "Add to cart" para cada produto
- Opção de ordenação dos produtos
- Ícone do carrinho com contador de itens

### Carrinho de Compras
- Visualização dos produtos adicionados
- Remoção de itens do carrinho
- Botão para continuar comprando
- Botão para avançar para o checkout

### Checkout
- Formulário com dados do usuário (nome, sobrenome e CEP)
- Resumo da compra
- Finalização do pedido

---

## Fluxos Principais

1. Usuário acessa a aplicação
2. Realiza login com credenciais válidas
3. Visualiza a lista de produtos
4. Adiciona produtos ao carrinho
5. Acessa o carrinho
6. Preenche os dados de checkout
7. Finaliza a compra

---

## Dados Críticos
- Credenciais de login (username e password)
- Identificação dos produtos
- Preço dos produtos
- Quantidade de itens no carrinho
- Dados do cliente no checkout

---

## Primeira Análise de Risco
- Falha no login impede o acesso ao sistema
- Erro no cálculo do valor total pode gerar inconsistência na compra
- Perda de itens do carrinho pode impactar a experiência do usuário
- Falha na finalização do checkout impede a conclusão do fluxo principal
