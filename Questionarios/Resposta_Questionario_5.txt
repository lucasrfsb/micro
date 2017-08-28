1.      (a)mov.w #1, R11;
	   bis 	R5, R11;

	(b)mov.w #3, R12;
	   bis R6, R12;
	
	(c)mov.w #4, R13;
	   bic R7, R13;

	(d)mov.w #12, R14;
	   bic R8, R14;


2. cmp R7, R8 
   jl SUB;
	add.w #10,R6;
	add.w R6,R5;
	add.w R5, R4;
	jmp END;
   sub: sub.w #10,R6;
	sub.w R6, R5;
	sub.w R5, R4;
   END:

3. ROUND: mov.w R7, R11;
	rla R11;
	add.w R12, R11;
	cmp 0(R11),R9;
	jeq END;
	inc.w R7;
	jmp ROUD;
   END:

