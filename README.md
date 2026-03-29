# fiap-labs-reservation

# Descrição do Problema
Alunos da FIAP têm dificuldade em encontrar e reservar espaços de estudo disponíveis (salas e laboratórios).
O uso de laboratórios precisa ser organizado para evitar conflitos de horário, sobreposição de reservas e falta de controle sobre quem está utilizando os recursos.

Muitas instituições ainda utilizam processos manuais ou pouco eficientes, o que pode gerar:

- Encontrar salas livres
- Organizar grupos de estudo
- Evitar conflitos de horários

# Solução Proposta
Este projeto propõe um sistema simples e eficiente de reserva de salas e laboratórios, permitindo que usuários realizem:
- Login no sistema
- Criação de reservas
- Visualização de reservas pessoais
- Cancelamento de reservas específicas
- O sistema garante validações importantes, como:
- Verificação de login obrigatório
- Validação de datas
- Bloqueio de conflitos de horário

# Tecnologias
- Python
- JSON
- Bibliotecas padrão: json e datetime

# Como Executar
python main.py

# Estrutura
- main.py
- reservas.json

# Funcionalidades
1 - Autenticação
- Login com nome, usuário e senha
- Controle de sessão do usuário

2 - Reserva de Laboratórios
- Criação de reservas
- Validação de formato de data (DD/MM/AAAA)
- Verificação de conflitos (mesmo lab, data e horário)

3 - Consulta de Reservas
- Listagem das reservas do usuário logado

4 - Cancelamento
- Cancelamento de reserva específica
- Confirmação antes da exclusão

5 - Persistência de Dados
- Armazenamento em arquivo reservas.json

# Demonstração
https://youtu.be/u_TFjun9e1M

## 👨‍💻 Integrantes
- Raissa Yukari Senoi - RM: 558120 - 3ECR

## 🔗 Links
- Miro:
- GitHub: https://github.com/Yukari1907/fiap-labs-reservation.git
