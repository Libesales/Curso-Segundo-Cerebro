# Aula 03 — Entendendo a Base

## Fonte

- **Título no anexo** — Entendendo a Base.
- **Vídeo** — [Entendendo a Base no YouTube](https://www.youtube.com/watch?v=WlUS6lWySKo).
- **Origem** — transcrição em português com marcações de tempo, no arquivo fornecido `3 - Entendendo a Base.md`. O link do anexo coincide com o enviado. O YouTube ficou indisponível para conferência direta do título e das legendas.
- **Cobertura** — o anexo vai da introdução ao encerramento, com marcas de 00:00 a 21:06. O módulo ficou sem confirmação. As interpretações de grafias duvidosas estão registradas na transcrição.

## Resumo da aula

**Ideia central.** Um segundo cérebro precisa de manutenção para continuar útil. Arquivos curtos de orientação ajudam a IA a chegar às fontes relevantes, enquanto quatro camadas organizam o trabalho: contexto, memória, rotinas e aplicativos conectados.

- **00:00–01:11 · Manutenção da base.** Antes da montagem, o instrutor explica que o sistema precisa receber informações novas e ter registros antigos corrigidos ou removidos. Conhecer sua estrutura ajuda a identificar onde intervir quando a qualidade das respostas cai.
- **01:12–06:15 · O arquivo de orientação como mapa.** Na estrutura demonstrada, arquivos Markdown como `CLAUDE.md` descrevem o conteúdo das pastas e indicam caminhos para os documentos. O instrutor também menciona nomes equivalentes para outros agentes. No exemplo da data de assinatura do contrato de XPTO, a IA consulta o mapa de Clientes, segue para a pasta de XPTO e localiza o contrato pelo mapa dessa pasta. Isso restringe a leitura ao material da pergunta. O instrutor mostra que uma pasta com poucas informações pode dispensar um mapa próprio.
- **06:16–09:52 · Como escrever e revisar os mapas.** O arquivo da comunidade Playbook Lab lista documentos e explica para que servem, como o mapa da comunidade e os registros de produtos, planos e operação. Mapas extensos aumentam o volume lido, enquanto mapas desatualizados podem deixar arquivos importantes fora da busca. Se a IA deixar de localizar informações conhecidas, o instrutor sugere pedir uma revisão dos mapas em relação ao conteúdo real das pastas. Ele adianta que o curso oferecerá *skills* para ajudar na configuração.
- **09:53–13:49 · Camada 1, contexto.** Reúne informações de referência sobre a pessoa e o negócio, como clientes, processos, equipe, perfil de cliente ideal (ICP), tom de voz e exemplos de trabalhos anteriores. Para começar, o instrutor sugere pedir à IA uma entrevista de 50 perguntas, organizar as respostas em documentos e vincular a pasta à ferramenta. Modelos de proposta, apresentações comerciais, planilhas financeiras e listas de leads em CSV também podem fazer parte da base. Revise o material à medida que a operação mudar.
- **13:50–16:39 · Camada 2, memória.** Registra acontecimentos do trabalho, como decisões, aprendizados, tarefas e pendências, muitas vezes em arquivos datados. Esses registros podem servir de contexto mais adiante. Na demonstração, `memory/decisões` reúne oito arquivos Markdown e `memory/diário` reúne 24 registros. A rotina de fim de dia usa conectores para reunir eventos e conversas com clientes e registrar um retrato do dia.
- **16:40–18:22 · Camada 3, rotinas.** São automações que executam processos de forma recorrente ou quando uma ação específica as dispara. Na configuração descrita, podem usar *skills* e um agendador. É a camada que permite ao sistema executar tarefas além da consulta aos arquivos.
- **18:23–19:10 · Camada 4, aplicativos e conectores.** A visualização da base reúne os aplicativos que o instrutor conectou, entre eles Notion, Gmail, Google Agenda, ClickUp e Pipedrive. Os conectores dão às rotinas acesso às ferramentas que fazem parte do trabalho.
- **19:11–21:06 · As quatro camadas em conjunto.** No exemplo da nota fiscal, uma rotina diária usa o conector de e-mail para localizar mensagens de fornecedores. Ao encontrar uma nota, registra o recebimento na memória e guarda o documento na pasta de contexto do fornecedor. O instrutor antecipa que os próximos módulos vão montar as camadas e mostrar como elas se integram.

## Revisão

1. Quais mapas a IA consultaria para localizar a data de assinatura de um contrato? O que cada mapa precisa indicar?
2. Se um agente deixa de encontrar arquivos que existem, como você verificaria se a falha está no mapa da pasta?
3. Onde você guardaria o modelo vigente de proposta e onde registraria a decisão tomada ontem de alterar o prazo comercial? Por quê?
4. No exemplo da nota fiscal, qual é o papel de cada uma das quatro camadas?
5. Que tarefa recorrente do seu trabalho poderia virar uma rotina? Qual seria o gatilho e quais registros ela consultaria ou atualizaria?

## Ideias para minhas aulas

- **Proposta de demonstração.** Monte a pasta de um festival fictício com um índice de fornecedores. Peça que os alunos descubram o horário de entrega do som. Mova a ficha de entrega sem atualizar o índice, repita a consulta e peça que identifiquem e corrijam a referência.
- **Proposta de exercício.** Dê à turma fichas de uma empresa fictícia com seu catálogo de serviços, a política atual de remarcação e anotações datadas sobre decisões e pendências. Peça que organizem os arquivos e expliquem como recuperar a política vigente e o histórico de mudanças.
- **Proposta de simulação.** Em grupos, desenhe uma rotina que lê respostas a um formulário de manutenção, localiza a ficha do equipamento e registra a ocorrência no histórico. Use respostas fictícias para mostrar que informação vem do conector, qual fica na ficha e qual entra no registro datado.
