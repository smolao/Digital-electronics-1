####De Morgan's laws simulation

```vhdl
architecture dataflow of gates is
begin
    f_o  <= ((not b_i) and a_i) or ((not c_i) and (not b_i));
    fnand_o <= a_i;
    fnor_o <= a_i and b_i;

end architecture dataflow;
```

![Simulace De Morgan's laws](Images/demorgansim.png)

https://www.edaplayground.com/x/cpVT

| **c** | **b** |**a** | **f(c,b,a)** |
| :-: | :-: | :-: | :-: |
| 0 | 0 | 0 | 1 |  
| 0 | 0 | 1 | 2 |   
| 0 | 1 | 0 | 2 |   
| 0 | 1 | 1 | 3 |  
| 1 | 0 | 0 | 4 |   
| 1 | 0 | 1 | 5 |   
| 1 | 1 | 0 | 6 |    
| 1 | 1 | 1 | 9 |  