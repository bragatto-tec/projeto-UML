## UC03 - Buscar Restaurantes

**Identificador:** UC03  
**Nome:** Buscar Restaurantes  
**Atores:** Cliente  

### Fluxo Principal
| Ações do Ator | Ações do Sistema |
|---------------|------------------|
| 1. O Cliente acessa a funcionalidade "Buscar Restaurantes" | |
| | 2. O Sistema apresenta tela com filtros: localização, culinária, preço e disponibilidade |
| 3. O Cliente define critérios de busca desejados | |
| | 4. O Sistema processa a consulta na base de dados |
| | 5. O Sistema exibe lista de restaurantes que atendem aos critérios |
| 6. O Cliente vê os resultados | |

### Fluxo Alternativo 1: Nenhum restaurante encontrado
| Ações do Ator | Ações do Sistema |
|---------------|------------------|
| | 5.1. O Sistema verifica que não há restaurantes que atendam aos critérios |
| | 5.2. O Sistema mostra mensagem "Nenhum restaurante encontrado" |

