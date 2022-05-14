# Operadores Relacionais

- são símbolos especiais quais são capazes de realizar comparações entre determinados operandos e, em seguida, retornar um resultado
- nem todo operandor relacional pode ser utilizado em qualquer operando
- nem todos os tipos de operandos podem ser comparados entre si

## Tipos

- similaridade = igual, diferente
  
  *igualdade (==)- determina se um operando é igual ao outro 
 
  *diferença (!=)- determina se um operando não é igual ao outro 
 
- tamanho = maior, maqior igual, menor, menor igual
 
 *maior (>) - determina se um operando é maior do que o outro
  
 *maior igual (>=) - determina se um operando é maior ou igual a outro
  
 *menor (<) - determina se um operando é menor do que o outro
  
 *menor igual (<=) - determina se um operando é menor ou igual a outro
   
* em operações relacionais sempre existirão pelo menos dois operandos

# Operadores Lógicos

- são símbolos especiais quais são capazes de realizar comparações lógicas entre operandos lógicos ou expressões e, em seguida, retornar um resultado
- não se pode aplicar operadores lógicos em cima de números, a menos que eles estejam dentro de expressões (mistura de variáveis e operadores)

## Tipos

- conjunção = operação lógica que só é verdadeira quando ambos os operandos ou expressões envolvidas são verdade 

* Simbologia &&

* Terminologia and(e)

- disjunção = operação que só é falsa quando ambos os operandos ou expressões envolvidas são falsos

* Simbologia ||

* Terminologia or(ou)

- disjunção exclusiva = operação que só é verdade quando ambos os operandos ou expressões são opostos

* Simbologia ^

* Terminologia xor

- negação = operação que inverte o valor lógico de um operando ou expressão

* Simbologia !

* Terminologia inversão

## Curiosidades

- operadores bitwise (mexe com bytes de num int, não é uma operação lógica) = & e |
- operadores shift = ~,>>,>>>,<<

## Boas práticas

- crie variáveis para guardar resultados intermediários 

# Controle de fluxo

- são estruturas que tem a capacidade de direcionar o fluxo de exexução do código

## Tipos

- decisão = if(se), if-else, if-else-if, switch(escolha) e operador ternário

* estrutura que avalia uma condição booleana (é uma expressão que resultam em um valor verdadeiro ou falso) ou variável para direcionar o fluxo de execução

- repetição = for, while, do while
- interrupção =  break, continue e return

## Boas práticas

- switch é para valores exatos e if para expressões booleanas
- evitar udar o default do switch para "cases genéricos"
- evitar o efeito "flecha" dos if's
- evitar muitos if's aninhados
- usar a boa prática da aula 2 para diminuir o tamanho if


# Blocos

- é um grupo de 0 ou mais códigos quais trabalham em conjunto para executar uma operação

## Tipos

- locais = dentro de métodos
{

...

}
- estáticos = dentro de classes
- instância = dentro de classes


