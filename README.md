# Sistema Experto | Bacteria Counter 
## ¿Qué es?
Bacteria Counter es un sistema experto capaz de emular el conocimiento de un microbiólogo para el conteo de bacterias y su posterior clasificación. Está desarrollado con jFuzzyLogic la cual es una librería de Java que sirve para crear modelos de lógica difusa. 
Toma tres variables de entrada las cueles son: 
- Tamaño
- Forma
- Número de unidades

Una vez que estas son combinadas y procesadas arroja como resultado dos variables de salida: 
- Contables 
- No contables 

## ¿Cómo usuarlo?
1. Descargar jFuzzyLogic de su sitio. 
2. Descargar jFuzzyLogic.jar
3. Crear un archivo en editor de texto preferido el cual al guardarlo tenga la extensión .fcl, por ejemplo "bacteria.fcl". 
4. Para correr el presente primero se tiene que abir el símbolo del sistema.
5. Posteriormente ingresar a la carpeta donde se almacenó.
6. Colocar el comando ```java –jar jFuzzyLogic.jar bacteria.fcl```

## Ejemplo 
Para ingresar variables realiza los siguientes pasos:
1. Ingresa a la carpeta donde se almacenó desde el símbolo del sistema.
2.  Colocar el comando ```java –jar jFuzzyLogic.jar -e bacteria.fcl 10 90 80``` . Donde: 
  - "-e" es para especificar variables de entrada.
  - "10" corresponde a la variada de entrada forma. 
  - "90" variable de entrada tamano.
  - "80" variable de entrada unidades.
3. jFuzzyLogic calculará y mostrará las variables de salida desfuzzizadas así como las gráficas correspondientes.  
