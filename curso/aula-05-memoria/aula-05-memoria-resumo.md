# Aula 05 — Memória

## Fonte

- **Título** — Memória
- **Vídeo** — [Memória no YouTube](https://www.youtube.com/watch?v=6PaEvxPMAG4)
- **Módulo** — memória do Segundo Cérebro, após a etapa de configuração do OS.
- **Origem da transcrição** — arquivo fornecido `5 - Memoria.md`, cujo cabeçalho contém o mesmo ID do vídeo. O material vai de 00:00 à fala final iniciada em 26:25. A duração e as legendas no YouTube ficaram sem confirmação direta.

## Resumo da aula

**Ideia central.** A configuração inicial dá ao Segundo Cérebro um ponto de partida. A camada de memória mantém o sistema atualizado sobre projetos, clientes, decisões e pendências. O professor propõe registrar o que aconteceu no fim do expediente, consultar a memória ao começar o dia e revisar o conjunto ao fechar um ciclo.

### 00:00–09:28 · Quatro mecanismos de memória

| Tempo | Mecanismo | O que registra e como é atualizado |
| --- | --- | --- |
| [00:45](https://www.youtube.com/watch?v=6PaEvxPMAG4&t=45s) | Diário | Pasta com um arquivo Markdown por dia. O registro reúne o que aconteceu a partir das sessões do Claude, dos aplicativos conectados e dos arquivos do próprio OS. Se as reuniões forem uma fonte importante, o sistema precisa de acesso às gravações ou transcrições, que também podem ser fornecidas manualmente. |
| [03:21](https://www.youtube.com/watch?v=6PaEvxPMAG4&t=201s) | Decisões | Pasta com um arquivo por decisão, identificado por data e título. Serve para recuperar escolhas que mudam o rumo de um projeto ou das prioridades. Quem usa o OS pode acionar `/decidir`, ou confirmar quando o Claude sugere registrar uma decisão da conversa. |
| [05:39](https://www.youtube.com/watch?v=6PaEvxPMAG4&t=339s) | Aprendizados | Arquivo Markdown com uma lista de lições úteis para trabalhos futuros, como a correção de um erro ou uma preferência de trabalho. O Claude pode registrar itens por iniciativa própria ou a pedido. O setup mostrado já inclui o arquivo, e a aula orienta fazer o pedido em linguagem natural. |
| [06:51](https://www.youtube.com/watch?v=6PaEvxPMAG4&t=411s) | Prioridades | Arquivo com metas do período e projetos importantes. O professor usa a criação do minicurso como exemplo de prioridade do mês. O briefing matinal recupera essas prioridades e a revisão periódica ajuda a confirmar se continuam valendo. |

O professor dá mais ênfase ao diário. Na rotina demonstrada, o registro depende de executar o fechamento do dia. Decisões, aprendizados e prioridades são atualizados quando surgem fatos relevantes.

### 09:29–17:58 · Comandos para colocar a memória em uso

1. **[09:47–12:40](https://www.youtube.com/watch?v=6PaEvxPMAG4&t=587s) · Fechar dia.** A skill reúne o contexto da sessão atual e, quando disponíveis, as demais sessões do dia. Escreve o diário datado em Markdown, por cliente ou tema, com acontecimentos, decisões e combinados, além de pendências para amanhã. Atualiza registros dos clientes quando couber, sugere `/decidir` para mudanças de rumo e encaminha lições ao arquivo de aprendizados. Se o expediente terminar depois da meia-noite, indique a data que deve ser fechada.
2. **[12:40–15:17](https://www.youtube.com/watch?v=6PaEvxPMAG4&t=760s) · Abrir dia.** Lê o diário, as prioridades e as pendências anteriores para montar um briefing matinal. No exemplo do professor, aparecem o foco do dia, a agenda, as reuniões semanais com clientes, os follow-ups vencidos, as três prioridades principais e a situação comercial. A estrutura vem da entrevista do setup. A aula mostra como explicitar as fontes que o briefing deve consultar, como Google Agenda e Pipedrive.
3. **[15:17](https://www.youtube.com/watch?v=6PaEvxPMAG4&t=917s) · Decidir e agendar as rotinas diárias.** Use `/decidir` quando uma decisão merecer registro. A aula antecipa a possibilidade de agendar a abertura e o fechamento do dia para horários definidos. Na demonstração, as duas rotinas são acionadas manualmente.
4. **[15:48–17:58](https://www.youtube.com/watch?v=6PaEvxPMAG4&t=948s) · Revisar.** Conduz uma revisão de cerca de dez minutos para fechar um ciclo. Consulta prioridades, clientes, comercial, diário, inbox e estado do OS. Mostra acontecimentos e alertas, como follow-ups atrasados, e ajuda a tratar itens do inbox do próprio Segundo Cérebro, revisar decisões e aprendizados e definir o próximo período. A frequência é flexível. O professor sugere, por exemplo, sexta-feira ou segunda-feira para a revisão semanal, ou uma revisão quinzenal.

### 17:59–26:25 · Conectar fontes e ajustar os comandos

1. **[18:30–21:51](https://www.youtube.com/watch?v=6PaEvxPMAG4&t=1110s) · Liste as fontes em que ficam os fatos que você quer lembrar.** Exemplos da aula incluem tl;dv, Granola e Fireflies para reuniões, e-mail para propostas e conversas, Slack e Teams para mensagens internas, WhatsApp para conversas externas, planilhas e arquivos de acompanhamento, ClickUp para projetos e Pipedrive para o comercial. Se uma ferramenta conectada acrescenta pouco ao diário, deixe sua consulta fora da rotina de fechamento para reduzir tempo e custo.
2. **[21:51–24:24](https://www.youtube.com/watch?v=6PaEvxPMAG4&t=1311s) · Conecte os aplicativos escolhidos.** Na demonstração, o professor pesquisa Pipedrive e Gmail na biblioteca de conectores do Claude. Se a integração faltar, ele mostra o caminho de adicionar um conector personalizado com nome e URL do servidor MCP. Também menciona o Composio como intermediário para ligar outros serviços ao Claude.
3. **[24:45–25:59](https://www.youtube.com/watch?v=6PaEvxPMAG4&t=1485s) · Atualize as skills e repita o ciclo conforme surgirem necessidades.** Em uma sessão nova, identifique o comando e descreva a mudança em linguagem natural. No fechamento, indique quais informações coletar do aplicativo recém-conectado. Na abertura, especifique o formato do briefing e as fontes que devem alimentá-lo.
4. **[25:59–26:25](https://www.youtube.com/watch?v=6PaEvxPMAG4&t=1559s) · Faça o exercício da aula.** Liste os aplicativos relevantes, conecte pelo menos alguns e ajuste os comandos já criados no setup. Em seguida, use **Fechar dia** ao encerrar o expediente, **Abrir dia** ao recomeçar e `/revisar` ao concluir a semana ou a quinzena.

## Revisão

1. Em que situações você usaria o diário, o registro de decisões, o arquivo de aprendizados e o de prioridades?
2. Que informações o fechamento de hoje precisa registrar para que a abertura de amanhã ajude a escolher a primeira ação do dia?
3. Quais fontes guardam os acontecimentos mais relevantes do seu trabalho? O que você pediria ao fechamento para recuperar de cada uma?
4. Ao revisar o ciclo, como você trataria um follow-up vencido, uma decisão que mudou o projeto e uma meta que perdeu prioridade?

## Ideias para minhas aulas

- **Proposta · Um expediente, quatro registros.** Dê à turma o relato de uma empresa fictícia que recebeu um pedido de mudança de escopo, corrigiu um erro recorrente de orçamento e marcou uma entrega prioritária. Peça que os alunos distribuam os fatos entre diário, decisões, aprendizados e prioridades e expliquem o que precisa aparecer no briefing seguinte.
- **Proposta · Feche hoje, abra amanhã.** Em duplas, uma pessoa escreve o fechamento com base em uma agenda e duas notas de reunião fictícias. A outra recebe os registros produzidos e monta um briefing de cinco linhas. Ao comparar o briefing com os materiais de partida, a dupla identifica qual registro do fechamento teria evitado uma lacuna.
- **Proposta · Escolha de fontes com orçamento de tempo.** Entregue cinco fontes fictícias e permita que a turma inclua apenas duas no fechamento. Cada grupo define qual dado buscar, como esse dado será usado e que sinal justificaria incluir uma terceira fonte.
