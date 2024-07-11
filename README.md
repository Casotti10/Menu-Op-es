val1 = int(input('Digite um valor: '))
val2 = int(input('Digite outro valor: ')) 

opcao = 0
while opcao != 5:
    print('''    [1] somar
    [2] multiplicar
    [3] maior
    [4] novos números 
    [5] sair do programa''') 
    opcao = int(input(('Qual é a sua opcão?: '))) 
    if opcao == 1:
        soma = val1 + val2 
        print(f'O resultado da soma de {val1} e {val2} é  {soma}')
    elif opcao == 2:
        multiplicar = val1 * val2 
        print(f'O Resultado da multiplicação de {val1} e {val2} é {multiplicar}')
    elif opcao == 3:
        if val1 > val2:
            maior = val1
        else:
            maior = val2
        print(f'O maior valor entre {val1} e {val2} é {maior}')
    elif opcao == 4:
        print('Informe os números novamente')
        val1 = int(input('Digite um valor: ')) 
        val2 = int(input('Digite outro valor: ')) 
    elif opcao == 5: 
        print('Programa finalizado :)'
    else:
        print('Opção inválida. Tente novamente')
print('Fim do programa')

    


