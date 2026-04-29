# Análise de Tarefas (HTA)

<img width="1006" height="582" alt="image" src="https://github.com/user-attachments/assets/1b274ced-af27-4596-8c87-dc7788f2c097" />

---

| Objetivos / Operações | Problemas/Recomendações |
|-----------------------|-------------------------|
| **0. Enviar resposta e obter feedback** 1>2 | Input: Credenciais de acesso (login/senha) e enunciado da questão dissertativa do ENADE. <br> Feedback: Nota automática e visualização do progresso no histórico. <br> Plano: Realizar a autenticação (precondição), responder a questão (1) e, após o processamento, avaliar o desempenho (2). <br> Recomendação: Permitir o cadastro simplificado para novos usuários (alunos e professores) antes de iniciar a tarefa.|
| **1. Responder à questão** 1/2 | Plano: O usuário deve selecionar um simulado/questão (1.1) ou redigir a resposta no campo de texto (1.2), caso a questão já esteja carregada. |
| **1.1 Selecionar simulado/questão** | Recomendação: Interface exibe o enunciado completo e o tempo sugerido para resposta. <br> Indicar quais questões o aluno já respondeu anteriormente para evitar repetição.|
| **1.2 Redigir resposta no campo de texto** | Problema: O aluno pode sentir insegurança sobre quais termos técnicos utilizar. <br> Recomendação: Implementar salvamento automático (autosave) para garantir que a resposta não seja perdida em caso de falha na conexão.|
| **2. Avaliar desempenho** | Ação: O sistema apresenta o feedback instantâneo e destaca as lacunas de aprendizado identificadas pelo NLP. <br> Recomendação: Oferecer links para materiais de revisão baseados nos conceitos que o aluno esqueceu de citar. <br> Exibição da resposta do aluno comparada lado a lado com o padrão de resposta da banca.|

---

<img width="983" height="368" alt="image" src="https://github.com/user-attachments/assets/06a3c564-5f87-4eef-b192-3d6f0b309890" />

---

| Objetivos / Operações | Problemas/Recomendações |
|-----------------------|-------------------------|
| **0. Analisar correção e desempenho da turma** 1> (2/3) | Input: Entrada de credenciais específicas para o perfil de professor e dados de submissão dos alunos e critérios de correção do ENADE <br> Feedback: Dashboard estratégico com dados consolidados. <br> Plano: Realizar a autenticação (1) e, posteriormente, decidir entre analisar o desempenho global (2) ou monitorar a qualidade da correção (3).|
| **1. Autenticar no sistema** | Recomendação: Utilizar autenticação única (SSO) integrada à instituição para garantir segurança e agilidade no acesso. |
| **2. Analisar desempenho global** 1/2 | Plano: O professor pode optar por acessar a visão geral do Dashboard Estratégico (2.1) ou ir diretamente para a análise visual do Mapa de Calor (2.2).|
| **2.1. Acessar Dashboard Estratégico** | Recomendação: Adicionar filtros por período ou turma para facilitar a comparação de evolução histórica e visão macro do desempenho, incluindo o "Relatório de Lacunas de Aprendizado".|
| **2.2. Consultar Mapa de Calor** | Recomendação: Permitir clicar na questão para visualizar os conceitos específicos que os alunos não conseguiram abordar.|
| **3. Monitorar qualidade da correção** 1/2 | Plano: Verificar se há divergências nos critérios (3.1) ou conferir alertas de desempenho do corretor (3.2). |
|  **3.1. Verificar Métricas de Discrepância** | Recomendação: Apresentar a média histórica de correção do ENADE como benchmark para o professor. |
| **3.2. Analisar alertas de fadiga do corretor** | Problema: O excesso de correções manuais pode gerar discrepâncias. <br> Recomendação: Notificar o professor quando o tempo de correção por questão diminuir drasticamente, indicando possível fadiga. |
---

# GOMS
## GOAL 0: Enviar Resposta e Obter Feedback

### Goal 1: Responder à Questão
#### Method 1.A: Seleção simulado/questão e Escrita <br>
(SEL. RULE: o aluno ainda não escolheu um tema para responder)

