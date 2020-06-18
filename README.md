# 2_Pass_Assembler
C implemetation of 2 Pass Assembler to convert assembly level code into machine level language.

Assembly level code can contain one of the following instructions:
1. MOV 2. ADD 3. SUB 4. MUL 5. CMP 6. AND 7. OR 8. NOT 9. JMP 10. LOOP 11. HLT 12. JNZ 

The input to the program is an assembly language program written using instructions from the above set only. The C program converts this input to a machine-level code. The conversion is done with
two passes:
- In the first pass, the assembler generates Symbol Table and Machine-Opcode Table.
- The second pass of the assembler uses the tables generated in the first pass and generates the final machine level code
