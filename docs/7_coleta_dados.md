# 📝 Metodologia de Coleta de Dados

Esta seção descreve o planejamento e a execução da coleta de dados para o projeto QuestIA, visando identificar as necessidades reais de alunos e professores no contexto do ENADE.

## 1. Identificação de Necessidades

### O que coletar?
- **Perfil Sociodemográfico:** Idade, curso, semestre, experiência prévia com tecnologia e IA.
- **Processos de Estudo/Trabalho:** Como o aluno estuda para o ENADE e como o professor corrige as questões.
- **Dores e Dificuldades:** Ansiedade do aluno por falta de feedback; fadiga e inconsistência do professor na correção manual.
- **Expectativas:** O que os usuários esperam de uma ferramenta de correção automática (transparência, velocidade, precisão).

### De quem coletar?
- **Alunos:** Estudantes de graduação (concluintes) que realizarão o ENADE.
- **Professores:** Docentes universitários com experiência em correção de provas dissertativas ou membros de bancas examinadoras.

## 2. Aspectos Éticos
Toda a coleta de dados seguiu os princípios éticos de pesquisa com seres humanos:
- **Termo de Consentimento Livre e Esclarecido (TCLE):** Todos os participantes foram informados sobre o objetivo da pesquisa, anonimato dos dados e direito de desistência a qualquer momento.
- **Privacidade:** Nenhum dado sensível ou identificável (nome, CPF, matrícula) foi armazenado de forma pública.
- **Uso dos Dados:** Os dados coletados são utilizados exclusivamente para o refinamento da interface IHC do projeto QuestIA.

## 3. Técnicas Utilizadas

### Técnica 1: Questionário (Alunos e professores)
- **Objetivo:** Coletar dados quantitativos sobre o perfil e as dores dos estudantes em larga escala.
- **Motivo:** A escolha do método de questionários para a fase de identificação de necessidades do QuestIA justifica-se, principalemte, pela sua capacidade de coletar dados de uma grande quantidade de usuários de forma rápida, fácil e barata. Dado que o público-alvo do projeto (estudantes e professores do ENADE) é geograficamente disperso e possui perfis variados, este método permite obter uma visão em larga escala sobre as dores e expectativas do sistema.
- **Protocolo de Aplicação:** Disponibilizado via Google Forms em grupos de alunos concluintes. Tempo estimado: 5 minutos.
- **Links dos questionários**: 
  - Questionário 1: Perfil do aluno: https://docs.google.com/forms/d/e/1FAIpQLSeM2lF9V7Jx3sbBCmQawAUP-P8aIxyYopJAHwXcEjlQQ8MRcg/viewform?usp=publish-editor
  - Questionário 2: Perfil de Professor/Corretor: https://docs.google.com/forms/d/e/1FAIpQLScJRsmwaDpBX2naI5MjdMaFyYFBwjJNy-Eav-Sh8CfLYle-tg/viewform?usp=publish-editor

#### Instrumento e Respostas Mockadas (Resumo):
- **Pergunta:** Como você avalia o feedback que recebe atualmente em simulados dissertativos?
  - *Respostas:* 70% consideram "Lento ou inexistente", 20% "Genérico", 10% "Satisfatório".
- **Pergunta:** Qual sua maior dificuldade ao responder questões do ENADE?
  - *Respostas:* "Não saber se usei os termos técnicos corretos", "Incerteza sobre o que a banca espera".

---

### Técnica 2: Entrevista Semiestruturada (Professores)
- **Objetivo:** Compreender em profundidade o fluxo mental e as dificuldades da correção manual.
- **Protocolo de Aplicação:** Entrevista remota via Teams/Zoom. Duração: 15 minutos. Roteiro com 5 perguntas abertas.

#### Roteiro de Entrevista:
1. Como é sua rotina quando recebe um lote de 100+ questões para corrigir?
2. Quais os sinais de cansaço você percebe durante o processo?
3. Como você garante que o critério usado na primeira prova é o mesmo da última?
4. Qual a funcionalidade mais crítica que uma IA de auxílio deveria ter?
5. Você confiaria em uma nota sugerida por IA? Em quais condições?

#### Resultados das entrevistas:
- **Entrevistado P1:** "Depois da 40ª prova, começo a ler mais rápido e sinto que posso estar sendo injusto. Um alerta de 'rigidez' seria muito útil."
- **Entrevistado P2:** "O maior problema é explicar o erro para o aluno. Perco muito tempo escrevendo o mesmo feedback."

## 4. Conclusão da Coleta
Os dados confirmam que a **transparência dos critérios** e a **redução da carga cognitiva** são as prioridades para o professor, enquanto o aluno busca **agilidade e clareza nos termos técnicos** exigidos pela banca.
