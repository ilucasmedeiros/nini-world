# 🕹️ Super Nini World — 2 em 1

Um "cartucho" com dois jogos retrô feitos de presente:

| Jogo | Arquivo | O que é |
|---|---|---|
| **Nossa História** — Dia dos Namorados | `namorados.html` | O personagem caminha por um mapa estilo Super Mario, passando por todas as fases do relacionamento, até resgatar a princesa no castelo. 🏰 |
| **Nini Fighter II** — Edição Aniversário | `aniversario.html` | Uma luta estilo Street Fighter: a **Nini** defende o bolo da Raquel contra a **Chatinha**, a shih-tzu mais chata da rua. A Nini sempre ganha, e no final vem a festa: velinhas, "Parabéns" em 8-bit, LEVEL UP e a foto da aniversariante. 🎂 |

O `index.html` é a **tela de seleção de jogos**, no estilo dos cartuchos "9999 em 1".
É esse o link que você manda pra ela.

## Como ver

Dê dois cliques no arquivo **index.html**. Ele abre direto no navegador e não precisa instalar nada.

> ⚠️ Importante: para as **fotos** carregarem, em alguns navegadores é
> melhor servir os arquivos localmente. Se alguma foto não aparecer,
> rode no Terminal, dentro desta pasta:
> ```
> python3 -m http.server 8000
> ```
> e abra http://localhost:8000

## Como jogar

**Menu:** use ← → e Enter, ou toque/clique num cartucho.

**Nossa História:** aperte START e avance com o botão **▶ AVANÇAR** (ou seta →, espaço, enter).
Cada fase abre um cartão com a história e a foto.

**Nini Fighter II:** primeiro vem a história, depois a seleção da lutadora, o VS e então 2 rounds.

| | Teclado | Celular (botões na tela) |
|---|---|---|
| Andar | ← → | ◀ ▶ |
| Pular | ↑ | ▲ |
| Mordida | Z (ou espaço) | **A** |
| Patada | X | **B** |
| AU-DOUKEN! (latido) | C — ou o clássico ↓ ↘ → + Z | **★** |
| SHIH-TZU-RYUKEN! (super) | C com a barra SUPER cheia | **★** quando aparece "SUPER!" |

A Nini **não perde**: se a vida dela chega a 25%, ela entra em **FÚRIA**, a barra
SUPER enche na hora e os golpes ficam mais fortes. O relógio é ∞, então não existe derrota por tempo.

No celular dá pra jogar em pé (controles embaixo, tipo Game Boy) ou deitado (tela maior).

Atalhos para testar: `aniversario.html#luta` (pula direto pra luta) e
`aniversario.html#final` (pula direto pro parabéns).

## Como personalizar

Cada jogo tem um bloco `CONFIG` **no topo do arquivo**, marcado com 💕 ou 🎂:

- **namorados.html**: os nomes, as fases (título, data, foto e texto de cada uma) e a mensagem final.
- **aniversario.html**:
  - os nomes da lutadora, da rival e da aniversariante;
  - a idade (`nivelAntes` / `nivelNovo`), que aparece nas velinhas e no LEVEL UP;
  - a história do começo e a frase de vitória;
  - a mensagem final, digitada letra por letra.

## Fotos

As fotos ficam na pasta `fotos/`. A lista completa está em `fotos/LEIA-ME.txt`.

## Como publicar de graça (para mandar o link pra ela)

- **Netlify Drop** (mais fácil): acesse https://app.netlify.com/drop e
  arraste esta pasta inteira. Pronto, sai um link na hora.
- **GitHub Pages** ou **Vercel** também funcionam (é só um site estático).

> 🔒 Antes de arrastar a pasta, tire dela os arquivos originais
> (`IMG_1121.HEIC`, `IMG_1321.JPG` e o print `Captura de Tela ... .png`).
> O site só usa as versões reduzidas que estão em `fotos/aniversario/`.
> O print original mostra o número da casa; no jogo ele aparece pixelado.

Feliz Dia dos Namorados e feliz aniversário! 🍄❤️🎂
