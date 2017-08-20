1.
	(a) mov.w #0,R4;
	(b) add.w #1,R5;
	(c) sub.w #1,R6;
	(d) add.w #2,R7;
	(e) sub.w #2,R8;

2. 
	(a) clr.w R4;
	(b) inc.w R5;
	(c) dec.w R6;
	(d) incd.w R7;
	(e) decd.w R8;

3.
	(a) add.w R4,R4;

	(b) mov.w R5, R11;
	    add.w R5,R5;
	    add.w R5, R11;

	(c) add.w R6,R6; 
	    add.w R6,R6;

	(d) mov.w 2(R9),R11;
	    mov.w 0(R9),R12;
	    add.w R11, R12;
	    mov.w R12, 4(R9);

	(e) mov.w R4, R11;
	    mov.w R6, R12;
	    add.w R11, R11;
	    mov.w R11, R13;
	    add.w R12, R12;
	    add.w R12, R12;
            mov.w R12, R14;
	    sub.w R14, R13;
	    mov.w R13; 6(R9);

	(f) mov.w R6, R11;
	    add.w R11, R11;
	    sub.w R11, R4;
	    add.w R4, R4;
	    mov.w R4, 6(R9);
	
	    

