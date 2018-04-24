# Excel-Sheet-Column-Number

    A -> 1
    B -> 2
    C -> 3
    ...
    Z -> 26
    AA -> 27
    AB -> 28
    
    如题。

给的参数是string,首先计算string的长度。在for循环中，s[i]-'A'+1为该次应加的数，并且要加上上一次计算的数*26（高位）
