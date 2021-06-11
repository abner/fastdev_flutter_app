

# Projeto Referência Flutter 2

## Geral

* Lint
* required ao invés de @required
* Dependências Null-safety

## Dart 2.12

* Sound Null Safety
* Operadores relacionados a null safety
* Boas práticas Null-safety


## Dart 2.13

* Type Aliases
  * Pseudo Json Type
  * Domain Language Types: `typedef ListaDeclaracoes = List<Declaracao>`
  * `typedef MapToList<X> = Map<String, List<X>>;`
  * Depreciar nomme de classes:

     ```dart
    class BetterNamedClass {...}
    @Deprecated('Use BetterNamedClass instead')
    typedef PoorlyNamedClass = BetterNamedClass;
    ```
  * Melhoria em Performance e Tamanho App gerado: https://medium.com/dartlang/announcing-dart-2-13-c6d547b57067
    * Gerar projeto em 2.12 e comparar com 2.13