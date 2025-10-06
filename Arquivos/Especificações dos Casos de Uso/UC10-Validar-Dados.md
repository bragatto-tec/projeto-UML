## UC10 - Validar Dados

**Identificador:** UC10  
**Nome:** Validar Dados  
**Atores:** Sistema (interno)  

### Fluxo Principal
| Ações do Ator | Ações do Sistema |
|---------------|------------------|
| | 1. O Sistema recebe os dados fornecidos pelo Cliente ou Restaurante |
| | 2. O Sistema verifica se todos os campos obrigatórios foram preenchidos |
| | 3. O Sistema valida o formato dos dados (ex.: e-mail válido, CPF/CNPJ, número de telefone, valores numéricos) |
| | 4. O Sistema consulta a base de dados para verificar consistência (ex.: usuário já cadastrado, reserva existente) |
| | 5. O Sistema retorna o resultado da validação para o caso de uso que o incluiu |

### Fluxo Alternativo 1: Dados ausentes ou inválidos
| Ações do Ator | Ações do Sistema |
|---------------|------------------|
| | 2.1. O Sistema identifica que há campos obrigatórios ausentes ou inválidos |
| | 2.2. O Sistema gera mensagem de erro informando a inconsistência |
| | 2.3. O Sistema retorna a falha ao caso de uso que o incluiu |

### Fluxo Alternativo 2: Dados duplicados ou inconsistentes
| Ações do Ator | Ações do Sistema |
|---------------|------------------|
| | 4.1. O Sistema identifica que já existe um registro igual na base de dados |
| | 4.2. O Sistema apresenta mensagem de erro sobre duplicidade ou inconsistência |
| | 4.3. O Sistema retorna a falha ao caso de uso que o incluiu |


