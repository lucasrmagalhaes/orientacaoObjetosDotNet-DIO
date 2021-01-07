<h1 align="left">O que são métodos</h1>

<h3 align="center">Métodos e tipos de métodos</h3>

<hr>

<h4 align="left">Parte 1: Métodos</h4>

<p align="left">
  &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Os métodos determinam o comportamento dos objetos de uma classe e são capazes de controlar o estado da instância. São funções que realizam tarefas. Eles podem ou não retorna valores, e podem ou não receber parâmetros.<br>
  &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;O envio de mensagens (chamada de métodos) pode alterar o estado de um objeto. Esses métodos temos como difundidos os Getters, os Setters e o Construct.
</p>

<hr>

<h4 align="left">Parte 2: Tipos de Métodos</h4>

<p align="center">
  &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Métodos Acessores
</p>

<p align="left">
  &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Os <strong>Getters</strong> ou <strong>métodos acessores</strong> solicitam o acesso a informações de um determinado produto sem dar acesso diretamente a ele, colocando ali uma barreira de proteção para os dados.
</p>

<p align="center">
  &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Métodos Modificadores
</p>

<p align="left">
  &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Os <strong>Setters</strong> ou <strong>métodos modificadores</strong> enviam o pedido de alteração de uma determinada informação de um objeto sem que altere diretamente o mesmo.<br>

</p>

``
public int Codigo
{
  get { return codigo; }
  set { codigo = value; }
}
``


