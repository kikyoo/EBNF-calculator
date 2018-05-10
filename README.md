# EBNF-calculator

*    EBNF
  <exp>     -> <term> { <addop> <term> }
  <addop>   -> +|-
  <term>    -> <factor> { <mulop> <factor> }
  mulop     -> *
  <factor>  -> ( <exp> )| Number


*    测试示例
  (1+2)*3+1
  Result = 10
