# Laboratorio - Flujo Git colaborativo: José David Quero Sánchez

# Tarea 1 — Fork y configuración inicial
**fork**: Es una copia de un repositorio que hago en mi cuenta de GitHub. Es la forma de colaborar en proyectos OpenSource.
**upstream**: Es un remoto que, por convención, se llama upstream y que es un remote que apunta al repositorio raíz del que hemos hecho fork.

![Captura 1](capturas/captura1.PNG)
![Captura 2](capturas/captura2.PNG)

# Tarea 2 — Feature branch A: añadir la Opción 5
Se parte de **dev** porque es la rama para desarrollo e integración, mientras que **main** es la rama de producción.
![Captura 3](capturas/captura3.PNG)

# Tarea 3 — Feature branch B: añadir la Opción 6 (aquí está el conflicto)
Un conflicto se produce cuando dos personas modifican el mismo fichero a la vez e intentan fusionarlo, de forma que Git se encuentra con dos versiones diferentes de la misma línea y no sabe cuál es la correcta.

En nuestro caso, tanto la rama **feature/opcion-5** como la rama **feature/opcion-6** parten de la rama **dev** y modifican el campo **description** de la **Opción 3** del fichero **app.tsx**. Cuando se intenten fusionar ambas ramas a **dev** se producirá el conflicto y deberemos decidir cuál de los dos cambios es el correcto.
