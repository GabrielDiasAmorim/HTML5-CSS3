#FLEXBOX 

#flex-conteiner/pai = display:flex;

##flex-direction:
<!--qual usar? basta saber como se lé para onde vocé esta criando o site-->
padrão: flex-diretion: row; em linha (da esquerda para direita)

flex-direition: row-reverse; em linha (da direita para esquerda)

flex-deretion: column; em pé (de cima para baixo)

flex-deretion: column-revese; em pé (de baixo para cima)

##eixos(axis)

eixo principal= main-axis: ele gera dois pontos o inicial e o final (main-start: ponto inicial) (main-end: ponto final)

eixo transversal= cross-axis: ele também gera dois pontos o inicial e o final 

<!--essa configuração é para quando usamos o flex:diretion: row;-->


<!--flex-diretion: row-reverse;-->
eixo principal= main-axis: (main-start (direita para esquerda))
eixo transversal= cross-axis: (main-end (cima para baixo))


<!--flex-diretion: column-->
eixo principal= main-axis: (main-start (cima para baixo))
eixo transversal= cross-axis: (main-end (esqueda para direita))



<!--flex-diretion: column-reverse-->
eixo principal= main-axis: (main-start (baixo para cima))
eixo transversal= cross-axis: (main-end (esquerda para direita))


##flex-wrap


padrão= flax-wrap:nowrap; (nao quebra)

flax-wrap: wrap; (quebra ele sempre no eixo cross-axis)

flax-wrap: wrap-reverse; (quebra so que no sentido oposto do eixo cross-axis)



##flex-flow: (shorthand) flex-direction + flex-wrap

flex-flow: row nowrap;