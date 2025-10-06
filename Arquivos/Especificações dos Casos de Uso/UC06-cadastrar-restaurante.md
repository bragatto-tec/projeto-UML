## UC06 - Cadastrar Restaurante

**Identificador:** UC06  
**Nome:** Cadastrar Restaurante  
**Atores:** Restaurante  

### Fluxo Principal
| Ações do Ator | Ações do Sistema |
|---------------|------------------|
| 1. O Restaurante acessa "Cadastrar Restaurante" | |
| | 2. O Sistema apresenta formulário com dados: endereço, contato, tipo de culinária, capacidade |
| 3. O Restaurante preenche informações solicitadas | |
| | 4. O Sistema valida os dados |
| | 5. O Sistema registra o restaurante na base de dados |
| | 6. O Sistema gera credenciais de acesso |
| | 7. O Sistema confirma cadastro realizado |

### Fluxo Alternativo 1: Dados empresariais inválidos
| Ações do Ator | Ações do Sistema |
|---------------|------------------|
| | 4.1. O Sistema identifica dados inconsistentes |
| | 4.2. O Sistema apresenta mensagem especificando erros |
| 4.3. O Restaurante corrige informações | |
| | 4.4. O Sistema volta ao passo 4 do fluxo principal |

