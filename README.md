# 🛍️ Catálogo Premium de Produtos

Um projeto de catálogo de e-commerce moderno, responsivo e profissional desenvolvido com **HTML5**, **SCSS** e **JavaScript puro**, seguindo as melhores práticas de CSS e acessibilidade web.

## ✨ Características Principais

### 🎨 Design Responsivo
- Totalmente adaptável para dispositivos mobile, tablet e desktop
- Grid system flexível com `CSS Grid` e `Flexbox`
- Breakpoints otimizados para melhor visualização
- Tipografia fluida com `clamp()`

### 📱 Navbar Profissional
- Menu sticky (fixo no topo)
- Logo com gradiente animado
- Menu hamburger responsivo para mobile
- Ícones de ação (Pesquisar, Favoritos, Carrinho)
- JavaScript para interação do menu
- Acessibilidade ARIA completa

### 🎯 Grid de Produtos
- Layout adaptativo com `grid-template-columns: repeat(auto-fill, minmax())`
- Cards com efeitos hover suaves
- Produto em destaque com destaque visual
- Contagem dinâmica de colunas por breakpoint
- Transições CSS fluidas

### 💎 Componentes Estilizados
- **Header**: Gradiente, padrão SVG de fundo, tipografia responsiva
- **Filtros**: Botões com estado ativo/inativo
- **Cards de Produto**: 
  - Imagem com zoom ao hover
  - Sombras elegantes
  - Badge de destaque
  - Preço em gradiente
  - Botão de ação
- **Footer**: Com créditos personalizados

### ♿ Acessibilidade
- Atributos ARIA (`aria-label`, `aria-expanded`, `role`)
- Navegação com teclado funcional
- Semântica HTML5 apropriada
- Contraste de cores WCAG compliant
- Textos alternativos em imagens

## 🚀 Como Usar

### Pré-requisitos
- Node.js instalado
- npm ou yarn

### Instalação

1. Clone o repositório:
```bash
git clone https://github.com/gabedossa/Exercicio-CSS.git
cd Exercicio-CSS
```

2. Instale as dependências:
```bash
npm install
```

### Desenvolvimento

Para compilar SCSS em tempo real:
```bash
npm run watch
```

Ou compile uma única vez:
```bash
npm run build
```

### Executar Servidor Local

Inicie um servidor local para visualizar o projeto:
```bash
npx live-server --port=5500
```

Acesse em: `http://localhost:5500`

## 📁 Estrutura do Projeto

```
Exercicio-CSS/
├── FrontEnd M19 - index.html    # Arquivo HTML principal
├── main.scss                     # Estilos SCSS com variáveis
├── main.css                      # CSS compilado
├── main.css.map                  # Source map para debugging
├── package.json                  # Configuração npm
└── README.md                     # Este arquivo
```

## 🛠️ Tecnologias Utilizadas

### Frontend
- **HTML5** - Semântica e estrutura
- **SCSS** - Preprocessador CSS com variáveis e mixins
- **CSS3** - Grid, Flexbox, Gradientes, Transições
- **JavaScript (ES6+)** - Interatividade do menu mobile

### Ferramentas
- **Sass** - Compilação SCSS → CSS
- **Live Server** - Servidor local com hot reload
- **npm** - Gerenciador de pacotes

## 📦 Scripts npm

```json
{
  "build": "sass main.scss main.css",
  "watch": "sass --watch main.scss:main.css"
}
```

## 🎨 Paleta de Cores

| Cor | Hex | Uso |
|-----|-----|-----|
| Primária | `#667eea` | Botões, links, destaques |
| Secundária | `#764ba2` | Gradientes, efeitos |
| Texto | `#2c3e50` | Títulos e corpo |
| Texto Leve | `#7f8c8d` | Descrições, subtítulos |
| Branco | `#ffffff` | Fundo dos cards |
| Background | `#f8f9fa` | Fundos alternativos |

## 📋 Breakpoints Responsivos

| Dispositivo | Largura | Colunas Grid |
|-------------|---------|-------------|
| Desktop | > 1024px | 4 colunas |
| Tablet | 768px - 1024px | 3 colunas |
| Tablet Small | 640px - 768px | 2 colunas |
| Mobile | < 640px | 1 coluna |

## 🔄 Fluxo de Desenvolvimento

1. **Edição de SCSS** → `main.scss`
2. **Compilação automática** → `main.css`
3. **Servidor local** recarrega automaticamente
4. **Teste responsivo** usando DevTools

## 🌐 Recursos de Responsividade

- ✅ Menu hamburger em mobile
- ✅ Tipografia fluida (clamp)
- ✅ Imagens responsivas
- ✅ Padding/Margin adaptativo
- ✅ Grid sistema flexível
- ✅ Touch-friendly buttons (>44px)

## 🎯 Boas Práticas Implementadas

### CSS
- ✅ Metodologia **BEM** (Block, Element, Modifier)
- ✅ Variáveis SCSS reutilizáveis
- ✅ Mobile-first approach
- ✅ Transições performáticas
- ✅ Especificidade controlada

### JavaScript
- ✅ Event delegation
- ✅ Manipulação clara do DOM
- ✅ Tratamento de cliques fora
- ✅ Comentários documentados

### HTML
- ✅ Semântica HTML5
- ✅ ARIA attributes
- ✅ Estrutura acessível
- ✅ Meta tags corretas

## 📊 Performance

- Compilação SCSS otimizada
- Minified CSS na produção
- Transições GPU-aceleradas
- CSS Grid nativo (melhor performance que Float)
- Source maps para debugging

## 🤝 Contribuições

Contribuições são bem-vindas! Por favor:

1. Faça um Fork do projeto
2. Crie uma branch para sua feature (`git checkout -b feature/AmazingFeature`)
3. Commit suas mudanças (`git commit -m 'Add some AmazingFeature'`)
4. Push para a branch (`git push origin feature/AmazingFeature`)
5. Abra um Pull Request

## 📝 Licença

Este projeto está sob a licença MIT. Veja o arquivo `LICENSE` para mais detalhes.

## 👨‍💻 Autor

**Gabriel Ouverney**

- GitHub: [@gabedossa](https://github.com/gabedossa)
- Projeto EBAC - Exercício de Boas Práticas de CSS
- © 2026 Todos os direitos reservados

## 🔗 Links Úteis

- [MDN Web Docs - CSS Grid](https://developer.mozilla.org/en-US/docs/Web/CSS/CSS_Grid_Layout)
- [SASS Documentation](https://sass-lang.com/documentation)
- [Web Accessibility Guidelines (WCAG)](https://www.w3.org/WAI/WCAG21/quickref/)
- [BEM Methodology](http://getbem.com/)

## 🐛 Bugs Conhecidos

Nenhum no momento. Se encontrar algum, abra uma [issue](https://github.com/gabedossa/Exercicio-CSS/issues).

---

**Desenvolvido com ❤️ e Boas Práticas de CSS**
