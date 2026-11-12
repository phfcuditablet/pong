# Pong 🏓

Recriação do Pong, um dos primeiros videogames da história, em HTML, CSS e JavaScript puros. Sem dependências, sem build: basta abrir o `index.html` no navegador.

O campo é vertical, com paredes laterais, rede tracejada e placar com números em pé, ao lado da rede.

## Modos de jogo

Ao abrir o jogo, escolha no menu:

- **Contra a máquina**, com 5 níveis de dificuldade: 1 Iniciante, 2 Fácil, 3 Médio, 4 Difícil e 5 Mestre. Quanto maior o nível, mais rápida e precisa é a raquete da máquina.
- **2 jogadores**, no mesmo aparelho.

## Como jogar

- **Voltar:** a setinha ← no canto inferior esquerdo leva à página dos jogos.
- **Menu:** o botão MENU (ou a tecla `Esc`) volta à escolha de modo.
- **Contra a máquina:** você joga embaixo. Use as setas `←` `→` (ou `A` `D`) ou o mouse. No celular, arraste o dedo.
- **2 jogadores:** o Jogador 1 fica embaixo e usa `←` `→`; o Jogador 2 fica em cima e usa `A` `D`. No celular, cada um arrasta o dedo na sua metade da tela.
- `Espaço`, `Enter` ou um toque na tela inicia cada partida.
- A bola acelera a cada rebatida e o ângulo muda conforme o ponto da raquete em que ela bate.
- Vence quem chegar primeiro a 11 pontos.
- Vencer por 11 a 0 (ou perder por 0 a 11) mostra **PERFECT!!!** na tela final, como nos jogos de luta.

## Executar localmente

```bash
git clone https://github.com/SEU-USUARIO/pong.git
cd pong
# abra o index.html no navegador
```

## Publicar no GitHub Pages

1. No repositório, abra **Settings → Pages**.
2. Em **Build and deployment**, escolha **Deploy from a branch**.
3. Selecione a branch `main` e a pasta `/ (root)`, e clique em **Save**.
4. O jogo ficará em `https://SEU-USUARIO.github.io/pong/`.

## Estrutura

```
pong/
├── index.html   # jogo completo (HTML + CSS + JS), com menu e botão de voltar
├── README.md
└── LICENSE
```

## Licença

MIT. Veja o arquivo [LICENSE](LICENSE).
