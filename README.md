# desafio-colaborativo-git

Este projeto foi criado para praticar conceitos básicos de Git e GitHub,
como branches, commits, Issues e Pull Requests. E aprender comando gits que faça tarefas mais básicas. É apresentado como exemplo um código sobre um quiz em python sobre o Brasil para treinar os conceitos básicos da atividade entre git e github.
Objetivos futuros: 
Adicionar novas funcionalidades ao projeto; criar uma interface; melhorar a organização e documentação do projeto; exemplos práticos de utilização; novas ferramentas e novas tecnologias.

Exemplo de código:
print("====== Quiz sobre o Brasil ======")

pontos = 0

print("Questão 1")
print("Qual é a capital do Brasil?")

print("A) São Paulo") 
print("B) Rio de Janeiro")
print("C) Brasília")
print("D) Salvador")

resposta= input("Digite a sua resposta aqui: ")

if resposta == "C":
    print("Correto!")
    pontos +=1

    else:
        print("Incorreto! A resposta é Brasília.")


print("Quantos estados o Brasil possui?")

print("A) 24")
print("B) 26")
print("C) 27")
print("D) 28")

resposta= input("Digite a sua resposta aqui: ")

if resposta == "B":
    print("Correto!")

    pontos += 1

    else:
        print("Incorreto! A resposta é 26.")


    print("Qual é o maior estado brasileiro em extensão territorial?")
    
    print("A)Amazonas")
    print("B)Pará")
    print("C)Mato Grosso")
    print("D)Bahia")

    resposta= input("Digite a sua resposta aqui: ")

    if resposta == "A":
        print("Correto!")

    pontos += 1

    else:

        print("Incorreto! A resposta é Amazonas.")


    print("Qual é o maior rio do Brasil em volume de água?")

    print("A) Rio São Francisco")
    print("B) Rio Paraná")
    print("C) Rio Amazonas")
    print("D) Rio Tocantins")

    resposta= input("Digite sua resposta aqui: ")

    if resposta == "C":
        print("Correto!")

    pontos += 1

    else:

        print("Incorreto! A resposta é Rio Amazonas.")


        print("Qual é a língua oficial do Brasil?")

        print("A) Espanhol")
        print("B) Português")
        print("C) Inglês")
        print("Francês")

        resposta= input("Digite a sua resposta aqui: ")


        if resposta == "B":

            print("Correto!")

            pontos += 1


            else:

                print("Incorreto! A resposta é Português.")

        

print("Resultado")

print("Você acertou", pontos, "de 5 questões")


if pontos == 5:
    print("Parabéns! Você acertou todas!")

elif pontos >= 3:
    print("Muito bem! Você teve um bom resultado.")

else:

    print("Continue estudando e tente novamente!")


    O que estou aprendendo:

    C — fundamentos de programação e lógica.
Python — programação e desenvolvimento de pequenos projetos.
HTML — estruturação de páginas web.
CSS — estilização e organização visual de páginas.
JavaScript — conceitos de programação para aplicações web.
Engenharia de Prompt — criação e aprimoramento de prompts para inteligência artificial.
Git e GitHub — versionamento de código, branches, commits, Issues e Pull Requests.
Lógica de programação — estruturas condicionais, loops, funções, vetores e matrizes.

