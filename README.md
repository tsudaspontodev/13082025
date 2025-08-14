# 13082025

PSEUDOCÓDIGO
*Estrutura Básica
*Algoritimo "nomeDoAlgoritimo"
var
  nome_da_variavel : Tipo_de_Dados

inicio
  <comandos>
FimAlgoritimos

-----------------------------------
Calcular o troco de uma compra

ALGORITIMO "TrocoDeCompra"

VAR
  valorDaCompra: Real;
  valorPago: Real;
  troco: Real;

INICIO

escreva "Digite o valor da Compra";
leia: valorDaCompra;

escreva "Digite o valor Pago;
leia: valorPago;

troco <- valorPago - valorDaCompra

escreva "O valor do trocao é ", troco

FimAlgoritimos

-----------------------------------

crie um pseudocodigo para um algoritimo que leia tres notas de um aluno e calcule a sua media final 

ALGORITIMO "NotasDoAluno"

VAR
  nomeAluno: texto;
  nota1: inteiro;
  nota2: inteiro;
  nota3: inteiro;
  media: inteiro;

INICIO

escreva "Informe o nome do aluno";
leia nomeAluno;

escreva "Informe a primeira nota do aluno";
leia nota1;

escreva "Informe a segunda nota do aluno";
leia nota2;

escreva "Informe a terceira nota do aluno";
leia nota3;

media <- (nota1 + nota2 + nota3)/3;

escreva "A media final do aluno ", nomeAluno, "foi de ";

se (media > 70) {
  escreva "O aluno foi APROVADO";
}então {
  escreva "O aluno foi REPROVADO";
 }fim se 

 FimAlgoritimos
