# ft_printf

**ft_printf** es una implementación propia de la función `printf()` de la biblioteca estándar de C. Este proyecto es parte del curso de programación del 42Cursus y tiene como objetivo profundizar en el manejo de cadenas, formatos y punteros, así como la correcta gestión de la memoria dinámica.

## :star2: Descripción

En este proyecto, creé una versión personalizada de la función `printf`, que soporta una variedad de especificadores de formato y funcionalidades como:

- **%c**: Imprime un solo carácter.
- **%s**: Imprime una cadena de caracteres.
- **%d** / **%i**: Imprime un número entero con signo.
- **%u**: Imprime un número entero sin signo.
- **%x** / **%X**: Imprime un número en formato hexadecimal (minúsculas/mayúsculas).
- **%p**: Imprime una dirección de memoria en formato hexadecimal.
- **%%**: Imprime un símbolo de porcentaje (`%`).

### :sparkles: Características

- **Eficiencia**: Se busca que la función sea eficiente en cuanto a la manipulación de los argumentos y la impresión de los resultados.
- **Compatibilidad**: La función es completamente compatible con los especificadores de formato más comunes, tal como se especifica en el estándar `printf`.
- **Flexibilidad**: Se permite un número indefinido de argumentos, utilizando un enfoque basado en punteros y la gestión adecuada de la memoria.

## Instalación

Este proyecto está diseñado para ser compilado con **CC** y **Make** en un entorno de desarrollo de C.
