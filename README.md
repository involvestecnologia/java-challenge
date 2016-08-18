Bem vindo ao Desafio Java
===================

Primeiramente gostaríamos de agradecer pelo interesse em fazer parte do nosso time.

O próximo passo do nosso processo seletivo é o chamado  **Desafio Java**. O  **Desafio Java** nada mais é do que um pequeno teste que realizamos com os candidatos para que tenham a oportunidade de mostrar um pouco de suas habilidades. Nesse teste buscamos avaliar a clareza do código, estrutura de classes e grau de cumprimento dos requisitos funcionais e não funcionais.

Bom, vamos logo ao que interessa.


# O Desafio

O desafio consiste em criar uma biblioteca que faça o parsing de **POJOs** comuns em arquivos **JSON** (Javascript object notation). 

## Requisitos

Abaixo seguem os requisitos da biblioteca a ser desenvolvida:

 -  **RF 1**:  Deverá ser possível enviar um POJO simples e transformá-lo em um JSON. Devem ser aceitos POJOs que contenham atributos simples (tipos primitivos) ou complexos (outros objetos), incluindo arrays e listas.
 -  **RF 2**: Deverá ser possível enviar uma lista de POJO simples e transformá-la em um JSON, conforme instruções do RF1.
 -  **RF 3**: A transformação em JSON deverá enviar o resultado para um *java.io.Outputstream* que deverá ser criado pelo usuário da biblioteca e enviado sob a forma de parâmetro.
 -  **Requisitos Não Funcionais** (para dar mais emoção):
	 - Os procedimentos da biblioteca devem ser logados utilizando o mecanismo de Log do Java.
	 - Só é permitido utilizar classes do próprio SDK do Java ou classes criadas pelo candidato, ou seja, fica vedado o uso de outros frameworks e bibliotecas.
	 - A estrutura da biblioteca deverá ser flexível a ponto de permitir o fácil desenvolvimento de futuros formatos de exportação, como XML e CSV.
	 - A biblioteca deverá ser desenvolvida no idioma inglês (métodos, atributos, classes, etc).
	 - Deverá ser criada uma classe de testes utilizando JUnit a qual deve executar testes para verificar o correto funcionamento da biblioteca.
	 - Deverá ser criado o diagrama de classes com a visão geral da biblioteca.
 - **Desejável**:  Se possível, utilizar a versão free do TravisCI para realizar os testes de unidade de forma automatizada

## Entrega

O código da biblioteca, diagrama de classes e classe de testes e link do Travis devem ser enviados para o GitHub do candidato e o link deverá ser enviado para a Involves através do e-mail talentos@involves.com.br com título **[seleção java – nome do candidato]** até o prazo enviado no email com esse desafio.
