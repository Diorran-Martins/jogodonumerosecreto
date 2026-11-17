# 🔢 Jogo do Número Secreto

Um jogo interativo de adivinhação desenvolvido em **JavaScript puro**, **HTML5** e **CSS3**, criado com foco em praticar a lógica de programação, manipulação do DOM e integração com recursos nativos do navegador (como a Web Speech API para acessibilidade por voz).

## 🎯 Como o jogo funciona?

1. O sistema sorteia de forma aleatória um número secreto entre **1 e 10**.
2. O jogador digita um palpite no campo numérico e clica no botão **Chutar**.
3. A aplicação valida o palpite e dá dicas dinâmicas na tela informando se o número secreto é **maior** ou **menor** que o valor digitado.
4. O jogo conta o número de tentativas e, ao acertar, reproduz uma mensagem de parabéns, além de habilitar o botão **Novo Jogo** para reiniciar a partida.
5. **Acessibilidade:** Conta com suporte à síntese de voz (`SpeechSynthesisUtterance`) para narrar os textos da interface em português do Brasil (`pt-BR`)[cite: 1].

## 🚀 Tecnologias Utilizadas

* **HTML5** — Estruturação semântica da página.
* **CSS3** — Estilização, design responsivo e fontes tipográficas (*Chakra Petch* e *Inter*)[cite: 2].
* **JavaScript (ES6)** — Lógica do jogo, controle de estado, manipulação de elementos e funções de áudio/voz.

## 💻 Como executar o projeto localmente

Você pode clonar este repositório e testar o jogo diretamente no seu computador:

1. Clone o repositório:
   ```bash
   git clone [https://github.com/Diorran-Martins/jogodonumerosecreto.git](https://github.com/Diorran-Martins/jogodonumerosecreto.git)
