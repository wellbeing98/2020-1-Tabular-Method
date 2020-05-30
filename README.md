# 2020-1-Tabular-Method
Tabular-MethodTabular method 구현
구현 내용
Prime Implicant Table 작성기능 구현 
Finding EPI ->  table reduction 구현 
Finding column and row dominance -> table reduction 구현 
Patrick’s method -> Finding an optimal cover 구현 
Input variable 개수 n=4를 기본으로 하며, n을 4보다 크게 구현



1 : find all  pls to construct a PI table
2 : find EPIs to simplify the table
  no nepis remained -> quit
3 : Apply column dominance raw
4 : Apply row dominance raw 
5 : Any simplication made from (3) and (4)
  yes- go to (2)
  no - move on to the next slide to learn Petrick's method
  Petrick's method = check minterm 하고 그중에 둘중에 고르는 형식이라면( p1 + p2 )이런 식으로 묶는다.
      
