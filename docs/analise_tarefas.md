# Análise de Tarefas (HTA)

<img width="1006" height="582" alt="image" src="https://github.com/user-attachments/assets/1b274ced-af27-4596-8c87-dc7788f2c097" />

---

| Objetivos / Operações | Problemas/Recomendações |
|-----------------------|-------------------------|
| **0. Enviar resposta e obter feedback** 1>2 | Input: Credenciais de acesso (login/senha) e enunciado da questão dissertativa do ENADE. <br> Feedback: Nota automática e visualização do progresso no histórico. <br> Plano: Realizar a autenticação (precondição), responder a questão (1) e, após o processamento, avaliar o desempenho (2). <br> Recomendação: Permitir o cadastro simplificado para novos usuários (alunos e professores) antes de iniciar a tarefa.|
| **1. Responder à questão** 1/2 | Plano: O usuário deve selecionar um simulado/questão (1.1) ou redigir a resposta no campo de texto (1.2), caso a questão já esteja carregada. |
| **1.1 Selecionar simulado/questão** | Feedback: Interface exibe o enunciado completo e o tempo sugerido para resposta. <br> Recomendação: Indicar quais questões o aluno já respondeu anteriormente para evitar repetição.|
| **1.2 Redigir resposta no campo de texto** | Problema: O aluno pode sentir insegurança sobre quais termos técnicos utilizar. <br> Recomendação: Implementar salvamento automático (autosave) para garantir que a resposta não seja perdida em caso de falha na conexão.|
| **2. Avaliar desempenho** | Feedback: Exibição da resposta do aluno comparada lado a lado com o padrão de resposta da banca. <br> Ação: O sistema apresenta o feedback instantâneo e destaca as lacunas de aprendizado identificadas pelo NLP. <br> Recomendação: Oferecer links para materiais de revisão baseados nos conceitos que o aluno esqueceu de citar.|

---

<img width="983" height="368" alt="image" src="https://github.com/user-attachments/assets/06a3c564-5f87-4eef-b192-3d6f0b309890" />

---

| Objetivos / Operações | Problemas/Recomendações |
|-----------------------|-------------------------|
| **0. Analisar correção e desempenho da turma** 1> (2/3) | Input: Dados de submissão dos alunos e critérios de correção do ENADE. <br> Feedback: Dashboard estratégico com dados consolidados. <br> Plano: Realizar a autenticação (1) e, posteriormente, decidir entre analisar o desempenho global (2) ou monitorar a qualidade da correção (3).|
| **1. Autenticar no sistema** | Ação: Entrada de credenciais específicas para o perfil de professor. <br> Recomendação: Utilizar autenticação única (SSO) integrada à instituição para garantir segurança e agilidade no acesso. |
| **2. Analisar desempenho global** 1/2 | Plano: O professor pode optar por acessar a visão geral do Dashboard Estratégico (2.1) ou ir diretamente para a análise visual do Mapa de Calor (2.2).|
| **2.1. Acessar Dashboard Estratégico** | Feedback: Visão macro do desempenho, incluindo o "Relatório de Lacunas de Aprendizado". <br> Recomendação: Adicionar filtros por período ou turma para facilitar a comparação de evolução histórica.|
| **2.2. Consultar Mapa de Calor** | Ação: Identificação gráfica das questões com maior índice de erro. <br> Feedback: Visualização intuitiva dos pontos críticos da turma. <br> Recomendação: Permitir clicar na questão para visualizar os conceitos específicos que os alunos não conseguiram abordar.|
| **3. Monitorar qualidade da correção** 1/2 | Plano: Verificar se há divergências nos critérios (3.1) ou conferir alertas de desempenho do corretor (3.2). |
|  **3.1. Verificar Métricas de Discrepância** | Feedback: Indicadores que mostram se a correção está seguindo um padrão muito rígido ou brando. <br> Recomendação: Apresentar a média histórica de correção do ENADE como benchmark para o professor. |
| **3.2. Analisar alertas de fadiga do corretor** | Ação: Controle de fadiga para evitar perda de assertividade ao longo das correções. <br> Problema: O excesso de correções manuais pode gerar discrepâncias. <br> Recomendação: Notificar o professor quando o tempo de correção por questão diminuir drasticamente, indicando possível fadiga. |


