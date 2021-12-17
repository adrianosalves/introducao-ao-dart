# introducao ao dart pequenos sites

Dart é uma liguagem de programação orientado a objetos para web, mobile.
Muito usado em desenvolvimento mobile.

https://dart.dev temos muitas informacoes e uma comunidade grande.

No https://dartpad.dev é um compilador online ajuda no aprendizado.

exemplo:

void main() {
  for (int i = 0; i < 5; i++)
    print('hello $(i + 1)');
    }
}

No codigo temos o:
abaixo do codigo.

void main() {
 
} 

Exemplo:

void main() {
  print("olakkk");
  print("kk");
  print("ml")  
}

# String, int e double

**Trabalhando com variaveis**

Uma variavel é um espaço na memoria que armazena alguma informação e ela perdura até a execução final do nosso programa:

void main() {
  // Meu programa!
  String produto;
  produto = 'banana';
  print(produto);
  
  //Quantidade de sacos de banana
  int quantidade = 20;
  
  //Preço do saco
  double preco = 10.99; //Double valores flutunte
  
}

**Bool e concatenação**

Bool = verdadeiro ou falso

void main() {
  // Meu programa!
  String produto;
  produto = 'banana';
  print(produto);
  
  //Quantidade de sacos de banana
  int quantidade = 20;
  
  //Preço do saco
  double preco = 10.99;
 
 
  print(quantidade);
  print(preco);
  
  bool entrega = true;
  
  print(entrega);
  
  produto = "Arroz";
  print('O ' + produto + 'esta');
  print('O arroz está 10.99')
  print('O ' + produto + ' kkesta $preco'); // Isso ***'$preco'** concatenar o valor, isso se chama                                                        interpolação de string!  
}

# Trabalhando com variáveis e condicionais no Dart
# Desenvolvimento de código

**Exemplo 1:**

void main() {
  
//Uso de variaves inteiras
 int valor1 = 15;
 int valor2 = 30;
  
 int resultado = valor1 + valor2;   
 print(resultado);   
 
}

**Exemplo 2:**

void main() {
 
 //Se utilizarmos 'double' em umas das variaveis, o resultado tambem precisa 'double'
 double valor1 = 15;
 int valor2 = 30;
  
 double resultado = valor1 + valor2;   
 print(resultado);   
 
}

**Exemplo 3:**

void main() { 
  
//Uso de variaves inteiras para as soma de divisão
 double valor1 = 15;
 int valor2 = 30;
  
 double resultado = valor1 / valor2;   
 print(resultado);   
 
}

**Exemplo 4:**

void main() {
  
//Uso de variaves inteiras
 double valor1 = 15;
 int valor2 = 30;
  
double resultado = valor1 * valor2;   
 print(resultado);
 resultado--;
 print(resultado);
 
}

**Exemplo 4:**

void main() {
  
//Uso de variaves inteiras
 double valor1 = 15;
 int valor2 = 30;
  
double resultado = valor1 * valor2;   
 print(resultado);
 resultado++;
 print(resultado);
 
}

**Exemplo 4:**

void main() {
  
//Uso de variaves inteiras
 double valor1 = 15;
 int valor2 = 30;
  
double resultado = valor1 * valor2;   
 print(resultado);
 resultado = resultado + 1;
 print(resultado);
 
}

**Exemplo 5:**

void main() {
  
//Uso de variaves inteiras
 double valor1 = 1;
 int valor2 = 2;
  
double resultado = valor1 + valor2;   
 print(resultado);
 resultado = resultado - 1;
 print(resultado);
 
}

**Exemplo 6:**

void main() {
  
//Uso de variaves inteiras
 double valor1 = 1;
 int valor2 = 2;
  
double resultado = valor1 + valor2;   
 print(resultado);
 resultado = (resultado - 1)*2;
 print(resultado);
 
}

**Exemplo 7:**

void main() {
  
//Uso de variaves inteiras
 double valor1 = 1;
 int valor2 = 2;
  
double resultado = valor1 + valor2;   
 print(resultado);
 resultado+=1;
 print(resultado);
 
}

# Igual, diferente, maior que e menor que
# Operadores logicos

**Exemplo 1:**

void main() {
  
//Operadores logicos
//IGUALDADE

int operador1 = 1;
int operador2 = 1;

bool resultado = operador1 == operador2; 
  print(resultado);
 
}

**Exemplo 2:**

void main() {
  
//Operadores logicos
//IGUALDADE

int operador1 = 1;
int operador2 = 1;
double operador3 = 1.1;

bool resultado = operador1 == operador3; 
  print(resultado);
 
}

**Exemplo 3:**

void main() {
  
//Operadores logicos
//DIFERENCA

int operador1 = 1;
int operador2 = 2;
double operador3 = 1.1;

bool resultado = operador1 != operador2; 
  print(resultado);
 
}

**Exemplo** 4

void main() {
  
//Operadores logicos
//MAIOR QUE ou MENOE QUE

int operador1 = 1;
int operador2 = 2;
double operador3 = 1.1;

bool resultado = operador1 > operador2; 
  print(resultado);
 
}

**Exemplo** 5

void main() {
  
//Operadores logicos
//MAIOR QUE, MENOOR IGUAL

int operador1 = 7;
int operador2 = 6;
double operador3 = 1.1;

bool resultado = operador1 >= operador2; 
  print(resultado);
 
}

**is, and, or e not**

// and
  
  /*
  
  print("####### and #############");
  bool operador1 = true;
  bool operador2 = true;
  
  bool resultado = operador1 ^ operador2;
  print(resultado); 
 
  */
  
  /*
  
  print("####### and #############");
  bool operador1 = true;
  bool operador2 = false;
  
  bool resultado = operador1 && operador2;
  print(resultado);
  
  */
  
  //Tabela verdade && - E (and):
  //FALSE + FALSE = FALSE
  //FALSE + TRUE = FALSE
  //TRUE + FALSE = FALSE
  //TRUE + TRUE = TRUE
  
  // or
  
  /*
  print("####### or #############");
  bool operador1 = true;
  bool operador2 = true;
  
  bool resultado = operador1 || operador2;
  print(resultado);
  
  //Tabela verdade || - OU (or)
  //TRUE + TRUE = TRUE
  //FALSE + FALSE = FALSE
  //TRUE + FALSE = TRUE
  //FALSE + TRUE = TRUE
  
  //not
  //Tabela verdade ! - Negação (NOT)
  //TRUE FALSE
  //FALSE TRUE

  */
  
  
  String s = "Amendoas";
  String a = "aa";
  s = "{a}";
  print(s);








