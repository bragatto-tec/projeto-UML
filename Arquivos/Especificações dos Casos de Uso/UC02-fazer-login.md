## UC02 - Fazer Login

**Identificador:** UC02  
**Nome:** Fazer Login  
**Atores:** Cliente  

### Fluxo Principal
| Ações do Ator | Ações do Sistema |
|---------------|------------------|
| 1. O Cliente acessa a opção "Fazer Login" | |
| | 2. O Sistema apresenta campos para email e senha |
| 3. O Cliente insere suas credenciais | |
| | 4. O Sistema valida as credenciais na base de dados |
| | 5. O Sistema valida o usuário |
| | 6. O Sistema redireciona para área logada |

### Fluxo Alternativo 1: Credenciais incorretas
| Ações do Ator | Ações do Sistema |
|---------------|------------------|
| | 4.1. O Sistema identifica credenciais incorretas |
| | 4.2. O Sistema apresenta mensagem de erro |
| 4.3. O Cliente corrige as credenciais | |
| | 4.4. O Sistema volta ao passo 4 do fluxo principal |

