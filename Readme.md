def lernotas():
    n= float(input('Digite uma nota para o aluno: '))
    return n

def resultado (n1,n2,n3):
    media=(n1+n2+n3)/3
    print('Nota 1: ',n1)
    print('Nota 2: ',n2)
    print('Nota 3: ',n3)
    print('Média: ', media, 'Resultado: ', end='')
    if media >= 7:
        print('Aprovado')
    else:
        print('Reprovado')

a = lernotas()
b = lernotas()
c = lernotas()
resultado(a,b,c)
