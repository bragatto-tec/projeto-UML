## UC04 - Fazer Reserva

**Identificador:** UC04  
**Nome:** Fazer Reserva  
**Atores:** Cliente  

### Fluxo Principal
| Ações do Ator | Ações do Sistema |
|---------------|------------------|
| 1. O Cliente seleciona restaurante | |
| | 2. O Sistema exibe informações do restaurante e disponibilidade de horários |
| 3. O Cliente escolhe data, horário e número de pessoas | |
| | 4. O Sistema verifica disponibilidade para as escolhas |
| | 5. O Sistema apresenta resumo da reserva |
| 6. O Cliente confirma a reserva | |
| | 7. O Sistema registra a reserva na base de dados |
| | 8. O Sistema gera código de confirmação e exibe para o cliente |

### Fluxo Alternativo 1: Horário indisponível
| Ações do Ator | Ações do Sistema |
|---------------|------------------|
| | 4.1. O Sistema identifica que não há disponibilidade no horário solicitado |
| | 4.2. O Sistema apresenta mensagem de indisponibilidade |
| | 4.3. O Sistema sugere horários próximos |
| 4.4. O Cliente seleciona outro horário ou cancela | |
| | 4.5. O Sistema volta ao passo 4 do fluxo principal (se novo horário selecionado) |


