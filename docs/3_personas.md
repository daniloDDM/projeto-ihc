# 👥 Personas e Contexto de Uso - QuestIA

Este documento detalha os perfis de usuários do QuestIA, incluindo suas motivações, dores, ganhos e os contextos específicos em que interagem com o sistema.

## 1. Persona Primária: O Professor Corretor

### Identidade
- **Nome:** Roberto Almeida
- **Idade:** 52 anos
- **Cargo:** Professor Adjunto em uma universidade privada e Corretor Credenciado do ENADE.
- **Caracterização Sociocultural:** Classe média alta, reside em metrópole, possui doutorado. Valoriza a meritocracia e a precisão técnica. Tem familiaridade com tecnologia (uso de Office, e-mail e sistemas acadêmicos), mas rejeita interfaces excessivamente complexas ou "modernas" demais que escondam funcionalidades básicas.

### Perfil e Comportamento
Roberto é um professor com mais de 20 anos de experiência. Ele é tecnologicamente pragmático: utiliza ferramentas digitais que resolvam problemas reais, mas tem pouca paciência para sistemas lentos ou com usabilidade confusa. Ele valoriza a precisão acadêmica acima de tudo. Roberto encara a correção como um dever cívico, mas sofre com a carga horária exaustiva. Ele é pragmático e busca ferramentas que aumentem sua produtividade sem sacrificar a qualidade da avaliação.

### Objetivos
- Otimizar o tempo de correção para focar em atividades de pesquisa.
- Reduzir o esforço cognitivo de leitura repetitiva.
- Garantir que nenhum aluno seja prejudicado por oscilações no seu humor ou cansaço.

### Dados que o sistema deve guardar:
- Nome completo e registro funcional.
- Histórico de lotes de correção atribuídos.
- Preferências de interface (ex: modo escuro, tamanho da fonte).
- Logs de alteração de notas sugeridas pela IA (para auditoria).

### A Jornada do Professor Roberto:
É um sábado à tarde e Roberto encara a tela do computador com um misto de resignação e cansaço. Diante dele, uma pasta digital contendo 60 provas dissertativas de "Engenharia de Software". No método tradicional, ele abriria arquivo por arquivo, leria textos manuscritos muitas vezes ilegíveis, anotaria a nota em uma planilha separada e repetiria o processo até a exaustão. Sua principal motivação para mudar esse processo não é apenas a velocidade, mas o medo da injustiça: ele se pergunta constantemente se será tão rigoroso com a prova nº 50 quanto foi com a nº 1, sabendo que sua atenção cai drasticamente após horas de leitura.

Roberto decide então utilizar o **QuestIA**. Ao carregar o lote de provas, o sistema processa as respostas usando algoritmos de NLP (Processamento de Linguagem Natural). Em vez de uma tela em branco, ele vê a resposta do aluno já analisada: os termos técnicos essenciais estão destacados em verde e as fugas ao tema em vermelho. A ferramenta sugere uma nota preliminar baseada nos critérios que ele mesmo configurou. Roberto sente-se no controle: ele ajusta a nota de um aluno que usou um sinônimo criativo que a IA não captou, mas aceita a sugestão da maioria. Quando o sistema emite um alerta de que sua média de notas está caindo em relação ao início do dia, ele percebe sua própria fadiga. Graças ao dashboard estratégico, ele pausa, toma um café e retorna para recalibrar as últimas correções, terminando o trabalho na metade do tempo e com a certeza de que garantiu a equidade para a turma inteira.

### Mapa de Empatia: Roberto

| O que VÊ? | O que OUVE? |
| :--- | :--- |
| • Pilhas de provas digitais desestruturadas.<br>• Interfaces de sistemas legados complexas. | • Cobranças da coordenação por agilidade.<br>• Alunos questionando a subjetividade das notas. |
| **O que PENSA e SENTE?** | **O que FALA e FAZ?** |
| • *"Será que fui mais rigoroso agora do que de manhã?"*<br>• Medo de ser injusto por fadiga. | • Busca automatizar tarefas repetitivas.<br>• Critica a falta de padronização nas respostas. |
| **DORES (Pains)** | **GANHOS (Gains)** |
| • Frustração com textos ilegíveis ou mal estruturados.<br>• Pressão psicológica por prazos curtos. | • Confiança de que a correção é padronizada.<br>• Sensação de controle e agilidade no fluxo de trabalho. |

---

## 2. Persona Primária: A Aluna (Candidata ENADE)

### Identidade
- **Nome:** Beatriz Costa
- **Idade:** 23 anos
- **Ocupação:** Estudante do 10º semestre de Ciência da Computação, estagiária em uma multinacional de TI.
- **Caracterização Sociocultural:** Classe média, reside em zona urbana, utiliza transporte público. Jovem conectada, "nativa digital", consome conteúdos educacionais via YouTube e TikTok. Sente a pressão do mercado de trabalho e vê o ENADE como uma validação necessária para o seu currículo e para a instituição.

### Perfil e Comportamento
Beatriz está prestes a se formar e sabe que a nota do ENADE impacta a avaliação do seu curso e sua empregabilidade. Beatriz é ansiosa e focada em resultados. Ela prefere feedbacks curtos, diretos e acionáveis. Não gosta de ler manuais e espera que a interface seja intuitiva o suficiente para ser usada sem treinamento.

