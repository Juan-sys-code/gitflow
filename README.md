# Proyecto Git Flow: gitflow-php-[tu_nombre]

## Paso 1: Creación del repositorio y configuración inicial
1. Se creó un nuevo repositorio en GitHub con el nombre **gitflow-php-[tu_nombre]**.
2. Se clonó el repositorio localmente usando `git clone`.
3. Se inicializó Git Flow con la estructura por defecto (main y develop).
4. Se creó y subió la rama `develop` si no existía previamente.

### Captura del historial de ramas:
(Ejecuta y pega la captura de pantalla del siguiente comando)
```bash
git branch -a


## Paso 2: Creación de un archivo PHP
1. Se creó una nueva funcionalidad en Git Flow con el nombre `feature/crear-mi-archivo`.
2. Dentro de la carpeta `alumnos/`, se creó el archivo PHP `tu_nombre.php` con el siguiente contenido:
   ```php
   <?php
   // Archivo: alumnos/tu_nombre.php
   echo "Hola, soy [Tu Nombre] y estoy aprendiendo Git Flow!";
   ?>
## Paso 3: Modificación de un archivo existente
1. Se creó una nueva funcionalidad en Git Flow llamada `feature/modificar-index`.
2. Se agregó la línea de código `include "alumnos/tu_nombre.php";` en el archivo `index.php`.
3. Se confirmó y subió la funcionalidad a la rama `develop`.

### Captura de git diff:
(Ejecuta y pega la captura de pantalla del siguiente comando antes de confirmar los cambios)
```bash
git diff


## Paso 4: Resolución de conflictos
1. Se intentó fusionar la rama `feature/otra-funcionalidad` en `develop`.
2. Se presentó un conflicto en el archivo `index.php`, el cual fue resuelto manualmente.
3. Se confirmó y subió la resolución del conflicto.

### Capturas:
- Captura de `git status` mostrando el conflicto.
- Captura del archivo `index.php` después de la resolución.
