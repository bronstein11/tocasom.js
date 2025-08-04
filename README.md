# 🥁 TocaSom JS

Um simulador de bateria interativo desenvolvido em JavaScript puro, HTML e CSS como parte dos meus estudos em desenvolvimento front-end. Toque diferentes sons de percussão clicando nos botões ou usando o teclado!

## 🎵 Demo

Experimente o projeto ao vivo: [https://tocasom-js.vercel.app](https://tocasom-js.vercel.app)

## 📚 Sobre o Projeto

Este projeto foi desenvolvido como parte dos meus estudos em **desenvolvimento front-end**. É uma aplicação que demonstra conceitos fundamentais como:

- Manipulação do DOM com JavaScript
- Eventos de mouse e teclado
- Reprodução de mídia com HTML5 Audio API
- Design responsivo com CSS Grid
- Organização de código e boas práticas

O objetivo principal é praticar e consolidar conhecimentos em JavaScript vanilla, CSS moderno e desenvolvimento web responsivo.

## ✨ Funcionalidades

- 🎼 **9 sons diferentes de percussão**: Pom, Clap, Tim, Puff, Splash, Toim, Psh, Tic, Tom
- 🖱️ **Interação com mouse**: Clique nos botões para reproduzir os sons
- ⌨️ **Suporte a teclado**: Use Space ou Enter para ativar o som quando um botão estiver em foco
- 🎨 **Design responsivo**: Interface moderna com gradientes e efeitos visuais
- 🔊 **Feedback visual**: Botões mudam de cor quando pressionados

## 🛠️ Tecnologias Utilizadas

- **HTML5**: Estrutura semântica e elementos de áudio
- **CSS3**: Estilização moderna com gradientes, sombras e animações
- **JavaScript**: Manipulação do DOM e controle de eventos
- **Google Fonts**: Tipografia Montserrat

## 🎨 Paleta de Cores

- **Cinza**: `#aaa`
- **Vermelho**: `#e93d50`
- **Vermelho Escuro**: `#af303f`
- **Branco**: `#fff`
- **Amarelo Brilhante**: `rgb(229, 255, 0)`

## 📁 Estrutura do Projeto

```
tocasom-js/
├── index.html          # Página principal
├── css/
│   ├── reset.css       # Reset de estilos
│   └── estilos.css     # Estilos principais
├── sounds/             # Arquivos de áudio
│   ├── keyq.wav        # Som Pom
│   ├── keyw.wav        # Som Clap
│   ├── keye.wav        # Som Tim
│   ├── keya.wav        # Som Puff
│   ├── keys.wav        # Som Splash
│   ├── keyd.wav        # Som Toim
│   ├── keyz.wav        # Som Psh
│   ├── keyx.wav        # Som Tic
│   └── keyc.wav        # Som Tom
├── images/
│   └── bateria.png     # Favicon
└── main.js             # Lógica JavaScript
```

## 🚀 Como Executar Localmente

1. **Clone o repositório**:
   ```bash
   git clone https://github.com/mauriciograss/tocasom-js.git
   cd tocasom-js
   ```

2. **Abra o arquivo HTML**:
   - Simplesmente abra o arquivo `index.html` em seu navegador
   - Ou use um servidor local como Live Server (VS Code extension)

3. **Divirta-se tocando**:
   - Clique nos botões para ouvir os sons
   - Use Tab para navegar entre os botões e Space/Enter para ativá-los

## 🎯 Como Usar

### Interação com Mouse
- Clique em qualquer botão colorido para reproduzir o som correspondente
- Os botões mudam de cor quando pressionados, fornecendo feedback visual

### Interação com Teclado
1. Use a tecla **Tab** para navegar entre os botões
2. Pressione **Space** ou **Enter** para reproduzir o som do botão selecionado
3. O botão ficará destacado com uma borda luminosa quando em foco

## 💡 Funcionalidades Técnicas

### JavaScript
- **Seleção de elementos**: Uso de `querySelectorAll` para capturar todos os botões
- **Manipulação de eventos**: `onclick`, `onkeydown`, `onkeyup`
- **Reprodução de áudio**: Controle dos elementos `<audio>` via JavaScript
- **Validação**: Verificação se o elemento existe antes de reproduzir o som

### CSS
- **CSS Grid**: Layout responsivo de 3 colunas para os botões
- **Variáveis CSS**: Organização das cores em variáveis reutilizáveis
- **Gradientes**: Fundo e botões com gradientes modernos
- **Pseudo-classes**: Estados `:hover`, `:active`, `:focus` para interatividade

## 🎓 Aprendizados

Durante o desenvolvimento deste projeto, pratiquei e aprendi:

### JavaScript
- **Seleção de elementos DOM**: `querySelector` e `querySelectorAll`
- **Manipulação de eventos**: Event handling com mouse e teclado
- **HTML5 Audio API**: Controle de reprodução de arquivos de áudio
- **Loops e iteração**: Processamento de arrays de elementos
- **Estruturas condicionais**: Validação e tratamento de erros
- **Manipulação de classes CSS**: `classList.add()` e `classList.remove()`

### CSS
- **CSS Grid**: Layout responsivo e organizado
- **Variáveis CSS (Custom Properties)**: Reutilização de valores
- **Pseudo-classes**: `:hover`, `:active`, `:focus` para interatividade
- **Gradientes**: Backgrounds modernos e atraentes
- **Box Shadow**: Efeitos de profundidade e elevação
- **Responsive Design**: Adaptação para diferentes tamanhos de tela

### HTML
- **Semântica**: Uso correto de elementos HTML5
- **Acessibilidade**: Suporte a navegação por teclado
- **Elementos de mídia**: Implementação de tags `<audio>`
- **Estruturação**: Organização lógica do conteúdo



---

⭐ **Projeto desenvolvido durante minha jornada de aprendizado em desenvolvimento front-end!**  
