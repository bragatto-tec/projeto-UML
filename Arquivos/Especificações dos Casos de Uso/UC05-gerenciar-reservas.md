## UC05 - Gerenciar Reservas

**Identificador:** UC05  
**Nome:** Gerenciar Reservas  
**Atores:** Cliente  

### Fluxo Principal
| Ações do Ator | Ações do Sistema |
|---------------|------------------|
| 1. O Cliente acessa "Minhas Reservas" | |
| | 2. O Sistema mostra lista de reservas ativas e no histórico |
| 3. O Cliente seleciona uma reserva específica | |
| | 4. O Sistema apresenta detalhes da reserva e opções: visualizar, modificar, cancelar |
| 5. O Cliente escolhe ação desejada | |
| | 6. O Sistema executa a ação selecionada |

### Fluxo Alternativo 1: Modificar reserva
| Ações do Ator | Ações do Sistema |
|---------------|------------------|
| | 5.1. O Sistema apresenta formulário para alteração de data/horário/pessoas |
| 5.2. O Cliente altera dados | |
| | 5.3. O Sistema verifica nova disponibilidade |
| | 5.4. O Sistema atualiza a reserva se disponível |

### Fluxo Alternativo 2: Cancelar reserva
| Ações do Ator | Ações do Sistema |
|---------------|------------------|
| | 5.1. O Sistema apresenta confirmação de cancelamento |
| 5.2. O Cliente confirma o cancelamento | |
| | 5.3. O Sistema remove a reserva da base de dados |
| | 5.4. O Sistema confirma cancelamento realizado |

