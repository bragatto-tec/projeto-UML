## UC09 - Gerenciar Cardápio

**Identificador:** UC09  
**Nome:** Gerenciar Cardápio  
**Atores:** Restaurante  

### Fluxo Principal
| Ações do Ator | Ações do Sistema |
|---------------|------------------|
| 1. O Restaurante acessa a opção "Gerenciar Cardápio" | |
| | 2. O Sistema apresenta o cardápio atual cadastrado |
| 3. O Restaurante escolhe uma ação (adicionar, editar ou remover item) | |
| | 4. O Sistema exibe o formulário correspondente à ação |
| 5. O Restaurante insere ou altera as informações do item (nome, descrição, preço, categoria) | |
| | 6. O Sistema valida os dados informados |
| | 7. O Sistema atualiza o cardápio na base de dados informados|
| | 8. O Sistema confirma a atualização realizada com sucesso |

### Fluxo Alternativo 1: Dados inválidos
| Ações do Ator | Ações do Sistema |
|---------------|------------------|
| 5.1. O Restaurante insere informações incompletas ou inválidas | |
| | 6.1. O Sistema identifica inconsistências nos dados |
| | 6.2. O Sistema apresenta mensagem de erro solicitando correção |
| | 6.3. O Sistema retorna ao passo 5 do fluxo principal |

