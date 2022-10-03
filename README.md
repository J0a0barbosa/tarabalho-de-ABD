User Stories
O usuário iniciar o questionário pressionando um botão, assim ele vê uma pergunta com 4 respostas possíveis, após selecionar uma resposta, 
É exibido a próxima pergunta para o usuário. Fazendo isso até que o quiz termine, ao final, o usuário pode ver as seguintes estatísticas
Tempo que levou para terminar o quiz, quantas respostas corretas ele obteve e uma mensagem mostrando se ele passou ou falhou no teste.

User Stories
O usuário pode compartilhar o resultado de um quiz nas redes sociais, respondendo a vários questionários do aplicativo. O usuário pode 
selecionar qual deles responder, também pode criar uma conta e ter todas as pontuações salvas em seu painel e ele pode completar um
questionário várias vezes.

User Stories
o quiz foi desenvolvido para testar os conhecimentos do usuário, respondendo ele além do usuário saber o nível do seu conhecimento, 
 ele pode aprender muito com o quiz também, e indo bem melhor no outro quiz e aumentando seu nível de conhecimento.  
 

código em Python.

print("Seja muito bem vindo ao quiz do Iury!")
answer_user = input("Quer começar? (S/N) ")

if answer_user != "S":
    quit()

score = 0

print("Começando...")
print("Quem desenvolveu o jogo Grand Theft Auto (GTA)? \n (A) Rockstar Games \n (B) Ubisoft \n (C) Activision \n (D) EA \n")
answer_1 = input("Resposta: ")

if answer_1 == "A":
    print("Correto!")
    score = score + 1
else:
    print("Incorreto!")

print("Qual o nome do protagonista do jogo GTA San Andreas?\n (A) Carlos John \n (B) Carl Jonhson \n (C) Carl Jaqueline \n (D) Carlos Jonhson \n")
answer_2 = input("Resposta: ")

if answer_2 == "B":
    print("Correto!")
    score = score + 1
else:
    print("Incorreto!")

print(f"Quiz acabou... Pontuação: {score}/2")



Diagrama:

![Captura de tela 2022-10-02 211846](https://user-images.githubusercontent.com/114430918/193482971-e2602eee-35c8-4309-96ae-087b6727abef.jpg)





