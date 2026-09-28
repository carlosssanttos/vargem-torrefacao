# Vargem Torrefação

Site de uma torrefação de café especial em que a rolagem conta a torra do grão, do verde cru ao espresso.

## Tecnologias

- [GSAP](https://gsap.com) 3.12 + ScrollTrigger
- [Lenis](https://lenis.darkroom.engineering) 1.3 para rolagem suave
- HTML, CSS e JavaScript puros em um único arquivo, sem build

## Destaques

- Abertura com revelação circular via `mask` animada
- Xícara vista de cima com espuma e texto circular que reagem à velocidade da rolagem
- Laboratório de torra fixado: grão muda de cor, curva de temperatura desenhada em tempo real e evento de primeiro crack com partículas
- Texto revelado palavra por palavra
- Cartões de origem empilhados com `position: sticky` e mapas topográficos gerados por código
- Header que se esconde ao descer, botão magnético com `gsap.matchMedia` e cores que mudam por seção

## Rodando localmente

Basta abrir o `index.html` no navegador. Para servir localmente:

```bash
npx serve .
```

## Publicando no GitHub Pages

Em **Settings → Pages**, escolha a branch `main` e a pasta `/ (root)`. O site fica em `https://SEU-USUARIO.github.io/vargem-torrefacao/`.

## Observações

Marca, produto e dados são fictícios. Projeto de demonstração de técnicas de animação por rolagem.
