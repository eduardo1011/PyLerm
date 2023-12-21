
# Examen Parcial 1 (21/12/2023)

### **Entrega**
#### **Desarrolla el examen en un notebook.**
#### **Cargar el examen en la siguiente liga: **
#### **La hora y fecha límite para entregar: hasta las 11:00 PM del 29 de diciembre de 2023.**

#### Aplicación de conocimientos:  
* Creación y manejo de listas.
* Búsqueda de patrones en listas.
* Uso de bucle `for`.
* Uso de condicionales.
* Uso de operadores booleanos.
* Uso de texto enriquecido (Markdown).
* Uso de la función re y expresiones regulares.
* Uso del módulo pandas y manejo de dataframes.

#### Se evaluará la organización del notebook y las salidas que respondan a cada una de las preguntas de la tarea (antes de enviar la tarea revisen que todos los comandos corran adecuadamente).

**Nota: para resolver estos ejercicios toma en cuenta lo que se ha visto hasta la clase 6.**


>
>---
>---
>

### Para esta actividad se usará el archivo alojado en la siguiente URL:
```
https://raw.githubusercontent.com/eduardo1011/PyLerm/main/problema.fasta
```

### Para abrir el archivo fasta usa el siguiente comando, guarda la salida en una variable y con esta resuelve los ejercicios.
```
# este comando abre el archivo fasta y devuelve un diccionario
def open_file(file = ''):
    fas = {}
    with open(file) as fq:
        for line in fq:
            line = line.rstrip()
            if '>' in line:
                header = line
                s = ''
            else:
                s += line
            fas[header] =  s
    return fas
```

```
# este comando define la variable fasta y en ella guarda todas las secuencias, y  con esta variable fasta ya puedes trabajar
fasta = open_file(file = 'problema.fasta')
```


#### 1. Cuántas secuencias contiene el archivo problema.fasta.

#### 2. El archivo problema.fasta contiene solo una secuencia de nucleótidos.
   * Usando comandos (de qué manera lo resolverías) encuentra esa secuencia e imprímela junto con su identificador.
   * Investiga y menciona de qué gen se trata y a qué organismo pertenece. 
   
#### 3. El archivo contiene secuencias de aminoácidos de 3 organismos diferentes, de qué organismos se trata.  

#### 4. Para responder la siguiente actividad usa esta condición:  filtrar solo aquellos identificadores que dentro de su secuencia tengan la siguiente expresion regular:
```
'C.{2,4}C.{3}[LIVMFYWC].{8}H.{3,5}H'
```
**Esta expresión regular corresponde a un dominio Zinc finger C2H2-type que se encuentra en proteínas de unión a ADN (https://prosite.expasy.org/PS00028).**

   > **4.1 Siguiendo el ejemplo de la [figura 1](https://raw.githubusercontent.com/eduardo1011/PyLerm/main/lista_para_dataframe.png) guarda en una lista la siguiente información:**  
   >> ▢ Identificador localizado entre los 2 pipe (|): ejemplo A0A364LTJ7 (como lo vimos en clase).  
   >> ▢ La longitud de la proteína.  
   >> ▢ El organismo (género y especie) al que pertenece la secuencia.  
   >> ▢ Número taxonómico.   
   >> ▢ Nombre de la proteína.  
   >> ▢ Secuencia de la proteína.
#### Nota: para este ejercicio revisa el ejemplo de la [figura 1](https://raw.githubusercontent.com/eduardo1011/PyLerm/main/lista_para_dataframe.png), esta actividad se realizó en la clase 5.


#### 5. Usando la lista generada en el punto 4.1 crea un dataframe y resuelve las siguientes cuestiones:
> ▤ Qué organismos presentan el dominio Zinc finger C2H2-type dentro de sus secuencias.  
> ▤ De los organismos ¿cuál no presenta el dominio Zinc finger C2H2-type? argumenta tu respuesta.  
> ▤ A qué organismo/s pertenece la proteína llamada brlA (busca solo dentro del dataframe).   
> ▤ Cuantifica el número de proteínas que contienen el dominio Zinc finger C2H2-type por cada organismo.  
