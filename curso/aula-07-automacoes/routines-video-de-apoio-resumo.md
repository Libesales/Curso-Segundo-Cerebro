# Aula — Routines (vídeo de apoio)

## Fonte

- **Título de referência** — Routines (vídeo de apoio). O título oficial e a descrição ficaram sem confirmação no YouTube.
- **Vídeo** — [Link original no YouTube](https://youtu.be/NODtcbAplBk).
- **Origem da transcrição** — arquivo fornecido `7.1 - Automacoes Rotinas.txt`, em português. A consulta às legendas do YouTube não retornou conteúdo.
- **Cobertura** — aparentemente completa no material fornecido, de 00:00 até a última marcação, em 23:52. A duração total do vídeo ficou sem confirmação.
- **Relação com o curso** — Este vídeo complementa a aula de Automações.

## Resumo da aula

**Ideia central** — A configuração de uma rotina começa pela escolha do gatilho e dos recursos de que ela precisa. O instrutor mostra como testar uma skill antes de automatizá-la e como dar acesso aos arquivos e conectores no ambiente em que ela vai rodar.

- **00:00–01:25 | Introdução.** O instrutor apresenta *Routines*, recurso da Anthropic no aplicativo desktop do Claude, como forma de executar processos automaticamente. Mostra onde encontrar rotinas existentes e criar uma nova.
- **01:26–02:47 | Local ou nuvem.** A rotina local é agendada e depende do computador ligado. A rotina na nuvem pode rodar com o equipamento desligado e reagir a eventos externos, como a entrada de um lead ou a assinatura de um contrato. A escolha depende de quanto atraso o processo tolera e de como ele começa.
- **02:48–04:57 | Configuração local.** Defina nome, descrição, instruções, modo de permissão, modelo, pasta ou projeto e frequência. O instrutor sugere o modo automático para evitar interrupções por pedidos de permissão. A pasta vinculada determina quais arquivos podem ser consultados ou editados. Na demonstração, uma execução marcada para as 9h espera até as 11h se o computador só for aberto nesse horário.
- **04:58–07:17 | Skills e conectores.** Uma skill reúne as instruções do processo em um arquivo Markdown ou em um conjunto de arquivos. O instrutor testa a skill *Limpar Inbox* manualmente, ajusta a triagem e agenda uma rotina que apenas chama a skill. A execução usa a pasta autorizada e os conectores configurados. No exemplo, o Gmail é acessado via Composio.
- **07:18–14:07 | Configuração na nuvem.** Escolha modelo e gatilho de horário ou API. O gatilho de API gera um *webhook*, um endereço para receber eventos de outra ferramenta. O instrutor cita integração direta ou via n8n e Make com uma requisição HTTP. Como a nuvem não lê arquivos do computador, ele conecta um repositório GitHub para dar acesso à skill. A demonstração também mostra a seleção de conectores, como ClickUp, e o uso de um *environment* para guardar credenciais de APIs externas separadas do texto da skill e do repositório.
- **14:08–16:36 | Exemplo 1. Limpeza do inbox.** A rotina local roda às 8h30. Uma primeira triagem por palavras-chave reduz a quantidade de e-mails enviados ao modelo e o consumo de tokens. O Claude analisa os demais e o histórico da execução mostra quais mensagens foram marcadas como lidas.
- **16:37–17:39 | Exemplo 2. Morning brief.** Às 8h45, a rotina local chama a skill *Bom Dia* e consulta a pasta do Segundo Cérebro, o e-mail, o calendário, o CRM e a ferramenta da comunidade. O relatório reúne foco do dia, agenda, três prioridades, respostas aguardadas, pendências e atualizações da comunidade.
- **17:40–20:03 | Exemplo 3. Novo lead.** O agendamento do site gera um webhook para a rotina na nuvem, que lê a skill de pós-agendamento no GitHub, cria e enriquece o lead no Pipedrive e usa a API de WhatsApp citada na aula para confirmar a reunião e avisar a equipe. A confirmação inclui data, horário e link do Google Meet.
- **20:04–21:51 | Exemplo 4. Registro de reuniões.** Quando a transcrição fica pronta, a ferramenta de transcrição aciona a rotina via webhook. Reuniões com clientes são registradas no ClickUp e reuniões comerciais no Pipedrive, com histórico e link para a gravação. Rascunho de e-mail e proposta aparecem como extensões possíveis do fluxo.
- **21:52–23:52 | Exemplo 5. Revisão do funil.** A rotina de sexta-feira encontra tarefas atrasadas, negócios sem tarefa, campos incompletos e negociações estagnadas. O instrutor mostra um e-mail para a equipe com 13 negócios sem tarefa e 12 sem valor preenchido, além de próximos passos. Ele indica os recursos gratuitos da comunidade Playbook Lab para consultar os materiais das cinco rotinas.

## Revisão

1. Em que caso a execução às 11h de uma rotina agendada para as 9h é aceitável?
2. Se uma rotina na nuvem precisa ler uma skill que só existe no seu computador, o que falta configurar no fluxo demonstrado?
3. Como um webhook aciona a rotina de registro de reuniões e por que o momento escolhido é importante?
4. Por que a triagem de e-mail do instrutor usa regras de palavras-chave antes de recorrer ao modelo?
5. Qual a diferença entre usar um conector e usar um *environment* para uma API externa?

## Ideias para minhas aulas

- **Proposta — simulação com dados fictícios.** Use um formulário de inscrição e uma planilha de exemplo. Entregue à turma o mesmo registro duas vezes e peça que defina como manter uma única inscrição ao processar o evento repetido.
- **Proposta — mapa de acesso.** Antes de configurar uma rotina, peça que cada aluno liste as fontes que ela precisa ler, os destinos em que pode escrever e onde ficam as instruções da skill. Use um resumo de reuniões fictícias para comparar a execução local com a execução na nuvem.
- **Proposta — triagem em duas etapas.** Distribua 12 mensagens sintéticas. Peça que os alunos separem casos claros com regras simples e reservem os ambíguos para revisão. Compare o volume revisado e as mensagens importantes que cada regra marcou por engano.
