## Subject

```
Assignment name  : rostring
Expected files   : rostring.c
Allowed functions: write, malloc, free
--------------------------------------------------------------------------------

Escreva um programa que pegue uma string e exiba essa string após girá-la
uma palavra para a esquerda.

Assim, a primeira palavra se torna a última, e as outras permanecem na mesma ordem.

Uma "palavra" é definida como uma parte de uma string delimitada por espaços/tabulações ou
pelo início/fim da string.

As palavras serão separadas por apenas um espaço na saída.

Se houver menos de um argumento, o programa exibirá \n.

Exemplo:

$>./rostring "abc   " | cat -e
abc$
$>
$>./rostring "Que la      lumiere soit et la lumiere fut"
la lumiere soit et la lumiere fut Que
$>
$>./rostring "     AkjhZ zLKIJz , 23y"
zLKIJz , 23y AkjhZ
$>
$>./rostring "first" "2" "11000000"
first
$>
$>./rostring | cat -e
$
$>
```
