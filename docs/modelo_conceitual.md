1) **Cenários de Interação**
### 1. Cenário: Prática de Simulado com Feedback Instantâneo
Atores: Lucas (Aluno de Ciência da Computação)

Faltando duas semanas para o ENADE, Lucas acessa o QuestIA para praticar questões dissertativas de edições anteriores. Ele seleciona uma questão sobre algoritmos de busca e o sistema apresenta o enunciado completo. Lucas redige sua resposta técnica diretamente no ambiente do sistema.

Ao finalizar, Lucas solicita a correção automática. O sistema processa o texto utilizando o modelo de NLP e, em poucos segundos, apresenta a nota estimada e um comparativo lado a lado com o padrão de resposta oficial. O sistema destaca as palavras-chave e conceitos que Lucas abordou corretamente e sinaliza as lacunas de aprendizado que faltaram ser citadas. Lucas analisa o feedback, compreende onde errou na estruturação e consulta as sugestões de revisão oferecidas pela plataforma para reforçar os pontos fracos.

### 2. Questões para refinamento

Quem pode/deve realizar simulados e enviar respostas no sistema? 
Quando as respostas do simulado são enviadas para correção? 
De onde o sistema obtém os padrões de resposta para comparação?
Quais dados da resposta dissertativa devem ser processados? 
Quantos simulados o aluno pode realizar em uma sessão de estudo?
Como o sistema avalia se um termo sinônimo é válido na correção?
Que informações são necessárias para o sistema gerar o feedback de lacunas? 
Como o feedback da correção é apresentado ao usuário? 
De quem depende a validação final da nota gerada pela IA? 
Como o aluno visualiza seu progresso histórico após múltiplos simulados?

### 3. Narrativa com respostas
Lucas, aluno do último ano de computação **[1]**, acessa o sistema durante sua sessão de estudos noturna **[2]**. Ele escolhe uma questão dissertativa cujos critérios de avaliação foram previamente cadastrados a partir dos dados do INEP **[3, 7]**. Lucas redige seu texto **[4]** e aciona a correção. O algoritmo de NLP analisa a semântica, aceitando sinônimos técnicos conforme sua base de treinamento **[6]**.

O sistema exibe o feedback instantâneo **[8]**, evidenciando o que foi abordado e o que faltou em relação ao padrão esperado **[10]**. Ao concluir, Lucas verifica o gráfico de sua evolução histórica para entender se está atingindo a meta de desempenho **[10]**. Ele sente-se seguro, pois a nota da IA possui baixa discrepância em relação ao critério oficial **[9]**.

2) **Design Centrado na Comunicação**

**Nome do Cenário: XXXXXX**

| tópico \> subtópico (diálogo) | falas e signos |
| :---- | :---- |
|  | U: Preciso … |
| \>  | U: Quero … D: Aqui está o mapa |
|  | U:  |
|  | U:  |
|  | D: Aqui está a informação filtrada |

3) **Mapa de Objetivos**
> **_NOTE:_**: cada um coloca seu mapa de objetivos e deverá ter um diagrama de consolidação

4) **Esquema Conceitual de Signos**

> **_NOTE:_**: fazer a junção das 3 tabelas abaixo em uma única

| Credenciais (C) \- credenciais para acesso ao sistema |  |  |
| :---- | :---- | :---- |
| **signo** | **origem** | **observações** |
| usuário | domínio |  |
| senha | domínio |  |

| Credenciais (C) \- credenciais para acesso ao sistema |  |  |  |
| :---- | :---- | :---- | :---- |
| **signo** | **Tipo de conteúdo** | **restrição sobre conteúdo** | **valor default** |
| usuário | texto | não pode ser nulo | — |
| senha | texto | não pode ser nulo | — |

| Credenciais (C) \- credenciais para acesso ao sistema |  |  |
| :---- | :---- | :---- |
| **signo** | **prevenção** | **recuperação** |
| usuário | PP: campo obrigatório | RA |
| senha | PP campo obrigatório  | RA |
