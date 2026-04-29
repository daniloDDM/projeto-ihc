# **Cenários de Interação**
### Cenário 1: Prática de Simulado com Feedback Instantâneo
Ator: Lucas (Aluno de Ciência da Computação) <br>

Faltando duas semanas para o ENADE, Lucas acessa o QuestIA para praticar questões dissertativas de edições anteriores. Ele seleciona uma questão sobre algoritmos de busca e o sistema apresenta o enunciado completo. Lucas redige sua resposta técnica diretamente no ambiente do sistema.

Ao finalizar, Lucas solicita a correção automática. O sistema processa o texto utilizando o modelo de NLP e, em poucos segundos, apresenta a nota estimada e um comparativo lado a lado com o padrão de resposta oficial. O sistema destaca as palavras-chave e conceitos que Lucas abordou corretamente e sinaliza as lacunas de aprendizado que faltaram ser citadas. Lucas analisa o feedback, compreende onde errou na estruturação e consulta as sugestões de revisão oferecidas pela plataforma para reforçar os pontos fracos.

### Questões para refinamento
 1. Quem pode/deve realizar simulados e enviar respostas no sistema?
 2. Quando as respostas do simulado são enviadas para correção? 
 3. De onde o sistema obtém os padrões de resposta para comparação?
 4. Quais dados da resposta dissertativa devem ser processados? 
 5. Quantos simulados o aluno pode realizar em uma sessão de estudo?
 6. Como o sistema avalia se um termo sinônimo é válido na correção?
 7. Que informações são necessárias para o sistema gerar o feedback de lacunas? 
 8. Como o feedback da correção é apresentado ao usuário? 
 9. De quem depende a validação final da nota gerada pela IA? 
 10. Como o aluno visualiza seu progresso histórico após múltiplos simulados?

### Narrativa com respostas
**Lucas, aluno do último ano de computação [1]**, acessa o sistema durante sua **sessão de estudos noturna [2]**. Ele escolhe uma questão dissertativa **cujos critérios de avaliação foram previamente cadastrados a partir dos dados do INEP [3, 7]**. Lucas **redige seu texto [4]** e aciona a correção. O algoritmo de NLP analisa a semântica, aceitando **sinônimos técnicos conforme sua base de treinamento [6]**.
O sistema **exibe o feedback instantâneo [8]**, evidenciando o que foi abordado e o que faltou em relação ao padrão esperado. Ao concluir, Lucas **verifica o gráfico de sua evolução histórica para entender se está atingindo a meta de desempenho [10]**. Ele sente-se seguro, pois a nota da IA possui baixa discrepância em **relação ao critério oficial [9]**.

---

### Cenário 2: Gestão Estratégica e Monitoramento de Qualidade
Ator: Marcos (Professor) <br>

Marcos acessa o QuestIA em seu local de trabalho para gerenciar a correção das provas da sua turma. O sistema já processou as submissões dos alunos e apresenta a Marcos um Dashboard Estratégico com a visão macro do desempenho. Marcos inicia consultando o Mapa de Calor, onde identifica imediatamente que a "Questão 3" teve o maior índice de erro.

Para garantir a justiça na avaliação, ele verifica as Métricas de Discrepância, onde o sistema emite um alerta caso a correção automática (ou as intervenções de Marcos) esteja se tornando muito rígida ou branda, ajudando-o a controlar o efeito da fadiga. Por fim, ele gera um Relatório de Lacunas de Aprendizado, que lista os conceitos técnicos mais esquecidos pelos alunos, e decide utilizar esses dados para planejar a próxima aula de revisão.

### Questões para refinamento 
1. Quem deve acessar as métricas de desempenho da turma? 
2. Quando o professor consulta o Dashboard Estratégico? 
3. Quem fornece os dados base para a geração do Mapa de Calor? 
4. Quais indicadores de qualidade devem ser exibidos no monitoramento? 
5. Quantas questões são analisadas simultaneamente no mapa de calor? 
6. Quem é considerado apto a validar as métricas de discrepância? 
7. Que dados são necessários para gerar o Alerta de Fadiga do Corretor? 
8. Como o professor obtém o relatório de lacunas de aprendizado? 
9. De quem depende a conclusão da análise estratégica da turma? 
10. Quais informações os alunos recebem após a análise do professor?

### Narrativa com respostas
Marcos, **professor responsável pela disciplina [1]**, acessa o sistema **após o encerramento do prazo de entrega dos simulados [2]**. O sistema utiliza as **submissões dos alunos e os critérios da banca [3]** para alimentar o dashboard. Marcos visualiza o desempenho de **todas as questões do período atual [5]** através do **Mapa de Calor e do Relatório de Lacunas [8]**.

O sistema exibe **indicadores de rigidez e alertas de fadiga [4, 7]** para que Marcos, como **especialista [6]**, possa ajustar os critérios se necessário. Ao finalizar **sua análise, o professor [9]** autoriza o disparo de notificações de **feedback para todos os alunos envolvidos [10]**.

---

# **Design Centrado na Comunicação**

**Nome do Cenário: Prática de Simulado com Feedback Instantâneo**

