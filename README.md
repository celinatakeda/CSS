# Flexbox em CSS

Foi projetado como um modelo de layout unidimensional e como um método que pode oferecer distribuição de espaço entre itens em uma 
interface e recursos de alinhamento. 

## Propriedades 
. display

. flex-direction

	É a propriedade que estabelece o eixo principal do container, definindo assim a direção que os flex items são colocados 
	no flex container. 

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
	. wrap-reverse: permite a quebra de linha assim que um dos flex itens não puder mais ser compactado, porém na direção 
	contrária da linha, acima. 


. flex-flow

	É um atalho para as propriedades flex-direction e flex-wrap. 

	Porém seu uso não é tão comum, visto que, quando mudamos o flex-direction para column, mantemos o padrão do 
	flex-wrap que é nowrap. 


. justify-content

	Essa propriedade vai se encarregar de alinhar os itens dentro do container de acordo com a direção pretendida e tratar 
	da distribuição de espaçamento entre eles. 
	OBS: caso seus itens esteja ocupando 100% de todo o container, ela não se aplica

. align-items

	Trata do alinhamento dos flex itens de acordo com o eixo do container. 
	O alinhamento é diferente para quando os itens estão em colunas ou linhas. 
	Permite o alinhamento central no eixo vertical.

	Tipos de alinhamento 
	● center: alinhamento dos itens ao centro 
	● stretch: padrão, e os flex itens cresçam igualmente 
	● flex-start: alinhamento dos itens no início 
	● flex-end: alinhamento dos itens no final 
	● baseline: alinhamento de acordo com a linha base da tipografia dos itens

. align-content

	É a propriedade responsável por tratar o alinhamento das linhas do container em relação ao eixo vertical do container. 

	Tipos de alinhamento 
	● center: alinhamento dos itens ao centro 
	● stretch: é o padrão e os flex itens crescem igualmente 
	● flex-start: alinhamento dos itens no início 
	● flex-end: alinhamento dos itens no final 
	● space-between: cria um espaçamento igual entre os elementos 
	● space-around: os espaçamentos do meio são duas vezes maiores que o inicial e final

. flex-grow

	Define a proporcionalidade de crescimentos dos itens, respeitando o tamanho de seus conteúdos internos. 
	
	OBS: não irá funcionar caso tenhamos adicionado justify-content ao nosso flex container

. flex-basis

	É a propriedade que estabelece o tamanho inicial do item antes das distribuição de espaço restante dentro
	dele, usando como base o conteúdo interno disposto.

	Valores possíveis
	. auto: caso o item não tenha tamanho, este será proporcional ao conteúdo do item.
	. px, %, em, ...: são valores exatos previamente definidos
	. 0 (zero): terá relação com a definição do flex-grow

. flex-shrink

	É a propriedade que estabelecer a capacidade de redução ou compressão do tamanho de um item.

. flex 

	Esta propriedade é um atalho ou abreviação de escrita para as propriedades: grow, shrink e basis.

. order
	Propriedade para fazer a ordenação dos items 

. align-self

	É a propriedade que estabelece o alinhamento de modo individual sobre um determinado item.

	Valores possíveis 
	● auto: valor padrão, irá respeitar a definição de align-items do container 
	● flex-start: ao início do container 
	● flex-end: ao final do container 
	● center: relativo ao centro de acordo com o eixo 
	● stretch: ocupa todo os espaço relativo 
	● baseline: utiliza a linha base da tipografia


