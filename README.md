# Jogo do Número Secreto

Jogo de adivinhação em JavaScript puro: o jogador tenta descobrir um número secreto entre 1 e 10, recebendo a dica de "maior" ou "menor" a cada tentativa, até acertar.

![HTML5](https://img.shields.io/badge/HTML5-E34F26?logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?logo=javascript&logoColor=black)

Segunda fase do projeto, com funções mais avançadas que a versão inicial.

---

## Como jogar

1. Abra o `index.html` no navegador
2. Digite um número entre 1 e 10
3. Clique em **Chutar**
4. O jogo indica se o número secreto é maior ou menor
5. Ao acertar, o botão **Novo jogo** é liberado para recomeçar

Não tem instalação, build nem dependência — é HTML, CSS e JS puros.

---

## Conceitos praticados

- Manipulação do DOM com `querySelector` e `getElementById`
- Funções com parâmetros e reaproveitamento de lógica
- Template literals para montar mensagens dinâmicas
- Condicionais e operador ternário
- Geração de números aleatórios com `Math.random()`
- Controle de estado entre rodadas (contador de tentativas)
- Habilitar/desabilitar elementos via atributos HTML

---

## Estrutura

```
├── index.html   # Estrutura da página e botões
├── app.js       # Lógica do jogo
├── style.css    # Estilos
└── img/         # Imagens de fundo e assets
```

### Principais funções

| Função | Responsabilidade |
|---|---|
| `gerarNumeroAleatorio()` | Sorteia o número secreto de 1 a 10 |
| `exibirTextoNaTela()` | Escreve texto em um elemento da página |
| `exibirMensagemInicial()` | Monta o título e a instrução iniciais |
| `verificarChute()` | Compara o chute com o número secreto |
| `limparCampo()` | Limpa o input após cada tentativa |
| `reiniciarJogo()` | Sorteia novo número e zera as tentativas |

---

## Sobre o projeto

Exercício desenvolvido durante os estudos de JavaScript, com foco em praticar manipulação do DOM e organização do código em funções.
