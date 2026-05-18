# 🔍 Avaliação de IHC através de Inspeção Heurística

Esta inspeção foi realizada pelos integrantes da equipe (Arthur e Danilo), cobrindo todas as telas principais do sistema QuestIA (Input, Feedback, Dashboard, Histórico).

## 1. Referenciais de Avaliação

### Tabela 1 - Conjunto de heurísticas de Nielsen (1994)
| ID | Heurística | Descrição |
| :---: | :--- | :--- |
| 1 | Visibilidade do status do sistema | Feedback constante sobre o que está acontecendo. |
| 2 | Compatibilidade com o mundo real | Linguagem familiar e ordem lógica. |
| 3 | Controle e liberdade do usuário | Saídas de emergência e desfazer/refazer. |
| 4 | Consistência e padrões | Mesmas palavras/ações para as mesmas coisas. |
| 5 | Prevenção de erros | Design que evita problemas. |
| 6 | Reconhecimento em vez de lembrança | Objetos e ações visíveis. |
| 7 | Flexibilidade e eficiência | Atalhos para usuários experientes. |
| 8 | Projeto minimalista e estético | Apenas informações relevantes. |
| 9 | Reconhecer e recuperar erros | Mensagens de erro em linguagem clara. |
| 10 | Ajuda e documentação | Fácil de encontrar e centrada na tarefa. |

### Tabela 2 - Escala de Severidade
- **0 (Sem importância):** Não afeta a operação.
- **1 (Cosmético):** Baixa prioridade estética.
- **2 (Simples):** Problema de baixa prioridade funcional.
- **3 (Grave):** Problema de alta prioridade.
- **4 (Catastrófico):** Deve ser reparado imediatamente.

---

## 2. Consolidação das Violações Encontradas

Abaixo, a tabela consolidada contendo as violações identificadas por ambos os avaliadores em todas as telas.

| Avaliador | Tela | Heurística | Severidade | Problema Identificado | Sugestão de Melhoria |
| :--- | :--- | :--- | :---: | :--- | :--- |
| Arthur | Feedback | 8 (Estética) | 1 | Fonte excessivamente grande no corpo do feedback, causando poluição. | Reduzir tipografia para 16px-18px. |
| Arthur | Input | 3 (Liberdade) | 2 | Falta de botão para cancelar ou voltar sem submeter. | Incluir botão "Cancelar" ou "Sair". |
| Danilo | Dashboard | 6 (Memória) | 2 | Ícones de métricas sem rótulos textuais explicativos. | Adicionar legendas ou *tooltips* permanentes. |
| Danilo | Histórico | 4 (Consistência) | 2 | Termos diferentes para a mesma ação ("Ver Resultado" e "Detalhes"). | Padronizar todos os botões de ação para "Ver Detalhes". |
| Arthur | Login | 5 (Erros) | 3 | O sistema permite clicar em "Entrar" sem preencher os campos, gerando erro genérico. | Desabilitar botão enquanto campos estiverem vazios. |
| Danilo | Feedback | 10 (Ajuda) | 2 | Não há explicação sobre como os critérios da IA foram aplicados na nota final. | Adicionar ícone de informação (?) ao lado de cada critério. |

---

## 3. Avaliação por Integrante (Detalhamento)

### Inspeção por Arthur Soares Sousa
- **Telas Inspecionadas:** Login, Input de Resposta, Feedback.
- **Destaque:** Identificou problemas críticos de controle de fluxo e prevenção de erros que impactam a segurança do aluno.

### Inspeção por Danilo David Miranda
- **Telas Inspecionadas:** Dashboard do Professor, Histórico de Provas.
- **Destaque:** Focou na consistência terminológica e na redução da carga de memória para usuários profissionais (professores).

---

## 4. Indicação de Boas Práticas (Heurísticas Não Violadas)

### Exemplo 1: Visibilidade do status do sistema (Tela de Processamento)
O sistema exibe um *spinner* e a mensagem "A IA está analisando sua resposta..." após a submissão. Isso cumpre a **Heurística 1**, mantendo o usuário informado sobre o tempo de espera.

### Exemplo 2: Compatibilidade com o mundo real (Dashboard)
O uso de um "Mapa de Calor" (verde para acertos, vermelho para erros) utiliza uma metáfora visual familiar para professores, atendendo à **Heurística 2**.
