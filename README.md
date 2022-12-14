# atividade-logica
questao 1
 inteiro A1, B2, C
		cadeia numero, posicao

		escreva("\nInforme vertor A1?"," ")
		leia(A1)
		escreva("\nInforme vertor B2?"," ")
		leia(B2)
		escreva("\nInforme vertor C"," ")
		leia(C)

	questao 2
  inteiro vetor[] = { 1, 2,3,4,5,6,7,8,9,10,11,12,13,14,15,16,17,18,19,20}  
		inteiro numero
		logico achou = falso  

		escreva ("Qual número deseja procurar? ")
		leia (numero)
    escreva("informe mais um numero")
    leia(numero)
    se(numero>1)
    escreva("o numero se repete 1 vez")

		para (inteiro repeticao = 1; repeticao < 1; repeticao++)
		{
			se (vetor[repeticao] == numero+1
			{
            
				escreva ("o numero se repete:" , repeticao,"\n")
    
				achou = verdadeiro  
			}
		}
		
		se (nao achou) 
		{
			escreva ("o numero se repete 1 vez""\n")
		}
	}
}


questao 4
inteiro vetor[] = { 1, 2, 3, 4, 5, 6, 7, 8, 9, 10, 11,12,13,14,15} 
		inteiro numero, V1,V2
		logico achou = falso  

		escreva ("Qual número deseja procurar? ")
		leia (numero)

		para (inteiro posicao = 0; posicao < 15; posicao++)
		{
			se (vetor[posicao] == numero)
			{
				escreva ("Encontrado na posição: ", posicao, "\n")
				achou = verdadeiro  
			}
		}
		
		se (nao achou) 
		{
			escreva ("O número não está no vetor\n")
		}
	}
}
/
 
}
