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
