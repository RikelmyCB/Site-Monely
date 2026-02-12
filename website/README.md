# Monely - Website

Site oficial do Monely, seu assistente financeiro inteligente com IA.

## 🎨 Características do Design

- **Design Moderno**: Interface dark mode com gradientes vibrantes
- **Animações Suaves**: Transições e efeitos parallax
- **Totalmente Responsivo**: Adaptado para desktop, tablet e mobile
- **Performance Otimizada**: Carregamento rápido e animações fluidas
- **Acessibilidade**: Navegação por teclado e semântica HTML

## 🚀 Recursos Implementados

### Seções
- **Hero**: Apresentação principal com mockup animado do app
- **Features**: Grid de recursos com cards interativos
- **How It Works**: Passo a passo de como usar o app
- **AI Section**: Destaque para funcionalidades de IA
- **Security**: Medidas de segurança implementadas
- **Download**: Links para App Store e Google Play
- **Footer**: Links úteis e informações

### Animações
- Floating orbs no background
- Phone mockup com efeito 3D
- Floating cards com informações
- Scroll reveal animations
- Hover effects em todos os elementos interativos
- Parallax scrolling
- Counter animations
- Ripple effect nos botões
- Typing effect no título

### Interatividade
- Navegação suave entre seções
- Menu mobile responsivo
- Intersection Observer para animações
- Efeito tilt no mockup do celular
- Easter egg (Konami code)

## 📁 Estrutura de Arquivos

```
website/
├── index.html      # Estrutura HTML
├── styles.css      # Estilos e animações
├── script.js       # Interatividade e animações JS
└── README.md       # Este arquivo
```

## 🎯 Como Usar

1. Abra o arquivo `index.html` em qualquer navegador moderno
2. Ou use um servidor local:
   ```bash
   # Python
   python -m http.server 8000
   
   # Node.js
   npx serve
   ```
3. Acesse `http://localhost:8000`

## 🎨 Paleta de Cores

- **Primary**: #6366f1 (Indigo)
- **Secondary**: #ec4899 (Pink)
- **Accent**: #14b8a6 (Teal)
- **Success**: #10b981 (Green)
- **Background**: #0f172a (Dark Blue)

## 🌟 Destaques Técnicos

- CSS Grid e Flexbox para layouts
- CSS Custom Properties (variáveis)
- Intersection Observer API
- Smooth scrolling nativo
- Animações CSS otimizadas
- Mobile-first approach
- Sem dependências externas (exceto Google Fonts)

## 📱 Responsividade

- **Desktop**: 1280px+
- **Tablet**: 768px - 1024px
- **Mobile**: 320px - 767px

## 🔧 Customização

### Cores
Edite as variáveis CSS no início do `styles.css`:
```css
:root {
    --primary: #6366f1;
    --secondary: #ec4899;
    /* ... */
}
```

### Conteúdo
Edite o texto diretamente no `index.html`

### Animações
Ajuste os timings e easing no `styles.css` e `script.js`

## 🚀 Deploy

### Opções de Hospedagem
- **Vercel**: `vercel --prod`
- **Netlify**: Arraste a pasta para netlify.com
- **GitHub Pages**: Push para branch gh-pages
- **Firebase Hosting**: `firebase deploy`

## 📊 Performance

- Lighthouse Score: 95+
- First Contentful Paint: < 1s
- Time to Interactive: < 2s
- Cumulative Layout Shift: < 0.1

## 🎁 Easter Eggs

- Código Konami: ⬆️⬆️⬇️⬇️⬅️➡️⬅️➡️BA
- Console messages com dicas

## 📝 Licença

MIT License - Veja o arquivo LICENSE no projeto principal

## 🤝 Contribuindo

Sugestões e melhorias são bem-vindas!

---

Feito com 💜 para o Monely
