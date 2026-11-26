# CLAUDE.md — prof2030-treinador

Curso no formato INEMA Learning v7.2 (skill `formato-curso-v72`). Conteúdo em `conteudo/<lang>/`; nunca editar o HTML gerado à mêo: editar o JSON e rodar `python3 gerar.py && python3 validar.py --links`. Conferir telas com `node ~/.claude/skills/formato-curso-v72/scripts/conferir-tela.cjs .` (HTTP local, 1366 e 390 px).
Autor dos commits: `inematds <inematds@gmail.com>`. Publicaçêo = commit + push (GitHub Pages, raiz da main).

## Self-learning

When I correct you, or you catch yourself making a mistake: before continuing, add the lesson as a one-line rule at the TOP of the Lessons section below.

## Lessons

- Diagrama: título de nó que começa com dígito ("90 dias") perde o número da etapa; e mais de 6 nós no estilo fluxo amontoa no desktop (19/10/2026).
- Traduçêo de bloco de código: o detector de linha de comando tem de casar palavra inteira; "Entregue" → "Deliver" virava o comando `del` e a traduçêo era recusada 3 vezes (19/10/2026).
- `mapa` com mais de 4 degraus espreme as colunas no desktop: use 4 degraus (as entregas principais) e deixe o `gerador` listar todas as aulas (19/10/2026).
- Copie o motor para o curso de novo depois de qualquer ajuste no motor: o `novo-curso.sh` copia uma vez só, e o curso piloto ficou com o rótulo antigo da simconversa (19/10/2026).
- Marca-texto (anotaçêo) dentro de elemento flex/grid vira item solto e abre espaço no meio da palavra: o texto anotável tem que estar num `span`/`p` próprio (ex.: `.nesta2 li > span`). Bloco anotável novo → conferir o `display` dele (18/10/2026).
- Rolagem guiada no desktop: o texto da etapa fica DENTRO do painel fixo (legenda que troca); cartões rolando por baixo do diagrama aparecem cortados e espiando no topo — o Nei viu na aula 1 (18/10/2026).
- Rolagem guiada: posiçêo de destino calculada com o diagrama JÁ grudado no topo (top do sticky + altura), nunca pela posiçêo atual; e a etapa só vira ativa quando o cartêo está visível abaixo do diagrama (18/10/2026).
- Menu do topo de curso segue o padrêo v2 (curso | INEMA.CLUB - PRO à esquerda; seções e Aa à direita); nêo inventar outro topo (18/10/2026).
- Simulaçêo com falha proposital: amarrar a falha à primeira execuçêo da tarefa, nêo à primeira rodada — senêo interromper e retomar esconde a falha (18/10/2026).
- Validar por HTTP local, nunca `file://` (o progresso e os caminhos relativos se comportam diferente) (18/10/2026).
