anatomia de um grid
—————————————————————————————————————————————————————————
grid conteiner (pai)
---------------------------------------------------------
grid item (filho)
---------------------------------------------------------
grid track (direção da linha)
row track (linha deitado)
column track (linha em pé)
---------------------------------------------------------
grid lines(
linha numerada da esquerda para direita e de cima para baixo (números positivos)
direita pra esquerda de baixo para cima (números negativos))
---------------------------------------------------------
grid area
---------------------------------------------------------
gap (espaço entre os itens)
---------------------------------------------------------
###### ######################
grid contêiner (pai de todos)
###### ######################

display: grid;
________________________________________________________
grid-template-columns: ;
________________________________________________________
grid-template-rows: ;
________________________________________________________
gap: ;
________________________________________________________
###### ##########
align-items =[vertical]
###### ##########
stretch (padrão/ ele vai esticar o item ate ele caber dentro da grade verticalmente)
---------------------------------------------------------
start (ele vai alinhar no início/cima da grade verticalmente)
---------------------------------------------------------
center (vai ficar no meio verticalmente na grade)
--------------------------------------------------------
end (vai alinhar na parte de baixo)
_________________________________________________________
###### ##########
justify-items =[horizontal]
###### ##########
stretch (ele vai esticar o item)
---------------------------------------------------------
start (ele vai alinhar a esquerda da grade horizontalmente)
--------------------------------------------------------
center (vai centralizar horizontalmente)
--------------------------------------------------------
end (ele vai alinhar a direita da grande horizontalmente)
_________________________________________________________
###### ##########
align-content =[vertical]
###### ##########

start (vai colar todo o conteúdo na parte de cima)
--------------------------------------------------------
center (vai centralizar)
end (vai colar o conteúdo na parte de baixo )
--------------------------------------------------------
space-between (vai colar o primeiro conteúdo na parte de cima e o último na parte de baixo)
--------------------------------------------------------
space-evenly (vai reposicionar os itens so que o espaço acima e abaixo entre os itens vai ser exatamente o mesmo)
--------------------------------------------------------
space-around (vai distribuir para que Acima e abaixo de cada elemento tenha o mesmo espaço so que o primeiro e o último vai estar mais perto da borda)
—————————————————————————————————————————————————————————
_________________________________________________________
###### ##########
justify-content =[horizontal]
###### ##########
stretch (padrão/normal)
--------------------------------------------------------
start (vai pegar todo o conteúdo e vai colar no lado esquerdo)
--------------------------------------------------------
center (vai centralizar)
--------------------------------------------------------
end (vai pegar todo o conteúdo e vai colar no lado direito)
--------------------------------------------------------
space-between (vai colar na esquerda e na direita)
space-evenly ( vai pagar todos os elementos e o espaço entre eles vai ser o mesmo)
--------------------------------------------------------
space-around (vai criar um espaço entre os elementos e todo os elementos terao o mesmo espaço, só que o último e o primeiro vai estar mais perto da borda)
—————————————————————————————————————————————————————————
_________________________________________________________
align (vertical/ cima pra baixo baixo pra cima)
--------------------------------------------------------
justify (horizontal esquerda pra direita direita pra esquerda)
_________________________________________________________
