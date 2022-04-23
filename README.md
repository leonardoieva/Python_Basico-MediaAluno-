print ("Média Semestral do Cursinho de Inglês")

aluno = (input("Nome do(a) Aluno(a): "))
at1 = (int(input("Atividade Escrita 1: ")))
at2 = (int(input("Atividade Escrita 2: ")))
at3 = (int(input("Atividade Oral: ")))
at4 = (int(input("Apresentação Expositiva: ")))
at5 = (int(input("Preparação Avaliativa: ")))
at6 = (int(input("Avaliação Semestral: ")))
at7 = (int(input("Atividade Complementar: ")))

media = int((at1+at2+at3+at4+at5+at6+at7)/7)

print ("A média final de",(aluno),"é",(media),".")

if (media>=6):
    print ("Aluno Aprovado")
else:
    print ("Aluno Reprovado")
