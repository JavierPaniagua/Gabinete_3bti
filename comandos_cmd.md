# Comandos Terminal Windows
- ls ; dir          ver directorios
- cd                ingresar a directorios
- cd ..             Volver hacia atras
- pwd               ver en el lugar en que me encuentro
- mkdir               crear una nueva carpeta
- code .            abril VsCode
- git log           sirve para ver el historial de confirmaciones (commits) de un repositorio


## COMANDOS BÁSICOS DE ARCHIVOS Y CARPETAS

| Comando        | Descripción                                 | Ejemplo                       |
| -------------- | ------------------------------------------- | ----------------------------- |
| `dir`          | Muestra el contenido del directorio actual  | `dir`                         |
| `cd`           | Cambia de directorio                        | `cd Documentos`               |
| `cd ..`        | Sube un nivel en el árbol de carpetas       | `cd ..`                       |
| `md` o `mkdir` | Crea una nueva carpeta                      | `mkdir Proyectos`             |
| `rd` o `rmdir` | Elimina una carpeta vacía                   | `rmdir Proyectos`             |
| `del`          | Elimina uno o varios archivos               | `del archivo.txt`             |
| `copy`         | Copia archivos                              | `copy origen.txt destino.txt` |
| `move`         | Mueve archivos o carpetas                   | `move archivo.txt Carpeta/`   |
| `ren`          | Cambia el nombre de un archivo o carpeta    | `ren viejo.txt nuevo.txt`     |
| `type`         | Muestra el contenido de un archivo de texto | `type archivo.txt`            |

## COMANDOS DEL SISTEMA

| Comando    | Descripción                                |
| ---------- | ------------------------------------------ |
| `cls`      | Limpia la pantalla del símbolo del sistema |
| `exit`     | Cierra la ventana de CMD                   |
| `echo`     | Muestra un mensaje en pantalla             |
| `tasklist` | Lista los procesos activos                 |
| `taskkill` | Finaliza un proceso por nombre o PID       |

## COMANDOS DE INFORMACIÓN DEL SISTEMA

| Comando      | Descripción                              |
| ------------ | ---------------------------------------- |
| `systeminfo` | Muestra detalles del sistema operativo   |
| `hostname`   | Muestra el nombre del equipo             |
| `ver`        | Muestra la versión del sistema operativo |
| `time`       | Muestra o cambia la hora del sistema     |
| `date`       | Muestra o cambia la fecha del sistema    |

## COMANDOS DE RED

| Comando    | Descripción                              |
| ---------- | ---------------------------------------- |
| `ipconfig` | Muestra la configuración de red          |
| `ping`     | Comprueba la conexión con otra máquina   |
| `netstat`  | Muestra estadísticas y conexiones de red |
| `tracert`  | Rastrea la ruta hasta una dirección IP   |
| `nslookup` | Consulta DNS                             |

## EJEMPLO PRÁCTICO: Crear una carpeta y archivo
- cd Desktop
- mkdir ClaseCMD
- cd ClaseCMD
- echo Hola mundo > mensaje.txt
- type mensaje.txt

