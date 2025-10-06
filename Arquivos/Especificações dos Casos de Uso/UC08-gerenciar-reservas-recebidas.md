## UC08 - Gerenciar Reservas Recebidas

**Identificador:** UC08  
**Nome:** Gerenciar Reservas Recebidas  
**Atores:** Restaurante  

### Fluxo Principal
| Ações do Ator | Ações do Sistema |
|---------------|------------------|
| 1. O Restaurante acessa a opção "Reservas Recebidas" | |
| | 2. O Sistema apresenta a lista de reservas pendentes |
| 3. O Restaurante seleciona uma reserva | |
| | 4. O Sistema exibe os detalhes da reserva |
| 5. O Restaurante escolhe uma ação (aceitar, recusar ou solicitar alteração) | |
| | 6. O Sistema registra a ação |
| | 7. O Sistema ajusta a disponibilidade do restaurante conforme a decisão (inclui: Gerenciar Disponibilidade) |
| | 8. O Sistema envia notificação ao Cliente sobre a decisão (inclui: Enviar Notificação) |

### Fluxo Alternativo 1: Nenhuma reserva recebida
| Ações do Ator | Ações do Sistema |
|---------------|------------------|
| | 2.1. O Sistema identifica que não há reservas recebidas |
| | 2.2. O Sistema apresenta a mensagem "Nenhuma reserva recebida no momento" |

### Fluxo Alternativo 2: Reserva aceita
| Ações do Ator | Ações do Sistema |
|---------------|------------------|
| 5.1. O Restaurante confirma a ação sobre a reserva (aceita) | |
| | 6.1. O Sistema registra a ação |
| | 6.2. O Sistema apresenta mensagem de confirmação ao restaurante|
| | 6.3. O Sistema retorna ao cliente que sua reserva foi aceita (inclui: Enviar Notificação)|

### Fluxo Alternativo 3: Reserva recusada
| Ações do Ator | Ações do Sistema |
|---------------|------------------|
| 5.1. O Restaurante confirma a ação sobre a reserva (recusado) | |
| | 6.1. O Sistema registra a ação |
| | 6.2. O Sistema apresenta mensagem de confirmação ao restaurante|
| | 6.3. O Sistema retorna ao cliente que sua reserva foi recusada (inclui: Enviar Notificação)|

