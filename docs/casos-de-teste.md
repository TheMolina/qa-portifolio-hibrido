# Casos de Teste – SauceDemo

| ID | Título | Pré-condição | Passos | Resultado Esperado | Tipo |
|----|-------|--------------|--------|-------------------|------|
| CT-001 | Login com credenciais válidas | Usuário na tela de login | 
1. Informar username válido  
2. Informar senha válida  
3. Clicar em Login | 
Usuário deve ser redirecionado para a tela de produtos | Funcional |
| CT-002 | Login com senha inválida | Usuário na tela de login | 
1. Informar username válido  
2. Informar senha inválida  
3. Clicar em Login | 
Sistema deve exibir mensagem de erro | Negativo |
| CT-003 | Exibir lista de produtos | Usuário autenticado | 
1. Acessar página inicial | 
Lista de produtos deve ser exibida corretamente | Funcional |
| CT-004 | Ordenar produtos por preço | Usuário autenticado | 
1. Selecionar ordenação por preço | 
Produtos devem ser ordenados corretamente | Funcional |
| CT-005 | Adicionar produto ao carrinho | Usuário autenticado | 
1. Clicar em "Add to cart" | 
Produto deve ser adicionado ao carrinho | Funcional |
| CT-006 | Remover produto do carrinho | Produto no carrinho | 
1. Acessar carrinho  
2. Remover produto | 
Produto deve ser removido do carrinho | Funcional |
| CT-007 | Finalizar checkout com dados válidos | Produto no carrinho | 
1. Iniciar checkout  
2. Preencher dados obrigatórios  
3. Finalizar | 
Checkout deve ser concluído com sucesso | Funcional |
| CT-008 | Checkout sem preencher dados obrigatórios | Produto no carrinho | 
1. Iniciar checkout  
2. Não preencher dados  
3. Continuar | 
Sistema deve exibir mensagem de erro | Negativo |
