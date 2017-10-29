# Reglas basadas en las oficiales de YII Framework

## General
- Etiqueta de apertura **<?php**
- Etiqueta de cierre **?>**
- Siempre tiene que tener cierre, no usar otras variaciones

## ARCHIVOS
- UTF-8
- Etiquetas de apertura **<?php**
- Deben usar el final de línea unix ** LF **

## LÍNEAS
- Menos de 120 de longitud
- Como máximo 80 carácteres
- No puede haber espacios al final de una línea
- Espacios de 4 para cada nivel de sangría (no tabulaciones)

## Variables
- Todas en minúsculas

## Clases
- Declaradas en **StudlyCaps** donde cada palabra comienza por mayúsculas
- Class constants MUST be declared in all upper case with underscore separators
- Llaves delimitadora de bloque no debe estar en la misma línea de la declaración, poner las llaves debajo
- Al crear una clase siempre hay que poner paréntesis aunque no tenga argumentos pasados al constructor.
- Las palabras clave ** extends ** e ** implements ** siempre se declaran en la misma línea que el nombre de la clase

## Métodos
- Nombres declarados en **camelCase**

## DATOS
- Usar la forma abreviada de palabras clave de tipo, es decir, **bool** en lugar de **boolean**, **int** en lugar de **integer**

## Estructuras de control
- Espacio entre palabra clave y paréntesis