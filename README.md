# ft_printf

![ft_printf logo](https://images.app.goo.gl/t7pG3qcvrdwtManW6)

## Sumário

- [Sobre o Projeto](#sobre-o-projeto)
- [Funcionalidades](#funcionalidades)
- [Instalação](#instalação)
- [Como Usar](#como-usar)
- [Exemplos](#exemplos)
- [Contribuição](#contribuição)
- [Licença](#licença)

## Sobre o Projeto

![C Programming](https://images.app.goo.gl/3XCaXhLZh2Vp6Hm37)

O `ft_printf` é uma recriação da função printf da biblioteca padrão do C. O objetivo deste projeto é entender como funciona essa função, além de praticar manipulação de strings, variáveis de va_list e outras funcionalidades básicas de C.

## Funcionalidades

![Features](https://images.app.goo.gl/fvXKDMAv8AeJqnFw6)

O `ft_printf` suporta as seguintes especificações:
- `%c`: Caracter
- `%s`: String
- `%p`: Ponteiro
- `%d`/`%i`: Inteiros
- `%u`: Unsigned integer
- `%x`/`%X`: Hexadecimal
- `%%`: Percentagem

## Instalação


Para compilar e utilizar o `ft_printf`, siga os seguintes passos:

```sh
git clone https://github.com/seu-usuario/ft_printf.git
cd ft_printf
make
```

## Como Usar

Inclua o ft_printf no seu projeto

```cc
#include "ft_printf.h"

int main() {
    ft_printf("Hello, %s!\n", "world");
    return 0;
}
```

## Exemplos

Aqui estão alguns exemplos de como usar o ft_printf:

```cc
ft_printf("Character: %c\n", 'A');
ft_printf("String: %s\n", "Hello, World!");
ft_printf("Pointer: %p\n", (void *)0x12345678);
ft_printf("Integer: %d\n", 42);
ft_printf("Unsigned: %u\n", 42);
ft_printf("Hexadecimal: %x\n", 255);
ft_printf("Percent: %%\n");
```
