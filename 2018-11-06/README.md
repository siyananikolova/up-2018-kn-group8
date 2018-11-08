# 2018-11-06 - Шесто упражнение

## Зад. 3

Да се напише програма, която извежда дължината на най-дългата последователност от ненамаляващи числа. Пример:

```
Sequence length: 10
Input sequence: 1 2 3 -5 11 23 47 9 1 0
Longest sequence: 4
```

## Зад. 3.1

Да се промени програмата така, че да извежда намерената поредица на екрана:

```
Sequence length: 10
Input sequence: 1 2 3 -5 11 23 47 9 1 0
Longest sequence: -5 11 23 47
```

## Зад. 4

Да се напишат имплементации на следните стандартни функции:

- `int strlen(char string[])` - връща дължината на низа
- `void strcpy(char destination[], char source[])` - копира низ
- `void strcat(char destination[], char source[])` - конкатенира два низа
- `int strcmp(char a[], char b[])` - сравнява два низа лексикографски

## Зад. 5 (Зад. 2.1* от предното упражнение)

Да се напише програма, която по въведен низ от стандартния вход, проверява дали скобите в низа са балансирани. Да се поддържат следните видове скоби - `()`, `{}`, `<>` и `[]`. Пример:

Балансирани - `(){}`, `({[]}[])`
Небалансирани - `][`, `({)}`