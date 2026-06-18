# Rating Card

Um componente simples de avaliação (rating card) construído com HTML, CSS e JavaScript. Permite que o usuário avalie uma experiência de 0 a 5 estrelas, com um emoji que reage dinamicamente à nota escolhida.

## Demonstração

A interface exibe um cartão centralizado contendo:

- Um **emoji de reação** que muda de acordo com a nota selecionada (ex: irritado para nota baixa, feliz para nota alta).
- Uma fileira de **5 estrelas** clicáveis para o usuário dar a nota.
- O texto **"Rate your experience"** como título do card.
- Um contador no formato **"X out of 5"**, exibindo a nota atual.

## Funcionalidades

- ⭐ Seleção de nota por estrelas (1 a 5).
- 🙂 Emoji reativo que muda conforme a avaliação.
- 🔢 Contador dinâmico mostrando a pontuação selecionada.
- 🎨 Layout centralizado com card sobre fundo colorido.

## Tecnologias utilizadas

- **HTML5** — estrutura do card.
- **CSS3** — estilização do card, emoji e estrelas.

## Como executar

1. Clone ou baixe este repositório.
2. Abra o arquivo `index.html` diretamente no navegador, **ou**
3. Use a extensão **Live Server** (VS Code) para servir o projeto localmente, por exemplo em:
   ```
   http://127.0.0.1:5500/index.html
   ```

Não há dependências externas ou processo de build — é um projeto front-end estático.

## Estrutura sugerida do projeto

```
rating-card/
├── index.html      # Estrutura do card
├── style.css       # Estilos do componente
└── README.md       # Este arquivo
```

## Possíveis melhorias futuras

- Salvar a avaliação em local storage ou em um backend.
- Adicionar animações de transição ao trocar o emoji.
- Permitir avaliação por teclado (acessibilidade).
- Adicionar mensagens de feedback de acordo com a nota (ex: "Obrigado!", "Sentimos muito, vamos melhorar!").

## Licença

Este projeto pode ser usado livremente para fins de estudo e prática de front-end.
