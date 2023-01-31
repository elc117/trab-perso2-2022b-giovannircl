# *Funções de alta ordem - Scala*

Link do repositório no replit: https://replit.com/@GiovanniCacioli/Trabalho-individual-02-Paradigmas#main.scala

### - Como visto em aula, as **funções de alta ordem** são aquelas que:

  - Contém outras funções como parâmetro;
  - Retorna uma função como saída;
  - No geral, funções que operam com outras funções.

### - Na linguagem Scala, as linguagens de alta ordem funcionam quase da mesma forma que em Haskell, porém a **sintaxe** é diferente, exemplo: 

  - **Haskell**:
<br />`hasFever :: [Float] -> [Float]`
<br />`hasFever x = filter isFever x`
             
  - **Scala**: 
<br />`def hasFever(x: List[Double]): List[Double] = x.filter(isFever)`

Enquanto em Haskell é preciso declarar o nome da função novamente para implementá-la, em Scala é só chamar as devidas funções de alta ordem a partir da variável que foi definida no argumento da função.

### - Funções de alta ordem da linguagem Scala:

  - Map
  - Filter
  - Reduce
  - Fold

### - Comparação Haskell/Scala:

  - Em Haskell é mais fácil de testar as funções já que quando rodamos o programa podemos testá-las na hora, digitando. Em Scala, as funções precisam ser  chamadas printando o resultado ou devem printar o resultado dentro das próprias funções.
  - Assim como Haskell, Scala é uma linguagem relativamente simples para entender e aplicar o paradigma de programação funcional.
  - Scala suporta tanto programação funcional quanto POO. Enquanto no Haskell é mais difícil aplicar qualquer outro paradigma que não seja o funcional.
  - A lógica para desenvolver os exercícios é bem semelhante em ambas as linguagens, bem como a manipulação de listas/variáveis. 

### - Curiosidades!

![](https://media.tenor.com/KW2w_CzRAQUAAAAC/curiosity-push-button.gif)

  - Scala foi lançada em 2003 (Tem a minha idade).
  - Twitter, Linkedin e Netflix estão entre as grandes empresas que utilizam Scala para lidar com a grande quantia de dados.
  - Scala possui uma biblioteca com muitas ferramentas para a programação funcional, incluindo coleções imutáveis, expressões lambda e operações de redução.

### - Referências:

  - https://docs.scala-lang.org/tour/higher-order-functions.html
  - https://www.baeldung.com/scala/higher-order-functions
  - https://www.scala-exercises.org/scala_tutorial/higher_order_functions
