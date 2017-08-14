Question�rio 2

1. Basicamente barramentos s�o conex�es e encaises que cada pe�a precisa para funcionar de maneira correta. Ent�o pelo barrament de dados � o modo como ocorre 
a troca de dados, tanto para enviar da CPU para a mem�ria quanto o contr�rio. J� o barramento de endere�os indica o local para onde os dados devem ser enviados ou 
recebidos.

2. Na mem�ria RAM � permitido a leitura e escrita dos dados, mas se a fonte de energia for desligada ou resetada essa mem�ria de dados ser� perdida
J� na mem�ria ROM os dados s� podem ser gravados uma �nica vez, sendo ent�o que s� � poss�vel acess�-la, e n�o apagar ou editar a informa��o. 
No entanto, o dado armazenado na ROM n�o ser� apagado ao simplesmente que seja cessada a fonte de energia.

3.(a) Na RAM, pois se toda vez que o programa fosse executado haveria a possibilidade de serem sempre reservados novos espa�os na mem�ria, e caso fosse armazenado 
na ROM, uma hora haveria uma sobrecarga, pois esses dados n�o seriam apagados com o desligamento do computador. Ao passo que se for na RAM, como de fato �, 
o espa�o de memoria bem como seu conte�do ser� atualizado conforme o usu�rio o fizer.
(b) J� o programa ser� armazenado na ROM, pois uma vez que foi compilado ser� criado um arquivo que ser� executado conforme o programador o fez e,
al�m disso, ele pode ser salvo, fazendo com que o armazenamento na RAM n�o fa�a sentido. Esse programa n�o ser� apagado caso o computador seja reiniciado, por exemplo.

4. Na arquitetura Harvard o caminho de dados e de instru��es s�o distintos, ent�o o caminho de dados � diferente, consequentemente seu processamento � mais r�pido:
O processador pode ler uma instru��o e ao mesmo tempo ter acesso � mem�ria de dados. Por�m, por ser um microcontrolador RISC, seu conjunto de instru��es � reduzido.
J� na arquitetura tipo Von Neumann, como o caminho de dados e de instru��es � o mesmo acaba que o desempenho de seu processamento cai, mas, por ser uma arquitetura 
mais simples, � muito comum encontrar tal arquitetura nos CPUs atuais.

5.(a) Little-Endian: 0xCD em 0x0200
		     0xAB em 0x0201
	     	     0x51 em 0x0202
		     0x80 em 0x0203
  (b) Big-Endian: 0x80 em 0x0200
		  0x51 em 0x0201
		  0xAB em 0x0202
		  0xCD em 0x0203

6. Dividindo cada n�mero bin�rio em duas partes de 16 bits, ou seja, ser�o necess�rios 4 registradores para armazenar os dois n�meros de 32 bits. Ent�o, seguindo a
formata��o Little-endian, � somado bit a bit, a partir do menos significativo.
