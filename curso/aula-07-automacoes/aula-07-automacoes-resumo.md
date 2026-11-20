# Aula 07 — Automações do OS

## Fonte

- **Título de referência** — Automações. O título oficial e a descrição ficaram sem confirmação no YouTube.
- **Vídeo** — [Link original no YouTube](https://www.youtube.com/watch?v=SzQn7Go0w6s).
- **Origem da transcrição** — arquivo fornecido `7 - Automacoes.txt`, em português. A consulta às legendas do YouTube não retornou conteúdo.
- **Cobertura** — aparentemente completa no material fornecido, de 00:00 até a última marcação, em 12:39. A duração total do vídeo ficou sem confirmação.
- **Relação com o curso** — A sequência do curso inclui Intro SB como Aula 01.

## Resumo da aula

**Ideia central** — Use rotinas para executar processos recorrentes do Segundo Cérebro. O instrutor prefere criar uma skill, rodá-la manualmente, ajustar seu comportamento e automatizá-la quando o resultado já atende à necessidade.

- **00:00–02:11 | Automações e painel.** O painel do Segundo Cérebro espelha as rotinas do Claude. Entre os exemplos exibidos estão registro de reuniões, revisão semanal, Squad Sync, novos leads, recuperação de inadimplentes da comunidade e limpeza da caixa de entrada. O instrutor menciona Gemini, GPT, Codex e GPT Work como possibilidades em outros ambientes, sem demonstrar sua configuração.
- **02:12–04:38 | Manutenção e triagem de e-mail.** A manutenção semanal roda às segundas, às 7h30. A limpeza do Gmail roda diariamente às 8h30, analisa e-mails não lidos e faz a triagem de conteúdo de marketing. A rotina usa o modelo Haiku. O campo de instruções pode conter o processo detalhado ou apenas chamar uma skill. O instrutor anuncia skills complementares e um vídeo sobre criação de rotinas.
- **04:39–07:40 | Resumo matinal e painel.** Um *morning brief* pode reunir agenda, e-mails e tarefas pendentes do dia anterior. A skill *Abrir Dia* produz um resumo no chat e pode ser acionada manualmente ou agendada. Na demonstração, ela evoluiu para uma rotina que atualiza o painel com o resumo matinal, tarefas e métricas do negócio.
- **07:41–08:47 | Criação da rotina.** Abra *Routines*, crie uma rotina e selecione a execução local ou na nuvem. O instrutor também demonstra a alternativa de pedir ao Claude que transforme uma skill em rotina e especifique a frequência. O exemplo usa *Abrir Dia* de segunda a sexta, às 8h.
- **08:47–11:43 | Execução local e na nuvem.** No funcionamento descrito, a rotina local é disparada por horário, depende do computador e pode aguardar a próxima abertura se ele estiver desligado. A nuvem atende à execução em horário fixo sem depender da máquina e a eventos externos, como formulário preenchido, pagamento recebido ou contrato assinado. O instrutor mostra dois casos na nuvem. A entrada de um lead pelo site ou LinkedIn exige resposta imediata. O fim de uma reunião comercial aciona a leitura da transcrição, o registro de uma nota no Pipedrive e a preparação de um rascunho de e-mail para envio manual.
- **11:43–12:39 | Primeiros testes.** O instrutor propõe testar com skills existentes, como *Abrir Dia* e *Fechar Dia*, e usar o painel para acompanhar as rotinas e seus resumos. Para a configuração em detalhe, ele indica o [vídeo de apoio Routines](https://youtu.be/NODtcbAplBk).

## Revisão

1. Quando vale a pena transformar uma skill que você usa manualmente em uma rotina?
2. O que precisa estar funcionando no teste manual da skill de manutenção antes de agendá-la?
3. Se um lead chega às 22h com o computador desligado, qual tipo de rotina atende ao caso e por quê?
4. Em que ponto do registro de uma reunião o processo demonstrado devolve o controle à pessoa responsável pelo contato?

## Ideias para minhas aulas

- **Proposta — do comando ao agendamento.** Use uma pasta fictícia de anotações do curso. Peça aos alunos que criem uma skill para listar notas sem título e rodem o mesmo teste duas vezes antes de definir um horário.
- **Proposta — escolha do gatilho.** Distribua três cenários, como conferir tarefas toda sexta, atualizar um painel antes de uma reunião e cadastrar uma inscrição recebida. Peça que cada grupo justifique o ambiente de execução e diga o que acontece se o computador estiver desligado.
- **Proposta — resumo de abertura.** Peça aos alunos que criem um resumo matinal com três prioridades e uma pendência. Depois, acrescente uma métrica e discuta quando o resultado passa a justificar um painel.
