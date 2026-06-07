# Space Rush

Jogo 2D de nave espacial feito com **HTML5 Canvas**, **CSS** e **JavaScript puro**.

Esta versão está pronta para hospedagem no **GitHub Pages**, **Vercel** ou **Netlify**.

## Jogar localmente

Abra o arquivo:

```text
index.html
```

diretamente no navegador.

Para testar com servidor local, use uma das opções:

```bash
python -m http.server 3000
```

Depois abra:

```text
http://localhost:3000
```

## Controles

- **WASD** ou **setas**: mover
- **Espaço**: atirar
- **Q**: habilidade especial
- **Shift**: dash
- **ESC**: pausar
- **F**: tela cheia, se disponível no jogo

## Hospedar no GitHub Pages

1. Crie um repositório no GitHub.
2. Envie todos os arquivos deste projeto.
3. Vá em **Settings**.
4. Entre em **Pages**.
5. Em **Build and deployment**, escolha:
   - Source: **Deploy from a branch**
   - Branch: **main**
   - Folder: **/root**
6. Salve.

O GitHub Pages publicará o jogo usando o arquivo `index.html`.

## Hospedar na Vercel

1. Crie um repositório no GitHub com estes arquivos.
2. Entre em **vercel.com**.
3. Clique em **Add New Project**.
4. Importe o repositório.
5. Use as configurações padrão.
6. Clique em **Deploy**.

Este projeto já inclui `vercel.json`.

## Hospedar na Netlify

1. Crie um repositório no GitHub com estes arquivos.
2. Entre em **netlify.com**.
3. Clique em **Add new site**.
4. Importe o repositório.
5. Use as configurações padrão.
6. Publique.

Este projeto já inclui `netlify.toml`.

## Estrutura

```text
space-rush-github-ready/
├── index.html
├── README.md
├── LICENSE
├── .gitignore
├── vercel.json
├── netlify.toml
└── package.json
```

## Observação de performance

O jogo usa muitos efeitos visuais, partículas e sons. Em computadores ou celulares mais fracos, pode ser necessário reduzir a quantidade de efeitos em uma versão futura.
