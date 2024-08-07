

## Comandos de Entrada
### Exemplo básico de programa:

``` c
#include <stdio.h>

int main() {
  printf("Hello World!");
  return 0;
}
```

### Comandos
|Função| Comando |
|------|---------|
|Exibir mensagem | `printf`|
|Comentário curto | // |
|Comentário longo | /* */ |
|Pular linhas | `\n`|



### Variáveis

- **Int**: Números inteiros (123)
- **Floa**t: Números reais (17.2)
- **Char**: Caracteres ('a')

#### Alguns exemplos

``` c
// Declare a variável
int myNum;

// Atribuí seu valor
myNum = 15;

```


### Formatações

|Comando | Função|
|--------|-------|
|%d |Exibir inteiros decimais|
|%c |Exibir um único caractere|
|%s |Exibir uma string de caractere|
|%f |Exibir um número em ponto flutuante|
|%t |Exibe tabulação |
|%c |Exibe um único caracter |
|%d |exibe um inteiro decimal
|%o |Exibe um número octal|
|%x |Exibe um número hexadecimal|
|%u |Exibe um inteiro sem sinal|
|%3.2f| Exibe um número real (ponto flutuante com 3 inteiro e 2 decimais)|
|%e| Exibe um número real (notação científica em e minúsculo)|
|%E| Exibe um número real (notação científica em E minúsculo)|
|%g| Escolhe o melhor entre ponto flutuante e notação científica (e)|
|%G| Escolhe o melhor entre ponto flutuante e notação científica (E)|
|%%| Exibe o caracter %|
|%p| Apresenta um ponteiro|



#### Alguns exemplos

**Ex 1:**
``` c
// Criando variáveis 
int myNum = 15;            
float myFloatNum = 5.99;   
char myLetter = 'D';       

// Print variáveis
printf("%d\n", myNum);
printf("%f\n", myFloatNum);
printf("%c\n", myLetter);

```

**Ex 2:**
``` c
int myNum = 15;
char myLetter = 'D';
printf("My number is %d and my letter is %c", myNum, myLetter);

```

### Alguns Exemplos Gerais

``` c
// Create integer variables
int length = 4;
int width = 6;
int area;

// Calculate the area of a rectangle
area = length * width;

// Print the variables
printf("Length is: %d\n", length);
printf("Width is: %d\n", width);
printf("Area of the rectangle is: %d", area);


```

## Comandos de Saída

### Comandos
|Comando | Função |
|--------|--------|
|%d | Ler inteiros decimais|
|%c |Ler um único caractere|
|(gets) |Ler uma string de caractere|
|%f |Ler um número em ponto flutuante|
|%o  |Ler um número octal|
|%x |Ler um número hexadecimal|

* A variável que receberá o valor deve ser precedida de: &
Exemplos:

```scanf(“%d”,&idade);```

```scanf(“%d”,&matricula);```

### Alguns exemplos

```c
#include <stdio.h>

int main() {
	
	char nome[15];
	int idade, anoNascimento, anoAtual=2024;
	float altura, peso, imc;
	
	printf("Qual e o seu nome? ");
	scanf("%s", nome);
	printf("Qual e o seu ano de nascimento? ");
	scanf("%d", &anoNascimento);
	idade = anoAtual - anoNascimento;
	
	printf("Qual e a sua altura (em metros)? ");
	scanf("%f", &altura);
	printf("Qual e o seu peso? ");
	scanf("%f", &peso);
	
	imc = peso / (altura * altura);
	
	printf("Voce tem %d anos", idade);
	printf("e um IMC de %.1f", imc);

}

```