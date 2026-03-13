# JC Barbearia - Landing Page

Landing page moderna e responsiva para a barbearia **JC Barbearia**, criada como parte do meu portfólio.

## Tecnologias utilizadas

- **HTML5**
  - Estrutura semântica (`header`, `main`, `section`, `article`, `footer`)
  - Layout mobile-first
  - Acessibilidade básica com `aria-label`, `alt` em imagens e navegação por âncoras

- **CSS3**
  - Estilização moderna com:
    - Variáveis CSS (`:root`) para cores, tipografia e espaçamentos
    - Gradientes (`linear-gradient`, `radial-gradient`) para fundos e cards
    - Flexbox e CSS Grid para criar layouts responsivos
    - Media queries para adaptação em diferentes resoluções
    - Animações e transições suaves em hovers de botões e cards
  - Componentização visual:
    - Botões reutilizáveis (`.btn-primary`, `.btn-outline`)
    - Cards de profissionais, planos e seções em destaque
    - Botões de contato com ícone customizado de WhatsApp em CSS
    - Botões de redes sociais estilizados com “ícones” feitos em CSS puro

- **JavaScript Vanilla (ES6+)**
  - Script simples para:
    - Controle do menu mobile (botão “hambúrguer” que abre/fecha o dropdown)
    - Atualização automática do ano no rodapé (`new Date().getFullYear()`)

## Estrutura do projeto

- `index.html` — Estrutura da landing page e conteúdo das seções.
- `style.css` — Todos os estilos da interface (cores, layout, animações, responsividade).
