# Aula 06 — Manutenção

## Fonte

- **Título de referência** — Aula 06 — Manutenção. O título no YouTube ficou sem confirmação.
- **Vídeo** — [Link original no YouTube](https://www.youtube.com/watch?v=cwHvBWtTaNs&t=2s).
- **Módulo** — manutenção do Segundo Cérebro. O nome oficial do módulo ficou sem confirmação.
- **Origem da transcrição** — `6 - Manutencao.txt`, fornecido com o vídeo. Vai da abertura em 00:00 à fala de encerramento iniciada em 06:50. A duração do vídeo, a descrição e as legendas no YouTube ficaram sem confirmação direta.
- **Material complementar** — [Pacote da skill manutencao-os](aula-06-manutencao-skill-manutencao-os.zip), fornecido com a aula como `6 - Skill -manutencao-os.zip`.

## Resumo da aula

**Ideia central.** À medida que o Segundo Cérebro cresce, a IA cria e organiza arquivos, e pequenos erros se acumulam. Uma rotina de manutenção ajuda a preservar os caminhos que a IA usa para encontrar informações e seguir referências entre notas.

| Tempo | Tópico | O que a aula apresenta |
| --- | --- | --- |
| 00:00–01:19 | Por que fazer manutenção | O uso diário pode deixar nomes fora do padrão, links quebrados e relações incorretas. O professor criou a skill `manutencao-os` a partir de práticas de outras pessoas e costuma rodá-la semanalmente, ou com mais frequência em períodos de uso intenso. |
| 01:20–02:25 | Conferir os roteadores | A revisão verifica se os arquivos `CLAUDE.md` continuam descrevendo as pastas e os documentos que surgiram com o uso e se orientam o Claude a procurar no lugar certo. |
| 02:26–03:32 | Revisar links e relações entre documentos | Wikilinks são referências que o Claude pode seguir durante a leitura. No exemplo, o documento 1 aponta para o 3, o 3 aponta para o 5 e o 5 aponta para o 4 e o 1. Se a informação procurada estiver no documento 3, o link no documento 1 fornece o próximo caminho. |
| 03:33–04:11 | Investigar duplicidade e nomes fora do padrão | O professor cita arquivos com o mesmo nome em pastas diferentes e nomes que fogem à convenção da pasta. São dois pontos de revisão, além dos roteadores e dos links. |
| 04:12–04:46 | Acionar a manutenção | A aula mostra o uso manual por comando e antecipa a automação no módulo seguinte. O professor cita sua rotina “manutenção brain semanal” e menciona sexta-feira como dia provável de execução. |
| 04:47–06:50 | Adaptar o pacote ao próprio Segundo Cérebro | O procedimento mostrado é selecionar o projeto do Segundo Cérebro no Claude, carregar o ZIP, pedir a leitura do README e a personalização para a estrutura em uso, revisar a personalização em conversa e salvar a skill. O professor menciona instruções de personalização, `SKILL.md`, referências, scripts e materiais extras. O comando documentado no ZIP é `/manutencao-os`. |

### O que o pacote anexado detalha

- A auditoria começa reconhecendo a estrutura e as convenções que o Segundo Cérebro já usa. Por exemplo, uma nota órfã é relevante numa base que usa links, e a falta de metadados no cabeçalho (*frontmatter*) é avaliada conforme as convenções e os padrões da base.
- O script Python `scripts/audit.py` faz verificações em modo de leitura. Ele aponta casos como links quebrados ou ambíguos, índices incompletos e referências a destinos inexistentes. Contradições, fatos desatualizados e duplicatas de conteúdo exigem leitura e julgamento.
- O relatório apresenta defeitos e recomendações. A documentação prevê uma prévia numerada, aprovação item a item e backup antes das alterações. Depois, a auditoria é repetida para conferir o resultado. Exclusão de notas, fusão de duplicatas e movimentação entre áreas ficam como sugestões para revisão humana.
- O ZIP não traz um arquivo autônomo chamado “Personalizar”. A adaptação à estrutura existente é descrita no README, no `SKILL.md` e nas referências. A periodicidade indicada pelo pacote é mensal ou após mudanças estruturais grandes.

## Revisão

1. Como um `CLAUDE.md` desatualizado pode impedir o Claude de localizar um documento que já existe?
2. No exemplo da aula, que caminho o Claude segue do documento 1 até o 4? Que trecho desse caminho seria afetado se o documento 3 fosse renomeado e a referência continuasse com o nome antigo?
3. Dois arquivos têm o mesmo nome em pastas diferentes. Que evidências você buscaria para distinguir um link ambíguo de uma duplicata de conteúdo?
4. Cite um problema que o script de auditoria consegue detectar por comparação e um caso que exige leitura. Como você verificaria se a correção funcionou?

## Ideias para minhas aulas

- **Proposta de exercício sobre roteamento.** Monte um Segundo Cérebro fictício de uma equipe comercial. Acrescente uma pasta de propostas sem atualizar o `CLAUDE.md`. Peça à turma que siga as orientações existentes para encontrar a proposta vigente e registre em que ponto a busca trava.
- **Proposta de exercício sobre links.** Crie duas notas chamadas `Checklist de implantação.md`, uma na área Comercial e outra em Operações. Entregue uma nota com um wikilink ambíguo e peça aos alunos que escolham o destino com base no contexto e explicitem o caminho.
- **Proposta de simulação de auditoria.** Use uma base fictícia com um link quebrado e duas notas que parecem duplicadas. Peça à turma que proponha uma correção verificável para o link, registre as evidências sobre a possível duplicata e compare os achados antes e depois da correção.
