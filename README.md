# 🧠 Exercícios de Lógica de Programação em *ADA* <img width="45" height="40" alt="image" src="https://github.com/user-attachments/assets/a9275006-bef7-4d56-bfa1-877e5bc54f20" />


Este repositório contém exercícios de lógica de programação que estou resolvendo para treinar minha base em desenvolvimento e fortalecer meu raciocínio lógico, usando a linguagem **Rust**.

---

## ✍️ Objetivo:
Praticar lógica de programação e registrar minha evolução nos estudos com Ada. Aqui você encontrará exercícios envolvendo:


 * Variáveis e tipos de dados em Ada

 * Condicionais (if, elsif, else)

 * Laços de repetição (for, while, loop)

 * Procedimentos e funções

 * Arrays e registros (array, record)

---

# EXERCICIOS *ADA*: 1

CALCULADORA SIMPLES:

Crie um programa que funcione como uma calculadora básica, realizando operações matemáticas entre dois números fornecidos pelo usuário.
Funcionalidades:

    Solicitar ao usuário que digite dois números.

    Solicitar qual operação matemática deseja realizar:

        Soma (+)

        Subtração (-)

        Multiplicação (*)

        Divisão (/)

    Realizar a operação escolhida e mostrar o resultado.

    Caso o usuário escolha uma operação inválida, exibir uma mensagem de erro.

    Perguntar ao usuário se deseja realizar outra operação, repetindo o processo enquanto desejar.

 # Codigo:    
<img width="1322" height="855" alt="screenshot-2025-09-02_12-00-58" src="https://github.com/user-attachments/assets/096ba3d1-e826-4ab3-9679-419dc0cf95b1" />



## 🚀 Como estou estudando

Estou estudando Rust diariamente, resolvendo exercícios passo a passo e aplicando boas práticas de código mesmo em problemas simples. A ideia é evoluir gradualmente e usar este repositório para acompanhar meu progresso.

---

## 📌 Observações

- Todos os exercícios foram feitos por mim, com base em listas de lógica e desafios disponíveis na internet ou criados por mim mesma.
- O foco é o **aprendizado**, então nem sempre o código será o mais otimizado — o importante é que funcione e eu entenda o que está acontecendo.


# EXERCICIO *ADA*: 2

FOLHA DE PAGAMENTO:

Faça um programa para cálculo de uma folha de pagamento, considerando os seguintes descontos e regras:

    Imposto de Renda (IR) descontado conforme tabela do salário bruto:

        Até R$ 900,00 (inclusive): isento

        Até R$ 1500,00 (inclusive): 5%

        Até R$ 2500,00 (inclusive): 10%

        Acima de R$ 2500,00: 20%

    Desconto de 10% para o INSS.

    FGTS corresponde a 11% do salário bruto, mas não é descontado do trabalhador — é um depósito feito pela empresa.

    O salário líquido é o salário bruto menos os descontos (IR + INSS).

O programa deverá solicitar ao usuário:

    Valor da hora trabalhada.

    Quantidade de horas trabalhadas no mês.

    Exemplo de saída: 
    Salário Bruto:                 : R$ 1100,00
    IR (5%)                       : R$   55,00
    INSS (10%)                    : R$  110,00
    FGTS (11%)                    : R$  121,00
    Salário Líquido               : R$  935,00

# Codigo:     


# EXERCICIO *ADA*: 3

TABUADA: Desenvolva um programa que faça a tabuada de um número qualquer inteiro que será digitado pelo usuário, mas a tabuada não deve necessariamente iniciar em 1 e terminar em 10, o valor inicial e final devem ser informados também pelo usuário, conforme exemplo abaixo:
```
Montar a tabuada de: 5
Começar por: 4
Terminar em: 7

Vou montar a tabuada de 5 começando em 4 e terminando em 7:
5 X 4 = 20
5 X 5 = 25
5 X 6 = 30
5 X 7 = 35
```
CODIGO:

# EXERCICIO *ADA*: 4

CAIXA ELETRONICO: Faça um Programa para um caixa eletrônico.
```
O programa deverá perguntar ao usuário a valor do saque e depois informar quantas notas de cada valor serão fornecidas.

As notas disponíveis serão as de 1, 5, 10, 50 e 100 reais. O valor mínimo é de 10 reais e o máximo de 600 reais.

O programa não deve se preocupar com a quantidade de notas existentes na máquina.

Exemplo 1: Para sacar a quantia de 256 reais, o programa fornece duas notas de 100, uma nota de 50, uma nota de 5 e uma nota de 1;

Exemplo 2: Para sacar a quantia de 399 reais, o programa fornece três notas de 100, uma nota de 50, quatro notas de 10, uma nota de 5 e quatro notas de 1.
```
CODIGO:

# EXERCICIO *ADA*: 5 

CAIXA REGISTRADORA: Crie um programa em Rust que simule o funcionamento de um caixa registradora. O sistema deve permitir o registro de múltiplos produtos em uma única compra, calcular o valor total, receber o pagamento do cliente, verificar se o valor é suficiente e calcular o troco. Ao final da operação, o programa deve perguntar se o caixa deve ser reaberto para uma nova compra. 

CODIGO:

# EXERCICIO *ADA*: 6

LITRO COMBUSTIVEL: 
 Um posto está vendendo combustíveis com a seguinte tabela de descontos: Álcool: até 20 litros, desconto de 3% por litro acima de 20 litros, desconto de 5% por litro Gasolina: até 20 litros, desconto de 4% por litro acima de 20 litros, desconto de 6% por litro
Escreva um algoritmo que leia o número de litros vendidos, o tipo de combustível (codificado da seguinte forma: A-álcool, G-gasolina), calcule e imprima o valor a ser pago pelo cliente sabendo-se que o preço do litro da gasolina é R$ 2,50 o preço do litro do álcool é R$ 1,90.

CODIGO:

# EXERCICIO *ADA*: 7

Um jogo da forca simples feito em Rust rodando no terminal. O objetivo é adivinhar a palavra secreta, letra por letra, com no máximo 3 erros.

# CODIGO JOGO DA FORCA:
<img width="1012" height="833" alt="screenshot-2025-09-02_12-01-19" src="https://github.com/user-attachments/assets/f0a8ae3b-9b02-47dd-bd37-d875c2edf3cc" />

# EXERCICIO *ADA*: 8

Este é um jogo da velha (tic-tac-toe) feito em **Rust**, rodando inteiramente no terminal. Dois jogadores se revezam jogando, inserindo as coordenadas da linha e coluna para marcar `X` ou `O` em um tabuleiro 3x3.

## 💡 Funcionalidades

- ✅ Interface de texto simples no terminal
- ✅ Validação de jogadas (evita sobrescrever posições)
- ✅ Verificação automática de vitória e empate
- ✅ Alternância automática entre os jogadores `X` e `O`

## 📷 Exemplo de uso

```bash
  0 1 2
0 _ _ _
1 _ _ _
2 _ _ _

Vez do jogador 'X'
Digite a linha e coluna (ex: 0 1): 1 1
```
# CODIGO JOGO DA VELHA 🦀: 

# EXERCICIO *ADA*: 9
Faça um Programa que pergunte em que turno você estuda. Peça para digitar M-Manhã ou t-TARDE ou N- noite.

Imprima a mensagem "Bom Dia!", "Boa Tarde!" ou "Boa Noite!" ou "Valor Inválido!", conforme o caso.

🦀 CODIGO: 

