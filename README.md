# 🔁 Proyecto Java – Estructuras de Repetición

Este proyecto tiene como objetivo demostrar el uso práctico de las estructuras de repetición en Java: **for**, **while** y **do-while**. Además, incluye el uso de bucles anidados y validaciones básicas, implementado todo en un entorno de consola con entrada del usuario.

---

## 📚 Tabla de Contenidos

- [Introducción](#-introducción)  
- [Objetivos](#-objetivos)  
- [Estructuras Implementadas](#-estructuras-implementadas)  
- [Bucle while: Acumulador con condición](#-bucle-while-acumulador-con-condición)  
- [Bucle do-while: Validación de entrada](#-bucle-do-while-validación-de-entrada)  
- [Bucles anidados: Tablas de multiplicar](#-bucles-anidados-tablas-de-multiplicar)  
- [Validación de Entradas](#-validación-de-entradas)  
- [Ejercicio Final: Dibujo con bucles anidados](#-ejercicio-final-dibujo-con-bucles-anidados)  
- [Conclusión y aprendizaje](#-conclusión-y-aprendizaje)  

---

## 💡 Introducción

Las estructuras de repetición son fundamentales en cualquier lenguaje de programación. Este proyecto demuestra cómo utilizarlas en Java para resolver distintos problemas prácticos, como contar, acumular valores, validar datos y generar figuras por consola.

---

## 🎯 Objetivos

- Aplicar estructuras de control repetitivas en diferentes situaciones.  
- Validar datos ingresados por el usuario.  
- Utilizar bucles anidados para construir figuras.  
- Fortalecer la lógica de programación básica en Java.  

---

## 🔁 Estructuras Implementadas

### 🔹 Bucle for: Contador simple

```java
for (int i = 1; i <= 10; i++) {
    System.out.println("Número: " + i);
}

Muestra los primeros 10 números enteros, ilustrando el uso de un contador.

### 🔹 Bucle while: Acumulador con condición

```java
while (numero != 0) {
    suma += numero;
    // ...
}

Suma todos los números ingresados por el usuario hasta que se ingresa un 0.

### 🔹 Bucle do-while: Validación de entrada

```java
do {
    System.out.print("Ingrese su edad (positiva): ");
    edad = sc.nextInt();
} while (edad <= 0);

Solicita una edad y asegura que sea un número positivo.

### 🔹 Bucle for: Contador simple

```java
for (int i = 1; i <= 10; i++) {
    System.out.println("Número: " + i);
}

Genera las tablas de multiplicar del 1 al 3 usando bucles anidados.

---

## 📐 Validación de Entradas

Se realiza validación para asegurarse de que los valores ingresados (como edad, ancho y alto) sean positivos:
```java
while (ancho <= 0) {
    System.out.print("ERROR. Ingresá el ancho: ");
}

---

## 📦 Ejercicio Final: Dibujo con bucles anidados
Se solicita al usuario el ingreso del ancho y alto, y se imprime un rectángulo utilizando el carácter 'X'.
```java
for (int f = 1; f <= alto; f++) {
    for (int c = 1; c <= ancho; c++) {
        System.out.print('X');
    }
    System.out.println();
}

---

## ✅ Conclusión y aprendizaje

Este proyecto permitió repasar los conceptos fundamentales de estructuras repetitivas en Java, destacando:

Diferencias entre for, while y do-while.

Validación de entrada para evitar errores lógicos.

Aplicación de bucles anidados para resolver problemas visuales.

Importancia de una lógica clara y estructurada.