**Operators:**
- **1.A.1:** Clicar em **"Selecionar simulado/questão"**.
- **1.A.2:** Decidir qual ano ou tema do ENADE revisar.
- **1.A.3:** Selecionar a questão desejada na lista.
- **1.A.4:** Analisar o enunciado e o tempo sugerido.
- **1.A.5:** Digitar a resposta dissertativa no campo de texto.
- **1.A.6:** Clicar em **"Enviar resposta"**.

---

#### Method 1.B : Escrita Direta
(SEL. RULE: a questão a ser respondida é a mesma que já está selecionada)

**Operators:**
- **1.B.1:** Raciocinar sobre os termos técnicos a serem usados.
- **1.B.2:** Digitar a resposta dissertativa.
- **1.B.3:** Clicar em **"Enviar resposta"**.

---

### 3. Goal: Avaliar Desempenho

**Operators:**
- **3.1:** Verificar a nota automática atribuída.
- **3.2:** Ler o comparativo lado a lado entre a resposta enviada e o padrão da banca.
- **3.3:** Identificar visualmente as lacunas de aprendizado apontadas pelo sistema.
- **3.4:** Mover o scroll para visualizar o progresso no **"Histórico de Evolução"**.
- **3.5:** Avaliar se é necessário revisar materiais de estudo sugeridos.

---

## GOAL 0: Analisar Correção e Desempenho da Turma

### Goal 1: Autenticar no Sistema

**Operators:**
- **1.1:** Mover o cursor para o campo **"Usuário/E-mail"**.
- **1.2:** Digitar as credenciais de professor.
- **1.3:** Pressionar a tecla **Enter** ou clicar no botão **"Acessar"**.

---

### Goal 2: Analisar Desempenho Global <br>
(SEL. RULE: O docente quer identificar falhas no aprendizado da turma)

#### Method 2.A: Acessar Dashboard estratégico <br>
(SEL. RULE: O docente deseja uma visualização geral do desempenho da turma)

**Operators:**
- **2.A.1:** Clicar no menu **"Dashboard Estratégico"**.
- **2.A.2:** Avaliar o panorama geral das notas da turma.

#### Method 2.B: Consultar Mapa de Calor
(SEL. RULE: O docente deseja uma visão geral das questões com maior número de erros)

**Operators:**
- **2.B.1:** Clicar na aba **"Mapa de Calor"**.
- **2.B.2:** Identificar quais questões possuem maior densidade de erros.

---

### Goal 3: Monitorar Qualidade da Correção <br>
(SEL. RULE: O docente utiliza a ferramenta como auxiliar na correção das provas)

#### Method 3.A: Visualizar métricas de discrepância <br>
(SEL. RULE: o docente deseja visualizar o padrão ouro de resposta e a tolerância para avaliação)

**Operators:**
- **3.A.1:** Clicar na seção **"Qualidade e Auditoria"**.
- **3.A.2:** Selecionar **"Métricas de Discrepância"**.
- **3.A.3:** Avaliar se a IA está sendo excessivamente rígida ou branda.

#### Method 3.B: Monitorar níveis de fadiga

**Operators:**
- **3.B.1:** Clicar no ícone de **"Alertas de Fadiga"**.
- **3.B.2:** Verificar se o tempo de correção por questão indica cansaço do corretor.
  
---

# CTT
### Legenda para diagrama
<img width="187" height="308" alt="image" src="https://github.com/user-attachments/assets/567ee5a8-7adc-4738-976c-bb5e6d77bfc5" />

---
### Tarefa 1: Enviar resposta e receber feedback (Aluno)
<img width="734" height="628" alt="image" src="https://github.com/user-attachments/assets/8b3988a6-b528-4fdc-9307-4f2597fa2929" />

---
### Tarefa 2: Avaliar correção e desempenho da turma (Professor)
<img width="906" height="602" alt="image" src="https://github.com/user-attachments/assets/57edb778-bc64-4cdd-bc89-ab7a35055773" />

