# ProgramacionFuncionalJupyter
Proyecto 02 Programación Funcional con el Kernel de iRacket en Jupyter

# Equipo 07

**Integrantes:**
- CHÁVEZ SOSA JOSÉ RAMSÉS
- CIAU MARTIN OSMAR RUBÉN

## Descripción

El proyecto se basa en 10 ejercicios que se resolvieron utilizando Racket, esto en forma de kernel de Jupyter. Los ejercicios se resolvieron utilizando recursividad, dichos programas se encuentran en la carpeta con nombre de “ProyectoTLP”, se encuentran numerados del 1 al 10 correspondiendo al número de ejercicio, en cada documento se encuentra el enunciado del problema, una breve explicación de las entradas que se reciben en las funciones y la salida esperada, además de una explicación de cómo funciona el algoritmo, también se presenta el código con un ejemplo de funcionamiento.

## Instalación y configuración del notebook

Para instalar notebook es necesario tener instalado Python, ya que para la instalación se usará pip Install.

Para comenzar debemos usar la terminal, en nuestro caso utilizamos cmd de Windows e ingresar el siguiente comando:

```
py -m pip install jupyterlab
```

Después de instalar jupyterlab debemos instalar el karnel de iRacket, para esto utilizaremos los siguientes comandos, es importante mencionar que ya debremos tener instalado racket dese su web oficial y agregar al path ‘raco’ que es lo que se utiliza para los comandos, este generalmente se encuentra en la carpeta raíz de Racket.

Los comandos por ingresar son los siguientes:

Primero hay que instalar el kernel llamado iRacket con:

```
raco pkg install iracket
```

Después hay que registrar el kernel en jupyter con el siguiente comando:

```
raco iracket install
```

Para terminar y asegurarnos de que funcionó lo que hicimos, en la terminal ingresamos:

```
jupyter lab
```

Debería abrirse una ventana en el navegador que nos debería mostrar en los kernel el logo de racket, si es así estamos listos para trabajar.

## Descripción de la ejecución de cada uno de los problemas

Dentro de cada archivo se muestra cómo funciona y su respectiva ejecución.
