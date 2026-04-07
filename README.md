## Regras de Negócio Testadas

- Produto deve ter nome não vazio  
  Testado em `ProductServiceTest#createProduct_shouldThrowException_whenNameIsEmpty`

- Preço deve ser maior que zero  
  Testado em `ProductServiceTest#createProduct_shouldThrowException_whenPriceIsNegative`

- Quantidade não pode ser negativa  
  Testado em `ProductServiceTest#createProduct_shouldThrowException_whenQuantityIsNegative`

- Atualização só para produtos existentes  
  Testado em `ProductServiceTest#updateProduct_shouldThrowException_whenProductNotFound`
