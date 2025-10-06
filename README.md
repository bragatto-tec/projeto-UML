# 🍽️ Reserva Gourmet - Sistema de Reservas de Restaurantes

<div align="center">

![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)
![PlantUML](https://img.shields.io/badge/PlantUML-0080FF?style=for-the-badge&logo=plantuml&logoColor=white)
![Mermaid](https://img.shields.io/badge/Mermaid-FF3670?style=for-the-badge&logo=mermaid&logoColor=white)
![UML](https://img.shields.io/badge/UML-FABD14?style=for-the-badge&logo=uml&logoColor=white)
![Status](https://img.shields.io/badge/Status-Em_Desenvolvimento-yellow?style=for-the-badge)

**Sistema de reservas online que conecta clientes e restaurantes de forma prática e eficiente!**

</div>

---

## 📌 Sobre o Projeto

O **Reserva Gourmet** é uma plataforma web que facilita a conexão entre clientes que desejam fazer reservas em restaurantes e estabelecimentos que precisam gerenciar sua disponibilidade de mesas. O sistema oferece uma solução completa para otimizar o processo de reservas, reduzir mesas vazias e melhorar a experiência gastronômica.

## 🎯 Objetivos

### Objetivo Geral
Otimizar o processo de reserva para clientes e melhorar a gestão de mesas para os restaurantes.

### Objetivos Específicos
- **Reduzir o tempo** gasto pelos clientes para encontrar e reservar mesas
- **Minimizar o risco** de mesas vazias ou overbooking nos restaurantes
- **Centralizar informações** sobre estabelecimentos gastronômicos
- **Facilitar a comunicação** entre clientes e restaurantes
- **Automatizar processos** de reserva e confirmação

## ✨ Funcionalidades Principais

### Para Clientes
- Busca de restaurantes por diversos critérios (localização, tipo de cozinha, avaliação)
- Visualização de informações detalhadas dos estabelecimentos
- Consulta de cardápios e preços
- Realização de reservas online com seleção de data, hora e número de pessoas
- Gerenciamento de reservas pessoais (visualizar, cancelar, reagendar)
- Sistema de avaliações e comentários sobre restaurantes

### Para Restaurantes
- Cadastro completo do estabelecimento com fotos e descrição
- Configuração de disponibilidade de mesas por capacidade
- Gerenciamento de horários de funcionamento
- Controle de reservas recebidas com status (pendente, confirmada, cancelada)
- Atualização e gerenciamento de cardápio online
- Painel de controle com estatísticas de reservas

## 🏗️ Modelagem UML

### Diagrama de Casos de Uso

O diagrama de casos de uso apresenta as interações entre os atores (Cliente e Restaurante) e o sistema:

**Principais Casos de Uso:**

**Clientes:**
- UC01: Cadastrar-se
- UC02: Fazer Login
- UC03: Buscar Restaurantes
- UC04: Fazer Reserva
- UC05: Gerenciar Reservas

**Restaurantes:**
- UC06: Cadastrar Restaurante
- UC02: Fazer Login (compartilhado)
- UC07: Gerenciar Disponibilidade
- UC08: Gerenciar Reservas Recebidas
- UC09: Gerenciar Cardápio

**Casos de Uso de Suporte:**
- UC10: Validar Dados (include)
- UC11: Enviar Notificação (include)

### Diagrama de Classes

O diagrama de classes modela a estrutura do sistema com 10 entidades principais:

**Entidades Principais:**

1. **Cliente**
   - Atributos: idCliente, nome, email, telefone, senha, dataCadastro
   - Métodos: cadastrar(), fazerLogin(), fazerReserva(), cancelarReserva(), avaliarRestaurante()

2. **Restaurante**
   - Atributos: idRestaurante, nome, telefone, email, tipoCozinha, descrição, avaliacaoMedia
   - Métodos: cadastrar(), atualizarPerfil(), verificarDisponibilidade(), receberReserva()

3. **Reserva**
   - Atributos: idReserva, data, hora, quantidadePessoas, status, observações, dataReserva
   - Métodos: confirmar(), cancelar()

4. **Mesa**
   - Atributos: idMesa, numero, capacidade

5. **Cardápio e ItemCardapio**
   - Gerenciamento completo do menu do restaurante

6. **Avaliação**
   - Sistema de feedback dos clientes

7. **Notificação**
   - Comunicação automatizada com clientes e restaurantes

**Relacionamentos:**
- Cliente faz Reservas (1:N)
- Cliente escreve Avaliações (1:N)
- Restaurante recebe Reservas (1:N)
- Restaurante possui Endereço (1:1)
- Restaurante possui Mesas (1:N)
- Reserva está vinculada a uma Mesa (1:1)

## 🛠️ Tecnologias Utilizadas

### Ferramentas de Modelagem

#### Git & GitHub
- **Controle de Versão**: Gerenciamento de código e documentação
- **Colaboração**: Trabalho em equipe com branches e pull requests
- **Histórico**: Rastreamento de mudanças no projeto
- **GitHub**: Hospedagem do repositório e diagramas

#### PlantUML (.puml)
- **Diagramas UML**: Criação de diagramas através de código
- **Formato Textual**: Arquivos `.puml` versionáveis
- **Diagramas Suportados**:
  - Diagrama de Classes
  - Diagrama de Casos de Uso
  - Diagrama de Sequência
  - Diagrama de Atividades
- **Vantagens**: 
  - Fácil manutenção
  - Integração com Git
  - Geração automática de imagens
