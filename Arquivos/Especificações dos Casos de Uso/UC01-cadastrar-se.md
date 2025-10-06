UC01 - Cadastrar-se

**Identificador:** UC01  
**Nome:** Cadastrar-se  
**Atores:** Cliente  


 ### Fluxo Principal
| Ações do Ator | Ações do Sistema |
|---------------|------------------|
| 1. O Cliente vai ao botão "Cadastrar-se" | |
| | 2. O Sistema apresenta formulário com campos: nome, email, telefone e senha |
| 3. O Cliente preenche os dados | |
| | 4. O Sistema executa a operação de validação |
| | 5. O Sistema adiciona o cliente na base de dados |
| | 6. O Sistema apresenta mensagem de confirmação de cadastro |

 ### Fluxo Alternativo 1: Dados não corretos ou incompletos
| Ações do Ator | Ações do Sistema |
|---------------|------------------|
| | 4.1. O Sistema identifica dados inválidos ou campos obrigatórios não preenchidos |
| | 4.2. O Sistema apresenta mensagem de erro especificando os problemas encontrados |
| 4.3. O Cliente corrige os dados | |
| | 4.4. O Sistema volta ao passo 4 do fluxo principal |


