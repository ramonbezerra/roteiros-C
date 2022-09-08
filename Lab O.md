# Lab 0

Olá. Seja bem-vindo a disciplina de Laboratório de Programação 1. Estaremos praticando a linguagem C, uma linguagem de propósito geral e de alto nível (e que também provê recursos de baixo nível). 

Desenvolvida no ano de 1972 pelo cientista americano Dennis Ritchie dentro da Bell Laboratories (a empresa do inventor do telefone, Graham Bell, hoje pertencente a Nokia), pensada para a criação de compiladores e sistemas operacionais, sendo a principal do Unix (suas características estão presentes nos sistemas MacOS, Linux e Android). 

Ela é considerada a "mãe" de muitas outras linguagens de alto nível conhecidas hoje, como C++, C#, Dart, Go, Java, PHP, Rust, Swift, entre outras, porém não deixou de ser atual, sendo ainda bastante utilizada nas áreas de seu propósito original e também em máquinas virtuais.

É uma linguagem de processamento muito rápido, em comparação com outras linguagens, como Java e Python, muito versátil, pois irá te ajudar, inclusive, a conhecer outras linguagens de programação. Por isso é tão popular.

## Nosso primeiro programa em C: Hello World

Para criarmos nosso primeiro programa, veja quais são os passos e a sintaxe do código:

```
#include <stdio.h>

int main()
{
  printf("Hello, World!");
  return 0;
}
```

Na primeira linha, temos a inclusão da biblioteca padrão de entrada e saída de dados (muito importante na resolução de problemas), o Standard I/O.

Como a maioria das linguagens de programação, C é composta por muitas funções, denotadas sempre que há uma palavra seguida de parênteses `()`. Nesse caso, estamos invocando a função principal, `main`, que é responsável por executar o código. Nela você poderá armazenar e manipular dados de entrada e saída.

Note que a função é um bloco de código, e que deve estar dentro de chaves `{}`. E mais uma observação: a função `main` sempre retorna alguma coisa, por isso temos a palavra `return` na última linha. Ela sinaliza que será devolvido um valor, que nesse caso é um número inteiro. Por isso que antes do nome da função aparece uma palavra reservada `int`, que corresponde ao tipo de informação que será devolvido ao final da função.

Por fim, veja o núcleo da nossa função: "imprimir" na tela a frase "Hello, World!". Para tanto, utilizaremos a função `printf` da biblioteca `stdio.h` para realizar essa tarefa para nós. 

Esse código pode ser escrito na sua máquina com a instalação de um compilador, como o CGC, por exemplo, e o uso de um editor de texto, como o Sublime. O arquivo deverá ter a extensão `.c`. 

Dica: Utilize uma IDE, como o CodeBlocks ou Visual Studio Code, para tornar sua tarefa de codar mais produtiva, ou utilize ambientes online, sempre priorizando aqueles integrados ao `GitHub`, como o `repl.it`.

## Um segundo programa: somando dois números



```
#include <stdio.h>

int main()
{
  int integer1 = 0;
  int integer2 = 0;
}
```