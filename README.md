# Pong 🏓

Recriação do Pong, um dos primeiros videogames da história, em HTML, CSS e JavaScript puros. Sem dependências, sem build: basta abrir o `index.html` no navegador.

O campo é vertical, com paredes laterais, rede tracejada e placar com números em pé, ao lado da rede.

## Como jogar

- Você controla a raquete de baixo; o computador joga em cima.
- **Computador:** setas `←` `→` (ou `A` `D`) ou o mouse. `Espaço` ou `Enter` inicia.
- **Celular:** arraste o dedo na tela. Toque para iniciar.
- A bola acelera a cada rebatida e o ângulo muda conforme o ponto da raquete em que ela bate.
- Vence quem chegar primeiro a 11 pontos.

## Executar localmente

```bash
git clone https://github.com/phfcuditablet/pong.git
cd pong
# abra o index.html no navegador
```

## Publicar no GitHub Pages

1. No repositório, abra **Settings → Pages**.
2. Em **Build and deployment**, escolha **Deploy from a branch**.
3. Selecione a branch `main` e a pasta `/ (root)`, e clique em **Save**.
4. O jogo ficará em `https://phfcuditablet.github.io/pong/`.

## Estrutura

```
pong/
├── index.html   # jogo completo (HTML + CSS + JS)
├── README.md
└── LICENSE
```

## Licença

MIT. Veja o arquivo [LICENSE](LICENSE).
