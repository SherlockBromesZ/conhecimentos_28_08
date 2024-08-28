# Ordem dos Operadores em C++

Em C++, a ordem dos operadores determina a sequência em que as operações são realizadas. Abaixo está uma lista da ordem dos operadores do mais alto para o mais baixo, incluindo operadores aritméticos, relacionais e lógicos.

## Ordem dos Operadores

1. **Operadores Aritméticos:**
   - `*` (Multiplicação)
   - `/` (Divisão)
   - `%` (Módulo)

   Esses operadores são avaliados antes dos operadores de adição e subtração.

2. **Operadores de Adição e Subtração:**
   - `+` (Adição)
   - `-` (Subtração)

   São avaliados após os operadores de multiplicação, divisão e módulo.

3. **Operadores Relacionais:**
   - `==` (Igualdade)
   - `!=` (Diferença)

   Estes operadores são usados para comparar valores e são avaliados após os operadores aritméticos.

4. **Operador Lógico E:**
   - `&&` (E lógico)

   Este operador avalia a expressão lógica antes do operador lógico OU.

5. **Operador Lógico OU:**
   - `||` (OU lógico)

   É avaliado após o operador lógico E.

6. **Operador de Negação Lógica:**
   - `!` (Negação lógica)

   O operador `!` tem a precedência mais alta entre os operadores lógicos, então é avaliado primeiro.

## Exemplo

Considere a seguinte expressão:

```cpp
int result = 5 + 3 * 2 == 16 / 2 && !false;
```
