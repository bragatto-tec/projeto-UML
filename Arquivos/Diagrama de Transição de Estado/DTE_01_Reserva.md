# DTE 01 - Ciclo de Vida da Reserva
```mermaid
@startuml
title Diagrama de Transição de Estado - Reserva (Entidade)

[*] -down-> Pendente : Cliente faz reserva (UC04)

Pendente -right-> Confirmada : Restaurante aceita (UC08)
Pendente -down-> Recusada : Restaurante recusa (UC08)
Pendente -down-> Cancelada : Cliente cancela (UC05)

Confirmada -down-> Concluída : Data/hora da reserva ultrapassada
Confirmada -left-> Pendente : Cliente modifica (UC05)
Confirmada -down-> Cancelada : Cliente cancela (UC05)

Recusada -down-> [*] : Fim (Histórico)
Cancelada -down-> [*] : Fim (Histórico)
Concluída -down-> [*] : Fim (Histórico)

@enduml
```
