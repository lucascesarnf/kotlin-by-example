# Hello World

```run-kotlin
package org.kotlinlang.play         // 1

fun main() {                        // 2
    println("Hello, World!")        // 3
}
```
1. Todo código escrito em Kotlin é definido em pacotes. Especificar o pacote é opcional: se você não especificar ele será definido no pacote padrão. 
2. O ponto de partida de todo código Kotlin é a função `main`. Desde o Kotlin 1.3, você pode declarar a função`main` sem nenhum parâmetros. Já que não é definido um retorno da função, ela não retornará nada.
3. `println` escreve na saída padrão. Ele é importado implicitamente. Observe também que os pontos-e-vírgulas são opcionais.

Nas versões anteriores ao Kotlin 1.3, a função `main` precisava receber um parâmetro do tipo` Array <String> `.

```run-kotlin
fun main(args: Array<String>) {
    println("Hello, World!")
}
```

