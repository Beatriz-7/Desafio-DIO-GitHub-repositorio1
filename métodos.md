# Métodos

- é uma porção de código (sub-rotina) que é disponibilizada por uma
classe.
- este é executado quando é feita uma requisição a ele. 
- são responsáveis por definir e realizar um determinado comportamento

- todo método deve ser criado dentro de uma classe
- não funciona sozinho, deve ser chamado
- são responsáveis por fazer as aplicações, fazer o software funcionar

## Padrão de definição 

?visibilidade?
?tipo?
?modificador?
retorno nome (?parâmetros?)
?exceções? = erros que podem ocorrer
corpo 

* o que está entre interrogações é obrigatório, os que não, são 
opcionais

'V = "public", "protected" ou "private"

T = concreto ou abstrato

M = "static" ou "final"

'R = tipo de dado (primitivos:int, long, byte, ...) ou "void" (vazio:vai executar, e ao final não retorna nada)

'N = nome fornceido ao método


'P = parâmetros que pode receber (entre ())

E = exceções que pode lançar

'C = código que possui ou vazio

public static R N(P) {...}

## Utilização

- passa-se uma mensagem através de uma classe ou objeto 

nome_da_classe.nome_do_metodo(); ou nome_da_classe.nome_do_metodo(...);
               ex:Math.random(); ou Math.sqrt(4);

nome_do_objeto.nome_do_metodo(); ou nome_do_objeto.nome_do_metodo(...);
         ex: usuario.getEmail(); ou usuario.alterarEndereco(endereco);

* classe possui primeira letra maiúscula e objeto possui primeira letra minúscula

## Particularidades

- Assinatura = forma de identificar unicamente o método
         Ass = nome + parâmetros

- Construtor e Destrutor = métodos especiais usados na orientação a 
objetos

- Mensagem = é o ato de solicitar ao método que o mesmo execute.Podendo ser direcionada a um objeto ou a uma classe

- Passagem de parâmetros
Por valor (cópia) 
Por referência (endereço)

### Boas práticas

- nomes devem ser descritivos, mas curtos
- notação camelo
- deve possuir entre 80 e 120 linhas
- evitar lista de parâmetros longas
- visibilidades adequadas

