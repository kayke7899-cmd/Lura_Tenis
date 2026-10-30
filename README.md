# 👟 Lura Tênis

> Site institucional estático de uma loja de tênis, desenvolvido com **HTML5** e **CSS3 puro**. Identidade visual *dark* com detalhes em verde-neon, focado em estrutura semântica, CSS modularizado e responsividade.

---

## 📑 Sobre o Projeto

A **Lura Tênis** é uma loja fictícia de calçados esportivos e urbanos. O site apresenta a marca, exibe uma vitrine de modelos em destaque, um catálogo com tabela de preços, conteúdo institucional com reviews em vídeo e um formulário de contato.

**Destaques técnicos:**
- Variáveis CSS (`:root`) centralizando todo o tema (Design System).
- CSS modularizado: um arquivo global + um arquivo específico por página.
- Efeitos de *hover* com `transform` e `box-shadow`.
- Layout fluido com `clamp()`, `min()` e `aspect-ratio`.
- Suporte a `prefers-reduced-motion` para acessibilidade.

---

## 🛠 Tecnologias Utilizadas

| Tecnologia | Uso |
|---|---|
| **HTML5** | Estrutura semântica (`header`, `nav`, `main`, `section`, `footer`, `table`, `form`) |
| **CSS3** | Estilização, Flexbox, animações e media queries |
| **Vs Code** | Editor de código  |
| **WebP** | Formato das imagens da vitrine para melhor compressão |

---

##  Estrutura de Arquivos

```text
lura-tenis/
├── imagens/                  # Assets visuais (formato WebP)
│   ├── nike.webp             # Nike Air Force Essential
│   ├── nikerosa.webp         # Nike AT (Rosa)
│   ├── adidasbranco.webp     # Adidas Adizero SL
│   ── adidas.webp           # Adidas Adizero Evo SL
│
├── paginas/                  # Arquivos HTML (Views)
│   ├── index.html            # Home: Vitrine, banners e links
│   ├── produtos.html         # Catálogo: Tabela de preços
│   ├── sobre.html            # Institucional: Quem somos + Reviews
│   └── suporte.html          # Contato: Formulário completo
│
└── css/                      # Folhas de Estilo
    ├── estilo.css            # Global: Reset, variáveis, tipografia, layout base
    ├── index.css             # Home: Estilos da vitrine e banners
    ├── produtos.css          # Produtos: Estilização da tabela de catálogo
    ├── sobre.css             # Sobre: Iframes de vídeo e imagens
    └── suporte.css           # Suporte: Formulários, inputs e botões

