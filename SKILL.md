---
name: macroprocesso-jornada-paciente
description: Mapeia processos hospitalares e linhas de cuidado em nível macro e alinha a jornada do paciente sobre cada macroetapa, bloqueando o detalhamento operacional de fluxogramas. Use sempre que pedir visão macro de processo, macrofluxo assistencial, cadeia de valor, jornada do paciente, interfaces entre setores ou estruturação de etapas de alto nível.
---

# macroprocesso-jornada-paciente

Esta skill estrutura processos assistenciais e operacionais exclusivamente em nível macro (de ponta a ponta) e sobrepõe a jornada do paciente a essas macroetapas. O objetivo é evitar a perda de foco causada por microetapas de fluxogramas operacionais (cliques em sistema, preenchimento de formulários ou rotinas de balcão) antes que a arquitetura do fluxo e as transições entre áreas estejam claras.

## Fluxo de Trabalho

### 1. Delimitar o Escopo Ponta a Ponta (SIPOC Macro)
Defina claramente o evento gatilho (onde o processo começa para o paciente) e o evento de encerramento (onde o ciclo termina), identificando entradas principais e saídas esperadas sem listar tarefas internas.

### 2. Estruturar de 5 a 8 Macroetapas Sequenciais
Decomponha o fluxo em grandes blocos de entrega de valor (macroprocessos). Cada macroetapa deve responder "o que acontece no fluxo do paciente" e não "como o colaborador opera".
- Agrupe microações operacionais dentro de um único marco.
- Nomeie cada macroetapa com substantivos ou verbos de estado claro.
- Pare obrigatoriamente no nível macro. Não crie raias de swimlane detalhadas, árvores de decisão de sistema ou instruções de trabalho.

### 3. Sobrepor a Camada da Jornada do Paciente
Para cada macroetapa definida no passo anterior, alinhe quatro dimensões da jornada do paciente:
- **O que o paciente vive (Pontos de Contato)**
- **Passagem de Bastão (Handoffs e Interfaces)**
- **Pontos de Atrito e Espera**
- **Indicador ou Barreira Chave**

### 4. Validar a Altitude do Mapeamento
Antes de entregar a resposta, revise se alguma etapa desceu para o nível de Procedimento Operacional Padrão (POP). Se houver passos granulares de execução interna, condense-os de volta para o marco macro correspondente.