### Objetivos
- Identificar rapidamente suas lacunas de conhecimento técnico.
- Ganhar confiança na escrita acadêmica/técnica exigida pela banca.
- Obter nota máxima no exame para valorizar seu diploma.

### Dados que o sistema deve guardar:
- Nome, e-mail e curso.
- Histórico de simulados realizados e evolução das notas.
- Lista de termos técnicos mais errados/esquecidos.
- Tempo médio de resposta por questão.

### A Jornada da Aluna Beatriz:
Faltam duas semanas para o ENADE e Beatriz está na biblioteca, cercada de livros. Ela domina a programação prática, mas sente insegurança nas questões dissertativas, pois tem dificuldade em traduzir seu conhecimento para o "jeitês acadêmico" exigido pela banca. Nos simulados tradicionais, ela escreve a resposta no papel e compara com o gabarito oficial, mas continua perdida: sua resposta parece correta, mas não é idêntica à do espelho. Sua motivação para usar o **QuestIA** é a necessidade de assertividade e feedback imediato, pois ela não tem tempo a perder esperando dias pela correção de um professor humano.

Ao acessar o modo de simulado do QuestIA, Beatriz seleciona uma questão antiga sobre "Normalização de Banco de Dados" e digita sua resposta. Ao clicar em "Avaliar", o feedback é instantâneo. O sistema não apenas atribui uma nota (6.0), mas explica o porquê: "Você explicou o conceito corretamente, mas não citou o termo 'Dependência Funcional', que era obrigatório nesta questão.". A frustração inicial de Beatriz se transforma rapidamente em clareza. Ela entende o padrão esperado pela banca. Imediatamente, ela reescreve a resposta inserindo o termo técnico e vê sua nota subir para 10.0. O QuestIA atua como um treinador pessoal, ensinando a linguagem técnica necessária e transformando sua ansiedade pré-prova em confiança.


### Mapa de Empatia: Beatriz

| O que VÊ? | O que OUVE? |
| :--- | :--- |
| • Editais e padrões de resposta complexos do INEP.<br>• Colegas compartilhando dicas de estudo. | • *"O ENADE avalia a qualidade do seu curso."*<br>• *"Você precisa ser técnica e objetiva."* |
| **O que PENSA e SENTE?** | **O que FALA e FAZ?** |
| • *"Será que minha resposta está completa?"*<br>• Ansiedade por não ter feedback imediato. | • Realiza diversos simulados online.<br>• Usa ferramentas de IA para estudo rápido. |
| **DORES (Pains)** | **GANHOS (Gains)** |
| • Incerteza se está no caminho certo de estudo.<br>• Demora excessiva para receber correções de professores. | • Clareza sobre o que a banca espera.<br>• Segurança emocional e prontidão para o dia do exame. |

---

## 3. Contexto de Uso Detalhado

O QuestIA é projetado para operar em condições que variam de sessões de foco intenso a consultas rápidas em mobilidade.

### O que normalmente está acontecendo no ambiente?
- **Para o Professor:** Sessões de 2 a 4 horas de trabalho contínuo, geralmente à noite ou fins de semana. O ambiente costuma ter múltiplas abas abertas, música de fundo ou silêncio absoluto. A fadiga visual é o maior fator crítico.
- **Para o Aluno:** Sessões fragmentadas de 20 a 40 minutos (intervalos de estudo). O ambiente pode ser ruidoso (biblioteca, café) e o foco é intercalado com notificações de redes sociais.

### Contexto Social, Econômico e Cultural
- **Social:** Existe uma assimetria de poder; o sistema deve garantir que o professor sinta que a IA é sua *assistente*, e não sua substituta, enquanto o aluno deve sentir que o sistema é um *aliado* imparcial.
- **Econômico:** O acesso ao sistema depende de dispositivos com boa conectividade (Desktop/Laptop para o professor, Smartphone/Laptop para o aluno).
- **Cultural:** No Brasil, a cultura do ENADE gera uma "obrigação" que muitas vezes é vista com desdém ou medo; o sistema deve transformar essa percepção em um processo de aprendizado útil.

### Cenário A: O Home Office do Professor
* **Ambiente Físico:** Escritório em casa, geralmente utilizando um desktop com monitor amplo (ou dois monitores) para visualizar a prova e a correção simultaneamente.
* **Condições:** Iluminação controlada, mas sujeito a interrupções domésticas. O usuário geralmente está sentado por longos períodos.
* **Implicação de IHC:** A interface deve ter modo de leitura confortável (evitar fundo branco excessivo), atalhos de teclado para agilizar a navegação e fontes legíveis para evitar fadiga visual.

### Cenário B: A Biblioteca/Mobilidade do Aluno
* **Ambiente Físico:** Biblioteca da faculdade, transporte público ou quarto. Dispositivos variados (Laptop, Tablet ou Smartphone).
* **Condições:** Ambiente pode ser barulhento (uso de fones de ouvido) e a conexão com a internet pode oscilar. O tempo de uso é fragmentado (intervalos de aula).
* **Implicação de IHC:** A interface deve ser responsiva (mobile-friendly), com feedback visual claro e imediato.