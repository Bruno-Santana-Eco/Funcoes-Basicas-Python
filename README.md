# Funções básicas - **Python**
---
## Descrição

Bom para meu primeiro portfólio irei começar com as funções básicas de python e a resolução de alguns problemas. Descrever bem cada comando do Python em uma apresentação é importante porque ajuda a garantir que a compreensão do que está acontecendo em cada etapa do seu código e por que você está tomando determinadas decisões. Ajudando a criar um contexto claro para o código que está apresentando, permitindo seguir a lógica do meu raciocínio e entender como cheguei a cada solução. Além disso, uma boa descrição ajuda a garantir não ficar confuso ou perdido durante a apresentação, permitindo a concentração em fornecer informações mais avançadas e insights mais valiosos. Por fim, descrever bem cada comando do Python em uma apresentação é uma tentativa de demonstrar habilidades de comunicação de forma clara e eficaz. Inicialmente irei fazer um breve resumo de cada capítulo dentro do código para facilitar a procura 

## 1) Tipo de entradas e saída de dados
  Em Python, as variáveis podem ser de vários tipos diferentes. Abaixo estão os principais tipos de variáveis em Python:

* Inteiros (int): variáveis inteiras que representam números inteiros, positivos ou negativos, sem decimais. Exemplo: x = 3

* Floats (float): variáveis que representam números com casas decimais. Exemplo: x = 3.5

* Booleanos (bool): variáveis que representam um valor verdadeiro ou falso (True ou False). Exemplo: x = True

* Strings (str): variáveis que representam uma sequência de caracteres. Exemplo: x = "Hello World"

* Listas (list): variáveis que representam uma coleção ordenada de itens. Exemplo: x = [1, 2, 3]

* Tuplas (tuple): variáveis que representam uma coleção ordenada e imutável de itens. Exemplo: x = (1, 2, 3)

* Dicionários (dict): variáveis que representam uma coleção de pares chave-valor, onde cada chave é única. Exemplo: x = {"nome": "João", "idade": 30}

Com esses tipos de variáveis, é possível armazenar diferentes tipos de dados e executar operações específicas em cada um deles. Saber identificar e entender cada tipo de variável em Python é fundamental para a escrita de um código correto e eficiente.


## 2) Operadores Aritméticos

Os operadores aritméticos em Python são utilizados para realizar operações matemáticas básicas, como adição, subtração, multiplicação e divisão. A seguir, são descritos os principais operadores aritméticos em Python:

* Adição (+): utilizado para somar valores.
* Subtração (-): utilizado para subtrair valores.
* Multiplicação (*): utilizado para multiplicar valores.
* Divisão (/): utilizado para dividir valores. Retorna um número de ponto flutuante.
* Divisão inteira (//): retorna o resultado da divisão com o resultado inteiro, sem arredondamento.
* Resto da divisão (%): retorna o resto da divisão.
* Potenciação (__**__): utilizado para elevar um número à potência de outro número

## 3) Strings

Variáveis do tipo string armazenam cadeias de caracteres como nomes e textos em geral. Chamamos cadeia de caracteres uma sequência de símbolos como letras, números, sinais de pontuação etc. É definida entre aspas simples ('Digite aqui seu texto') ou aspas duplas ("Digite aqui seu texto"). As strings são imutáveis, o que significa que não podem ser alteradas após a criação. No entanto, é possível criar uma nova string a partir de uma string existente. Outra característica importante da strings é o fatiamento, que consiste em apresentar somente o que queremos dentro de uma string

## 4) Condições

Quando se é necessário tomar decisões com situações diferentes e se os problemas podem ser resolvidos com expressões lógicas podemos usar as condições.

As condições consistem no uso de uma estrutura de decisão, a primeira estrutura de decisão se chama **'if'** nada mais é que o famoso 'se', 'se' a condição for verdadeira será executado o código. Usarei exemplos para definir melhor essa função. Da mesma maneira e tentando resolver problemas de situações distintas quando o **'if'** não é atendido (situação verdadeira) tem a possibilidade de outra estrutura de decisão chamada **'else'**, comumente chamada de 'senão', ou seja, 'senão' for atendida a condição 'se' será executado o código descrito na condição **'else'** (situação falsa). Perceba que situação verdadeira e falsa é meramente instruções lógicas para atender problemas, caso uma situação lógica não for atendida a outra será colocada em prática. Em python é possível colocar mais de uma condição usando a instrução **'elif'**, isso permite solucionar diversos problemas.

## 5) Repetições

A repetição **"for"** em Python é uma estrutura de controle que permite que um bloco de código seja executado várias vezes em uma sequência de valores. Há outra estrutura de repetição chamada **"while"** é utilizada em Python para executar um bloco de código repetidamente enquanto uma determinada condição for verdadeira.
Geralmente é usado **"for"** quando o programador sabe a quantidade exata de repetições e **"while"** quando quer repetir indefinidamente até uma determinada condição.

## 6) Tuplas

Em Python, uma tupla é um tipo de sequência imutável, ou seja, uma coleção de objetos que não pode ser modificada após a criação. É definida utilizando parênteses ( ) e os elementos são separados por vírgulas.

Uma tupla pode conter elementos de diferentes tipos de dados, como inteiros, strings, floats, booleanos, listas, dicionários e até mesmo outras tuplas. As tuplas são indexadas e podem ser acessadas de maneira semelhante às listas, utilizando colchetes e o índice correspondente.

As tuplas são úteis em situações em que é necessário armazenar um conjunto de valores que não deve ser modificado, como por exemplo para representar coordenadas x e y de um ponto em um plano cartesiano ou uma data com dia, mês e ano. Além disso, as tuplas são mais eficientes que as listas em termos de processamento e armazenamento, uma vez que ocupam menos espaço na memória e são mais rápidas para serem percorridas.

## 7) Listas

Em Python, listas são uma coleção de elementos ordenados e mutáveis. Elas podem armazenar uma sequência de objetos, incluindo outros tipos de dados como inteiros, floats, strings, tuplas e até outras listas. As listas são definidas usando colchetes [ ] e os elementos são separados por vírgulas.

## 8) Dicionários

Em Python, um dicionário é uma estrutura de dados que mapeia um conjunto de chaves a seus respectivos valores. É uma coleção não ordenada, mutável e indexada. As chaves devem ser únicas e imutáveis (como strings, números ou tuplas) e os valores podem ser de qualquer tipo de dado.

Um dicionário é definido utilizando chaves { } e os pares chave-valor separados por dois pontos :

## 9) Funções

Funções em Python são blocos de código nomeados que executam uma determinada tarefa. Elas são definidas com a palavra-chave "def", seguida pelo nome da função e seus parâmetros entre parênteses.
Diferente do que já vimos, as linhas não serão executadas imediatamente, ela executa somente quando a função é chamada em outra parte do programa.
Funções são especialmente interessantes para isolar uma tarefa específica em um trecho de programa. Isso permite que a solução de um problema seja reutilizada em outras partes do programa, sem precisar repetir as mesmas linhas. 

