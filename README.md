4-Bit Equality Comparator  

Overview  
This circuit compares two 4-bit binary inputs, A[3:0] and B[3:0], and checks if they are equal.  

Working  
- Inputs: Two 4-bit numbers A (A3 A2 A1 A0) and B (B3 B2 B1 B0).  
- The comparator checks each corresponding bit.  
- If all bits match, the output (Equal = 1).  
- If any bit differs, the output (Equal = 0).  

Logic Expression  
Equal = (A3 XNOR B3) AND (A2 XNOR B2) AND (A1 XNOR B1) AND (A0 XNOR B0)  

Truth Table (Example)  
A (binary)   B (binary)   Equal  
1010         1010         1  
1101         1011         0  
0000         1111         0  
0110         0110         1  

Applications  
- Digital identity checks  
- Address matching in memory systems  
- Control logic in processors  
