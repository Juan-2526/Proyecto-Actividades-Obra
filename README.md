# Proyecto Actividades de Obra

## Descripción
Este proyecto consiste en llevar un control básico del estados de actividades de una obra de construccón de vivienda usando Git y GitHub como herramienta de gestión de versiones..
El archivo base tiene como nombre actividades.txt, en el cual se registran las diferentes actividades de construcción y su estado para el control, permitiendo evidenciar cambios, commits, ramificaciones y fusiones de ramas dentreo del repositorio.

## Contenido del archivo

El archivo actividades.txt, contiene actividades principales de una obra de construcción de vivienda, tales como:

- Descapote.
- Cimentación.
- Estructura Piso 1.
- Mampostería.
- Instalaciones eléctricas.

Cada actividad cuenta con un estado de avance, iddentificado por:

- Pendiente.
- En proceso.
- Cumplido.

Esto permite llevar un registro simple y ordenado de un avance de obra.

## Clonar repositorio

Para realizar la clonación del repositorio en un equipo local, se debe utilizar el siguient comando en Git:

git clone https://github.com/Juan-2526/Proyecto-Actividades-Obra.git

## Contribución en el proyecto

Para realizar modificaciones en el proyecto, se recomienda seguir los siguientes pasos:
1. Crear una nueva rama.
   Con el comando git checkout -b nombre-de-rama.
   
2. Realizar modificaciones
   Actualizar el archivo actividades.txt , agregando nuevas actividades y/o modificando estado de las existentes.

3. Guardar los cambios
   Usar los siguientes comandos : git add, git commit -m "describir cambio realizado", git Push.

4. Fusionar los cambios.
   Una vez validados los cambios , se puede regresar a la rama principal y realizar la fusión mediante la ejecución de los siguientes comandos:
   
   git checkout main
   git merge nombre-nueva-rama

   Esto permite mantener el trabajo organizado y controlado dentro del proyecto.

## Como ejecutar el proyecto

Este proyecto no requiere instalación, compilación ni ejecución de programas especiales, ya que se basa en el uso de un archivo de texto.
Unicamente se debe abrir el archivo.txt desde Visual Studio Code o cualquier editor de texto para visualizar, consultar o actualizar actividades registradas.

## Herramientas usadas

- Git
- GitHub
- Visual Studio Code
- Archivo de texto (txt)




   
