# Practica 3 - GIT 
## Historial de Cambios - Ramas

![](https://victorhckinthefreeworld.files.wordpress.com/2016/09/git_commit_fire.png?w=1024)

El historial de cambios se visualiza con la orden:
````
$git log

ó 
$git log --oneline
````
Para las ramas:
````
$git branch : mostrar ramas existentes
$git branch [name] : crear rama [name]
$git branch -d [name] : borrar rama [name]
$git checkout [name] : moverme a rama [name]
$git merge [name] : fusionar la rama actual con [name] 
$git log --oneline
````

1. Entrad en el directorio de la práctica2 (practica2git) y a partir de ahí realizaremos esta práctica

2. Cread la carpeta "unidades". 

    <img src="https://i.ibb.co/frvHxb8/imagen-2023-11-21-122058663.png">

3. Cread 2 Ramas, Windows y Ubuntu.

    <img src="https://i.ibb.co/hfv2Ct1/imagen-2023-11-21-122312104.png">

4.  Situaos en Windows y dentro de ella cread un fichero llamado windows1.txt con el siguiente texto:
    ```
    Windows es el nombre de una familia de distribuciones de software para PC, teléfonos inteligentes, servidores y sistemas empotrados, desarrollados y vendidos por Microsoft y disponibles para múltiples arquitecturas, tales como x86, x86-64 y ARM.
    ```
    
    <img src="https://i.ibb.co/w65qnvK/imagen-2023-11-21-122936615.png"> 
    
5. Añadid los cambios realizados a la zona de preparado

    <img src="https://i.ibb.co/4NSTF9K/imagen-2023-11-21-123039330.png">

6. Haced un commit con el comentario "Añadido fichero windows1"

    <img src="https://i.ibb.co/Hgb48gL/imagen-2023-11-21-123441857.png">

7. Mostrad de nuevo el historial de cambios del repositorio + push.

    <img src="https://i.ibb.co/9bkwHFp/imagen-2023-11-21-123327052.png">
    
    <img src="https://i.ibb.co/VMd3LzK/imagen-2023-11-21-123914982.png">

8. Cambiad a la rama Ubuntu y dentro de ella cread un fichero llamado ubuntu1.txt con el siguiente texto:
    ```
    Ubuntu es una distribución GNU/Linux basada en Debian GNU/Linux, que incluye principalmente software libre y de código abierto. Puede utilizarse en ordenadores y servidores. Está orientado al usuario promedio, con un fuerte enfoque en la facilidad de uso y en mejorar la experiencia del usuario.
    ```
    
    <img src="https://i.ibb.co/WHN8bzy/imagen-2023-11-21-124118784.png"> 
    
    <img src="https://i.ibb.co/8dRBtv1/imagen-2023-11-21-124743568.png">
    
9. Añadid los cambios realizados a la zona de preparado

    <img src="https://i.ibb.co/TbmR0h2/imagen-2023-11-21-124202539.png">

10. Haced un commit con el comentario "Añadido fichero windows1"

    <img src="https://i.ibb.co/rs2VdFC/imagen-2023-11-21-124900687.png">

11. Mostrad de nuevo el historial de cambios del repositorio + push

    <img src="https://i.ibb.co/wJNc14H/imagen-2023-11-21-124952173.png">

12. Volved a Windows y cread el fichero "windows2.txt" dentro de "unidades" con el texto:
    ````
    Desde un punto de vista técnico, no son sistemas operativos, sino que contienen uno (tradicionalmente MS-DOS, o el más actual cuyo núcleo es Windows NT) junto con una amplia variedad de software; no obstante, es usual (aunque no necesariamente correcto) denominar al conjunto como sistema operativo en lugar de distribución. Microsoft introdujo un entorno operativo denominado Windows el 20 de noviembre de 1985 como un complemento para MS-DOS en respuesta al creciente interés en las interfaces gráficas de usuario (GUI).2​ Microsoft Windows llegó a dominar el mercado mundial de computadoras personales, con más del 90 % de la cuota de mercado, superando a Mac OS, que había sido introducido en 1984.
    
    ````
    
    <img src="https://i.ibb.co/pKTh9LJ/imagen-2023-11-21-125139610.png">

13. Añadid los cambios a la zona de preparado

    <img src="https://i.ibb.co/q97nQKq/imagen-2023-11-21-125237801.png">

14. Haced commit de cambios con el comentario "añadido windows2.txt"

    <img src="https://i.ibb.co/FDhsdyq/imagen-2023-11-21-125334449.png">

15. Mostrad las diferencias entre los dos últimos commits de esta rama.

    <img src="https://i.ibb.co/SKy7gwK/imagen-2023-11-21-125508904.png">
    
    <img src="https://i.ibb.co/3pYnFKm/imagen-2023-11-21-125934828.png">

16. Añadid al fichero windows2.txt las lineas:
    ```
    La versión más reciente de Windows es Windows 10 para equipos de escritorio, Windows Server 2019 para servidores y Windows 10 Mobile para dispositivos móviles. La primera versión en español fue Windows 2.1.
    ```
    
    <img src="https://i.ibb.co/tC8D4Jj/imagen-2023-11-21-125724119.png">
    
17. Añadid los cambios a la zona de preparado

    <img src="https://i.ibb.co/MSgz6yZ/imagen-2023-11-21-130154651.png">

18. Haced commit de los cambios con el comentario "Añadidas versiones a windows2.txt"

    <img src="https://i.ibb.co/NxkmJtn/imagen-2023-11-21-130250612.png">

19. Mostrad quien ha hecho cambios en el fichero windows2.txt

    <img src="https://i.ibb.co/VJcYWdq/imagen-2023-11-21-130345823.png">

20. Situaos en Master y haced merge para que quede todo en una única rama.

    <img src="https://i.ibb.co/QMp0w7T/imagen-2023-11-21-130556341.png">

21. Borrad las 2 ramas restantes

    <img src="https://i.ibb.co/93rzRny/imagen-2023-11-21-130806065.png">
    
    <img src="https://i.ibb.co/GpNTY6M/imagen-2023-11-21-130842627.png">
    
    <img src="https://i.ibb.co/94DBbY7/imagen-2023-11-21-130917595.png">

22. Descargad el programa SourceTree y añadid el repositorio con el que estais trabajando para ver el eje cronológico

    <img src="https://i.ibb.co/7j56X7R/imagen-2023-11-21-131127822.png">
    
----

<center><h2><a href="https://github.com/EdgarFenollar/Practica-2-Git">Enlace al repositorio</a></h2>