# Analizador FASTA Proteico - Script 1

## Descripción

El Script 1 permite analizar un único archivo de proteínas en formato FASTA (.faa o .fasta).

Durante la ejecución, el programa recorre todas las proteínas presentes en el archivo y genera un reporte con estadísticas relacionadas con la longitud de las secuencias y la
frecuencia de un aminoácido de interés.

## Aplicaciones

Este script puede utilizarse para:

- Obtener estadísticas básicas de un proteoma.
- Comparar la longitud de las proteínas de un organismo.
- Identificar proteínas extremadamente largas o cortas.
- Calcular la frecuencia de un aminoácido específico dentro del conjunto de proteínas.


## Funcionalidades

El script realiza las siguientes tareas:

- Lee un archivo FASTA de proteínas.
- Cuenta el número total de proteínas.
- Calcula cuántas proteínas poseen una longitud mayor o igual al valor definido en la configuración.
- Identifica la proteína más larga.
- Identifica la proteína más corta.
- Calcula la frecuencia total del aminoácido de interés.
- Muestra un reporte final en la terminal.

 
 ## Estructura del script

 Proyecto/
  analizador_proteinas.sh
   - secuencias
    - archivo.faa


## Ejecución

otorgar permisos al script:
chmod +x analizador_proteinas.sh

Ejecutar el script indicando el archivo FASTA:
/analizador_proteinas.sh secuencias/archivo.faa

## Resultados del script

El programa analiza un archivo con formato .faa y genera un reporte con los siguientes datos:
- Nombre del archivo analizado.
- Número total de proteínas.
- Proteínas con longitud ≥100 aminoácidos.
- Proteína más larga.
- Proteína más corta.
- Frecuencia total del aminoácido


## Ejemplo de salida del script en la terminal

=========================================
REPORTE DEL ANALISIS COMPLETO DEL ARCHIVO
=========================================

Archivo: archivo.faa

Proteinas encontradas: 124

Proteinas con longitud >=100 aa:
98

Proteina mas larga:
DNA polymerase (1325 aa)

Proteina mas corta:
Ribosomal protein L36 (44 aa)

Frecuencia total de K:
5834

