**Python - Básico**
===
#### print() 
- É uma função para chamar e imprimir valores e mensagens no terminal ou na saída padrão.

#### Variáveis
- Para criar uma variável, basta escolher um nome para ela e atribuir um valor usando o sinal de igual (=).
    ex:
     
        x = 4  # cria a variável x e atribui o valor 4 a ela
        y = "Olá, mundo!"  # cria a variável y e atribui a string "Olá, mundo!" a ela

#### Tipos de dados
- Suporta vários tipos de dados como números inteiros (int), números de ponto flutuante (float), strings (str) e booleanos (bool).
    ex: 
    
        x = 4  # inteiro
        y = 3.14  # ponto flutuante
        z = "Olá, mundo!"  # string
        w = True  # booleano

#### Operadores
- Matemáticos e lógicos. Alguns exemplos são o operador de adição (+), o operador de subtração (-), o operador de multiplicação (*) e o operador de divisão (/). Também há operadores de comparação, como o operador de igualdade (==) e o operador de diferença (!=).
    ex:
    
        x = 4 + 2  # x é 6
        y = 4 - 2  # y é 2
        z = 4 * 2  # z é 8
        w = 4 / 2  # w é 2.0
        a = 4 == 2  # a é False
        b = 4 != 2  # b é True

#### Condicionais
- Algumas dessas estruturas são o if (se), o for (para) e o while (enquanto). 
    ex:
    
        # if (se)
        if x > 0:
          print("x é positivo")
        elif x < 0:
          print("x é negativo")
        else:
          print("x é zero")
        
        # for (para)
        for i in range(5):
          print(i)  # imprime 0, 1, 2, 3, 4
        
        # while (enquanto)
        i = 0
        while i < 5:
          print(i)  # imprime 0, 1, 2, 3, 4
          i += 1

#### Funções
- Elas permitem que você divida o código em pedaços menores e mais fáceis de gerenciar, além de permitir que você reutilize o código.
    ex: 
    
        def nome_da_funcao(argumentos):
          # código da função
          return resultado

- Função que calcula o fatorial de um número:

    ex:

        def fatorial(n):
          if n == 0:
            return 1
          else:
            return n * fatorial(n - 1)
        
        print(fatorial(5))  # imprime 120 (5! = 5 * 4 * 3 * 2 * 1)
    
- Além disso, as funções em Python podem ter argumentos padrão e argumentos opcionais. 
    ex: 
        
        def greet(name, greeting="Olá"):
          print(f"{greeting}, {name}!")
        
        greet("João")  # imprime "Olá, João!"
        greet("Maria", "Oi")  # imprime "Oi, Maria!"
