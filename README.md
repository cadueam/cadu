# Cadu Andrade — Portfolio

## Como adicionar imagens ao portfólio

### 1. Coloque as imagens na pasta correta

```
cadu-portfolio/
└── assets/
    └── portfolio/   ← AQUI
        ├── projeto-01.jpg
        ├── campanha-verao.png
        └── key-visual.webp
```

Formatos aceitos: `.jpg`, `.jpeg`, `.png`, `.webp`, `.avif`, `.gif`

---

### 2. Abra o `index.html` num editor de texto e edite o array `IMAGES`

Procure essa parte no script (lá embaixo no HTML):

```js
const IMAGES = [
  // "seu-projeto-01.jpg",
  // "seu-projeto-02.png",
];
```

Adicione os nomes dos seus arquivos (exatamente como salvou):

```js
const IMAGES = [
  "projeto-01.jpg",
  "campanha-verao.png",
  "key-visual.webp",
];
```

---

### 3. Abra o `index.html` no navegador

Dê dois cliques no arquivo — o portfólio vai abrir com suas imagens no grid Bento.

> **Dica:** A ordem das imagens no grid segue a ordem do array `IMAGES`.
> O nome do arquivo (sem extensão e sem traços/underlines) vira o label que aparece no hover.

---

## Estrutura da pasta

```
cadu-portfolio/
├── index.html          ← site principal
├── README.md           ← este arquivo
└── assets/
    └── portfolio/      ← suas imagens aqui
```
