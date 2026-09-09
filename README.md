# Project Coca-Cola

Landing page estática inspirada na marca Coca-Cola.

## Descrição

Página única com layout moderno focado em exibição de produto, navegação simples e identidade visual forte. Desenvolvida com HTML5 e CSS3 puro, com suporte completo a dispositivos móveis e acessibilidade.

## Funcionalidades

- Header com logo e menu de navegação
- Seção hero com chamada para ação (CTA)
- Ícones de redes sociais
- Composição de imagens de produtos
- Elementos decorativos com clip-path
- Layout responsivo (mobile, tablet, desktop)
- Skip link para navegação por teclado
- Estilos de focus-visible para acessibilidade
- Suporte a prefers-reduced-motion

## Responsividade

| Dispositivo | Viewport | Breakpoint |
|-------------|----------|------------|
| iPhone 14/15/16 | 390×844, 430×932 | Mobile (< 768px) |
| Smartphones Android | 360×800, 412×915 | Mobile (< 768px) |
| iPad | 768×1024 | Tablet (768px - 1023px) |
| Desktop | 1280×720, 1920×1080 | Desktop (≥ 1024px) |

## Acessibilidade

- Skip link para pular navegação
- aria-label no menu de navegação
- Estilos de focus-visible para navegação por teclado
- Suporte a prefers-reduced-motion
- Textos alt descritivos em todas as imagens
- Elementos semânticos (main, figure, footer)

## Performance

- Google Fonts carregado via `<link>` com display=swap
- Imagens com width/height definidos (evita CLS)
- Lazy loading nas imagens de produto
- Imagens com max-width: 100%

## Tecnologias

- **HTML5** (semântica, meta tags, acessibilidade)
- **CSS3** (clip-path, transforms, transitions, media queries)
- **Google Fonts** (Poppins)
- **Assets:** Imagens PNG locais

## Como Rodar

```bash
# Abra diretamente no navegador
open index.html

# Ou use o Live Server do VS Code
# Botão direito -> Open with Live Server
```

Nenhuma instalação ou build necessário.

## Estrutura

```
project-coca-cola/
├── index.html      # Página principal
├── style.css       # Estilos
└── assets/         # Imagens (logo, garrafas, redes sociais)
    ├── logo.png
    ├── cocacola1.png
    ├── cocacola2.png
    ├── cocacola3.png
    ├── cocacola4.png
    ├── facebook.png
    ├── twitter.png
    └── instagram.png
```

## Licença

MIT License - Diego Vieira
