# Aula 08 — Frontend

## Fonte

- **Título de referência** — Frontend, conforme o arquivo da aula. O título oficial e a descrição do vídeo ficaram sem confirmação.
- **Vídeo** — [Link original no YouTube](https://www.youtube.com/watch?v=KIks5r-CvjA&t=1s).
- **Módulo** — A aula apresenta o módulo de visualização do Segundo Cérebro. A numeração segue a sequência que inclui Intro SB.
- **Origem da transcrição** — `8 - Frontend.txt`, em português, de 00:00 até a última marcação em 13:30. O texto inclui o encerramento da aula. A consulta ao YouTube não retornou legendas nem a duração total.
- **Materiais de apoio** — [8 - FoundersOS.zip](aula-08-frontend-foundersos.zip) (projeto e README) e [8.1 - Prompt.txt](aula-08-frontend-prompt.txt) (roteiro de adaptação para o Claude).

## Resumo da aula

**Ideia central** — O FoundersOS transforma as pastas e os recursos de um Segundo Cérebro em dois espaços de trabalho locais: um grafo para explorar e buscar conhecimento e o Mission Control para acompanhar o dia. A aula demonstra como reaproveitar o projeto e adaptá-lo à estrutura do aluno.

1. **00:00–02:29 — Mapa visual do Segundo Cérebro.** O centro do grafo é o `CLAUDE.md`, ligado aos departamentos que o painel identifica na estrutura do aluno. Os anéis representam as quatro categorias de ARMS: **Applications** (aplicações e conectores), **Routines** (rotinas), **Memory** (documentos e contexto) e **Skills** (habilidades que o agente pode executar). A skill de limpar a caixa de entrada ilustra o último grupo. Na memória, o número em um nó indica quantos arquivos existem dentro da pasta. A legenda permite ocultar departamentos e camadas da visualização.
2. **02:30–05:16 — Busca, agrupamento e expansão.** A busca por palavra-chave encontra arquivos e documentos do cérebro. No exemplo de uma base com 564 documentos, a busca por `inbox` mostra resultados com etiquetas coloridas e permite saltar direto para a skill. O menu oferece diferentes formatos de grafo, agrupamento por departamentos ou pela estrutura de pastas no modo *Ring*, e ajuste de velocidade da rotação. Expandir revela níveis sucessivos de subpastas e documentos. O exemplo de uma pasta de cliente com 38 arquivos mostra como o total se distribui ao abrir o nível seguinte.
3. **05:17–06:28 — Mission Control.** O painel reúne a lista de tarefas (*to-dos*) e o *Morning Brief*, um resumo operacional do dia. O painel personalizado do instrutor também mostra indicadores de YouTube, LinkedIn e Instagram, reuniões do mês, previsão comercial e membros da comunidade. A versão demonstrada para alunos traz as seções de tarefas e *Morning Brief* e oferece espaço para acrescentar indicadores próprios.
4. **06:29–08:44 — Preparar a adaptação.** A demonstração combina o ZIP `FoundersOS` e o prompt de apoio em uma sessão do Claude aberta no contexto do Segundo Cérebro de teste. A IA inspeciona a estrutura real e adapta o código e o mapeamento ao novo conjunto de pastas. O instrutor recomenda um modelo capaz de lidar com a análise e comenta que a tarefa consome tokens. Na demonstração, o plano saiu após cerca de cinco minutos.
5. **08:45–10:36 — Revisar e aprovar o plano.** O Claude identificou sete comandos ou skills, a memória em Markdown, rotinas e conectores da configuração do Claude, como Pipedrive, tl;dv, Google Drive e Notion. Também propôs departamentos e cores para Clientes, Comercial, Conteúdo, Time e Identidade/Infraestrutura. O instrutor sugere revisar nomes e agrupamentos antes de aprovar, como mover Time para dentro de Administrativo ou Financeiro. A aprovação da demonstração incluiu o local do app, o caminho do espelho de tarefas e as melhorias propostas durante a análise.
6. **10:37–12:03 — Abrir e conferir o painel local.** Depois de cerca de nove minutos de configuração, o instrutor abre o painel original na porta `5210` e o novo na `5211`. O Segundo Cérebro de teste tem menos arquivos e gera um grafo menor. A demonstração confere as pastas criadas no curso, a legenda, o menu, o Mission Control e a opção de sincronizar ou atualizar.
7. **12:04–13:30 — Personalizar com IA.** O instrutor fornece um logotipo e pede ao Claude que pesquise a identidade visual da marca, em especial cores e tipografia, e aplique o estilo ao frontend. A demonstração mostra logotipo, amarelo, fundo mais escuro e botões atualizados. O encerramento sugere usar o mesmo processo para acrescentar botões, telas e funções ao painel.

**Detalhes dos materiais de apoio**

- O prompt descreve um aplicativo local em Node.js sem dependências externas. O app fica em pasta própria, aponta para o caminho absoluto da base em Markdown (*vault*) e usa a base para leitura. A exceção descrita para a operação do painel é o arquivo espelho de tarefas, cujo local é definido em `missionControl.mirrorPath`.
- O roteiro pede um inventário de três ou quatro níveis e a revisão do README e dos modelos `config/*.example`. O plano apresenta o mapeamento ARMS, departamentos, cores e o que aparece no grafo por padrão. Após a aprovação, ajustam-se os caminhos e filtros de `config/workspace.json`, as regras de classificação de `config/departments.json` e os caminhos e o padrão de pendências no bloco `missionControl`. O material orienta confirmar o destino do espelho antes de gravar nesse arquivo.
- O teste descrito no prompt inicia o app com `node server.js`, abre o endereço local e compara as contagens de arquivos e nós com a estrutura real. Um grafo vazio ou concentrado em um único departamento merece revisão do mapeamento.
- Segundo o prompt e o README, o *Morning Brief* lê `state/mission.json`, alimentado por uma rotina externa. O formato está em `state/mission.example.json`. Sem essa rotina, o resumo fica vazio e a lista de tarefas pode ser usada. O README descreve a entrada manual de tarefas e a leitura de pendências do diário, com acesso à nota de origem pelo painel.

## Revisão

1. O que cada camada de ARMS representa? Dê um exemplo de cada uma no seu Segundo Cérebro.
2. Quando vale agrupar o grafo por departamentos? Quando a visualização por pastas ajuda mais?
3. O que você conferiria no plano do Claude antes de aprovar a adaptação, incluindo o destino do espelho de tarefas?
4. Como você verificaria se o grafo representa bem sua base? Que sinais indicariam um problema no mapeamento?
5. Que dados alimentam o *Morning Brief* e de onde vêm as tarefas exibidas no Mission Control?

## Ideias para minhas aulas

- **Proposta de exercício de classificação** — Entregue uma base fictícia com atas, uma rotina de revisão semanal, um conector de CRM e uma skill para qualificar oportunidades. Peça a cada grupo que posicione os itens no ARMS e escolha os departamentos que usaria no painel.
- **Proposta de demonstração de busca** — Em uma base fictícia de agência, proponha encontrar um briefing antigo primeiro expandindo as pastas e depois por palavra-chave. Mostre como os dois caminhos ajudam em situações diferentes: explorar a estrutura e localizar um item conhecido.
- **Proposta de personalização funcional** — Peça que cada aluno desenhe um cartão do Mission Control para uma decisão real, como priorizar propostas sem retorno. O exercício deve identificar a fonte dos dados, a frequência de atualização e a ação que o cartão facilita.


## Anexo — Prompt original

Texto integral do arquivo 8.1 - Prompt.txt, material de apoio da aula.

```text
PROMPT:

Vou te passar um projeto chamado FoundersOS. É um app local em Node.js puro (zero dependências, não precisa de npm install) que lê uma pasta de segundo cérebro em markdown e a exibe de duas formas: um grafo orbital interativo e uma tela de Mission Control com Morning Brief e lista de to-dos.

O app foi configurado para a estrutura de pastas de outra pessoa. Sua missão é adaptá-lo à MINHA estrutura, que é diferente.

Onde o app deve morar (leia primeiro)

O app e o meu segundo cérebro são duas pastas separadas e continuam separados:

O app do FoundersOS mora numa pasta própria, FORA do meu segundo cérebro. Ele nunca é copiado para dentro do vault, nem o vault é copiado para dentro dele.
O app apenas lê os conteúdos do vault. Ele aponta para o meu segundo cérebro por caminho (absoluto) na configuração, e é de lá que ele carrega tudo.
A única coisa que o app escreve dentro do vault é o arquivo espelho de to-dos, no caminho definido em missionControl.mirrorPath (ver Fase 3). Fora esse arquivo, o vault é somente leitura para o app.
Se o app ainda não estiver numa pasta separada, a primeira coisa a fazer é colocá-lo numa (ex.: uma pasta irmã do vault), e só então seguir para a Fase 1. Me diga qual pasta você usou para o app e qual é a pasta do meu segundo cérebro antes de continuar.

Contexto

Pasta do app (a instalar fora do vault, conforme acima)
Pasta do meu segundo cérebro (o vault que o app vai ler)

Fase 1: entenda antes de escrever

Liste a estrutura real do meu segundo cérebro, 3 ou 4 níveis de profundidade.
Leia o README.md do app e todos os arquivos em config/*.example para entender o contrato de configuração.
Não escreva nem altere nenhum arquivo nesta fase.

Fase 2: me mostre o plano e espere aprovação

Antes de aplicar qualquer coisa, me apresente:

Como cada pasta minha se encaixa no modelo ARMS do app (A = Applications, R = Routines, M = Memory, S = Skills)
O mapeamento das minhas pastas para departamentos e cores
O que ficará visível no grafo por padrão

Se alguma parte do meu cérebro não encaixar no modelo, me diga em vez de forçar.

Fase 3: aplique

Copie cada config/*.json.example para o config/*.json correspondente (dentro da pasta do app, nunca dentro do vault).
Em config/workspace.json, ajuste: root, memoryDir, memoryIndex, projectsDir, skillDirs, visibleRoots e excludeDirs. O root (e os caminhos derivados) devem apontar para a pasta do meu segundo cérebro, que fica fora do app.
Em config/departments.json, ajuste: departments, pathRules, memoryKeywords, projectPrefixes e default.
No bloco missionControl do workspace.json, ajuste: diaryDir, clientsDir, mirrorPath e pendingHeadingPattern.

ATENÇÃO: o Mission Control ESCREVE um arquivo espelho de to-dos DENTRO do meu segundo cérebro, no caminho definido em missionControl.mirrorPath. Me diga qual caminho você escolheu e confirme comigo antes de rodar qualquer coisa que grave nesse arquivo.

Fase 4: rode e verifique

Suba com: node server.js (porta 5210; se estiver ocupada, PORT=5211 node server.js). Rode a partir da pasta do app.
Abra e me diga quantos arquivos e nós ele escaneou.
Confira se esse número bate com o tamanho real do meu cérebro. Se o grafo vier vazio, ou se tudo cair num departamento só, o mapeamento está errado: investigue e corrija, não me entregue assim.

Sobre o Morning Brief

O app nunca chama API externa: ele só lê state/mission.json. Esse arquivo é escrito por uma rotina externa minha. Enquanto eu não montar essa rotina, o Morning Brief vai aparecer vazio, e isso é o comportamento esperado. O contrato do formato está em state/mission.example.json. A lista de to-dos funciona normalmente desde já.

Regras

O app mora fora do vault e só lê o vault;
Não invente minha estrutura: olhe minhas pastas de verdade antes de decidir, de forma completa para pegar o contexto do negócio e criar o visual de acordo
Não me pergunte o que você consegue descobrir lendo os arquivos.
Ao terminar, me diga em uma linha o que ficou configurado e o que ficou pendente.
```
