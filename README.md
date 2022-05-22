# Proçesso seletivo

## Introdução
Seja bem vindo ao processo seletivo da ACDG. 
Nessa parte do processo você irá resolver 6 desafios no tempo que conseguir. 
Quando terminar mande ou mande o link de um repositorio com todos os desafios 
completos, ou mande a pasta com os codigos e os execultaveis
caso exista, para o email: gaderaldo10@gmail.com. Com o assunto: PROCESSO SELETIVO - ACDG 

## Desafios

- DESAFIO 01: 

        Implemente uma função que converta o valor booleano fornecido em sua representação de string.
        Nota: Somente entradas válidas serão fornecidas.


    | Parâmetro   | Tipo       | Descrição                           |
    | :---------- | :--------- | :---------------------------------- |
    | `string_entrada` | `Bool` | Essa será a string que será convertida para um bool |

   #### Retorno da função

    ```http
        Retornará tipo string com o valor correspondente da entrada boleana. 
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

  dado uma entrada 

  | Parâmetro   | Tipo       | Descrição                           |
  | :---------- | :--------- | :---------------------------------- |
  | `numero_de_balas` | `int` | Numero de balas que o heroi irá carregar |
  | `numero_de_dragões` | `int` | Numero de dragões que o heroi irá derrotar |

  
    
   #### Retorno da função
    O retorno será em strig, informando o numero de balas que restou, a quantidade de dragões que foram abatidos e se ele irá sobreviver.
    
- DESAFIO 04:
  Breno está no primeiro semestre de computação, 
e ele está aflito se irá conseguir passar na materia de algoritimos.
 Então ele decidiu fazer uma pequena função que irá calcular suas notas e dizer se ele 
 foi aprovado ou não, e se ele precisará fazer a terceira prova, já que em sua universidaden 
 se um aluno tiver uma media aritimetica das duas primeiras notas maior que 8, 
 ele não precisa fazer a terceira prova. Breno então foi na coordenação do curso e pegou 
 os criterios de aprovação para todos os casos. Ajude o Breno a fazer uma função que receba 
 como parametro de entrada um vetor com as 2 notas de 0…10 e saia uma string dizendo se ele foi 
 aprovado ou não, e caso ele vá para a prova final, qual a nota que ele precisará para poder ser 
 aprovado na materia.

  dado uma entrada 

  | Parâmetro   | Tipo       | Descrição                           |
  | :---------- | :--------- | :---------------------------------- |
  | `notas_obtidas` | `[int]` | esse vetor contem as duas primeiras notas do aluno |

  Criterios de aprovação do aluno fornecidos pela coordenação

  | legenda de nomeclatura das provas | Descrição |
  |----------|:-------------:|
  | AV1  | primeira prova realizada pelo aluno | 
  | AV2 | segunda prova realizada pelo aluno  |
  | AF |  prova final, realizada caso o aluno não atinja a media precisa na AV1 e AV2 |  


  | Descrição do criterio de aprovação | resultado |
  |----------|:-------------:|
  | (AV1 + AV2) / 2 >= 8 | passou sem final| 
  | (AV1 + AV2) / 2 >= 4 & <= 7.9 | irá para final  |
  | [(AV1 + AV2) + AF]/ 2 >= 5 |  Aluno aprovado |
  | (AV1 + AV2) / 2 < 4  |  Aluno reprovado |
  | [(AV1 + AV2) + AF]/ 2 < 5  |  Aluno reprovado |  
  

  Exemplos de calculos de medias:
  
  EX1:

      AV1: NOTA - 8
      AV2: NOTA - 4
      AF: 6

      media regular: (8 + 4) / 2 => 6 

      resultado -> a nota do aluno na media da primeira prova mais a segunda deu 6 então
      ele terá que realizar a prova final.

      media final: (media regular + AF) / 2

      resultado de aprovação: nota 6 - Passou na materia.

  EX2:
  
      AV1: NOTA - 8
      AV2: NOTA - 10
      AF: -

      media regular: (8 + 10) / 2 => 9

      resultado -> a nota do aluno na media da primeira prova mais a segunda deu 9, 
      então o aluno não precisará realizar a prova final. APROVADO DIRETAMENTE.

  EX3:
  
      AV1: NOTA - 4
      AV2: NOTA - 4
      AF: 4

      media regular: (4 + 4) / 2 => 4 

      resultado -> a nota do aluno na media da primeira prova mais a segunda deu 4 então
      ele terá que realizar a prova final.

      media final: (media regular + AF) / 2

      resultado de aprovação: nota 4 - Infelismente o aluno reprovou na materia.
  
  EX4:
  
      AV1: NOTA - 2
      AV2: NOTA - 4
      AF: -

      media regular: (2 + 4) / 2 =>  3 

      resultado -> Infelismente o aluno reprovou na materia.

   #### Retorno da função
    O retorno esperado é uma string.

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



