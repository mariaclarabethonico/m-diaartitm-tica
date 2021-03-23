# m-diaartitm-tica
{
	
	funcao inicio()
	{
		real Janeiro,Fevereiro,Marco,Abril,total,media
		cadeia vendedor
		
		escreva("Digite o nome do Vendedor:")
		leia(vendedor)
		escreva("Digite o valor da venda de Janeiro: ")
		leia(Janeiro)
		escreva("Digite o valor da venda de Fevereiro: ")
		leia(Fevereiro)
		escreva("Digite o valor da venda de Marco: ")
		leia(Marco)
		escreva("Digite o valor da venda de Abril: ")
		leia(Abril)

		total = (Janeiro+Fevereiro+Marco+Abril)

		media = (Janeiro+Fevereiro+Marco+Abril)/4

		escreva("O vendedor: " + vendedor + " obteve o total de vendas: " + total + " a média de vendas:" + media) 
	}

