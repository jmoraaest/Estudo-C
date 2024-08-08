## Operadores

### Aritiméticos 

| Operador | Nome        | Descrição                            | Exemplo  |
|----------|-------------|--------------------------------------|----------|
| `+`      | Adição      | Soma dois valores                    | `x + y`  |
| `-`      | Subtração   | Subtrai um valor de outro            | `x - y`  |
| `*`      | Multiplicação| Multiplica dois valores              | `x * y`  |
| `/`      | Divisão     | Divide um valor por outro            | `x / y`  |
| `%`      | Módulo      | Retorna o resto da divisão           | `x % y`  |
| `++`     | Incremento  | Aumenta o valor de uma variável em 1 | `++x`    |
| `--`     | Decremento  | Diminui o valor de uma variável em 1 | `--x`    |

### Atribuição

| Operador | Exemplo  | Equivale a          |
|----------|----------|---------------------|
| `=`      | `x = 5`  | `x = 5`             |
| `+=`     | `x += 3` | `x = x + 3`         |
| `-=`     | `x -= 3` | `x = x - 3`         |
| `*=`     | `x *= 3` | `x = x * 3`         |
| `/=`     | `x /= 3` | `x = x / 3`         |
| `%=`     | `x %= 3` | `x = x % 3`         |
| `&=`     | `x &= 3` | `x = x & 3`         |
| `^=`     | `x ^= 3` | `x = x ^ 3`         |
| `>>=`    | `x >>= 3`| `x = x >> 3`        |
| `<<=`    | `x <<= 3`| `x = x << 3`        |

### Comparação 

| Operador | Nome                        | Exemplo  | Descrição                                                                 |
|----------|-----------------------------|----------|---------------------------------------------------------------------------|
| `==`     | Igual a                     | `x == y` | Retorna 1 se os valores forem iguais                                      |
| `!=`     | Diferente de                | `x != y` | Retorna 1 se os valores forem diferentes                                  |
| `>`      | Maior que                   | `x > y`  | Retorna 1 se o primeiro valor for maior que o segundo valor               |
| `<`      | Menor que                   | `x < y`  | Retorna 1 se o primeiro valor for menor que o segundo valor               |
| `>=`     | Maior ou igual a            | `x >= y` | Retorna 1 se o primeiro valor for maior ou igual ao segundo valor         |
| `<=`     | Menor ou igual a            | `x <= y` | Retorna 1 se o primeiro valor for menor ou igual ao segundo valor         |

### Lógico 

| Operador | Nome    | Exemplo              | Descrição                                              |
|----------|---------|----------------------|--------------------------------------------------------|
| `&&`     | E (AND) | `x < 5 && x < 10`    | Retorna 1 se ambas as condições forem verdadeiras      |
| `||`     | OU (OR) | `x < 5 || x < 4`     | Retorna 1 se uma das condições for verdadeira          |
| `!`      | NÃO (NOT) | `!(x < 5 && x < 10)` | Inverte o resultado; retorna 0 se o resultado for 1    |
