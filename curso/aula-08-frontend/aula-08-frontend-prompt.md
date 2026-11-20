# Aula 08 — Frontend

## Prompt original do FoundersOS

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
