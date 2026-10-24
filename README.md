# Detona Ralph

Um jogo simples de reflexo inspirado no clássico "acerte o alvo". Clique no Ralph assim que ele aparecer em uma das casas para acumular pontos antes que o tempo acabe.

## Como jogar

1. Abra `index.html` em um navegador.
2. Clique na casa que estiver mostrando o Ralph.
3. Faça o máximo de pontos em 60 segundos.

Cada acerto soma um ponto e toca um efeito sonoro. Ao fim da rodada, o jogo exibe a pontuação final.

## Executar localmente

O projeto não precisa de instalação de dependências nem de etapa de build. Você pode abrir `index.html` diretamente no navegador. Como alternativa, use a extensão Live Server do VS Code e inicie um servidor a partir desse arquivo.

## Estrutura

```text
.
├── index.html
└── src/
    ├── audios/
    │   └── hit.m4a
    ├── images/
    │   ├── favicon.jpg
    │   ├── player.png
    │   ├── ralph.png
    │   └── wall.png
    ├── script/
    │   └── engine.js
    └── styles/
        ├── main.css
        └── reset.css
```

## Tecnologias

- HTML
- CSS
- JavaScript
- Fonte Press Start 2P, carregada do Google Fonts
