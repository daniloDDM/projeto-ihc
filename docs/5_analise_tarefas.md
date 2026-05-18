# 📊 Análise de Tarefas

A análise de tarefas permite decompor o trabalho dos usuários em objetivos e ações concretas para orientar o design da interface.

## 1. HTA (Hierarchical Task Analysis)

### Tarefa: Submissão de Resposta e Feedback (Aluno)
<img width="1006" height="582" alt="HTA Aluno" src="images/hta_aluno.png" />

### Tarefa: Auditoria de Correção e Gestão (Professor)
<img width="983" height="368" alt="HTA Professor" src="images/hta_professor.png" />

---

## 2. GOMS (Goals, Operators, Methods, and Selection Rules)

### Goal: Obter feedback de uma questão dissertativa
- **Method 1:** Escrever resposta diretamente
    - Op 1: Selecionar campo de texto
    - Op 2: Digitar resposta
    - Op 3: Clicar em "Avaliar"
- **Method 2:** Revisar rascunho antes de submeter
    - Op 1: Digitar rascunho
    - Op 2: Clicar em "Revisar"
    - Op 3: Ajustar texto
    - Op 4: Clicar em "Avaliar"
- **Selection Rule:** Usar Method 2 se o usuário estiver inseguro sobre os termos técnicos.

### Goal: Analisar discrepância da turma no dashboard
- **Method 1:** Visualização via Mapa de Calor
    - Op 1: Abrir Dashboard
    - Op 2: Identificar áreas vermelhas
    - Op 3: Clicar no indicador para detalhes
- **Operators:** Clicar, Analisar, Comparar, Decidir.

---

## 3. CTT (ConcurTaskTrees)

Os diagramas abaixo mostram a decomposição das tarefas com foco nas relações temporais (concorrência, sequência e escolha).

### Fluxo do Aluno
<img width="734" height="628" alt="CTT Aluno" src="images/ctt_aluno.png" />

### Fluxo do Professor
<img width="906" height="602" alt="CTT Professor" src="images/ctt_professor.png" />

**Legenda de Relações:**
- **>> (Sequência):** Uma tarefa deve terminar antes da outra começar.
- **[] (Escolha):** O usuário deve escolher entre uma tarefa ou outra.
- **||| (Concorrência):** Tarefas podem ser realizadas ao mesmo tempo.
