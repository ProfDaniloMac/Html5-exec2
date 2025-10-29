# Projeto ONG Ação Social - Segunda Entrega

## Descrição

Esta segunda entrega concentra-se na aplicação de CSS3 para transformar a estrutura HTML da Entrega 1 em uma interface visual profissional, responsiva e acessível. Os alunos devem demonstrar domínio de leiautes modernos, sistemas de design e técnicas de estilização.

## Objetivos da Segunda Entrega

Aplicar CSS3 para criar uma interface visual profissional, responsiva e acessível, mantendo toda a estrutura HTML da primeira entrega intacta.

## Especificações Técnicas Implementadas

### 1. Sistema de Design

#### Paleta de Cores (8+ cores)
- **Primária**: #2c3e50 (Azul escuro)
- **Secundária**: #3498db (Azul)
- **Terciária**: #e74c3c (Vermelho)
- **Quaternária**: #27ae60 (Verde)
- **Quintenária**: #f39c12 (Laranja)
- **Fundo**: #ecf0f1 (Cinza claro)
- **Texto**: #2c3e50 (Azul escuro)
- **Texto Claro**: #7f8c8d (Cinza)

Cores adicionais: Branco, Cinza claro, Cinza médio, Cinza escuro, Sucesso, Aviso, Erro, Info

#### Tipografia Hierárquica (5+ tamanhos)
- **Extra Small**: 0.75rem (12px)
- **Small**: 0.875rem (14px)
- **Base**: 1rem (16px)
- **Medium**: 1.125rem (18px)
- **Large**: 1.25rem (20px)
- **Extra Large**: 1.5rem (24px)
- **2XL**: 2rem (32px)
- **3XL**: 2.5rem (40px)
- **4XL**: 3rem (48px)

Fonte: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif

#### Sistema de Espaçamento Modular
- **XS**: 8px
- **SM**: 16px
- **MD**: 24px
- **LG**: 32px
- **XL**: 48px
- **2XL**: 64px

### 2. Leiautes Responsivos com Flexbox e Grid

#### CSS Grid (12 colunas)
- Grid container customizado com 12 colunas
- Sistema de classes `.col-1` até `.col-12`
- Gap responsivo entre elementos
- Classes utilitárias para controle de layout

#### Flexbox
- Navegação principal com flexbox
- Cards container responsivo
- Componentes internos alinhados com flexbox
- Justify-content e align-items aplicados

#### Breakpoints Responsivos
- **Mobile**: 576px (1 coluna)
- **Tablet**: 768px (6 colunas)
- **Desktop**: 992px (12 colunas)
- **Large**: 1200px (container máximo)

### 3. Navegação Sofisticada e Interativa

#### Menu Principal Responsivo
- Menu horizontal em desktop
- Menu vertical em mobile
- Transições suaves ao passar o mouse
- Estados visuais (hover, active, focus)

#### Submenu Dropdown
- Dropdown funcional ao passar o mouse
- Posicionamento absoluto
- Sombras e efeitos visuais
- Animações de entrada

#### Menu Hambúrguer Mobile
- Botão toggle para dispositivos móveis
- Menu expansível em telas pequenas
- JavaScript necessário para funcionalidade completa (próxima entrega)

### 4. Componentes de Interface

#### Cards Responsivos
- Layout flexível com wrap
- 3 colunas em desktop
- 2 colunas em tablet
- 1 coluna em mobile
- Efeitos hover (elevação e sombra)
- Imagens com object-fit
- Transições suaves

#### Botões com Estados Visuais
Estados implementados:
- **Normal**: Cor padrão
- **Hover**: Mudança de cor e escala
- **Focus**: Outline visível para acessibilidade
- **Active**: Escala reduzida ao clicar
- **Disabled**: Opacidade reduzida, cursor not-allowed

Variações:
- Botão Primário (azul)
- Botão Secundário (cinza)
- Botão Submit (azul)
- Botão Reset (cinza)

#### Formulários Estilizados
- Fieldsets com bordas arredondadas
- Legends estilizadas
- Inputs com estados de foco
- Validação visual (border colors)
- Espaçamento consistente
- Labels bem definidas
- Radio buttons e checkboxes estilizados

#### Sistema de Badges e Tags
**Badges** (pequenos, coloridos, maiúsculas):
- Badge Sucesso (verde)
- Badge Aviso (laranja)
- Badge Erro (vermelho)
- Badge Info (azul)

**Tags** (maiores, cinza):
- Para categorização
- Estilo discreto
- Border-radius sutil

#### Componentes de Feedback

**Alerts** (4 tipos):
- Alert Sucesso
- Alert Aviso
- Alert Erro
- Alert Info

Cada um com:
- Cor de fundo apropriada
- Border lateral colorida
- Ícone visual (implementação futura com JS)

**Toasts**:
- Posicionamento fixo (canto inferior direito)
- Animação de entrada (slideIn)
- Sombra pronunciada
- Z-index elevado

**Modals**:
- Overlay com background escurecido
- Centralizado na tela
- Conteúdo com sombra
- Display controlado por JavaScript (próxima entrega)

