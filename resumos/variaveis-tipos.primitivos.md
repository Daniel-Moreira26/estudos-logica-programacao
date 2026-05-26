# 🧠 Resumo: Variáveis e Tipos de Primitivos

Na lógica de programação, uma **variável** é como uma gaveta ou uma caixa na memória do computador onde guardamos uma informação que vamos precisar usar mais tarde no nosso programa.

## 📥 Tipos de Dados no VisuAlg (Portugol)

No VisuAlg, precisamos avisar o computador que tipo de informação vai entrar em cada gaveta. Os 4 tipos principais são:

* **INTEIRO:** Números inteiros, positivos ou negativos, sem casas decimais. (Ex: Idade, quantidade de produtos).
  * *Exemplo:* `idade: inteiro`
* **REAL:** Números com casas decimais (ponto flutuante). 
  * *Exemplo:* `salario: real` (Ex: 1500.50)
* **CARACTERE:** Textos, letras, palavras ou símbolos. Sempre ficam entre aspas double (`""`).
  * *Exemplo:* `nome: caractere` (Ex: "Felipe")
* **LOGICO:** Aceita apenas dois valores: `VERDADEIRO` ou `FALSO`. Muito usado para testes e condições.
  * *Exemplo:* `estaChovendo: logico`

## 💻 Estrutura Básica de um Algoritmo

```portugol
algoritmo "exemplo_variaveis"
var
   // Aqui é onde criamos as "gavetas"
   nome: caractere
   idade: inteiro
inicio
   // Aqui o programa acontece (Entrada, Processamento, Saída)
   nome <- "Felipe"
   idade <- 25
   
   escreval("Olá, meu nome é ", nome, " e eu tenho ", idade, " anos.")
fimalgoritmo
