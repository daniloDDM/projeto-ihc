# 🔄 Ciclo de Vida de Engenharia de Usabilidade

Este documento detalha os requisitos, restrições e metas de usabilidade que orientam o desenvolvimento do QuestIA.

## 1. Características da Plataforma

| Característica | Descrição |
| :--- | :--- |
| **Software** | Interface web responsiva integrada a modelos de NLP (Python/Node). |
| **Hardware** | Desktops/Laptops (Professores) e Laptops/Tablets/Smartphones (Alunos). |
| **Capacidades** | 1. **Feedback Instantâneo:** Processamento em tempo real.<br>2. **Visualização:** Dashboards com mapas de calor.<br>3. **Alertas:** Monitoramento de discrepância e fadiga. |
| **Restrições** | 1. **Conectividade:** Exige internet estável para processamento na nuvem.<br>2. **Domínio:** Focado exclusivamente no padrão de resposta ENADE. |

## 2. Princípios Gerais do Projeto

| Nome | Descrição | Link |
| :--- | :--- | :--- |
| **Contexto de Uso** | Ambiente acadêmico de alta pressão, prazos curtos e necessidade de precisão técnica. | - |
| **LGPD** | Proteção de dados sensíveis de desempenho e identidade. | [Lei 13.709/18](https://www.planalto.gov.br/ccivil_03/_ato2015-2018/2018/lei/l13709.htm) |
| **Acessibilidade** | Garantia de uso por pessoas com deficiências visuais ou motoras. | [Lei 10.098/00](https://www.planalto.gov.br/ccivil_03/leis/l10098.htm) |
| **ISO 9241-11** | Definição de usabilidade como eficácia, eficiência e satisfação. | [Norma ISO](https://www.iso.org/standard/63500.html) |
| **Ética (CNS 510/16)** | Atualização da 196/96: ética em pesquisas em ciências humanas e sociais. | [Res. 510/16](http://conselho.saude.gov.br/resolucoes/2016/Reso510.pdf) |

## 3. Metas de Usabilidade

### 3.1 Qualitativas
- **Confiança:** Transparência nos critérios de IA para que o usuário aceite a nota sugerida.
- **Redução de Carga Mental:** Simplificação de dados complexos em *insights* visuais diretos.
- **Satisfação:** Redução da ansiedade do aluno através de feedback positivo e imediato.

### 3.2 Quantitativas (Critérios Mensuráveis)

| Fator de Usabilidade | Meta Quantitativa (KPI) | Justificativa |
| :--- | :--- | :--- |
| **Eficiência** | Professores devem localizar a questão com pior desempenho em **menos de 45 segundos**. | Reduzir o tempo de análise macro da turma. |
| **Facilidade de Aprendizado** | 90% dos alunos devem conseguir submeter o primeiro simulado **sem erros de interação**. | Interface intuitiva que dispense manuais. |
| **Segurança (Erros)** | Máximo de **1 erro crítico** (ex: fechar sem salvar) por sessão de 1 hora. | Prevenir perda de trabalho devido à interface. |
| **Memorização** | Usuários que retornam após 30 dias devem realizar a tarefa principal em **até 2 minutos**. | Interface consistente que suporte o uso sazonal. |
| **Satisfação** | Média de pontuação no questionário SUS (System Usability Scale) **acima de 75**. | Garantir uma percepção de qualidade superior à concorrência. |
