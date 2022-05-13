# Proçesso seletivo

## Introdução
Seja bem vindo ao processo seletivo da ACDG. 
Nessa parte do processo você irá resolver 6 desafios no tempo que conseguir. 
Quando terminar mande ou mande o link de um repositorio com todos os desafios 
completos, ou mande a pasta com os codigos e os execultaveis
caso exista para o email: gaderaldo10@gmail.com. Com o assunto: PROCESSO SELETIVO - ACDG 

## Desafios

- DESAFIO 01: 

        Implemente uma função que converta o valor booleano fornecido em sua representação de string.
        Nota: Somente entradas válidas serão fornecidas.


    | Parâmetro   | Tipo       | Descrição                           |
    | :---------- | :--------- | :---------------------------------- |
    | `string_entrada` | `string` | Essa será a string que será convertida para um bool |

   #### Retorno da função

    ```http
      Retornará tipo boleano com o valor correspondente da entrada. 
    ```
        Exemplo:
        Entrada: false 
        Saida: "false"


- DESAFIO 02: 

      Dado uma entrada de uma string, inverta essa string.


    | Parâmetro   | Tipo       | Descrição                           |
    | :---------- | :--------- | :---------------------------------- |
    | `string_entrada` | `string` | Essa será a string que será invertida |

   #### Retorno da função
    ```http
      Retornará tipo string
    ```
      Exemplo:

        Entrada: 'world'
        Saida:   'dlrow'

        Entrada: 'word'
        Saida:   'drow'

- DESAFIO 03: 

Um herói está a caminho do castelo para completar sua missão. 
No entanto, ele foi informado de que o castelo está cercado por alguns dragões poderosos! cada dragão leva 2 balas para ser derrotado,
nosso herói não tem ideia de quantas balas ele deve carregar. Supondo que ele vai pegar um determinado número de balas e avançar para lutar contra
outro determinado número de dragões, ele sobreviverá?

   #### Retorno da função
    Retorna True se sim, False caso contrário
    
- DESAFIO 04:
  
OBS: Esse desafio é particulamente mais chato de realizar então não se acanhe se não conseguir.

A Terra Média está prestes a entrar em guerra. As forças do bem terão muitas batalhas com as forças do mal. Diferentes raças certamente estarão envolvidas.
Cada raça tem um certo valor ao lutar contra outras. Do lado do bem temos as seguintes raças, com o seu valor associado:

  Do lado do bom temos:
  | RAÇAS    |    Quantidades|
  |----------|:-------------:|
  | Hobbits  | 1             | 
  | Homens   | 2             |
  | Elfos    | 3             |  
  | Anões    | 3             |
  | Águias   | 4             |
  | Magos    | 10            |

  Do lado do mal temos:
  | RAÇAS    |    Quantidades|
  |----------|:-------------:|
  | Orcs     | 1             | 
  | Homens   | 2             |
  | Wargs    | 2             |  
  | Goblins  | 2             |
  | Uruk Hai | 3             |
  | Trolls   | 5             |
  | Magos    | 10            |

Embora o clima, a localização, os suprimentos e o valor desempenhem um papel em qualquer batalha, se você somar o valor do lado do bem e compará-lo com o valor do lado do mal,
o lado com o maior valor tenderá a vencer.

Assim, dada a contagem de cada uma das raças do lado do bem, seguida da contagem de cada uma das raças do lado do mal, determine qual lado vence.

Entrada:
    
    A função receberá dois parâmetros. Cada parâmetro será uma string de vários inteiros separados por um único espaço. Cada string conterá a contagem de cada raça do lado do bem e do mal.

    O primeiro parâmetro conterá a contagem de cada corrida do lado bom na seguinte ordem:

    Hobbits, Homens, Elfos, Anões, Águias, Magos.
    
    EXEMPLO: "2 10 10 2 4 6"

    O segundo parâmetro conterá a contagem de cada raça do lado do mal na seguinte ordem:

    Orcs, Homens, Wargs, Goblins, Uruk-Hai, Trolls, Magos.

    EXEMPLO: "1 10 10 2 4 6"

    Todos os valores são inteiros não negativos. A soma resultante do valor de cada lado não excederá o limite de um inteiro de 32 bits.

  ```
  func evaluate(good: String, evil: String) -> String {
    //seu codigo aqui... lembre que pode implementar na linguagem que desejar.
  }

  ```

  SAIDA:
    ```O retorno da função
      será tipo string
    ```
      
      Saida:  "Battle Result: Good triumphs over Evil" ***caso o lado bom vença***
      Saida:  "Battle Result: Evil eradicates all trace of Good", ***caso o lado mal vença***
      Saida:  "Battle Result: No victor on this battle field", ***caso haja empate***


- DESAFIO 04:
De acordo com os pseudos codigos diga o que se saira como desejado, caso o pseudo codigo esta errado informe por que está errado.

    soma(valor1,valor2):
        return valor1 - valor2
    
    Resultado:
        Entrada: soma(45,5)
        Saida: 50
        A saida está correta? : 
        Precisa mudar algo? : 
    
    soma(valor1,valor2):
        return valor1 + valor2

    Resultado:
        Entrada: soma(100,5)
        Saida: 105
        A saida está correta? : 
        Precisa mudar algo? : 
    
    multiplicacao(valor1,valor2):
        return valor1 * valor2
    
    Resultado:
        Entrada: multiplicacao(10,5)
        Saida: 50
        A saida está correta? : 
        Precisa mudar algo? : 

- DESAFIO 05:
Quinto desafio:
    
  Dado um conjunto de números, retorne o inverso aditivo de cada um. Cada positivo torna-se negativo, e os negativos tornam-se positivos.
    
  | Parâmetro   | Tipo       | Descrição                           |
  | :---------- | :--------- | :---------------------------------- |
  | `array_original` | `[int]` | Esse será o array que os valores serão invertidos |

    Exemplo:
    Entrada: [1,2,3,4,5] 
    Saida: [-1,-2,-3,-4,-5]

    
    Exemplo:
    Entrada: [1,-22,3,-4,5] 
    Saida: [-1,2,-3,4,-5]

- DESAFIO 06:


  Dado a entrada de dois vetores some cada valor de um com o valor do outro.
    
  | Parâmetro   | Tipo       | Descrição                           |
  | :---------- | :--------- | :---------------------------------- |
  | `primeiro_array` | `[int]` | Aqui é o primeiro array |
  | `segundo_array`  | `[int]` | Aqui é o segundo array  |

      SAIDA: Retorno da função será um array de inteiros

    Exemplo:
    
       Exemplo:
        Entrada: 
          primeiro_array = [1,2,3,4,5] 
          segundo_array =  [1,2,3,4,5] 
        
        Saida: [2,4,6,8,10]

    
    Exemplo:
        
        Entrada: 
          primeiro_array = [10,20,30,40,50] 
          segundo_array =  [1,2,3,4,5] 
        
        Saida: [11,22,34,44,55]



