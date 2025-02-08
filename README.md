# Low Level Informatic

## Description
This repos contain some of my try in logic schema. 
Learn and explore this fundamental aspect of informatics realy help me for understand and optimize some of algo and problem.

8 bits ALU : 
![ALU](/Models/ALU/alu.jpg)
OP Code map for alu :

0000 NO
0001 HALT
0010 ADD 
0011 SUB
0100 MUL
0101 DIV
0110 AND
0111 OR
1000 XOR


Or an old version of my first try CPU : 
![oldCpu](/Models/Olds/CPUV1.png)

Assembly instruction :

000 add
001 load
010 sous
011 ==
100 &&
101 ||
110 Jump
111 Jump_if


Structure d'input : 

3 bit pour l'instruction
3 bit pour le registre de sortie
4 bit pour le registre/valeur a mettre 	dans input 1 de l'alu (3 si on met une addresse de registre et 4 si c'est un nombre par exemple avec load on a le droit au 4 bit)

3 bit pour l'addresse du registre a mettre dans l'input 2 de l'ALU

Flag : 
Zero : 1
Overflow : 2