### 5. Tabelas Responsivas

#### Desktop
- Layout tradicional de tabela
- Cabeçalho com fundo colorido
- Hover nas linhas
- Bordas sutis

#### Mobile
- Conversão para layout de cards
- Cada linha vira um bloco
- Labels dinâmicos com data-label
- Melhor leitura em telas pequenas

### 6. Responsividade Completa

#### Mobile First
- Base desenvolvida para mobile
- Media queries para telas maiores
- Testes em múltiplos dispositivos

#### Adaptações por Breakpoint

**Mobile (até 576px)**:
- Menu hambúrguer
- 1 coluna
- Fontes reduzidas
- Tabelas em formato de cards
- Espaçamentos compactos

**Tablet (577px - 768px)**:
- 2 colunas nos cards
- Grid de 6 colunas
- Menu vertical
- Fontes intermediárias

**Desktop (769px+)**:
- 3 colunas nos cards
- Grid completo de 12 colunas
- Menu horizontal
- Fontes completas

### 7. Animações e Transições

#### Transições Implementadas
- Botões: 0.15s ease
- Links: 0.15s ease
- Cards hover: 0.3s ease
- Inputs focus: 0.3s ease
- Fade in: 0.5s ease

#### Animações CSS
- @keyframes fadeIn
- @keyframes slideIn
- Transform em hover
- Opacity transitions

### 8. Acessibilidade

#### Foco Visível
- Outline de 3px para elementos focados
- Offset de 2px para clareza
- Cor contrastante (azul secundário)

#### Alto Contraste
- Media query para prefers-contrast
- Ajuste de cores para melhor contraste
- Preto/branco em modo alto contraste

#### Redução de Movimento
- Media query para prefers-reduced-motion
- Animações desabilitadas para quem prefere
- Transições mínimas

#### Semântica Visual
- Cores não são única forma de comunicação
- Icons e textos complementam cores
- Labels apropriadas em formulários

## Estrutura de Arquivos

```
projeto-ong/
│
├── README.md (ESTE ARQUIVO)
├── style.css (NOVO)
├── index.html (ATUALIZADO - link CSS)
├── projetos.html (ATUALIZADO - link CSS)
├── cadastro.html (ATUALIZADO - link CSS)
│
└── imagens/
    └── (mesmas imagens da Entrega 1)
```

## Alterações nos Arquivos HTML

### Modificações Mínimas
Apenas foram adicionadas:
1. **Link para CSS**: `<link rel="stylesheet" href="style.css">` no `<head>` de cada página
2. **Classe container**: Adicionada `class="container"` na tag `<main>` para centralização

**Nenhuma estrutura HTML foi alterada**, conforme especificado.

## Como Testar o Projeto

### 1. Verificar Estrutura
Certifique-se que os arquivos estão organizados:
- style.css na raiz
- 3 arquivos HTML na raiz
- Pasta imagens com todas as imagens

### 2. Abrir no Navegador
1. Abra index.html
2. Verifique se o CSS está carregando
3. Teste a navegação entre páginas
4. Verifique se todas as imagens aparecem

### 3. Testar Responsividade
**Método 1 - DevTools:**
1. Abra o inspetor (F12)
2. Clique no ícone de dispositivo móvel
3. Teste diferentes tamanhos de tela:
   - 375px (iPhone)
   - 768px (iPad)
   - 1024px (Desktop)
   - 1920px (Full HD)

**Método 2 - Redimensionar Janela:**
1. Redimensione manualmente a janela do navegador
2. Observe as mudanças no layout
3. Verifique quebras de linha
4. Teste o menu em mobile

## Diferenças da Entrega 1

### O que foi mantido:
- ✅ Toda estrutura HTML
- ✅ Todas as tags semânticas
- ✅ Todo o conteúdo
- ✅ Hierarquia de títulos
- ✅ Formulários completos
- ✅ Validação nativa HTML

### O que foi adicionado:
- ✅ Arquivo style.css
- ✅ Link CSS nos 3 HTMLs
- ✅ Classe "container" no main
- ✅ Sistema completo de estilização

## Tecnologias Utilizadas

- **HTML5**: Estrutura semântica (mantida da Entrega 1)
- **CSS3**: Estilização completa
- **CSS Grid**: Layout de 12 colunas
- **Flexbox**: Componentes e navegação
- **Media Queries**: Responsividade
- **CSS Variables**: Sistema de design
- **CSS Animations**: Transições e animações
- **Pseudo-classes**: Estados de hover, focus, active


## Observações Importantes

### Compatibilidade
- ✅ Chrome (últimas 2 versões)
- ✅ Firefox (últimas 2 versões)
- ✅ Safari (últimas 2 versões)
- ✅ Edge (últimas 2 versões)

### Boas Práticas Aplicadas
- Mobile-first approach
- BEM naming (parcial)
- DRY (Don't Repeat Yourself)
- Variáveis CSS para manutenção
- Comentários organizados
- Código indentado e legível

