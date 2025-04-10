This is a really simple functional programming language app to help pupils understand how we apply composite functions
The BNF for this very simple language is here:

<apply>   = <combine> <number>
<combine> = <function> | <combine> <function>
<function> = double | square | triple | succ | pred
<number>   = <digit>  | <number><digit>
<digit>    = 0 | 1 | 2 | 3 | 4 | 5 | 6 | 7 | 8 | 9
