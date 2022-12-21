# JavaScript

---

#### Buscando um elemento:

- document.getElementById('')
- document.getElementByClassName('')
- document.querySelector('./#')
- document.querySelectorAll('./#')

  ##### Diferença de "querySelector" e "querySelectorAll"

  - O querySelector retorna o primeiro elemento dentro do documento e querySelectorAll retorna uma lista de elementos presentes no documento.

---

#### Operadores de atribuição

###### Um operador de atribuição atribui um valor ao operando à sua esquerda baseado no valor do operando à direita. O operador de atribuição básica é o igual (=), que atribui o valor do operando à direita ao operando à esquerda. Isto é, x = y atribui o valor de y a x.

<table>
  <tr>
    <th>Operadores</th>
    <th>Operador encurtado</th>
  </tr>
  <tr>
    <td>Atribuição</td>
    <td>x = y</td>
  </tr>
  <tr>
    <td>Atribuição de adição</td>
    <td>x += y</td>
  </tr>
  <tr>
    <td>Atribuição de subtração</td>
    <td>x -= y</td>
  </tr>
  <tr>
    <td>Atribuição de multiplicação</td>
    <td>x *= y</td>
  </tr>
  <tr>
    <td>Atribuição de divisão</td>
    <td>x /= y</td>
  </tr>
  <tr>
    <td>Atribuição de resto</td>
    <td>x %= y</td>
  </tr>
</table>

---

#### Operadores aritiméticos

###### Operadores aritméticos tomam valores numéricos como seus operandos e retornam um único valor numérico. Os operadores aritméticos padrão são os de soma (+), subtração (-), multiplicação (\*) e divisão (/). Estes operadores trabalham da mesma forma como na maioria das linguagens de programação quando utilizados com números

<table>
  <tr>
    <th>Operador</th>
  </tr>
  <tr>
    <td>Incremento (++)</td>
  </tr>
  <tr>
    <td>Decremento (--)</td>
  </tr>
  <tr>
    <td>Negação (-)</td>
  </tr>
  <tr>
    <td>Adição (+)</td>
  </tr>
  <tr>
    <td>Exponência (**)</td>
  </tr>
</table>

---

#### Operadores de comparação

###### Um operador de comparação compara seus operandos e retorna um valor lógico baseado em se a comparação é verdadeira. Na maioria dos casos, se dois operandos não são do mesmo tipo, o JavaScript tenta convertê-los para um tipo apropriado. Isto geralmente resulta na realização de uma comparação numérica.

<table>
  <tr>
    <th>Operador</th>
    <th>Descrição</th>
  </tr>
  <tr>
    <td>Igual (==)</td>
    <td>Retorna "true" caso os operandos sejam iguais</td>
  </tr>
  <tr>
    <td>Não igual (!=)</td>
    <td>Retorna "true" caso os operandos não sejam iguais</td>
  </tr>
  <tr>
    <td>Estritamente igual (===)</td>
    <td>Retorna "true" caso os operandos sejam iguais e do mesmo tipo</td>
  </tr>
  <tr>
    <td>Estritamente não igual (!==)</td>
    <td>Retorna "true" caso os operandos não sejam iguais e do mesmo tipo</td>
  </tr>
  <tr>
    <td>Maior que (>)</td>
    <td>Retorna "true" caso o operando da esquerda seja maior que o da direita</td>
  </tr>
  <tr>
    <td>Maior ou igual que (>=)</td>
    <td>Retorna "true" caso o operando da esquerda seja maior ou igual que o da direita</td>
  </tr>
  <tr>
    <td>Menor que (<)</td>
    <td>Retorna "true" caso o operando da esquerda seja menor que o da direita</td>
  </tr>
  <tr>
    <td>Menor ou igual que (<=)</td>
    <td>Retorna "true" caso o operando da esquerda seja menor ou igual que o da direita</td>
  </tr>
</table>
 
 ---
 ### Condicionais

##### If

- As estruturas condicionais são utilizadas para verificar uma condição e definir se algo deve
  ou não acontecer.

#### Else

- Caso você queira executar algo quando a condição for falsa, utilizamos o else (se não). O else sempre será executado caso o if seja falso.

#### Else If

- O else if (se não se) nos ajuda a fazer mais do que uma condição, ou seja se a condição anterior não for verdadeira verifique uma nova condição.

---

### Consumindo API com axios

#### O que é API?

- API, ou Application Programming Interface, é um conjunto de definições e protocolos para integrar softwares de aplicações. Um exemplo clássico de API é a do Google Maps. Por meio de seu código, conseguimos ter acesso a localização, muitas outras aplicações utilizam os dados do Google Maps adaptando-o da melhor forma.

#### O que é Axios?

- Axios é uma biblioteca JavaScript baseada em promessas (promises) para interceptar requisições (requests) HTTP. Esses interceptadores são úteis quando queremos pegar ou alterar requisições HTTP. Cada requisição HTTPpode usar um dos métodos de requisição existente, temos sete tipos de requisição, mas nesse ebook iremos abordar somente o método GET para consultar os dados em uma API.

#### Axios é a unica solução?

- Não! Não precisamos do Axios para consumir uma API, temos nativamente no JavaScript o fetch(). Ele é perfeitamente capaz de reproduzir as principais funcionalidades do Axios! Mas o Axios é uma biblioteca que traz bastante benefícios quando estamos trabalhando com APIs.
