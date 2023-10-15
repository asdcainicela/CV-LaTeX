# CV-LaTeX
Repositorio que contiene una plantilla de currículum vitae en LaTeX, personalizada para su uso personal y un ejemplo de mi currículum vitae. Si deseas utilizarla para crear tu propio CV, siéntete libre de clonar el repositorio y modificarla según tus necesidades. ¡Contacta si necesitas ayuda!

## Usando Overleaf 

Descargue el zip y sube al overleaf, si no tienes una cuenta, ingresa a [Overleaf](https://es.overleaf.com/).

- Crear una en [Overleaf](https://es.overleaf.com/).
- Debes ir a tus [proyectos de Overleaf](https://es.overleaf.com/project).
- Clic en Nuevo proyecto
    - Subir Proyecto
      - Selec a .zip file
        - Seleccionar el .zip que descargaste o clonaste.

## Usando offLine
Puede revisar cualquier tutorial, debe clonar o descomprimir, luego ejecutas el 
```bash
main.tex
```
Debes instalar todos los paquetes necesario para la correcta compilación.

## Cómo Clonar este Repositorio

1. Clona este repositorio a tu máquina local para acceder a los códigos:

   ```bash
   git clone https://github.com/asdcainicela/CV-LaTeX.git
    ```
## Guía
1. Encontrarás un archivo llamado myCV-gbca.tex , es mi CV personal que está de ejemplo.
2. En el preámbulo de main.tex, hay un yourName, es donde debes escribir tu nombre, lo mismo para \myDegree. 
    ```bash
       \newcommand{\myName}{yourName}
        \newcommand{\myDegree}{Lo que estudio o estudié}
    ```
3. Si deseas incluir una foto, debes hacer en \perfil, debes guardar la imagen como perfil.png en
   - asset
        - img
              - perfil.png
    ```bash
       \newcommand{\perfil}{asset/img/perfil.png}
    ```
Además, en perfil debe escribir _true_ si desea subir su foto de perfil o _false_ cuando no lo requiera.
    ```bash
       \miTitulo{Descripción}{perfil}
    ```
4. En datos personales puede escribir lo que usted crea conveniente, pero respetando el siguiente orden,
    ```bash
    \datosPersonales{opción1}{opción2}{opción3}
    ```
    si no tiene la opción 3 nada que escribir, debe dejar en blanco entre las llaves ```bash {}```
5. En el archivo main.tex explica está explicado y comentado la función de cada comando.
