# box_sizing
essa aula vamos ver sobre o box-sizing que é o responsável pelo calculo do tamanho total da caixa (box).

Podemos usar a ferramenta de desenvolvedor do próprio navegador para visualizar as especificações dos elementos da página

 é por isso que é tão importante conhecer a propriedade do box-sizing.

Por padrão o navegador vai calcular o tamanho da caixa pelo content-box e vai somar com os outros boxes, no exemplo acima no lugar de 100px a caixa vai ficar com uma largura de 140px. Para que isso não aconteça, é possível mudar qual vai ser a referência para o calculo do tamanho da caixa adicionando a propriedade box-sizing: border-box;.

Dessa forma o elemento vai ficar com a largura (width) determinado, que no caso do exemplo citado é de 100px.
o calculo da box e feita pelo content box ou seja pelo conteudo que esta na caixa

# display block vs display inline

Como as caixas se comportam em relação as outras caixas
Comportamento externo das caixas

* Display Block
Ocupa toda a linha, colocando o próximo elemento abaixo desse

* Display Inline
Os elementos ficam ao lado do outro e não empurram outros elementos para baixo



