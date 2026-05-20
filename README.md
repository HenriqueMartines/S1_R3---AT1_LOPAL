# Explicando os exercicios

## Exercicio 1

<img width="279" height="125" alt="image" src="https://github.com/user-attachments/assets/78c9673f-114d-4e3b-8d5e-4bed5333047b" />


for numero in range(0, 101): Faz um giro por todos os números começando no 0 até chegar no 100.

if numero % 2 == 0: Analisa se o resto da divisão desse número por 2 dá zero.

categoria = "par": Se não sobrar nada na divisão, ele rotula o número como par.

else: categoria = "impar": Se sobrar algum resto, ele define que o número é ímpar.


## Exercicio 2 

<img width="327" height="224" alt="image" src="https://github.com/user-attachments/assets/eb068b0b-ae71-4c75-be78-9db5f419d1c8" />


n1, n2, n3: Cria as tres variaveis para guardar os números.

if n1 > n2: e n1, n2 = n2, n1: Se o primeiro for maior que o segundo, eles trocam de lugar para organizar a fila.

if n1 > n3: e n1, n3 = n3, n1: Se o novo primeiro ainda for maior que o terceiro, eles também trocam.

if n2 > n3: e n2, n3 = n3, n2: Compara o segundo com o terceiro e arruma a ordem se precisar.

print(f"...{n1}") e print(f"...{n3}"): mostra na tela quem ficou na primeira posição (menor) e na última (maior).

## Exercicio 3 

<img width="250" height="62" alt="image" src="https://github.com/user-attachments/assets/e8aae136-f02a-4213-b1ac-6bd0d20dd4f0" />


nome = input(...): Abre a caixinha de texto para o usuário escrever o nome dele.

for i in range(1, len(nome) + 1): Um laço que conta desde o 1 até o total de letras que o nome tiver.

print(nome[:i]): Vai fatiando o nome e imprimindo, começando só com a primeira letra e aumentando uma por uma até completar.


## Exercicio 4

<img width="214" height="192" alt="image" src="https://github.com/user-attachments/assets/7cf0068c-9517-4154-b6b3-98ee39648e83" />

n = 78: Define que a gente quer ver os 50 primeiros resultados.

termo1 = 1 e termo2 = 1: os dois números que vão iniciar na sequência.

for i in range(n): Faz o código repetir a conta 78 vezes seguidas.

print(termo1): Mostra o número que está na vez agora.

proximo = termo1 + termo2: Soma os dois últimos números para descobrir qual é o próximo da fila.

termo1 = termo2 e termo2 = proximo: Atualiza os valores para que a próxima soma use os números mais recentes.


## Exercicio 5

<img width="516" height="445" alt="image" src="https://github.com/user-attachments/assets/6f2a769b-eaa6-423d-a3af-9684ae2d1204" />

while len(nome) <= 3: Só deixa passar se o nome tiver mais que 3 letras, se for curto demais, dá erro e pede de novo.

while idade < 0 or idade > 150: Trava o sistema se a idade for impossível (menor que zero ou maior que 150).

while salario <= 0: Não aceita salários negativos ou zerados.

while sexo != "f" and sexo != "m": Obriga a escolher entre as opções 'f' ou 'm' (o .lower() serve para aceitar tanto letra minúscula quanto maiúscula).

while ec not in ['s','c','v','d']: Verifica se o que foi digitado bate com as letras da lista (solteiro, casado, etc).

print(...): Depois de passar por todos os filtros, ele exibe os dados limpos e confirma que está tudo certo.


## Exercicio 6


<img width="481" height="338" alt="image" src="https://github.com/user-attachments/assets/9018c0b4-4b86-4cb8-84e7-6b9733cfcf9d" />

nprimo = True: O programa começa acreditando que o número é primo.

if n <= 1: Se o número for 1 ou menos, ele já descarta e diz que não é primo.

for i in range(2, n): Testa a divisão do seu número por todos os outros entre 2 e ele mesmo.

if n % i == 0: Se o resto for zero em qualquer uma dessas divisões, ele não é primo.

break: Para o teste na hora porque já achamos um divisor.

## Exercicio 7


<img width="517" height="188" alt="image" src="https://github.com/user-attachments/assets/40076080-66f4-4a8f-af51-97e54efca3c8" />


fatorial = 1: Começa a conta com o valor 1 para poder multiplicar depois.

for i in range(1, numero + 1): Cria uma contagem que vai do 1 até o número que você digitou.

fatorial = fatorial * i: Pega o que já tinha e multiplica pelo próximo número da contagem, acumulando o resultado.

## Exercicio 8
<img width="504" height="215" alt="image" src="https://github.com/user-attachments/assets/28e6e8bd-f470-499e-803c-77092989fd7f" />


lista = [...]: Uma lista com vários números fora de ordem.

len(lista), max(lista), min(lista), sum(lista): Comandos que calculam sozinhos o tamanho, o maior valor, o menor e o total da soma.

sorted(lista): Pega a bagunça e coloca tudo na ordem do menor para o maior.

reverse=True: Faz a mesma coisa, só que ao contrário (do maior para o menor).


## Exercicio 9
<img width="285" height="199" alt="image" src="https://github.com/user-attachments/assets/905771ec-a978-4d5a-b166-bc310f3d4b44" />


produtos = { ... }: Cria uma estrutura tipo um menu, cada nome (chave) tem um preço (valor) grudado nele.

print(produtos): mostra o cardápio completo na tela para consulta.


## Exercicio 10


<img width="497" height="191" alt="image" src="https://github.com/user-attachments/assets/4ca4af5b-bf22-485a-bc68-7b4a0696a363" />


senha_correta = "676767": Define qual é o código secreto.

while senha != senha_correta: Enquanto você não digitar exatamente o código acima, o programa te barra.

print("acesso liberado"): Só aparece quando o loop do while finalmente termina (ou seja, quando você acerta).


## Exercicio 11


<img width="475" height="162" alt="image" src="https://github.com/user-attachments/assets/171e6c39-cf5e-4a60-ad7e-30059e892505" />


for i in range(1, 11): Prepara uma lista de multiplicação do 1 ao 10.

resultado = numero * i: Faz a conta matemática do número escolhido vezes a posição atual do laço.

print(numero, "x", "i", "=", resultado): Desenha a tabuada bonitinha na tela para o usuário ler.










