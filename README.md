# CineGroup

Site estático de divulgação para um cinema, desenvolvido em HTML e CSS puros (sem frameworks ou build tools).

## Páginas

- **`index.html`** — Página inicial: banner, trailer em vídeo e sinopse, com botão de redirecionamento para compra de ingressos.
- **`cadastro.html`** — Formulário de contato/cadastro (nome e e-mail).
- **`criadores.html`** — Página com os cartões dos criadores/desenvolvedores do projeto.

## Estrutura

```
cinemaemc/
├── index.html
├── cadastro.html
├── criadores.html
├── styles.css
├── cadastro.css
├── criadores.css
└── (imagens e vídeo usados nas páginas)
```

Cada página tem sua própria folha de estilo correspondente (`styles.css`, `cadastro.css`, `criadores.css`).

## Como rodar

Por ser um site 100% estático, basta abrir os arquivos `.html` diretamente no navegador, ou servir a pasta com um servidor local:

```bash
python -m http.server 8080
```

Depois acesse [http://localhost:8080/index.html](http://localhost:8080/index.html).

## Desenvolvido por

CineGroup
