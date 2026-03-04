<img width="1006" height="582" alt="image" src="https://github.com/user-attachments/assets/1b274ced-af27-4596-8c87-dc7788f2c097" />


# Análise de Tarefas (HTA)

| Objetivos / Operações | Problemas/Recomendações |
|-----------------------|-------------------------|
| **0. Enviar resposta e obter feedback** 1>2 | Input: Credenciais de acesso (login/senha) e enunciado da questão dissertativa do ENADE. <br> Feedback: Nota automática e visualização do progresso no histórico. <br> Plano: Realizar a autenticação (precondição), responder a questão (1) e, após o processamento, avaliar o desempenho (2). <br> Recomendação: Permitir o cadastro simplificado para novos usuários (alunos e professores) antes de iniciar a tarefa.|
| **1. Responder à questão** 1/2 | Plano: O usuário deve selecionar um simulado/questão (1.1) ou redigir a resposta no campo de texto (1.2), caso a questão já esteja carregada. |
| **1.1 Selecionar simulado/questão** | Feedback: Interface exibe o enunciado completo e o tempo sugerido para resposta. <br> Recomendação: Indicar quais questões o aluno já respondeu anteriormente para evitar repetição.|
| **1.2 Redigir resposta no campo de texto** | Problema: O aluno pode sentir insegurança sobre quais termos técnicos utilizar. <br> Recomendação: Implementar salvamento automático (autosave) para garantir que a resposta não seja perdida em caso de falha na conexão.|
| **2. Avaliar desempenho** | Feedback: Exibição da resposta do aluno comparada lado a lado com o padrão de resposta da banca. <br> Ação: O sistema apresenta o feedback instantâneo e destaca as lacunas de aprendizado identificadas pelo NLP. <br> Recomendação: Oferecer links para materiais de revisão baseados nos conceitos que o aluno esqueceu de citar.|


analisar metricas da correção

