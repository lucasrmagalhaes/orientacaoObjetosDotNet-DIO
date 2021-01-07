<h1 align="left">
  Entenda os diferentes tipos por valor, referência e ponteiro
</h1>

<hr>

<h4 align="left">Objetivos da Aula</h4>

<ol>
  <li>Tipos por valor</li>
  <li>Tipos por referência</li>
  <li>Tipos ponteiro</li>
</ol>

<hr>

<h4 align="left">Parte 1: Tipos por Valor</h4>

<p align="left">
  &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;O C# tem duas grandes categorias de tipos: por valor e por referência. Os tipos por valor são gerenciados diretamente e têm as seguintes características principais:
</p>

<ul>
  <li>Todos os tipos de dados numéricos.</li>
  <li>Não precisam ser inicializados com o operador new.</li>
  <li>A variável armazena o valor diretamente.</li>
  <li>A atribuição de uma variável a outra copia o conteúdo, criando efetivamente outra cópia da variável.</li>
  <li>Não podem conter o valor null.</li>
  <li>Exemplos de variáveis desse tipo são: integers, doubles, floats e char.</li>
</ul>

<h4 align="left">Inteiros</h4>

<p align="left">
  &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Os tipos inteiros (Integers) têm sempre o mesmo significado, independentemente da implementação.
</p>

<table>
    <tr>
        <th>Tipo</th>
        <th>Implementação</th>
    </tr>
    <tr>
        <th>byte</th>
        <td>Inteiro de 8 bits sem sinal (0 a 255).</td>
    </tr>
    <tr>
        <th>sbyte</th>
        <td>Inteiro de 8 bits com sinal (-127 a 128).</td>
    </tr>
    <tr>
        <th>ushort</th>
        <td>Inteiro de 16 bits sem sinal (0 a 65 535).</td>
    </tr>
    <tr>
        <th>short</th>
        <td>Inteiro de 16 bits com sinal (-32 768 a 32 767)</td>
    </tr>
    <tr>
        <th>uint</th>
        <td>Inteiro de 32 bits sem sinal (0 a 4 294 967 295).</td>
    </tr>
        <tr>
        <th>int</th>
        <td>Inteiro de 32 bits com sinal (-2 147 483 648 a 2 147 483 647).</td>
    </tr>
        <tr>
        <th>ulong</th>
        <td>Inteiro de 64 bits sem sinal (0 a 18 446 744 073 709 551615).</td>
    </tr>
        <tr>
        <th>long</th>
        <td>Inteiro de 64 bits com sinal (-9 223 372 036 854 775 808 a 9 223 372 036).</td>
    </tr>
</table>

<h4 align="left">Double e Float</h4>

<p align="left">
  &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Os números de ponto flutuante são bastante convencionais, as operações de ponto flutuante não geram erros.
</p>

<table>
    <tr>
        <th>Tipo</th>
        <th>Implementação</th>
    </tr>
    <tr>
        <td>double</td>
        <td>Ponto flutuante binário IEEE de 8 bytes, 15 dígitos decimais de precisão.</td>
    </tr>
    <tr>
        <td>float</td>
        <td>Ponto flutuante binário LEEE de 4 bytes, 7 dígitos decimais de precisão.</td>
    </tr>
</table>

<h4 align="left">Caracteres</h4>

<p align="left">
  &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Em C#, todos os caractes (char) são armazenados no padrão Unicode e usam 16 bits por caractere. O Unicode permite armazenar os caracteres de todas as línguas vivas (como grego, japonês, chinês e coreano) e algumas mortas (como sânscrito).
</p>

<table>
    <tr>
        <th>Tipo</th>
        <th>Implementação</th>
    </tr>
    <tr>
        <td>char</td>
        <td>Um único caractere Unicode de 16 bits. Não é compatível com inteiro.</td>
    </tr>
</table>

<hr>

<h4 align="left">Parte 2: Tipos por Referência</h4>

<p align="left">
  &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Um tipo por referência armazena uma referência a seus dados. Os tipos de referência incluente o seguinte:
</p>

<ul>
  <li>Duas variáveis podem conter a referência a uma mesmo objeto.</li>
  <li>Operações em uma variável, podem afetar uma outra variável.</li>
  <li>Todas as matrizes, mesmo que seus elementos sejam de tipos de valor.</li>
  <li>Exemplos de tipos por referência: Strings, classes e arrays.</li>
</ul>

<h4 align="left">Strings</h4>

<p align="left">
  &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Semelhante ao char, strings são variáveis do tipo texto. São uma sequência de caracteres, geralmente utilizada para representar palavras, frases ou textos de um programa.
</p>

<table>
    <tr>
        <th>Tipo</th>
        <th>Implementação</th>
    </tr>
    <tr>
        <td>string</td>
        <td>String Unicode com até 1 giga caracteres.</td>
    </tr>
</table>

<p align="left">
  &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;As strings são consideradas imutáveis e não podem ser alteradas depois de criadas. Quando você efetua uma operação qualquer, como por exemplo, concatenar um caractere, você na verdade está criando outra string e descartando a anterior.
</p>

<h4 align="left">Classes</h4>

<p align="left">
  &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Como visto anteriormente é um tipo definido pelo usuário e correspondem a uma class. As classes são sempre derivadas de object e podem conter campos, métodos e propriedades. Uma classe pode derivar de uma única outra classe, e também de várias interfaces.
</p>

<h4 align="left">Arrays</h4>

<p align="left">
  &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Um array (matriz) é uma lista de valores onde todos os valores no grupo são referenciados pelo nome da matriz e o índice atribuído ao valor específico na matriz.
</p>

<hr>

<h4 align="left">Parte 3: Tipo Ponteiro</h4>

<p align="left">
  &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Um <strong>ponteiro</strong> ou <strong>apontador</strong> é um tipo de dado de cujo valor se refere diretamente um outro valor alocado em outra área da memória, através de seu endereço.
</p>