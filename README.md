# ✈️ Sistema de Monitoramento de Segurança de um Avião

[cite_start]**Projeto de Internet das Coisas (IoT)**   
[cite_start]**Curso:** Engenharia de Computação   
[cite_start]**Instituição:** Pontifícia Universidade Católica de Minas Gerais (PUC Minas) [cite: 1]  
[cite_start]**Professor:** Júlio Conway 

---

## 🎯 1. Objetivos

[cite_start]Este projeto propõe um protótipo de um sistema de monitoramento de segurança interno para aeronaves[cite: 6, 21]. [cite_start]A principal motivação é aplicar os conceitos de IoT para desenvolver um modelo funcional que resolva problemas do mundo real [cite: 24][cite_start], focando em um sistema crítico para a segurança e preservação de veículos aéreos[cite: 21].

## 🛠️ 2. Funcionalidades e Componentes

[cite_start]O sistema utiliza módulos ESP-32 ou Arduino  para gerenciar diversos sensores e atuadores.

### [cite_start]Sensores (Monitoramento) [cite: 7]
* [cite_start]**Despressurização:** Módulo Sensor Barométrico Digital 0-40KPa[cite: 8, 28].
* [cite_start]**Detecção de Incêndio:** Sensor de Temperatura LM35DZ[cite: 9, 29].
* [cite_start]**Peso/Turbulência:** Célula de Carga 5Kg (Sensor de Peso)[cite: 10, 30].

### [cite_start]Atuadores (Ações de Emergência) [cite: 11]
* [cite_start]**Portas de Emergência:** Modelo em papelão e palitos, controladas por Micro Servo 9g SG90[cite: 12, 32].
* [cite_start]**Luzes de Emergência:** LEDs[cite: 13, 31].
* [cite_start]**Sirene de Emergência:** Buzzer[cite: 14, 31].
* [cite_start]**Exaustor de Fumaça:** Motor de corrente contínua[cite: 15, 32].

### [cite_start]Conectividade e Visualização [cite: 16]
* [cite_start]Monitoramento da pressão interna[cite: 17].
* [cite_start]Monitoramento de incêndio[cite: 18].
* [cite_start]Controle (Abrir/Fechar) das portas de emergência via celular[cite: 19].
* [cite_start]**Protocolo:** MQTT[cite: 49].
* [cite_start]**Serviços:** Cloud [cite: 52][cite_start], Banco de Dados [cite: 58] [cite_start]e Aplicativo Móvel[cite: 56].

##  metodologia 3. Metodologia Ágil

[cite_start]O projeto é gerenciado utilizando **SCRUM** com o auxílio de um quadro **Kanban** (Trello)[cite: 37, 38].

* [cite_start]**Scrum Master:** Henrique Augusto Figueiredo[cite: 39, 41].

## 🗓️ 4. Cronograma (Sprints)

1.  [cite_start]**Sprints 1-2 (01/08-21/08):** Planejamento, pesquisa e testes iniciais[cite: 43].
2.  [cite_start]**Sprints 3-4 (30/08-26/09):** Montagem do Hardware e Firmware (Lógica de emergência)[cite: 46].
3.  [cite_start]**Sprint 5 (27/09-10/10):** Implementação da comunicação MQTT[cite: 49].
4.  [cite_start]**Sprint 6 (11/10-31/10):** Configuração do serviço de Nuvem[cite: 52].
5.  [cite_start]**Sprint 7 (01/11-14/11):** Desenvolvimento do App móvel e configuração do DB[cite: 56].
6.  [cite_start]**Sprint 8 (15/11-30/11):** Integração final, testes, documentação e apresentação[cite: 58].

## 🧑‍💻 5. Equipe

* [cite_start]Henrique Augusto Figueiredo (Scrum Master) [cite: 39]
* (Adicione os outros membros da equipe aqui)
