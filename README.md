# MoodFilm

> Filmes que sentem com você: recomendações emocionais baseadas no seu humor.

## Descrição

MoodFilm é um projeto front-end leve, responsivo e 100% mobile-first que usa lógica de IA para recomendar filmes de acordo com o estado emocional ou situação descrita pelo usuário. Ele oferece:

* Campo de texto livre para input de humor.
* Sugestões de quebra-gelos clicáveis.
* Geração de 3 cards de filmes com pôster, título, sinopse curta e insight emocional.
* Modal de detalhes com análise aprofundada, sugestões de trilha sonora e chat simulado com personagem.

## Funcionalidades

* **Input de humor**: textarea para o usuário descrever como se sente.
* **Quebra-gelos**: botões com frases prontas para agilizar a escrita.
* **Recomendações**: 3 filmes sugeridos via chamada a API (ex.: Gemini API).
* **Detalhes**: modal com análise da IA, trilha sonora sugerida e chat com personagem principal.
* **Design**: tema escuro, efeito glassmorphism e animações sutis.

## Tech Stack

* HTML5, CSS3 e JavaScript (ES6+)
* Tailwind CSS para estilização
* Google Fonts (Inter)
* Fetch API para chamadas externas

## Pré-requisitos

* Navegador moderno com suporte a ES6 e Fetch API
* Chave de API válida para a GPT ou Gemini API (ou outra generative AI)

## Instalação e Uso

1. **Clone este repositório**:

   ```bash
   git clone https://github.com/seu-usuario/moodfilm.git
   cd moodfilm
   ```

2. **Configurar chave de API**:

   * Abra `script.js` e localize a variável `apiKey`.
   * Insira sua chave de API gerativa:

     ```js
     const apiKey = "SUA_CHAVE_AQUI";
     ```

3. **Executar localmente**:

   * Abra `index.html` no navegador.
   * Ou, use um servidor local (recomendado):

     ```bash
     npx http-server .
     ```

4. **Testar**:

   * Descreva como se sente ou clique em um quebra-gelo.
   * Clique em **Recomendar Filmes**.
   * Explore os cards e abra o modal para detalhes.

## Estrutura de Arquivos

```
├── index.html       # Marcações e estrutura do layout
├── style.css        # Estilos customizados (Tailwind + CSS)
├── script.js        # Lógica de recomendação e interações
└── README.md        # Documentação do projeto
```

## Customização e Extensões

* **Fonte**: troque no `index.html` via Google Fonts.
* **Temas**: ajuste as cores em `.gradient-bg` e classes do Tailwind.
* **Filmes**: substitua o JSON local por integração com TMDB ou outra API de catálogo.
* **Análise de Sentimento**: troque a chamada de API para outra solução de NLP.

## Contribuições

Contribuições são bem-vindas! Abra issues para sugestões ou bugs e envie pull requests.

## Licença

Este projeto está licenciado sob a [MIT License](LICENSE).
