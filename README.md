## Proyecto - POS

Proyecto para practicar Ingeniería Inversa

# Diagrama de clases
[Editor en línea](https://mermaid.live/)
```mermaid
---
title: Clase
---
classDiagram
      class Clase
      Clase: -x
      Clase: -y
      Clase: +op1()
      Clase: +op2()
      Clase: +op3()
      Clase: +op4()
```
[Referencia-Mermaid](https://mermaid.js.org/syntax/classDiagram.html)

* Ejecutar

```
gradle run
```
* Probar

```
gradle test
```
* Generar el Diagrama de Secuencia 

```
gradle appmap test
```
El Diagrama de Secuencia se puede consultar en `/app/build/appmap/junit/**.json`


Los comandos anteriores están considerados para un ambiente Linux
