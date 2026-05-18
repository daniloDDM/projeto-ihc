# 👥 Personas e Contexto de Uso - QuestIA

Este documento detalha os perfis de usuários do QuestIA, incluindo suas motivações, dores, ganhos e os contextos específicos em que interagem com o sistema.

## 1. Persona Primária: O Professor Corretor

### Identidade
- **Foto:** ![Roberto Almeida](https://raw.githubusercontent.com/arthsousa/projeto-ihc/main/docs/images/persona_professor.png) *(Imagem Local: Roberto Almeida, 52 anos)*
- **Nome:** Roberto Almeida
- **Idade:** 52 anos
- **Cargo:** Professor Adjunto em uma universidade privada e Corretor Credenciado do ENADE.
- **Caracterização Sociocultural:** Classe média alta, reside em metrópole, possui doutorado. Valoriza a meritocracia e a precisão técnica. Tem familiaridade com tecnologia (uso de Office, e-mail e sistemas acadêmicos), mas rejeita interfaces excessivamente complexas ou "modernas" demais que escondam funcionalidades básicas.

### Perfil e Comportamento
Roberto encara a correção como um dever cívico, mas sofre com a carga horária exaustiva. Ele é pragmático e busca ferramentas que aumentem sua produtividade sem sacrificar a qualidade da avaliação.

### Objetivos
- Otimizar o tempo de correção para focar em atividades de pesquisa.
- Reduzir o esforço cognitivo de leitura repetitiva.
- Garantir que nenhum aluno seja prejudicado por oscilações no seu humor ou cansaço.

### Dados que o sistema deve guardar:
- Nome completo e registro funcional.
- Histórico de lotes de correção atribuídos.
- Preferências de interface (ex: modo escuro, tamanho da fonte).
- Logs de alteração de notas sugeridas pela IA (para auditoria).

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
- **Foto:** ![Beatriz Costa](https://raw.githubusercontent.com/arthsousa/projeto-ihc/main/docs/images/persona_aluna.png) *(Imagem Local: Beatriz Costa, 23 anos)*
- **Nome:** Beatriz Costa
- **Idade:** 23 anos
- **Ocupação:** Estudante do 10º semestre de Ciência da Computação, estagiária em uma multinacional de TI.
- **Caracterização Sociocultural:** Classe média, reside em zona urbana, utiliza transporte público. Jovem conectada, "nativa digital", consome conteúdos educacionais via YouTube e TikTok. Sente a pressão do mercado de trabalho e vê o ENADE como uma validação necessária para o seu currículo e para a instituição.

### Perfil e Comportamento
Beatriz é ansiosa e focada em resultados. Ela prefere feedbacks curtos, diretos e acionáveis. Não gosta de ler manuais e espera que a interface seja intuitiva o suficiente para ser usada sem treinamento.

### Objetivos
- Identificar rapidamente suas lacunas de conhecimento técnico.
- Ganhar confiança na escrita acadêmica/técnica exigida pela banca.
- Obter nota máxima no exame para valorizar seu diploma.

### Dados que o sistema deve guardar:
- Nome, e-mail e curso.
- Histórico de simulados realizados e evolução das notas.
- Lista de termos técnicos mais errados/esquecidos.
- Tempo médio de resposta por questão.

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
