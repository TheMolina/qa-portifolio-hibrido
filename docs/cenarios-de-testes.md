# Cenários de Teste – SauceDemo

## Login

### Cenário: Login com credenciais válidas
Dado que o usuário esteja na tela de login  
Quando informar credenciais válidas  
Então o sistema deve permitir o acesso à listagem de produtos  

### Cenário: Login com senha inválida
Dado que o usuário esteja na tela de login  
Quando informar uma senha inválida  
Então o sistema deve exibir uma mensagem de erro  

---

## Produtos

### Cenário: Visualizar lista de produtos
Dado que o usuário esteja autenticado  
Quando acessar a página inicial  
Então o sistema deve exibir a lista de produtos  

### Cenário: Ordenar produtos por preço
Dado que o usuário esteja na página de produtos  
Quando selecionar a opção de ordenação por preço  
Então os produtos devem ser ordenados corretamente  

---

## Carrinho

### Cenário: Adicionar produto ao carrinho
Dado que o usuário esteja autenticado  
Quando clicar em "Add to cart" em um produto  
Então o produto deve ser adicionado ao carrinho  

### Cenário: Remover produto do carrinho
Dado que o usuário esteja no carrinho  
Quando remover um produto  
Então o produto não deve mais aparecer na lista  

---

## Checkout

### Cenário: Finalizar compra com dados válidos
Dado que o usuário tenha produtos no carrinho  
Quando preencher os dados obrigatórios e finalizar  
Então o sistema deve concluir o checkout com sucesso  
