#### 1. Cuántas secuencias tiene el archivo fasta.

#### 2. El archivo fasta tiene una secuencia de nucleótidos.
   * Usando comandos (de qué manera lo resolverías) encuentra cuál es e imprime el identificador y la secuencia.
   * Menciona a qué gen y organismo pertenece la secuencia. 
   
#### 3. El archivo contiene secuencias de aminoácidos de 3 organismos diferentes, de qué organismos se trata.  

#### 4. Para responder la siguiente actividad usa esta condición:  filtrar solo aquellos identificadores que dentro de su secuencia tengan la siguiente expresion regular: <font color = red>'C.{2,4}C.{3}[LIVMFYWC].{8}H.{3,5}H'</font>. Esta expresión regular corresponde a un dominio Zinc finger C2H2-type que se encuentra en proteínas de unión a ADN (https://prosite.expasy.org/PS00028).

   > **4.1 Siguiendo el ejemplo de la figura 1 guarda en una lista la siguiente información:**  
   >> ▢ Identificador localizado entre los 2 pipe (como lo vimos en clase): ejemplo A0A364LTJ7  
   >> ▢ La longitud de la proteína.  
   >> ▢ El organismo (género y especie) al que pertenece la secuencia.  
   >> ▢ Número taxonómico.   
   >> ▢ Nombre de la proteína.  
   >> ▢ Secuencia e la proteína.
#### <font color = red>Nota: para este ejercicio revisa el ejemplo de la [figura 1](https://raw.githubusercontent.com/eduardo1011/PyLerm/main/lista_para_dataframe.png), esta actividad se realizó en la clase 5.</font> 


#### 5. Usando la lista del punto anterior crea un dataframe y resuelve las siguientes cuestiones:
> ▤ Qué organismos presentan el dominio Zinc finger C2H2-type dentro de sus secuencias.  
> ▤ De los organismos ¿cuál no presenta el dominio Zinc finger C2H2-type? argumenta tu respuesta.  
> ▤ A qué organismo pertenece la proteína llamada brlA (busca solo dentro del dataframe).   
> ▤ Cuantifica el número de proteínas que contienen el dominio Zinc finger C2H2-type por cada organismo.  