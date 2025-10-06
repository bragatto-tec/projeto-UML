UC11 - Enviar-Notificação

**Identificador:** UC11  
**Nome:** Enviar-Notificação  
**Atores:** Sistema 

 ### Fluxo Principal
| Ações do Ator | Ações do Sistema |
|---------------|------------------|
| | 1. O Sistema identifica evento que requer notificação|
| | 2. O Sistema seleciona template de notificação apropriado |
| | 3. O Sistema personaliza mensagem com dados específicos |
| | 4. O Sistema envia notificação por canal preferido do usuário |
| | 5. O Sistema registra o envio da notificação |

 ### Fluxo Alternativo 1:  Notificação de Confirmação de Reserva
| Ações do Ator | Ações do Sistema |
|---------------|------------------|
| | 1.1. Após confirmação de reserva bem-sucedida |
| | 2.1. O Sistema utiliza template "Confirmação de Reserva"|
| | 3.1. O Sistema inclui dados da reserva (data, hora, restaurante)|
| | 4.1. O Sistema envia email e/ou SMS |

### Fluxo Alternativo 2: Notificação de Lembrete
| Ações do Ator | Ações do Sistema |
|---------------|------------------|
| | 1.2. 24 horas antes da reserva|
| | 2.2. O Sistema inclui detalhes da reserva e opções de cancelamento|
| | 3.2. O Sistema envia notificação email |

### Fluxo Alternativo 3:  Notificação de Alteração
| Ações do Ator | Ações do Sistema |
|---------------|------------------|
| | 1.3. Quando restaurante altera disponibilidade|
| | 2.3. O Sistema informa sobre a alteração e novas opções|
| | 3.3. O Sistema envia notificação para usuários afetados |

