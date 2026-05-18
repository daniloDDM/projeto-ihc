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

### Técnica 1: Questionário (Alunos)
**Objetivo:** Coletar dados quantitativos sobre o perfil e as dores dos estudantes em larga escala.
**Protocolo de Aplicação:** Disponibilizado via Google Forms em grupos de alunos concluintes. Tempo estimado: 5 minutos.

#### Instrumento e Respostas Mockadas (Resumo):
- **Pergunta:** Como você avalia o feedback que recebe atualmente em simulados dissertativos?
  - *Respostas:* 70% consideram "Lento ou inexistente", 20% "Genérico", 10% "Satisfatório".
- **Pergunta:** Qual sua maior dificuldade ao responder questões do ENADE?
  - *Respostas:* "Não saber se usei os termos técnicos corretos", "Incerteza sobre o que a banca espera".

---

### Técnica 2: Entrevista Semiestruturada (Professores)
**Objetivo:** Compreender em profundidade o fluxo mental e as dificuldades da correção manual.
**Protocolo de Aplicação:** Entrevista remota via Teams/Zoom. Duração: 15 minutos. Roteiro com 5 perguntas abertas.

#### Roteiro de Entrevista:
1. Como é sua rotina quando recebe um lote de 100+ questões para corrigir?
2. Quais os sinais de cansaço você percebe durante o processo?
3. Como você garante que o critério usado na primeira prova é o mesmo da última?
4. Qual a funcionalidade mais crítica que uma IA de auxílio deveria ter?
5. Você confiaria em uma nota sugerida por IA? Em quais condições?

#### Resultados Mockados:
- **Entrevistado P1:** "Depois da 40ª prova, começo a ler mais rápido e sinto que posso estar sendo injusto. Um alerta de 'rigidez' seria muito útil."
- **Entrevistado P2:** "O maior problema é explicar o erro para o aluno. Perco muito tempo escrevendo o mesmo feedback."

---

### Técnica 3: Investigação Contextual (Estudo de Campo)
**Objetivo:** Observar o ambiente real e as interrupções durante a tarefa de correção.
**Protocolo de Aplicação:** Observação silenciosa do professor Ricardo em seu ambiente de trabalho (escritório doméstico) durante 30 minutos de correção manual.

#### Registro de Observação:
- **Ambiente:** Mesa com dois monitores, café, diversos arquivos PDF abertos e uma planilha Excel.
- **Ações:** O professor alterna entre o PDF da resposta e o PDF do gabarito oficial em média 4 vezes por questão.
- **Interrupções:** Notificações de e-mail e cansaço visual (esfregar os olhos) após 20 minutos.
- **Dificuldade observada:** O professor teve que voltar 5 provas atrás para conferir se uma resposta similar tinha recebido a mesma nota, gastando 3 minutos apenas nessa busca manual.

## 4. Conclusão da Coleta
Os dados confirmam que a **transparência dos critérios** e a **redução da carga cognitiva** são as prioridades para o professor, enquanto o aluno busca **agilidade e clareza nos termos técnicos** exigidos pela banca.
