Introdução a Algoritmos
O Que é um Algoritmo?
Um algoritmo é um conjunto finito e ordenado de passos que, quando executados, resolvem um determinado problema. É importante não confundir "algoritmo" com "número", embora ambas as palavras tenham a mesma origem etimológica.

Algoritmos no Dia a Dia
Algoritmos não são conceitos abstratos ou restritos à computação. Eles estão presentes em diversas situações cotidianas:

Tecnologia: Acesso a sites, e-mails, redes sociais, compras online, reprodução de vídeos, jogos, smartphones e TVs interativas dependem de algoritmos.
Veículos: Carros autônomos que estacionam ou freiam sozinhos utilizam algoritmos.
Natureza e Arte: A Proporção Áurea (
ϕ
ϕ) é um exemplo de padrão matemático que pode ser considerado um tipo de algoritmo natural e artístico.
Definição Formal
Segundo Manzano, em seu livro "Algoritmos, Lógica de Programação de Computadores": "Algoritmos são sequências finitas e ordenadas de passos que, quando executados, resolvem um determinado problema."

Rotinas e Algoritmos
Toda solução surge da necessidade de resolver um problema. A relação entre problemas e soluções pode ser vista como a criação de "rotinas". Um algoritmo é essencialmente uma rotina bem organizada para solucionar um problema específico.

Exemplos de Algoritmos no Cotidiano
Atravessar a Rua
Um algoritmo simples para atravessar a rua:

Chegar à rua.
Olhar para a direita.
Olhar para a esquerda.
Condição: Se um carro estiver vindo, não atravesse. Caso contrário, atravesse.
Uma variação deste algoritmo:

Chegar à rua.
Olhar para a esquerda.
Olhar para a direita.
Condição: Se um carro não estiver vindo, atravesse. Caso contrário, não atravesse.
Ambas as sequências de passos, embora ligeiramente diferentes na ordem e na condição, representam um algoritmo válido para a tarefa de atravessar a rua de forma segura. A ordem dos passos é crucial para a eficácia do algoritmo. Uma ordem incorreta, como tentar atravessar antes de olhar, não constituiria um algoritmo funcional para a segurança.

Outras Rotinas Diárias
Fazer uma ligação telefônica.
Preparar um bolo.
Realizar um saque em um caixa eletrônico.
Cancelar um plano de TV a cabo (considerado um algoritmo complexo e difícil pelo autor).
Algoritmos e Computadores
Programas de Computador
Um programa de computador é desenvolvido para atender a necessidades específicas, ou seja, para resolver problemas através de algoritmos.

Exemplo: Equações Quadráticas
Um problema comum que pode ser resolvido por um algoritmo é a solução de equações quadráticas. A fórmula geral de uma equação quadrática é:
a
x
2
+
b
x
+
c
=
0
ax 
2
 +
bx+
c=
0

Para resolver essa equação, utilizamos a fórmula de Bhaskara, que envolve o cálculo do discriminante (Delta):
Δ
=
b
2
−
4
a
c
Δ=
b 
2
 −
4ac

E as raízes da equação são dadas por:
x
=
−
b
±
Δ
2
a
x=
2a
−b± 
Δ
​
 
​
 

Um algoritmo computacional para resolver equações quadráticas seguiria estes passos:

Entrada: Receber os valores dos coeficientes 
a
a, 
b
b e 
c
c.
Cálculo do Delta: Calcular o valor de 
Δ
Δ usando a fórmula 
Δ
=
b
2
−
4
a
c
Δ=b 
2
 −4ac.
Análise do Delta:
Se 
Δ
>
0
Δ>0: Existem duas raízes reais distintas. Calcular 
x
1
=
−
b
+
Δ
2
a
x 
1
​
 = 
2a
−b+ 
Δ
​
 
​
  e 
x
2
=
−
b
−
Δ
2
a
x 
2
​
 = 
2a
−b− 
Δ
​
 
​
 .
Se 
Δ
=
0
Δ=0: Existe uma raiz real (ou duas raízes reais iguais). Calcular 
x
=
−
b
2
a
x= 
2a
−b
​
 .
Se 
Δ
<
0
Δ<0: Não existem raízes reais. As raízes são imaginárias.
Saída: Apresentar as raízes encontradas ou a mensagem indicando a ausência de raízes reais.
Exemplo de Execução:

Entrada: 
a
=
2
a=2, 
b
=
5
b=5, 
c
=
2
c=2
Cálculo do Delta: 
Δ
=
5
2
−
4
⋅
2
⋅
2
=
25
−
16
=
9
Δ=5 
2
 −4⋅2⋅2=25−16=9
Análise do Delta: Como 
Δ
=
9
>
0
Δ=9>0, existem duas raízes reais.
Cálculo das Raízes:
x
1
=
−
5
+
9
2
⋅
2
=
−
5
+
3
4
=
−
2
4
=
−
0.5
x 
1
​
 = 
2⋅2
−5+ 
9
​
 
​
 = 
4
−5+3
​
 = 
4
−2
​
 =−0.5
x
2
=
−
5
−
9
2
⋅
2
=
−
5
−
3
4
=
−
8
4
=
−
2
x 
2
​
 = 
2⋅2
−5− 
9
​
 
​
 = 
4
−5−3
​
 = 
4
−8
​
 =−2
Saída: As raízes são 
−
0.5
−0.5 e 
−
2
−2.
Entrada: 
a
=
1
a=1, 
b
=
2
b=2, 
c
=
3
c=3
Cálculo do Delta: 
Δ
=
2
2
−
4
⋅
1
⋅
3
=
4
−
12
=
−
8
Δ=2 
2
 −4⋅1⋅3=4−12=−8
Análise do Delta: Como 
Δ
=
−
8
<
0
Δ=−8<0, não existem raízes reais.
Saída: Delta é negativo, então não há raízes reais.
Entrada: 
a
=
1
a=1, 
b
=
2
b=2, 
c
=
1
c=1
Cálculo do Delta: 
Δ
=
2
2
−
4
⋅
1
⋅
1
=
4
−
4
=
0
Δ=2 
2
 −4⋅1⋅1=4−4=0
Análise do Delta: Como 
Δ
=
0
Δ=0, existe uma raiz real (ou duas iguais).
Cálculo da Raiz: 
x
=
−
2
2
⋅
1
=
−
2
2
=
−
1
x= 
2⋅1
−2
​
 = 
2
−2
​
 =−1
Saída: A raiz é 
−
1
−1.
Objetivos do Estudo de Algoritmos
Desenvolver o raciocínio lógico.
Organizar instruções de forma sequencial e coerente.
Preparar-se para construir aplicações computacionais.
O estudo de algoritmos é um processo gradual, começando com rotinas simples e progredindo para problemas mais complexos.
