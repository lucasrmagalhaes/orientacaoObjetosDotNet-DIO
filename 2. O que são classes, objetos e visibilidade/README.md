<h1 align="left">
  O que são classes, objetos e visibilidade
</h1>

<h3 align="center">Principais conceitos de classes, objetos e visibilidade</h3>

<hr>

<h4 align="left">Objetivos da Aula</h4>

<ol>
  <li>Classes</li>
  <li>Objetos</li>
  <li>Visibilidade</li>
</ol>

<hr>

<h4 align="left">Parte 1: O que são Classes?</h4>

<p align="left">
  &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Pode ser considerado como se fosse um molde para o objeto, contendo dentro de si as principais informações para a sua criação. Define os atributos e métodos comuns que serão compartilhados por um objeto.
</p>

<hr>

<h4 align="left">Parte 2: O que são Objetos?</h4>

<p align="left">
  &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Considera-se um objeto tudo aquilo que em geral possui atributos, comportamentos e um estado. A classe em si é um conceito abstrato, como um molde, que se torna concreto e palpável através da criação de um objeto.<br>
  &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Na programação o objeto é uma instanciação (criação a partir) de uma classe. Para criarmos ou "instanciarmos" objetos de uma determinada classe, utilizamos o operador new.
</p>

<hr>

<h4 align="left">Parte 3: O que é Visibilidade?</h4>

<p align="left">
  &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;A visibilidade é importante para a proteção do código e suas funcionalidades, define quem pode alterar cada dado dos trechos de código em três principais níveis:
</p>

<ul>
  <li>Pública (representada pelo símbolo "+");</li>
  <li>Privada (representada pelo símbolo "-"); e</li>
  <li>Protegida (representa pelo símbolo "#").</li>
</ul>

<p align="left">
  &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;De forma completa se encontram os modificadores:
</p>

<table>
    <tr>
        <th>Modificador</th>
        <td>Significado</td>
    </tr>
    <tr>
        <th>public</th>
        <td>Sem limitação de acesso.</td>
    </tr>
    <tr>
        <th>protected internal</th>
        <td>Acesso limitado à própria classe, às classes derivadas e ao próprio assembly.</td>
    </tr>
    <tr>
        <th>protected</th>
        <td>Acesso limitado à própria classe, às classes derivadas.</td>
    </tr>
    <tr>
        <th>internal</th>
        <td>Acesso limitado ao próprio assembly.</td>
    </tr>
    <tr>
        <th>private</th>
        <td>Acesso limitado à própria classe.</td>
    </tr>
</table>

<p align="left">
  &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Esse encapsulamento de atributos e métodos impede o chamado vazamento de escopo, onde um atributo ou método é visível por alguém que não deveria vê-lo, como outro objeto ou classe.<br>
  &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Isso evita a confusão do uso de variáveis globais no programa, deixando mais fácil de identificar em qual estado cada variável vai estar a cada momento do programa, já que a restrição de acesso nos permite identificar quem consegue modificá-la.
</p>