# Proyecto-Integrador-de-Sistemas-Operativos-Rocha-Coronado-Carlos-Julian
Simulador de Gestión de Memoria (RAM y Swap)
Este proyecto consiste en un simulador de gestor de memoria para Sistemas Operativos, implementando técnicas de paginación, memoria virtual (Swapping) y traducción de direcciones.

Integrantes del Equipo

-Terán Ramírez Leonardo Alonso

-Rocha Coronado Carlos Julián

-Argüelles Obregón René

-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

Descripción del Proyecto

Este proyecto consiste en un simulador de gestión de memoria creado en Python 3. Su objetivo es mostrar cómo un sistema operativo maneja la memoria virtual, incluyendo la traducción de direcciones, el uso de RAM, el área de Swap y el reemplazo de páginas.

El simulador utiliza estructuras simples de Python para representar sus componentes: diccionarios para las tablas de páginas, listas para la memoria RAM y Swap, y colas (deque) para administrar procesos y el historial de marcos. También incluye una TLB, implementada con OrderedDict, que simula una pequeña caché de traducción.

Cuando la memoria se llena, el sistema aplica el algoritmo de reemplazo FIFO, que libera el marco más antiguo y lo envía a Swap para cargar una nueva página.

En conjunto, el simulador permite comprender de manera sencilla cómo funciona la administración de memoria en un sistema operativo real.
