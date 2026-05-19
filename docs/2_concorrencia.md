# 📊 Análise de Concorrência

A análise de concorrência do QuestIA foca em três grandes grupos de soluções que atualmente ocupam o espaço de apoio à correção e estudo, visando identificar padrões de interface e lacunas de experiência do usuário.

## 1. Público-Alvo da Análise
- **Professores Universitários:** Buscam agilidade e ferramentas de gestão de turma.
- **Alunos de Graduação (Concluintes):** Buscam feedback imediato e assertivo para simulados.
- **Coordenadores de Curso:** Interessados em métricas de desempenho institucional.

## 2. Análise Sistemática de Concorrentes

### Grupo 1: Ferramentas de GenAI (ChatGPT / Gemini)
- **Descrição:** Modelos de linguagem de propósito geral.
- **Opinião/Análise de UX:** Usuários elogiam a velocidade, mas reclamam da "alucinação" e da falta de critérios técnicos de bancas como o INEP. A interface de chat puro é cansativa para fluxos de correção em lote.
- **Pontos fortes:** 
    - Intuitiva e fácil de usar (baixo tempo de aprendizado).
    - Suporte a múltiplos formatos (texto, código, listas, Markdown).
    - Boa experiência multiplataforma.
- **Pontos fracos:**
    - Pouca personalização visual para contextos educacionais específicos.
    - Histórico confuso em conversas longas.
    - Falta de ferramentas específicas para correção de exames (como gabaritos estruturados e métricas de banca).
- **Qual nossso diferencial?**
    O QuestIA é especializado no domínio do ENADE, integrando gabaritos oficiais, métricas de discrepância de correção e dashboards estratégicos que as IAs genéricas não oferecem nativamente.
- **Exemplos de Interface:**
<img width="900" height="450" alt="ChatGPT" src="images/concorrente_chatgpt.png" />
<img width="900" height="450" alt="Gemini" src="images/concorrente_gemini.png" />

### Grupo 2: Plataformas de Dashboard (Grafana / Qlik)
- **Descrição:** Ferramentas de visualização de dados e BI.
- **Opinião/Análise de UX:** Professores consideram a interface "poluída" e técnica demais. É difícil extrair um *insight* pedagógico sem treinamento prévio na ferramenta.
- **Pontos fortes:**
    - Visão geral clara e centralizada.
    - Uso eficaz de indicadores visuais (cards, gráficos).
    - Dados críticos destacados rapidamente.
- **Pontos fracos:**
    - Interface densa, intimidadora para usuários não técnicos (professores).
    - Falta de contexto explicativo para métricas pedagógicas.
    - Não possuem integração nativa com processamento de linguagem natural para correção de textos.
- **Qual nossso diferencial?**
    O QuestIA combina a análise de dados com a correção automatizada de textos, oferecendo um dashboard focado em lacunas de aprendizado e métricas de correção humana (como fadiga), simplificando a interface para o ambiente acadêmico.
- **Exemplos de Interface:**
<img width="900" height="450" alt="Grafana" src="images/concorrente_grafana.png" />
<img width="900" height="450" alt="Qlik" src="images/concorrente_qlik.png" />

### Grupo 3: Ambientes Virtuais (Moodle / Google Classroom)
- **Descrição:** Sistemas de Gestão de Aprendizagem (LMS).
- **Opinião/Análise de UX:** Experiência de correção de questões dissertativas é vista como "arcaica", baseada apenas em caixas de texto e notas manuais, sem auxílio cognitivo.
- **Pontos fortes:**
    - Amplamente adotados em instituições de ensino.
    - Centralização de notas e materiais de aula.
- **Pontos fracos:**
    - Ferramentas de correção de questões dissertativas são rudimentares (muitas vezes apenas um campo de texto sem auxílio de IA).
    - Feedback limitado a comentários manuais do professor.
- **Qual nossso diferencial?**
    O QuestIA foca especificamente na automação e qualidade da correção de questões dissertativas complexas, fornecendo feedback instantâneo baseado em critérios técnicos da banca examinadora, o que não é o foco principal dos LMS tradicionais.
---

## 3. Tabela de Padrões e Tendências de Mercado

Abaixo, os principais padrões observados na concorrência que influenciam o design do QuestIA.

| Padrão de Interface | Onde foi observado? | Tendência de Uso | Aplicação no QuestIA |
| :--- | :--- | :--- | :--- |
| **Cards de Métricas** | Grafana / Qlik | Exibição de KPIs de forma rápida e isolada. | Uso de cards para "Índice de Discrepância" e "Média da Turma". |
| **Comparação Lado a Lado** | Google Classroom | Facilita a validação de documentos contra uma referência. | Exibição da Resposta do Aluno vs. Padrão de Resposta do INEP. |
| **Feedback por Cores** | Duolingo / Khan Academy | Uso de semântica de cores (verde/vermelho) para acertos. | Mapa de calor de desempenho das questões. |
| **Chat de Apoio** | ChatGPT / Gemini | Interação em linguagem natural para dúvidas. | Assistente de ajuda para explicar os critérios da nota. |
| **Hierarquia Visual de Dashboard** | Grafana | Destaque para dados críticos no topo da página. | Métricas de urgência (baixa nota da turma) aparecem primeiro. |

## 4. Referências e Fontes
1. [OpenAI - ChatGPT](https://chat.openai.com)
2. [Grafana Labs - Dashboards](https://grafana.com)
3. [Moodle - LMS Platform](https://moodle.org)
4. [Google for Education](https://edu.google.com)
