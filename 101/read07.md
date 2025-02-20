### 1. ¿Qué es el control de versiones?

El control de versiones es un sistema que permite realizar un seguimiento de los cambios en los archivos y directorios a lo largo del tiempo. Facilita la colaboración en proyectos, manteniendo un historial de modificaciones, permitiendo revertir cambios, y asegurando que varias personas puedan trabajar en un proyecto sin sobrescribir el trabajo de los demás.

### 2. ¿Qué es “clone” en Git?

El comando `git clone` se usa para crear una copia local de un repositorio remoto. Esto descarga todo el historial de versiones del repositorio, permitiendo trabajar con el código en tu máquina de forma independiente y realizar cambios antes de sincronizarlos de nuevo con el repositorio remoto.

### 3. ¿Cuál es el comando para agregar los archivos modificados a la zona de preparación?

El comando para agregar archivos modificados a la zona de preparación es:
```bash
git add <nombre-del-archivo>
```
Para agregar todos los archivos modificados:
```bash
git add .
```

### 4. ¿Cuál es el comando para enviar la captura de los archivos modificados a Github?

El comando para enviar los cambios (captura) a GitHub es:
```bash
git push
```
Este comando sube los cambios de la rama local al repositorio remoto en GitHub. Si es la primera vez, puede que necesites especificar el nombre del remoto y la rama, por ejemplo:
```bash
git push origin main
```