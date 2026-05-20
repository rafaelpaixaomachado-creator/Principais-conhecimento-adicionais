# Principais-conhecimento-adicionais

Python 
pontos_acumulados = 0  # Inicializa o acumulador

pontuacoes = [10, 5, 15, 8]  # Lista de pontuações a serem acumuladas

for pontuacao in pontuacoes:

  pontos_acumulados += pontuacao  # Adiciona a pontuação atual ao acumulador

print("Total de pontos acumulados:",

def verificar_paridade(numero):

  if numero % 2 == 0:

    print(f"{numero} é Par.")

  else:

    print(f"{numero} é Ímpar.")

verificar_paridade(10)  # Saída: 10 é Par.

verificar_paridade(7)   # Saída: 7 é Ímpar.

contador = 0  # Inicializa o contador

i = 0

while i < 5:  # Loop enquanto i for menor que 5

  print("Iteração número:", contador + 1)

  contador += 1  # Incrementa o contador

  i += 1       # Incrementa a variável de controle do loop

print("O loop executou", contador, "vezes.")  # Saída: O loop executou 5 vezes.

def calcular_porcentagem(valor, total):

  if total == 0:

    return "Erro: O total não pode ser zero."

  return (valor / total) * 100

print("25% de 200 é:", calcular_porcentagem(50, 200))  # Saída: 25% de 200 é: 25.0

print("10% de 150 é:", calcular_porcentagem(15, 150))  # Saída: 10% de 150 é: 10.0

def calcular_media_aritmetica(n1, n2, n3, n4):

  return (n1 + n2 + n3 + n4) / 4

print("A média de 10, 20, 30, 40 é:", calcular_media_aritmetica(10, 20, 30, 40))  # Saída: A média de 10, 20, 30, 40 é: 25.0

print("A média de 5, 5, 5, 5 é:", calcular_media_aritmetica(5, 5, 5, 5))        # Saída: A média de 5, 5, 5, 5 é: 5.0

def verificar_

(Float)
var
  nota1, nota2, media : real;
begin
  writeln('Digite a primeira nota: ');
  readln(nota1);
  writeln('Digite a segunda nota: ');
  readln(nota2);
  media := (nota1 + nota2) / 2;
  writeln('A média é: ', media);
end.

let nota1 = parseFloat(prompt("Digite a primeira nota:"));
let nota2 = parseFloat(prompt("Digite a segunda nota:"));
let media = (nota1 + nota2) / 2;
console.log("A média é: " + media);

let celsius = parseFloat(prompt("Digite a temperatura em Celsius:"));
let fahrenheit = (celsius * 9/5) + 32;
console.log("Temperatura em Fahrenheit: " + fahrenheit);

