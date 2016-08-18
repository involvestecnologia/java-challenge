Bem vindo ao Desafio Java
===================

Primeiramente gostar�amos de agradecer pelo interesse em fazer parte do nosso time.

O pr�ximo passo do nosso processo seletivo � o chamado  **Desafio Java **. O  **Desafio Java ** nada mais � do que um pequeno teste que realizamos com os candidatos para que tenham a oportunidade de mostrar um pouco de suas habilidades. Nesse teste buscamos avaliar a clareza do c�digo, estrutura de classes e grau de cumprimento dos requisitos funcionais e n�o funcionais.

Bom, vamos logo ao que interessa.


# O Desafio

O desafio consiste em criar uma biblioteca que fa�a o parsing de **POJOs** comuns em arquivos **JSON** (Javascript object notation). 

## Requisitos

Abaixo seguem os requisitos da biblioteca a ser desenvolvida:

 -  **RF 1 **:  Dever� ser poss�vel enviar um POJO simples e transform�-lo em um JSON. Devem ser aceitos POJOs que contenham atributos simples (tipos primitivos) ou complexos (outros objetos), incluindo arrays e listas.
 -  **RF 2 **: Dever� ser poss�vel enviar uma lista de POJO simples e transform�-la em um JSON, conforme instru��es do RF1.
 -  **RF 3 **: A transforma��o em JSON dever� enviar o resultado para um *java.io.Outputstream* que dever� ser criado pelo usu�rio da biblioteca e enviado sob a forma de par�metro.
 -  **Requisitos N�o Funcionais** (para dar mais emo��o):
	 - Os procedimentos da biblioteca devem ser logados utilizando o mecanismo de Log do Java.
	 - S� � permitido utilizar classes do pr�prio SDK do Java ou classes criadas pelo candidato, ou seja, fica vedado o uso de outros frameworks e bibliotecas.
	 - A estrutura da biblioteca dever� ser flex�vel a ponto de permitir o f�cil desenvolvimento de futuros formatos de exporta��o, como XML e CSV.
	 - A biblioteca dever� ser desenvolvida no idioma ingl�s (m�todos, atributos, classes, etc).
	 - Dever� ser criada uma classe de testes utilizando JUnit a qual deve executar testes para verificar o correto funcionamento da biblioteca.
	 - Dever� ser criado o diagrama de classes com a vis�o geral da biblioteca.
 - **Desej�vel**:  Se poss�vel, utilizar a vers�o free do TravisCI para realizar os testes de unidade de forma automatizada

## Entrega

O c�digo da biblioteca, diagrama de classes e classe de testes e link do Travis devem ser enviados para o GitHub do candidato e o link dever� ser enviado para a Involves atrav�s do e-mail talentos@involves.com.br com t�tulo **[sele��o java � nome do candidato]** at� o prazo enviado no email com esse desafio.