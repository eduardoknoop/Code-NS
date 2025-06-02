# 🔢 Jogo do Número Secreto

Este é um simples jogo interativo de adivinhação de números feito com **JavaScript**, **HTML** e **CSS**, com suporte a **voz sintetizada** usando a API do `responsiveVoice`.

---

## 🎮 Como funciona

- O jogo escolhe aleatoriamente um número secreto entre **1 e 10**.
- O jogador tenta adivinhar o número digitando um valor no campo de entrada.
- A cada tentativa:
  - Se acertar, o jogo exibe uma mensagem de sucesso com o número de tentativas.
  - Se errar, ele avisa se o número secreto é **maior** ou **menor** que o chute.
- Ao acertar, o botão "Reiniciar" é habilitado para jogar novamente.
- O jogo evita a repetição de números já sorteados até que todos sejam utilizados, garantindo variedade a cada nova rodada.

---

## 🧠 Lógica por trás

- `gerarNumeroAleatorio()`: Gera um número entre 1 e 10 que **ainda não foi sorteado**.
- `verificarChute()`: Compara o número digitado com o número secreto e exibe a resposta apropriada.
- `exibirTextoNaTela(tag, texto)`: Atualiza o conteúdo da página e também **fala o texto em voz alta** com a voz feminina brasileira (via `responsiveVoice`).
- `reiniciarJogo()`: Reseta o número secreto, limpa os campos e reativa o jogo.
- `listaDeNumerosSorteados`: Evita que números se repitam até que todos já tenham sido sorteados.

---

## 🗣️ Funcionalidade de Voz

Este jogo usa a biblioteca `responsiveVoice.js` para **falar as mensagens exibidas na tela**, tornando a experiência mais acessível e divertida.

---

## 🚀 Como executar localmente

1. Clone este repositório:
   ```bash
   git clone https://github.com/eduardoknoop/Code-NS.git

