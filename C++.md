

# Revisão de apredizado de C++

## Bibliotecas:

São um conjunto de funções pré-definidas que podem ser implementadas ao código. 

**Principais bibliotecas:**

**iostream** - para entrada e saída de dados 
(utilizar junto "using namespace std")
**cmath** - para funções matemáticas comuns 
**ctime** - para manipulação de tempo 

## Definindo variáveis

Int Variável_Inteira;
Float Variável_Flutuante;
Char Caracter_Unico;
Bool Verdadeiro_Ou_Falso;

## Função de entrada e saída

Cout << "Para saída de dados";
Cin >> Entrada;

## Operadores

**Aritméticos**

Adição = 1 + 1;
Subtração = 2 - 1;
Multiplicação = 2 * 3;
Divisão = 6 / 2;
Resto = 3 % 10; 

**Comparação**

Igual == 1;
Diferente != 1;
Maior > 0;
Menor < 1;
Maior_Ou_Igual >= 0;
Menor_Ou_Igual = 1;

**Lógicos**

And && E
Or || Ou
Not ! Não

**Incremento**

Incrementa ++
Decrementa --

## Estruturas de controle

**Estruturas de decisão**

Controla o fluxo do programa de acordo com condições específicas.

**If-else:** 
Executa um bloco de a condição for verdadeira e outro se a condição for falsa.

If (condição) {
  cout << "Faça isso";
} else {
  cout << "Faça aquilo";
}

**Switch case:**
Executa um bloco de código com base no valor de uma expressão.

Switch (opção){
	case 1:
    cout << "Opção 1 selecionada";
    break;
  case 2:
    cout << "Opção 2 selecionada";
    break;
  default:
    cout << "Opção inválida";
  }

**Estruturas de repetição**

Executa um bloco várias vezes enquanto a condição for verdadeira.

**While:**
Executa um código enquanto a condição for verdadeira.

While (contador < 5) {
    cout << "Contagem: " << Contador;
    Contador++;
}

**For:** 
Executa um código um número específico de vezes.

for (inicialização; condição; incremento)

for (int contador = 0; contador < 5; contador++){
    cout << "Contagem: " << contador;
	      }
