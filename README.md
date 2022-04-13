# Evoluindo no CSS

Foi projetado como um modelo de layout unidimensional e como um método que pode oferecer distribuição de espaço entre itens em uma 
interface e recursos de alinhamento. 

## Propriedades 
. display

. flex-direction
	 É a propriedade que estabelece o eixo principal do container, definindo assim a direção que os flex items são colocados no flex container. 

	 Os eixos

	. row( padrão ): à direção do texto, esquerda para direita 
	. row-reverse: sentido oposto à direção do texto
	. column: ordenação de cima para baixo, em coluna unica
	. column-reverse: ordenação inversa, de baixo para cima 

. flex-wrap
	É a propriedade que define se os itens devem ou não quebrar a linha. 

	Por padrão eles não quebram linhas, isso faz com que os flex itens sejam compactados além do limite do conteúdo.
	
	. nowrap: é o padrão, não permite a quebra de linha. 
	. wrap: permite a quebra de linha assim que um dos flex itens não puder mais ser compactado.	
	. wrap-reverse: permite a quebra de linha assim que um dos flex itens não puder mais ser compactado, porém na direção contrária da linha, acima. 


. flex-flow
	É um atalho para as propriedades flex-direction e flex-wrap. 

	Porém seu uso não é tão comum, visto que, quando mudamos o flex-direction para column, mantemos o padrão do flex-wrap que é nowrap. 


. justify-content
	Essa propriedade vai se encarregar de alinhar os itens dentro do container de acordo com a direção pretendida e tratar da distribuição 
	de espaçamento entre eles. 
	OBS: caso seus itens esteja ocupando 100% de todo o container, ela não se aplica

. align-items

. align-content

. flex-grow

. flex-basis

. flex-shrink

. flex

. order

. align-self


