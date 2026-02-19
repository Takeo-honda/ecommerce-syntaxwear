# SyntaxWear E-Commerce - Documentação

## 📋 Briefing do Projeto

SyntaxWear é uma loja de e-commerce focada em roupas e acessórios com tema de tecnologia/programação.

### Objetivos
- Criar uma experiência de compra intuitiva e responsiva
- Destacar produtos com design moderno
- Facilitar navegação e busca de produtos
- Implementar sistema de carrinho e checkout

## 📁 Estrutura do Projeto

```
ecommerce-syntaxwear/
├── index.html (página inicial)
├── css/
│   ├── base.css (reset, tipografia, variáveis)
│   ├── layout.css (grid, containers, espaçamento)
│   └── components/
│       ├── header.css
│       ├── hero.css
│       ├── product-card.css
│       ├── product-grid.css
│       ├── panel.css
│       ├── newsletter.css
│       └── footer.css
├── images/
│   ├── logo/
│   ├── banners/
│   ├── products/ (com subcategorias)
│   ├── icons/ (SVGs)
│   ├── fonts/ (fontes self-hosted)
│   └── favicons/
└── docs/
    └── README.md (este arquivo)
```

## 🎨 Design System

### Cores
- **Primária**: #000 (Preto)
- **Secundária**: #fff (Branco)
- **Accent**: #ff6b6b (Vermelho)
- **Neutro Escuro**: #333
- **Neutro Claro**: #f5f5f5

### Tipografia
- **Font Principal**: Segoe UI, sans-serif
- **Font Secundária**: Georgia, serif

### Espaçamento
- xs: 0.25rem
- sm: 0.5rem
- md: 1rem
- lg: 1.5rem
- xl: 2rem
- 2xl: 3rem

## 📝 Guia de Conteúdos

### Seções Principais
1. **Header** - Navegação e busca
2. **Hero** - Banner principal com CTA
3. **Product Grid** - Catálogo de produtos
4. **Newsletter** - Inscrição em newsletter
5. **Footer** - Links e informações

### Categorias de Produtos Sugeridas
- Camisetas
- Hoodies
- Acessórios
- Eletrônicos
- Livros

## 🛠️ Componentes Disponíveis

### base.css
- Variáveis CSS (cores, fontes, espaçamento)
- Reset de estilos
- Tipografia global
- Utilitários de texto e layout

### layout.css
- Container responsivo
- Sistema de grid
- Flexbox helpers
- Espaçamento e alinhamento

### components/
Cada arquivo CSS de componente inclui:
- Estilos base do componente
- Estados (hover, active)
- Responsividade
- Acessibilidade

## 📱 Breakpoints

- Mobile: < 768px
- Tablet: 768px - 1024px
- Desktop: > 1024px

## ✅ Checklist de Implementação

- [ ] Implementar HTML base (index.html)
- [ ] Criar páginas de categoria
- [ ] Adicionar página de detalhes do produto
- [ ] Implementar carrinho de compras
- [ ] Criar page de checkout
- [ ] Adicionar sistema de busca
- [ ] Implementar filtros de produtos
- [ ] Otimizar imagens
- [ ] Testes de responsividade
- [ ] SEO optimization
- [ ] Performance optimization

## 🔗 Recursos Úteis

- CSS Variables/Tokens documentados em `css/base.css`
- Componentes reutilizáveis em `css/components/`
- Layout helpers em `css/layout.css`

## 👤 Autor

Seu Nome - 2026

---

*Última atualização: Fevereiro 2026*
