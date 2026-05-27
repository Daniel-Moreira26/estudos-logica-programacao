# 📥 Entrada de Dados e Interatividade

Na programação, a **Entrada de Dados** é o mecanismo que permite ao usuário interagir com o programa. Em vez de o algoritmo trabalhar apenas com valores fixos definidos no código, ele passa a receber informações de fora (digitadas pelo teclado, por exemplo) em tempo de execução.

---

## 📌 O Comando `leia` no VisuAlg

No VisuAlg, o comando responsável por capturar o que o usuário digita e armazenar dentro de uma variável é o **`leia()`**.

### ⚙️ Como funciona o fluxo?
1. O computador executa o comando `leia(nome_da_variavel)`.
2. O programa **pausa** a execução e fica esperando o usuário digitar algo.
3. O usuário digita o valor e aperta a tecla `Enter`.
4. O programa pega esse valor, guarda dentro da variável correspondente e continua executando as próximas linhas.

---

## 💡 Boa Prática: O "Par Perfeito" (`escreva` + `leia`)

Nunca coloque um comando `leia` solto no código sem antes explicar para o usuário o que ele deve fazer. Se você colocar apenas `leia(idade)`, a tela vai ficar preta com o cursor piscando e o usuário não vai saber o que o programa está esperando.

Sempre use um comando de saída (`escreva` ou `escreval`) antes de um comando de entrada.

### ❌ Forma Ruim (Tela confusa):
```pascal
leia(n1)
