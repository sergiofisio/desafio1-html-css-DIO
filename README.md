# desafio1-html-css-DIO

Este projeto é um desafio de criação de uma página web responsiva utilizando **somente HTML e CSS**, sem o uso de bibliotecas ou frameworks JavaScript. Ele faz parte da Trilha de CSS oferecida pela **DIO (Digital Innovation One)**, com o objetivo de solidificar os conhecimentos em estilização e layout para desenvolvimento de sites profissionais.

## 🚀 Tecnologias Utilizadas

* **HTML5**: Para a estruturação do conteúdo da página.
* **CSS3**: Para toda a estilização, incluindo layout, cores, tipografia, efeitos e responsividade.
* **Google Fonts**: Para importar as fontes `Raleway` e `Montserrat`.

## ✨ Funcionalidades e Destaques

* **Layout Responsivo**: A página se adapta a diferentes tamanhos de tela, proporcionando uma boa experiência em desktops, tablets e smartphones.
* **Design Moderno**: Utiliza um esquema de cores vibrante (azul/ciano e preto) com gradientes e sombras para um visual atraente.
* **Estilização Avançada de CSS**:
    * Uso de `flexbox` para layouts flexíveis.
    * Bordas com gradiente (`border-image`).
    * Efeitos de `hover` em botões.
    * Sombras internas (`box-shadow: inset`) e externas (`filter: drop-shadow`).
    * Texto com gradiente de cor (`-webkit-background-clip: text;` e `background-clip: text;`).
    * Tratamento de texto com `white-space: nowrap;`, `overflow: hidden;` e `text-overflow: ellipsis;` para controle de quebras de linha em elementos específicos.
* **Estrutura Semântica**: O HTML utiliza tags semânticas (`<header>`, `<section>`, `<footer>`, `<main>`) para melhorar a acessibilidade e SEO.

## 📁 Estrutura do Projeto

desafio1-html-css-DIO/
├── assets/
│   ├── bg.svg              # Imagem de fundo do cabeçalho
│   ├── logo.svg            # Logo principal
│   ├── logodio.svg         # Logo da DIO no rodapé
│   ├── evolua.svg          # Imagem da seção "Evolua"
│   └── transforme.png      # Imagem de fundo da seção "Transforme o mundo"
├── global.css              # Estilos CSS globais (h1, h2, p, h3, h4, a)
├── index.html              # Estrutura principal da página web
└── style.css               # Estilos CSS específicos da página e componentes

## 💻 Como Rodar o Projeto

1.  **Clone o repositório:**
    ```bash
    git clone [https://github.com/seu-usuario/desafio1-html-css-DIO.git](https://github.com/seu-usuario/desafio1-html-css-DIO.git)
    ```
2.  **Navegue até o diretório do projeto:**
    ```bash
    cd desafio1-html-css-DIO
    ```
3.  **Abra o arquivo `index.html` em seu navegador:**
    Você pode simplesmente clicar duas vezes no arquivo `index.html` ou usar uma extensão de servidor local (como o "Live Server" do VS Code) para uma melhor experiência de desenvolvimento.

## ⚙️ Configurações e Customizações

* **Cores**: As cores principais (`#33a8db`, `#1472b7`, `#000`, `#252525`, `#fff`) podem ser facilmente ajustadas nos arquivos `.css` para mudar o tema da página.
* **Fontes**: As fontes são importadas do Google Fonts. Para usar outras fontes, basta alterar os `@import url()` e as declarações `font-family`.
* **Conteúdo**: Todo o texto e as imagens podem ser modificados diretamente no arquivo `index.html`.

## 🤝 Contribuições

Contribuições são bem-vindas! Se você tiver sugestões, melhorias ou encontrar algum bug, sinta-se à vontade para abrir uma issue ou enviar um pull request.

## 📝 Licença

Este projeto está sob a licença MIT. Veja o arquivo `LICENSE` para mais detalhes.

---
**Desenvolvido como parte do desafio da Trilha de CSS da DIO.**