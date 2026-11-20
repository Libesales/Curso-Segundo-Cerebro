# Aula — Routines (vídeo de apoio)

- **Título de referência** — Routines (vídeo de apoio). O título oficial e a descrição ficaram sem confirmação no YouTube.
- **Vídeo** — [Link original no YouTube](https://youtu.be/NODtcbAplBk).
- **Origem da transcrição** — arquivo fornecido `7.1 - Automacoes Rotinas.txt`, em português. A consulta às legendas do YouTube não retornou conteúdo.
- **Cobertura** — aparentemente completa no material fornecido, de 00:00 até a última marcação, em 23:52. A duração total do vídeo ficou sem confirmação.
- **Relação com o curso** — Este vídeo complementa a aula de Automações.

## Notas de leitura

- **00:00–01:01** — “Antropic” e “Cloud” correspondem provavelmente a Anthropic e Claude. O nome próprio transcrito como “Víor” em **00:20** e a expressão “um novo ch” em **02:08** ficaram sem identificação segura.
- **06:49 e 14:32–15:03** — “Composeial”, “Composel”, “Compose” e variantes parecem indicar Composio. “autorização ou alf”, em **14:55**, pode se referir a OAuth.
- **08:09** — “NN” e “nod” parecem indicar n8n e *node*, respectivamente. **08:40–10:26** — “gitub” indica GitHub.
- **17:48–18:10** — “call.com” parece indicar Cal.com. **18:27** — “Zapi” provavelmente indica Z-API. **18:44–19:07** — “pipeedrive” indica Pipedrive.
- **20:51–21:15** — “TLDV” e “TldV” indicam provavelmente tl;dv. “Webook” corresponde a *webhook*.

## Transcrição original

Capítulo 1: Introdução às Routines
0:000 segundoUm tempo atrás, Antropic lançou uma função chamada routines ou rotinas.
0:044 segundosBasicamente, uma maneira de construir automações dentro do próprio cloud para executar processos sem você precisar ficar dando comandos para irá ou até mesmo estar na frente do computador.
0:1212 segundosNesse vídeo aqui, eu vou te explicar todos os detalhes das rotinas e também te entregar de graça cinco automações para vendas que eu uso todos os dias. Se você é novo por aqui, seja muito
0:2020 segundosbem-vindo ao canal. Meu nome é Víor, eu sou fundador da Playbook Lab, uma agência de IA para vendas. Nos últimos anos, eu e a minha equipe já implementamos automações e há para mais
0:2828 segundosde 70 negócios diferentes. E aqui nesse canal eu compartilho um pouco dos nossos aprendizados nesse universo de inteligência artificial e vendas. Então se esse tema te interessa, não esquece
0:3636 segundosde se inscrever para não perder os próximos conteúdos. Todo o material desse vídeo vai estar disponível lá na comunidade da Playbook Lab, junto com mais de 40 outros tutoriais e materiais.
0:4545 segundosVocê pode pegar tudo de graça, basta acessar o link que tá aí na descrição. E se você quiser ter acesso a recursos exclusivos, como aulas, lives todas as
0:5353 segundossemanas e um grupo no WhatsApp super valioso, você pode se inscrever como membro VIP da comunidade. Agora bora pro vídeo. Dentro do app desktop do Cloud
1:011 minuto e 1 segundoinstalado aí no seu computador, as rotinas ficam nesse menuzinho aqui do canto esquerdo, routines. Aqui embaixo ficam pinadas, ó, todas as rotinas que você já tem rodando para você. Elas
1:101 minuto e 10 segundosaparecem aqui dentro também do painel e você consegue aqui criar uma nova rotina. Uma rotina pode rodar tanto localmente no seu computador quanto na nuvem. E aqui já começa a complicar a
1:181 minuto e 18 segundosvida da maioria das pessoas. Então eu quero dar um passo atrás e explicar a diferença entre rodar uma rotina localmente no seu computador e na nuvem para que você não tenha mais dúvida de
Capítulo 2: Local vs Nuvem
1:261 minuto e 26 segundoscomo isso funciona. A primeira diferença é que a rotina que roda localmente, ela precisa do seu computador ligado para funcionar. Então basicamente você vai ter que estar na frente do seu
1:341 minuto e 34 segundoscomputador. Já uma rotina que roda na nuvem não precisa do seu PC ligado. Você vai poder estar fazendo outra coisa, vai poder estar dormindo e essa automação,
1:421 minuto e 42 segundosessa rotina vai acontecer. E a outra diferença relevante é que nas rotinas locais, o único gatilho, você pode acionar ela a partir de um horário
1:491 minuto e 49 segundosagendado uma vez por dia às 9 da manhã ou toda semana na segunda-feira às 8 ou então a cada 1 hora, durante os dias de semana, você pode personalizar o
1:581 minuto e 58 segundoshorário, mas a única forma de você ativar ela é com um gatilho de horário.
2:012 minutos e 1 segundoJá as rotinas de nuvem você pode ativar a partir de um evento externo. Por exemplo, um novo lead que você recebeu no seu site, um novo contrato assinado,
2:082 minutos e 8 segundosum novo ch, um pedido de cancelamento na sua plataforma, um e-mail que você recebeu. Todos esses são eventos de softwares externos que estão acionando
2:162 minutos e 16 segundosuma automação dentro do seu cloud, porque ela tá rodando na nuvem.
2:192 minutos e 19 segundosImportante frisar que não tem nem certo nem errado para isso aqui. É mais o seu entendimento de quais são as automações que você precisa que rodem na nuvem, porque elas precisam rodar em um horário
2:272 minutos e 27 segundosque você não necessariamente tá na frente do computador ou a partir de um evento externo. Ou então as automações que podem rodar localmente porque você não tem e imediatismo que elas
2:352 minutos e 35 segundosaconteçam, elas não dependem de um evento externo e geralmente são aquelas que você não tem problema de, pô, acionar só a hora que você abrir o computador, né? Então bora voltar aqui
2:432 minutos e 43 segundospro cloud e mostrar como é que configura primeiro uma rotina que roda localmente.
2:482 minutos e 48 segundosNela você vai poder configurar o nome e uma descrição. A parte mais importante são as instruções. Eu já vou explicar a melhor forma de você construir as instruções de uma rotina. Você pode
2:572 minutos e 57 segundosconfigurar se ela vai rodar no piloto automático ou se vai pedir permissão. Eu aconselho deixar sempre aqui no modo automático, porque daí ela não vai ficar te pedindo para clicar lá naquelas permissões quando ela for rodar, né?
Capítulo 3: Configurando Rotinas Locais
3:063 minutos e 6 segundosVocê pode escolher também qual que é o modelo do da Antropic que vai rodar por trás dessa automação e qual pasta ou projeto do seu computador você quer
3:133 minutos e 13 segundosatrelar a essa rotina. Essa parte é bem importante porque quando essa rotina for acontecer, ela pode tanto consultar informações e arquivos dentro do seu
3:213 minutos e 21 segundoscomputador ou até mesmo modificar, inserir e editar os arquivos. E a rotina só vai fazer isso nos arquivos, documentos, informações que tiverem nas
3:293 minutos e 29 segundospastas que você vincular aqui. Então, se você escrever uma instrução aqui para ela criar um novo documento de texto numa numa pasta tal e deixar salvo e
3:373 minutos e 37 segundosvocê não selecionar qual é a pasta onde ela onde você quer que ela salve essa informação, ela não tem acesso, ela não vai conseguir rodar do jeito certo. E por último, a gente tem como selecionar
3:453 minutos e 45 segundosqual é a frequência ou horário exato em que essa automação vai acontecer. Eu mencionei antes que as rotinas locais elas precisam do seu computador aberto.
3:533 minutos e 53 segundosVamos supor que você criou uma rotina para rodar diariamente às 9 da manhã, mas em algum dia você não estava com o computador aberto às 9 da manhã. O que que acontece? Nesse dia específico, essa
4:014 minutos e 1 segundorotina vai ficar numa fila de espera, esperando você abrir o seu computador.
4:054 minutos e 5 segundosEntão, se você abrir seu computador às 11 da manhã, ela vai começar a rodar.
4:084 minutos e 8 segundosAssim que você abrir o computador, às 11 da manhã, ela começa a funcionar. Então, de volta, se você tem alguma automação que você precisa que rode todos os dias
4:154 minutos e 15 segundosàs 9, na maioria dos dias você vai estar lá disponível com o computador aberto, mas sei lá, de vez em quando você não está, é melhor você transformar numa
4:234 minutos e 23 segundosrotina que roda na nuvem para garantir que isso aconteça às 9 horas da manhã.
4:264 minutos e 26 segundosSe não tem problema essa rotina atrasar, se não tem problema um dia você não trabalhar, não abrir o computador, aí tudo bem. Aí eu aconselho que você deixe essa rotina rodando é nesse formato
4:344 minutos e 34 segundoslocal, até porque ela é mais fácil de configurar. Antes da gente avançar para as rotinas que rodam na nuvem, deixa eu te falar como é que é a melhor forma de você construir as instruções aqui dentro
4:434 minutos e 43 segundosdessa rotina, porque esse é um erro bem comum de pessoas que tentam usar, acabam não tendo resultado que esperam e daí deixa de utilizar as rotinas e fica
4:514 minutos e 51 segundosusando só o cloud com os comandos e promps normais do dia a dia. Então eu vou te dar um hackzinho aqui que vai facilitar muito na hora de você criar as
4:584 minutos e 58 segundossuas automações. Minha sugestão é que você crie primeiro uma skill igual essa que eu tenho aqui chamada limpar inbox.
5:045 minutos e 4 segundosBasicamente é uma skill que toda vez que eu aciono, ela faz uma triagem da minha caixa de e-mail. Então, ela vai pegar toda a minha caixa de e-mail, os e-mails não lidos, ler cada um deles e entender
5:125 minutos e 12 segundosse eles são e-mails eh relevantes para mim ou se são e-mails de marketing, coisas aleatórias que podem ser descartadas. Eu construí essa skill
5:205 minutos e 20 segundosfinalmente para ser um comando, para eu acionar ela. Então, se eu digitar aqui barra limpeza, ela aparece aqui, ó, limpar em box, né, essa skill. E toda vez que eu sentia que minha caixa de
Capítulo 4: Otimizando com Skills
5:295 minutos e 29 segundose-mail estava muito cheia, eu acionava essa skill, ela rodava, fazia limpeza por mim e eu ficava com a minha caixa de e-mail só com os e-mails relevantes. Só depois disso eu transformei essa skill
5:375 minutos e 37 segundosem uma rotina. Então a minha rotina limpar em box, basicamente a a aba de instrução lá, que é o prompt, né, as instruções dessa skill, pede para que o
5:455 minutos e 45 segundosClod rode a skill tal. Então eu não preciso escrever o que é, né, todo o processo de limpeza, o que que ela tem que entender como um e-mail bom e um
5:535 minutos e 53 segundose-mail ruim. eh as linhas de código que ela usa para fazer essa limpeza. Não preciso nada disso. Nas instruções da rotina, eu simplesmente peço que ela
6:026 minutos e 2 segundosrode a skill, limpar em box. E daí eu não preciso de um grande bloco de instruções aqui. A maior vantagem disso é que quando você cria uma skill, você
6:096 minutos e 9 segundosconsegue rodar ela por comando várias vezes, reiterar, entender se ela tá funcionando de fato para você. E só depois disso, só depois de você ter a garantia de que ela tá funcionando, que
6:176 minutos e 17 segundostá dando certo, você transforma ela numa rotina. Então, basicamente, as rotinas que rodam localmente são skills que você agenda o horário para que elas aconteçam
6:266 minutos e 26 segundosde forma automática. É praticamente a mesma coisa, tá? Outra coisa importante de falar é que as rotinas que rodam localmente, elas têm acesso não só às
6:346 minutos e 34 segundospastas, à informações dentro do seu computador, mas também aos conectores que você tem configurados dentro do seu cloud. No exemplo que eu acabei de
6:416 minutos e 41 segundosmostrar, o Cláudio não conseguiria ler os meus e-mails para decidir quais são relevantes e também não conseguiria marcar esses e-mails como lidos se ele
6:496 minutos e 49 segundosnão tivesse acesso ao meu Gmail. No meu caso, o Gmail tá conectado via Composio e lá na skill tem a instrução de como o Cloud ler os meus e-mails através desse
6:586 minutos e 58 segundosconector. Então você pode criar a skill ou as instruções lá da rotina numa boa, escrevendo que você precisa que use um MCP específico ou conector específico
7:067 minutos e 6 segundospro software externo que você quer. E essa rotina vai rodar numa boa, fazendo essas ações, lendo ou modificando, né, informações dentro desses softwares
7:147 minutos e 14 segundosexternos através dos próprios conectores que você tem aqui dentro do seu cloud.
7:187 minutos e 18 segundosAgora bora falar das rotinas que rodam na nuvem. Aqui eu vou ter que mostrar algumas coisas que talvez sejam um pouquinho mais técnicas, mas não tem nada de muito complicado não, tá? Nas
7:257 minutos e 25 segundosrotinas em nuvem você também consegue configurar o nome e as instruções, selecionar o modelo que você quer que essa rotina use para rodar. Consegue também escolher uma data e horário, né?
7:347 minutos e 34 segundosUm um gatilho de horário, igual a gente viu nas rotinas locais, mas praticamente todo o resto aqui é diferente. E eu vou te mostrar o que que muda. A primeira
7:427 minutos e 42 segundosdiferença é que na hora de selecionar um gatilho pra sua automação, você pode escolher a API. O que isso aqui faz é criar um web hook do próprio Cloud para que você possa chamar de forma externa.
7:537 minutos e 53 segundosBasicamente uma porta que você abre para poder enviar eventos de softwares externos. Dessa forma você pode fazer com que eventos, por exemplo, do seu CRM
8:018 minutos e 1 segundoenviem informações para dentro do cloud e iniciem esse processo da rotina. Dá para fazer isso conectando o web hook diretamente nas suas ferramentas
Capítulo 5: Configurando Rotinas na Nuvem
8:098 minutos e 9 segundosexternas ou então usando ferramentas tipo NN ou make, usando aquele nod, né? Requisição HTTP funciona da mesma forma.
8:178 minutos e 17 segundosOutra diferença relevante é que como essa rotina aqui ela tá rodando na nuvem, ela não tem acesso às informações que estão dentro do seu computador. Ou
8:258 minutos e 25 segundosseja, qualquer tipo de documento que você precisa que essa rotina tenha acesso e esse documento mora dentro do seu computador, ela não vai conseguir
8:328 minutos e 32 segundosacessar. Para resolver isso, você precisa enviar esse documento também pra nuvem. E o Cloud permite que você faça isso através de um repositório lá do
8:408 minutos e 40 segundosGitHub. Eu sei que isso assusta um pouquinho a galera que não é muito técnica, mas é extremamente simples de você fazer. Basta você criar uma conta
8:488 minutos e 48 segundospara você dentro do GitHub, conectar essa conta com o Cloud através dos MCPs, os conectores, né? Super simples de fazer. E uma vez que você fizer isso,
8:568 minutos e 56 segundosbasta pedir pro Cloud mesmo, conversa com ele aqui para subir esse documento pra conta do GitHub. Ele vai subir para lá sem você precisar nem encostar mais no GitHub, tá? Quando você fizer isso,
9:059 minutos e 5 segundosesse repositório, essa pasta, né, que o GitHub cria lá dentro do sistema deles, vai aparecer como uma das opções para você conectar aqui na sua na sua rotina.
9:149 minutos e 14 segundosDeixa eu te dar um exemplo de uma coisa que eu faço usando, né, essa essa conexão pras minhas rotinas, você entender mais ou menos o o que que é isso, né, e por que isso é importante.
9:239 minutos e 23 segundosLembra que agora h pouco eu falei para vocês que a nas instruções, ao invés de você escrever toda a automação que ela deve fazer aqui, você pode chamar uma
9:309 minutos e 30 segundosskill. Uma skill nada mais é do que um documento de instruções. É um arquivo de texto, né, um ponto MD ou um arquivo ou um conjunto de arquivos. Nas rotinas que
9:399 minutos e 39 segundosrodam localmente no meu computador, o Cloud tem acesso a esse documento pon md a essa skill e daí ele consegue fazer a rotina funcionar. Se eu escrever aqui
9:479 minutos e 47 segundoschame a skill tal ele funciona. Agora, se eu fizesse a mesma coisa numa rotina da nuvem não vai funcionar porque a hora que eu escrevo chame a a skill tal, ele
9:569 minutos e 56 segundosvai procurar essa skill, está na nuvem, ele não tem acesso ao meu computador, ele não vai achar esse documento, né?
10:0110 minutos e 1 segundoEntão, para configurar rotinas na nuvem, do mesmo jeito que eu eu configuro, que eu mostrei como configurar as rotinas locais usando as skills que você já construiu, você precisa fazer com que
10:0910 minutos e 9 segundosessa skill suba lá pro gitub. Então, tá aqui a importância, né? Pelo menos se você for construir igual eu tenho construído, que é usando as skills para depois transformar em rotinas, você vai
10:1810 minutos e 18 segundosprecisar que essa skill que você quer acionar de forma remota, né, na nuvem, que ela esteja lá no gitub numa num repositório, numa pastinha lá do teu
10:2610 minutos e 26 segundosGitHub, senão o Cloud não vai conseguir acessar, não vai conseguir ler o que tem dentro dessa skill. Bom, dito isso, é, tem mais duas diferenças que existem
10:3410 minutos e 34 segundosentre as rotinas locais e as na nuvem, tá? Uma delas é essa opção aqui de configurar um environment, né, um ambiente para você colocar acessos que
10:4310 minutos e 43 segundossão secretos, né, chaves API e tudo mais para dar a capacidade do cloud e executar às vezes linhas de comando ou chamadas de API que precisam das suas credenciais.
10:5310 minutos e 53 segundosE isso aqui é muito parecido com os próprios conectores que a gente vê aqui embaixo e vocês já conhecem como funciona. A diferença é que quando você tem um conector disponível que você já
11:0211 minutos e 2 segundosconfigurou, você pode deixar ele selecionado. Então vamos supor que nessa rotina que eu tô construindo, eu quero que ele adicione novas tarefas dentro do
11:1011 minutos e 10 segundosClickup. Eu posso tirar todas as outras aqui, até para que o Cloud não se confunda com o excesso de conectores. E eu deixo o Clickup. O Clickup é uma
11:1811 minutos e 18 segundossolução, né? Uma ferramenta que já está conectada ao cloud. é uma conexão nativa, né? Então já tem essa integração
11:2511 minutos e 25 segundose mesmo essa rotina rodando na nuvem, ela o Cloud vai ter acesso, né, ao Clickup, vai conseguir executar as coisas que você precise que execute.
11:3211 minutos e 32 segundosAgora vamos supor que durante essa rotina você precisa chamar um software externo usando API de algum software que não tem um conector disponível. Um caso
11:4111 minutos e 41 segundosclássico disso é o WhatsApp. O WhatsApp ainda não tem conexão nativa aqui com o clube. Se você pesquisar lá na biblioteca de conectores, você não vai achar WhatsApp. Você não vai achar nenhuma API relacionada ao WhatsApp.
11:5111 minutos e 51 segundosEntão, nesse caso, você precisa usar de forma externa. Quando você vai usar essas ferramentas e APIs externas, você precisa das suas credenciais, as suas
11:5911 minutos e 59 segundoschaves, que são só suas, né? E o ideal é que você não coloque essas chaves dentro do texto da skill para que o Cloud use, porque isso é extremamente arriscado.
12:0812 minutos e 8 segundosEntão o que o Cloud fez foi deixar um ambiente aqui, né, essa opção de você criar um novo ambiente seguro, só para escrever quais são as suas chaves. E
12:1612 minutos e 16 segundosquando a skill for utilizar, ela vai ter lá no texto dela assim: "Ah, você nessa hora você precisa enviar uma mensagem no WhatsApp pro número do lead. Como enviar
12:2412 minutos e 24 segundosa mensagem? você vai chamar uma API externa com essas informações e daí você vai consultar os tokens, né, os segredos dentro do ambiente que eles chamam de environment, né, um ambiente seguro.
12:3512 minutos e 35 segundosEsse ambiente aqui ele faz com que eh nada eh vaze, né, que você não precise, por exemplo, subir isso pro GitHub e tal. Então, é um ambiente que o Cloud criou seguro para você poder depositar
12:4312 minutos e 43 segundosas suas chaves caso você precise e acionar softwares externos via API, que não estão conectados, né? Não tem os conectores nativos aqui do cloud. Eu não
12:5212 minutos e 52 segundosvou me aprofundar muito em como fazer isso, porque o próprio cloud pode te ajudar a criar esses environments. Ele cria ali o texto. Você simplesmente copia e cola aqui é dentro dessa opção,
13:0013 minutostá? Então aqui, ó, tem um formatinho, né, que ele precisa que seja construído.
13:0413 minutos e 4 segundosVocê pode pedir pro cloud criar esse formato e daí sim você traz essas informações para cá com as suas chaves, com seus tokens e tudo mais. E também
13:1113 minutos e 11 segundosnão vou me aprofundar muito porque na maioria das vezes, 90, 95% das vezes, as suas rotinas não vão precisar de acessos
13:1913 minutos e 19 segundosa softwares externos com API e tal. você vai conseguir fazer através dos próprios conectores que você já tem aí dentro do seu cloud. Bom, dessa forma a gente
13:2613 minutos e 26 segundosencerra por aqui essa explicação que era para ser curta, acabou sendo longa, mas eu gosto de fazer com que vocês entendam, né, eh, o funcionamento das coisas e não só saiam copiando, porque
13:3513 minutos e 35 segundoseu eu quero que vocês tenham liberdade de construir as próprias skills, as próprias rotinas, configurar as próprias automações, até porque essas coisas são
13:4313 minutos e 43 segundosmuito particulares, né? Os meus processos, as ferramentas que eu uso são totalmente diferente das que você usa aí. Então, por mais que eu sempre disponibilize muita coisa para vocês de
13:5113 minutos e 51 segundosgraça, para vocês pegarem, copiarem, clonarem, nunca vai funcionar. Se você só, né, der dois cliques, e quiser que funcione para você, você vai ter que configurar de uma forma ou de outra.
13:5913 minutos e 59 segundosEntão, eu gosto que vocês entendam o conceito das coisas para você ganhar essa autonomia, poder construir eh as coisas que você precisa para você, pro seu dia a dia, pra sua empresa, né?
14:0814 minutos e 8 segundosVamos falar agora sobre as cinco rotinas que eu uso no meu dia a dia aqui, principalmente pro meu comercial. Vou mostrar rapidinho como elas funcionam e também te mostrar como é que você pode
14:1614 minutos e 16 segundoster acesso a elas para depois personalizar aí para você. A primeira rotina é a própria limpeza do inbox, né, do meu e-mail, que eu mostrei mais cedo
14:2414 minutos e 24 segundospara você. Essa é uma rotina que eu tenho configurada para rodar localmente, tá? Todo dia às 8:30 da manhã. Quando eu não acordo nesse horário, ela roda assim
14:3214 minutos e 32 segundosque eu abro o meu computador. Ela tá conectada, obviamente ao meu Gmail através de uma ferramenta chamada Composeial. Basicamente o Composel é um
14:3914 minutos e 39 segundoshub que te permite conectar várias ferramentas lá dentro e você conecta só o compose no Cloud, tá? Então eu até deixo como sugestão você pesquisar aí no Google pela Compose, que é super legal.
14:4814 minutos e 48 segundosEles tm inclusive softwares que o Cloud não tem nativamente como conector, eles têm lá. Então você conecta lá no composo de forma super simples, só com login
14:5514 minutos e 55 segundossenha da ferramenta ou autorização ou alf, né? E uma vez que você conecta lá, o cloud pode acessar através do composio, né? O compos fica no meio de
15:0315 minutos e 3 segundoscampo ali, faz essa conexão cloud, compos e as ferramentas que você quer conectar. Então, eu tenho meu Gmail conectado por aqui. E o grande diferencial dessa minha rotina aqui é
15:1215 minutos e 12 segundosque o Cloud me ajudou a construir alguns comandos que ele roda de código para identificar dentro dos e-mails que tem lá no meu na minha caixa de entrada, é,
15:2015 minutos e 20 segundosalgumas palavras chave ou sentenças, né, que costumam indicar que é um e-mail que não é relevante. E por que que ele roda
15:2815 minutos e 28 segundosesses comandos? Porque vamos supor que eu tive 60 e-mails não lidos e que ele vai analisar. Se ele fosse usar o próprio cloud, né, inteligência
Capítulo 6: 5 Automações de Vendas
15:3515 minutos e 35 segundosartificial para carregar todo o texto de 60 e-mails e analisar se eles são válidos ou não, eu estaria gastando muito token todos os dias só para fazer
15:4315 minutos e 43 segundosessa limpeza, porque ele tá lendo muita informação, né? Então, nessa rotina aqui, eu configurei para que ela rode primeiro esse comando de código que não
15:5015 minutos e 50 segundosgasta quase nada de token para limpar uma primeira leva desse 60. E daí vão sobrar ali 10, 5, 10 e-mails que de fato
15:5815 minutos e 58 segundosele vai ler para daí com inteligência artificial entender se são e-mails relevantes ou não. Então essa é a primeira rotina que eu quero deixar para
16:0516 minutos e 5 segundosvocês. Depois mostro como pegar. Ela é bem simples, não é muito para vendas, mas eu acredito que, sei lá, não tem um ser humano na face da Terra que não e
16:1316 minutos e 13 segundosusaria isso aqui, não acharia legal uma rotina dessa. E uma coisa legal que toda vez que ela roda, ela deixa um resuminho aqui. Se você quiser visitar depois, né, basta visitar aqui a sessão que ela
16:2216 minutos e 22 segundosrodou e deixa um resumo aqui, ó. Foram, nesse caso aqui, né, foram cinco e-mails que ela marcou como lido e mantidos como não lidos nenhum. Então, nessa sessão
16:3016 minutos e 30 segundosaqui, ela simplesmente pegou tudo que ela leu, tinham lá na minha caixa e deixou eles todos como como lidos, tá? Não ficou nada aqui para eu ler depois.
16:3716 minutos e 37 segundosA próxima rotina é uma que eu chamo de morning brief. Ela traz um relatório matinal aqui para mim. Ela roda todo dia às 8:45, logo logo depois da limpeza do
16:4516 minutos e 45 segundosinbox. Tá conectada, isso aqui é bem importante, né? Tá conectada numa pasta que eu chamo de segundo cérebro, né? O meu segundo cérebro. Então, ela lê
16:5216 minutos e 52 segundosvárias informações eh de memória que tem dentro dessa pasta e tá conectado a ferramenta aqui da comunidade e mais algumas outras que não não estão
16:5916 minutos e 59 segundoslistados aqui. Tá conectado também ao meu e-mail, ao calendário, ao meu CRM. E o resultado dela é basicamente esse aqui, ó. Todo dia de manhã eu tenho qual
17:0717 minutos e 7 segundosé o meu foco do dia, os eventos que estão na minha agenda, as top três prioridades do meu dia com base nos documentos que ela tá lendo lá do meu segundo cérebro, quais e-mails eu tenho
17:1617 minutos e 16 segundosaguardando resposta, só aqueles que de fato são relevantes, as minhas pendências do dia anterior, as tarefas que eu deixei de fazer e algumas atualizações quanto à minha comunidade.
17:2517 minutos e 25 segundosEssa é uma rotina que também tá rodando localmente. Ela executa uma skill minha chamada Bom Dia. Fica bem fácil de você personalizar isso para você, para que eh
17:3217 minutos e 32 segundoso teu relatório matinal saia sempre com as informações que você quer, aquelas que são relevantes para te dar um um bom start aí no seu dia. A terceira rotina é
17:4017 minutos e 40 segundosbem interessante porque ela não tá local, ela tá na nuvem, tá? Ela roda toda vez que um novo lead preenche o formulário do meu site. Então lá no meu
17:4817 minutos e 48 segundossite eu tenho esse formulariozinho que, na verdade é uma integração com o call.com para agendamento, né? Então, a pessoa escolhe um horário, preenche as informações aqui e uma vez que ela clica
17:5517 minutos e 55 segundosem confirmar, essas informações são enviadas via web hook, né, para dentro do cloud para essa para essa rotina acontecer. Então aqui tá um exemplo
18:0318 minutos e 3 segundosprático para aquela explicação sobre como construir rotinas que rodam na nuvem, né? Eu tenho o meu call.com, que é esse essa aplicação, né, de
18:1018 minutos e 10 segundosagendamento. E dentro do evento lá que a pessoa preenche, eu conectei aqui, ó, o web hook, né, o RL do Web Hook, que aciona diretamente lá a automação.
18:1918 minutos e 19 segundosComeça uma rotina que também chama uma skill, no caso, essa skill aqui de após agendamento, né? Então, rode a skill pós agendamento. Eu precisei conectar o meu repositório do GitHub, como vocês podem
18:2718 minutos e 27 segundosver aqui, tá conectado lá para ele poder ler essa skill. E eu precisei também conectar uma API de WhatsApp, que é a Zapi. Então eu precisei configurar
18:3518 minutos e 35 segundosaquele ambientezinho, né, o environment aqui no canto direito, para que o Cloud pudesse fazer o envio da mensagem que eu quero que ele mande pro lead toda vez que ele que ele roda esse processo, né?
18:4418 minutos e 44 segundosEssa rotina tá conectada ao pipeedrive porque toda vez que alguém preenche, né, o formulário, eu quero que crie um lead dentro do meu CRM. O lead é criado aqui
18:5118 minutos e 51 segundosdentro do pipeedrive com uma bela de uma nota aqui de enriquecimento, né? Então, puxa um monte de informação além daquelas que o cara preencheu no no
18:5918 minutos e 59 segundosformulário, traz dados sobre a pessoa, sobre a empresa, se tem fit com a gente, um resumo executivo, um monte de coisa legal, já preenche vários campos aqui de
19:0719 minutos e 7 segundosdentro do pipeedrive de forma automática, né? Então vem super enriquecido pro meu pro meu CRM. Além disso, a rotina usa a API de WhatsApp
19:1519 minutos e 15 segundosque eu mostrei, né, que tá configurada para fazer um envio de uma notificação aqui dentro do grupo da empresa da Playbook Lab, de uma nova reunião agendada com os dados da pessoa e um
19:2319 minutos e 23 segundospequeno resumo, além de enviar uma mensagem de agradecimento pro próprio lead, já incluindo, por exemplo, a data e o horário dessa reunião, né? Eh, e
19:3119 minutos e 31 segundostambém o link aqui de acesso para pro Google Meet, ou seja, uma mensagem personalizada que o Cloud envia usando API do WhatsApp. Então esse aqui é um
19:3919 minutos e 39 segundosbom exemplo de uma rotina que usa basicamente tudo que eu te mostrei aqui, né? Ela roda no automático sendo acionada por um evento externo. Ela faz pesquisas usando a própria IA,
19:4819 minutos e 48 segundosinteligência do Cloud. Ela cadastra o lead do meu CRM, preenchendo campos de forma automática e ela ainda aciona o WhatsApp tanto para mandar uma mensagem
19:5519 minutos e 55 segundosde agradecimento pro lead quanto notificar a equipe interna da Playbook Lab sobre essa nova reunião agendada. A quarta rotina é uma extremamente útil
20:0420 minutos e 4 segundospara mim. Essa rotina se chama registrar reuniões. Ela tá rodando na nuvem e ela é acionada toda vez que uma reunião que eu participo termina. No meu dia a dia
20:1320 minutos e 13 segundoseu faço muitas reuniões com clientes da agência que eu gosto sempre de logar essas reuniões lá dentro do Clickup, né?
20:1920 minutos e 19 segundosE eu também faço muitas reuniões de vendas. Essas eu gosto de logar dentro do PipeDrive no CRM lá no card para ter o histórico da reunião que foi falado, a
20:2620 minutos e 26 segundosdata, o a o próprio link, né, para ver a gravação de novo. Antes eu fazia isso manualmente. Toda vez que acabava a reunião, eu tinha que ir lá logar, pegar
20:3320 minutos e 33 segundoso link. transcrever e tal. E agora o Cloud faz isso sozinho por mim. Então vocês podem ver que ela também tem instrução, né, de sempre usar uma skill que já tá treinada, preparada para fazer
20:4220 minutos e 42 segundosesse processo. Ela tá conectada ao Clickup e ao PipeDrive e ela é acionada via API. O que eu fiz para ela funcionar foi copiar o URL do Webook, que você
20:5120 minutos e 51 segundospega aqui nesse botãozinho de copiar. E no meu caso, eu fui até o TLDV. Eu uso o TldV, que é uma ferramenta de transcrição de reuniões, né? E eles têm
20:5820 minutos e 58 segundosaqui como você configurar um novo web hook. Eu selecionei aqui para toda vez que uma transcrição estiver pronta, ele apontar para este URL aqui, né, que é o
21:0721 minutos e 7 segundosque eu acabei de copiar. Então, toda vez que uma reunião minha termina e o transcriptão tá pronto, ele aponta para esse destino aqui, que é a ativação da
21:1521 minutos e 15 segundosprópria rotina. Então, só para vocês verem um exemplo, esse aqui é um cliente nosso. Eu tenho todas as minhas reuniões logadas aqui, o link, né, direto pra
21:2221 minutos e 22 segundosreunião. E se eu clico na tarefa, ele abre também aqui, ó, o transcript completo dessa reunião. Tá tudo sendo logado automaticamente. Funciona
21:3021 minutos e 30 segundosexatamente dessa forma dentro do pipeedrive também. Então, se você faz muita reunião de vendas ou reunião com clientes, essa skill vai ser super legal, registrar tudo que você conversa
21:3721 minutos e 37 segundoscom os clientes. E daria até para automatizar outras coisas, por exemplo, conectar com um draft de e-mail para ele já gerar um e-mail com base no
21:4421 minutos e 44 segundostranscriptão, conectar com um processo de geração de proposta automatizado. Aí o céu é o limite. Dá para ir pensando em várias coisas para fazer com automações
21:5221 minutos e 52 segundosque começam a partir do término de uma reunião, né, de uma call de vendas ou de uma call seu. E a última rotina é uma revisão do nosso pipeline de vendas.
22:0122 minutos e 1 segundoBasicamente, ela roda toda sexta-feira no fim ali do dia, porque eu quero sempre olhar para as tarefas que estão com problema e fazer com que o pessoal
22:0822 minutos e 8 segundosdo meu time resolva essas tarefas, né, organização de CRM e tal, antes da gente e entrar no final de semana. Então, o que ela faz é olhar pro pipe captar
22:1722 minutos e 17 segundostodos os problemas que tem nos negócios, tarefas em atraso, negócios sem tarefa, campos que estão faltando preenchimento.
22:2422 minutos e 24 segundosE daí ela envia um e-mail pro pessoal dando esse alerta assim desses pontos que precisam de correção. Essa aqui roda localmente, não preciso que ela rode na
22:3222 minutos e 32 segundosnuvem, até porque mundo não vai explodir se ela não acontecer. Então, tá aqui o funil que a rotina analisa dentro do pipeve. E esse aqui é o e-mail que ele
22:4122 minutos e 41 segundosenvia pra equipe, ó. identificou 13 negócios que estão sem nenhuma tarefa agendada, 12 negócios que não tem um valor preenchido, campo valor.
22:4922 minutos e 49 segundosIdentificou uma negociação grande aqui que nunca saiu do lugar, então tá estagnada, traz alguns números positivos, né, e também os próximos passos. Então isso aqui serve até como
22:5722 minutos e 57 segundosum lembrete, né, pra galera não deixar a semana fechar sem antes corrigir esses probleminhas aí que eles deixaram no CRM. Lembrando que se você quiser acessar o material completo dessas
23:0623 minutos e 6 segundosrotinas, você pode acessar a comunidade da Playbook Lab, mesmo como membro free vai ter acesso, tá? Como membro VIP, você libera alguns acessos e recursos mais exclusivos dentro da comunidade.
23:1723 minutos e 17 segundosBasta vir aqui em recursos gratuitos para acessar o material completo. Além disso, você pode pegar aqui todos os materiais que eu já produzi. Tem muita coisa legal aqui mesmo na versão
23:2523 minutos e 25 segundosgratuita da comunidade, beleza? Então é isso. Espero que esse vídeo tenha te ajudado a entender mais aí o conceito das rotinas no cloud e que essas aqui
23:3323 minutos e 33 segundosque eu uso no meu dia a dia sirvam de inspiração para você construir as automações aí para você também. Se você quiser trabalhar com a gente implementando IAI e automação nos seus
23:4123 minutos e 41 segundosprocessos comerciais dentro da sua equipe, da sua empresa, vou deixar nosso site aqui na descrição. Por lá você pode agendar um bate-papo diretamente comigo.
23:4823 minutos e 48 segundosNão deixa de se inscrever aqui no canal para não perder os próximos conteúdos.
23:5223 minutos e 52 segundosQualquer dúvida pode deixar aqui nos comentários que eu vou responder.
