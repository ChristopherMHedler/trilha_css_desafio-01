# Landing Page CSS - Trilha de CSS DIO

## Descrição
Este projeto contém um CSS profissional e responsivo para a landing page institucional da Trilha de CSS da DIO. O design foi criado com foco em modernidade, usabilidade e responsividade.

## Arquivos Incluídos
- `style.css` - Arquivo CSS principal (para usar com HTML externo)
- `index.html` - Arquivo HTML completo com CSS incorporado (para demonstração)

## Funcionalidades Implementadas

### 🎨 Design Moderno
- **Gradientes**: Uso de gradientes lineares em várias seções para criar profundidade visual
- **Sombras**: Box-shadows e text-shadows para dar dimensão aos elementos
- **Tipografia**: Fonte moderna (Segoe UI) com hierarquia visual clara
- **Cores**: Paleta de cores harmoniosa com tons de azul, roxo e laranja

### 📱 Responsividade
- **Mobile First**: Design adaptável para dispositivos móveis
- **Breakpoints**: 768px e 480px para tablets e smartphones
- **Grid Layout**: Sistema de grid flexível para os módulos
- **Imagens Responsivas**: Imagens que se adaptam ao tamanho da tela

### ✨ Animações e Efeitos
- **Fade In**: Animação de entrada suave no banner principal
- **Hover Effects**: Efeitos de hover nos botões e cards dos módulos
- **Transform**: Efeitos de elevação e escala nos elementos interativos
- **Background Animation**: Animação de pontos flutuantes na seção "Transform World"

### 🎯 Seções Estilizadas

#### Banner Principal
- Fundo com gradiente e overlay escuro
- Texto com gradiente e sombra
- Botão com efeito hover e sombra
- Animação de entrada fadeInUp

#### Seção de Conteúdo do Curso
- Fundo com gradiente suave
- Cards dos módulos com hover effects
- Cores diferentes para cada módulo
- Layout em grid responsivo

#### Seção Transform World
- Fundo com gradiente vibrante
- Animação de pontos flutuantes
- Texto em destaque com sombra

#### Seção Desafios Profissionais
- Layout limpo e centrado
- Imagem com hover effect
- Tipografia legível e espaçamento adequado

#### Footer
- Fundo escuro com gradiente
- Links com efeito hover
- Logo com filtro de brilho

### 🔧 Recursos Técnicos
- **CSS Grid**: Para layout dos módulos
- **Flexbox**: Para alinhamento e centralização
- **CSS Variables**: Cores e valores reutilizáveis
- **Media Queries**: Responsividade completa
- **Pseudo-elementos**: Para decorações e efeitos
- **Smooth Scrolling**: Navegação suave
- **Print Styles**: Estilos para impressão

### ♿ Acessibilidade
- **Focus Styles**: Indicadores visuais para navegação por teclado
- **Contraste**: Cores com contraste adequado
- **Alt Text**: Suporte para textos alternativos
- **Semantic HTML**: Estrutura semântica preservada

## Como Usar

### Opção 1: CSS Externo
1. Copie o conteúdo do arquivo `style.css`
2. Salve em um arquivo `.css` no seu projeto
3. Adicione a tag `<link>` no `<head>` do seu HTML:
```html
<link rel="stylesheet" href="caminho/para/seu/style.css">
```

### Opção 2: CSS Incorporado
1. Use o arquivo `index.html` como base
2. O CSS já está incorporado na tag `<style>`
3. Substitua as imagens pelos caminhos corretos

## Estrutura de Pastas Recomendada
```
projeto/
├── index.html
├── style.css
└── assets/
    └── images/
        ├── logo.png
        ├── professional-challenges.png
        └── dio-logo.png
```

## Personalização
O CSS foi estruturado de forma modular, permitindo fácil personalização:
- Altere as cores nos gradientes para mudar a identidade visual
- Modifique os breakpoints nas media queries conforme necessário
- Ajuste as animações alterando os valores de `transition` e `animation`
- Personalize a tipografia mudando a `font-family`

## Compatibilidade
- ✅ Chrome 60+
- ✅ Firefox 55+
- ✅ Safari 12+
- ✅ Edge 79+
- ✅ Dispositivos móveis iOS e Android

## Observações
- As imagens são opcionais - o CSS inclui placeholders para quando não estão disponíveis
- O design é otimizado para performance com uso eficiente de CSS
- Todas as animações respeitam a preferência do usuário por movimento reduzido

