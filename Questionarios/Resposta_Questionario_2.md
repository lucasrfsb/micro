Questionário 2

1. Basicamente barramentos são conexões e encaises que cada peça precisa para funcionar de maneira correta. Então pelo barrament de dados é o modo como ocorre 
a troca de dados, tanto para enviar da CPU para a memória quanto o contrário. Já o barramento de endereços indica o local para onde os dados devem ser enviados ou 
recebidos.

2. Na memória RAM é permitido a leitura e escrita dos dados, mas se a fonte de energia for desligada ou resetada essa memória de dados será perdida
Já na memória ROM os dados só podem ser gravados uma única vez, sendo então que só é possível acessá-la, e não apagar ou editar a informação. 
No entanto, o dado armazenado na ROM não será apagado ao simplesmente que seja cessada a fonte de energia.

3.(a) Na RAM, pois se toda vez que o programa fosse executado haveria a possibilidade de serem sempre reservados novos espaços na memória, e caso fosse armazenado 
na ROM, uma hora haveria uma sobrecarga, pois esses dados não seriam apagados com o desligamento do computador. Ao passo que se for na RAM, como de fato é, 
o espaço de memoria bem como seu conteúdo será atualizado conforme o usuário o fizer.
(b) Já o programa será armazenado na ROM, pois uma vez que foi compilado será criado um arquivo que será executado conforme o programador o fez e,
além disso, ele pode ser salvo, fazendo com que o armazenamento na RAM não faça sentido. Esse programa não será apagado caso o computador seja reiniciado, por exemplo.

4. Na arquitetura Harvard o caminho de dados e de instruções são distintos, então o caminho de dados é diferente, consequentemente seu processamento é mais rápido:
O processador pode ler uma instrução e ao mesmo tempo ter acesso à memória de dados. Porém, por ser um microcontrolador RISC, seu conjunto de instruções é reduzido.
Já na arquitetura tipo Von Neumann, como o caminho de dados e de instruções é o mesmo acaba que o desempenho de seu processamento cai, mas, por ser uma arquitetura 
mais simples, é muito comum encontrar tal arquitetura nos CPUs atuais.

5.(a) Little-Endian: 0xCD em 0x0200
		     0xAB em 0x0201
	     	     0x51 em 0x0202
		     0x80 em 0x0203
  (b) Big-Endian: 0x80 em 0x0200
		  0x51 em 0x0201
		  0xAB em 0x0202
		  0xCD em 0x0203

6. Dividindo cada número binário em duas partes de 16 bits, ou seja, serão necessários 4 registradores para armazenar os dois números de 32 bits. Então, seguindo a
formatação Little-endian, é somado bit a bit, a partir do menos significativo.
