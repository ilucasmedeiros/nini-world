# ❤ Nossa História — Dia dos Namorados (estilo Mario)

Um site-jogo onde o personagem caminha por um mapa estilo Super Mario,
passando por todas as fases do relacionamento (conquistas e desafios),
até resgatar a princesa no castelo no final. 🏰

## Como ver

Dê dois cliques no arquivo **index.html** — abre direto no navegador,
não precisa instalar nada.

> ⚠️ Importante: para as **fotos** carregarem, em alguns navegadores é
> melhor servir os arquivos localmente. Se alguma foto não aparecer,
> rode no Terminal, dentro desta pasta:
> ```
> python3 -m http.server 8000
> ```
> e abra http://localhost:8000

## Como personalizar (3 passos)

Tudo que você precisa editar está **no topo do `index.html`**, na
seção marcada com `💕💕💕 EDITE AQUI A HISTÓRIA DE VOCÊS 💕💕💕`:

1. **Nomes** — troque `jogador` (você) e `princesa` (ela).
2. **Fases** — cada item da lista `fases` é uma parada no mapa:
   - `titulo`, `data` e `texto`: a história de vocês, do seu jeito
   - `tipo`: `"conquista"`, `"desafio"` ou `"inicio"` (muda o selo da fase)
   - `emoji`: o ícone que flutua no mapa
   - `foto`: o nome do arquivo na pasta `fotos/`
   - Pode **adicionar ou remover fases** à vontade — o mapa se ajusta sozinho.
3. **Mensagem final** — edite `mensagemFinal`, que é digitada letra por
   letra na tela do resgate da princesa.

## Fotos

Coloque as fotos na pasta `fotos/` com os nomes listados em
`fotos/LEIA-ME.txt`. Sem foto, aparece um quadro "SUA FOTO AQUI"
(o site funciona normalmente mesmo assim).

## Como jogar

- **START** na tela inicial
- Botão **▶ AVANÇAR** (ou seta →, espaço, enter) para caminhar até a próxima fase
- Cada fase abre um cartão com a história + foto
- Clique em fases já visitadas para rever
- No final: **🏰 RESGATAR A PRINCESA** → fogos, corações e a mensagem final

## Como publicar de graça (para mandar o link pra ela)

- **Netlify Drop** (mais fácil): acesse https://app.netlify.com/drop e
  arraste esta pasta inteira — pronto, sai um link na hora.
- **GitHub Pages** ou **Vercel** também funcionam (é só um site estático).

Feliz Dia dos Namorados! 🍄❤️