| tópico \> subtópico (diálogo) | falas e signos |
| :---- | :---- |
| **Praticar Simulado** | **U:** Quero treinar para a prova dissertativa do ENADE. |
| **\> Selecionar Questão** | **D:** Quais temas ou anos de prova você deseja revisar hoje? <br> **U:** Quero uma questão de Engenharia de Software do ENADE 2021. |
| **\> Redigir Resposta** | **D:** Aqui está o enunciado. Pode escrever sua resposta no campo abaixo; eu salvarei seu rascunho automaticamente. <br> **U:** (_Digita o texto técnico sobre Ciclo de Vida de Software_).  |
| **\> Solicitar Correção** | **U:** Terminei. Pode corrigir para mim? <br> **D:** Com certeza. Estou analisando seu texto com base nos critérios oficiais da banca...  |
| **\> Avaliar Desempenho** | **D:** Sua nota estimada é 8,5. Note que você abordou bem os requisitos, mas esqueceu de citar a fase de manutenção. <br> **U:** Onde exatamente eu errei? |
| **\> Comparar com Referência** | **D:** Veja o comparativo lado a lado: em verde está o que você acertou e em vermelho o que o padrão de resposta esperava e não foi encontrado. |
| **\> Consultar Evolução** | **U:** Estou melhorando em relação ao simulado passado? <br> **D:** Sim! Seu gráfico de evolução mostra um crescimento de 15% na precisão técnica. |


**Nome do Cenário: Gestão Estratégica e Monitoramento de Qualidade**

| tópico \> subtópico (diálogo) | falas e signos |
| :---- | :---- |
| **Analisar Turma** | **U:** Preciso ver como meus alunos foram no simulado de ontem. |
| **\> Consultar Mapa de Calor** | **D:** Aqui está o mapa. Note que a Questão 4 possui 70% de erro. |
| **\> Monitorar Qualidade** | **U:** A correção automática está sendo muito rigorosa nessa questão? |
| **\> Verificar Discrepância** | **U:** O índice de discrepância está em 3%, dentro do limite aceitável. O erro parece ser conceitual dos alunos. |
| **\> Gerar Relatório** | **U:** Quero o relatório de lacunas para a aula de revisão. <br> **D:** OK, os conceitos 'Complexidade de Algoritmos' e 'Big O' foram os mais esquecidos. |

# **Mapa de Objetivos**
### Mapa de objetivos do perfil aluno:

<img width="1179" height="584" alt="image" src="https://github.com/user-attachments/assets/16d6e2c0-6c62-4a43-8abf-8bc5c8102e2f" />

### Diagrama de consolidação para perfil aluno:

<img width="3540" height="8192" alt="image" src="https://github.com/user-attachments/assets/b4939902-4d5e-4294-9fa8-9537bd9148e5" />

---

### Mapa de objetivos do perfil professor:
<img width="865" height="562" alt="image" src="https://github.com/user-attachments/assets/258c7f52-20c3-4724-ab7c-2f5d64d0b783" />

### Diagrama de consolidação para perfil professor:
<img width="2283" height="8191" alt="image" src="https://github.com/user-attachments/assets/bb34e20c-a202-427d-a0b5-ce59ac55f740" />

---

# **Esquema Conceitual de Signos**

| Credenciais (C) \- credenciais para acesso ao sistema |  |  |  |  |  |  |  |
| :---- | :---- | :---- | :---- | :---- | :---- | :---- | :---- |
| **signo** | **origem** | **observações** | **Tipo de conteúdo** | **restrição sobre conteúdo** | **valor default** | **prevenção** | **recuperação** |
| Usuário | Domínio | Utilizado para identificação única do Aluno ou Professor. | Texto | Não pode ser nulo | - | PP: campo obrigatório | RA |
| Senha | Domínio | Garante a privacidade e proteção dos dados conforme a LGPD. | Texto | Não pode ser nulo | - | PP: campo obrigatório | RA |
| Nota estimada | Sistema (NLP) | Representa a avaliação automática baseada no modelo BERT. | Numérico | 0.0 a 10.0 | - | PP: Exibição apenas após processamento concluído. | RA: Opção de "Verificar Critérios". |
| Comparativo Lado a Lado | Design | Exibe a resposta do aluno em paralelo aos tópicos da banca. | Visual/Texto | Leitura apenas | - | PP: Cores distintas para acerto (verde) e erro (vermelho). | RA: Destaque visual dos termos faltantes. |
| Gráfico de Evolução | Domínio (Estatística) | Mostra a progressão da nota em diferentes simulados. | Gráfico | Temporal | - | PP: Escalas automáticas para evitar distorção. | RA: Filtros por período ou tema. |
| Mapa de Calor | Domínio/Design | Identifica visualmente as questões com maior índice de erro na turma. | Gráfico (Cores) | Baseado em volume de erros | - | PP: Legenda de cores clara (Frio/Quente). | RA: Zoom ou filtro por questão específica. |
| Métrica de Discrepância | Sistema | Indica se a IA está sendo muito rígida ou branda. | Percentual | 0% a 100% | 0% | PP: Alerta visual se ultrapassar 5%. | RA: Reajuste manual de critérios. |
| Alerta de Fadiga | Design | Informa o professor sobre a perda de assertividade por cansaço. | Notificação/Ícone | Gatilho por tempo/comportamento | - | PP: Notificação não intrusiva em área de destaque. | RA: Opção de pausar sessão de correção. |
