# Encontros do módulo (repositório público)

Esta pasta é um repositório git **público** próprio, publicado no GitHub Pages a cada push em `main`
(endereço e repositório em `curso.json`). O resto do módulo (`../lbl`, `../projeto`, `../avaliacoes`) não entra aqui.

- `curso.json` é a fonte única do site: dados do curso e a lista de encontros, na ordem em que acontecem.
- Cada encontro tem a pasta `<slug>/`, com o deck em `apresentacao/` (`deck.html` e `dist/index.html`, commitado,
  porque o CI não compila decks) e, se houver, `guias/<nome>.json` (roteiros e passo a passo). Sem pastas datadas: a
  data fica em `curso.json` e versões antigas, no histórico do git.
- `.design-system` é um link para `../.design-system` (fora do repositório); os decks o usam por `../../.design-system/`.
- `site/` e `tools/` são cópias de `Disciplinas/compartilhado/modulo-inteli/modelo/meus-encontros/` (o CI precisa dos
  arquivos de verdade). Uma melhoria feita aqui deve voltar para o modelo.
- Para decks, skill `apresentacao-inteli`; para o site, a prévia e a publicação, skill `cursos-site`.
- Nunca entram aqui: nomes ou notas de alunos, material interno do parceiro, nada de `../avaliacoes`.
