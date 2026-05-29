# Velora – Red Social para Ciclistas Aficionados

Proyecto final de **FH1037 – Pensamiento Computacional**, 2026-1

| | |
|---|---|
| **Estudiante** | Juan José Bedoya |
| **Profesor** | Edwin Montoya – emontoya@eafit.edu.co |
| **Fecha de entrega** | 29 de mayo de 2026 |

---

## Descripción

Aplicación en consola desarrollada en Java que simula una red social básica para ciclistas aficionados, inspirada en servicios como Strava. Permite registrar perfiles, agregar rutas favoritas, conectar amigos y consultar estadísticas de rendimiento.

---

## Funcionalidades

- Registrar usuarios con nombre, edad, tipo de ciclismo y ciudad
- Agregar rutas con tipo de terreno, distancia, dificultad y tiempo
- Conectar ciclistas como amigos (relación bidireccional)
- Visualizar datos filtrando por tipo de ciclismo
- Buscar ciclistas por nombre, ciudad o tipo de ciclismo
- Ordenar usuarios por nombre, edad o tipo de ciclismo (algoritmo burbuja)
- Leaderboard de rutas ordenado por tiempo (algoritmo burbuja)
- Estadísticas por usuario: km totales, tiempo, velocidad promedio y dificultad
- Persistencia de datos en archivos CSV (carga automática al abrir, guardado al salir)

---

## Estructura del proyecto

```
Velora/
├── Main.java        # Lógica principal, menú e interfaz de consola
├── Usuario.java     # Clase que modela un ciclista registrado
├── Ruta.java        # Clase que modela una ruta
└── README.md
```

---

## Cómo ejecutar

**Requisitos:** Java JDK 8 o superior

```bash
# 1. Compilar
javac Main.java Usuario.java Ruta.java

# 2. Ejecutar
java Main
```

---

## Menú principal

```
==================================
 RED SOCIAL CICLISTAS - VELORA
==================================
1. Registrar nuevo usuario
2. Añadir ruta a usuario
3. Conectar con otro ciclista
4. Visualizar datos
5. Buscar ciclista
6. Listar ciclistas
7. Lista rutas (leaderboard)
8. Estadísticas de usuario
9. Guardar datos
0. Salir
```

---

## Herramientas utilizadas

- Lenguaje: **Java**
- IDE: **Visual Studio Code**
- Se utilizó **ChatGPT (OpenAI)** como herramienta de apoyo en partes del desarrollo (estructura del programa, dudas de sintaxis y persistencia CSV). Todo el código fue revisado y comprendido por el estudiante.
