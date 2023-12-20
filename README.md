# PyLerm
Curso

## Análisis de datos e información biológica con Python

### Temario

[Temario](https://github.com/eduardo1011/PyLerm/blob/main/UNIDAD%20DE%20ENSE%C3%91ANZA%20UEA%20Optativa.pdf)  

### Clases grabadas

Contraseña: `pylerm2023`

#### [Clase 2: 22-11-2023](https://1drv.ms/v/s!ArGs92xOZGDEkkf1DeY1avHQecz2?e=7okcKK)


#### [Clase 3: 29-11-2023](https://1drv.ms/v/s!ArGs92xOZGDEkkg2yE70cSIR4UTk?e=yIqxPI)


#### [Clase 4: 06-12-2023](https://1drv.ms/v/s!ArGs92xOZGDEkkmc0qeqEKrHupZ_?e=wGzzJG)


#### [Clase 5: 13-12-2023](https://1drv.ms/v/s!ArGs92xOZGDEkkqYDMAp_yNWxCkE?e=dxTxlm)
>---------------------
>---------------------

## Tarea 1  

(06 de diciembre de 2023)

### **Entrega**
#### **Desarrolla la tarea en un notebook.**
#### **Cargar la tarea en la siguiente liga: https://forms.gle/L8n8fC5ERK2sDLQ49**
#### **La hora y fecha límite para entregar: hasta las 11:00 PM del 12 de diciembre de 2023.**

#### Aplicación de conocimientos:  
* Creación y manejo de listas.
* Búsqueda de patrones en listas.
* Uso de bucle `for`.
* Uso de condicionales.
* Uso de operadores booleanos.
* Uso de texto enriquecido (Markdown).

#### Se evaluará la organización del notebook y las salidas que respondan a cada una de las preguntas de la tarea (antes de enviar la tarea revisen que todos los comandos corran adecuadamente).

**Nota: para resolver estos ejercicios toma en cuenta lo que se ha visto hasta la clase 4.**

A patir de la lista de organismos disponibles en la base de datos [KEGG](https://www.kegg.jp/kegg/catalog/org_list.html):

1. Cuántas y cúales especies corresponden al género *Escherichia*.
2. Cuántas corresponden a *Escherichia coli*.
3. Qué otras especies se encuentran además de *E. coli*.
4. Cuántas y cúales especies corresponden al género *Klebsiella*.
5. Cuántas corresponden a *Klebsiella pneumoniae*.

A partir de la información contenida en la siguiente URL (https://rest.kegg.jp/list/T00007):

6. Cuántas filas contienen la etiqueta ncRNA (non-coding RNA).
7. Cuántas filas contienen la etiqueta tRNA (transfer RNA).
8. Cuántas filas contienen la etiqueta CDS (coding sequence).

>---------------------
>---------------------



sec = ['caagggatctatgatagaccac','tatgccctcgtctatacacctaggcgc','taagcgcatatctatcgcaaatccagtt',
              'gtcttatgcctgtgtcaggatctacttcct','aaattagttttctgtgtttagagcacct','ggcctcacatgagtctacagacct',
              'agtacccccatttgtcaagcg','ttaggggtatttacacagcccgcgtac','attggctcagaaccggagctatcaaggact',
              'ttaccgtactcgcctca','ggtgaactccccctagtattgtgg','ttgctctggcggatttcttcaggc',
              'ccagttataactcctgagtattct','gtcaatttgaatggggtttgac','tactccggtgtgatccattatggagat',
              'acggtaaaacgatggacgttgtccca','ggcctcattctccttcccataa','gtacatggttctccccgcgatcat',
              'ccatcgacaatgagctaaacctg','gctatgctgggtcctaccggcaacc','gcgtaactaatgagcatcctat',
              'agagtaaaggtaatgggtggttat','ctaggtatcgactgtcgaataatccgtcc','catctgtatccc',
              'cttgcccgtctacatggcctaggggca','tgctaaacggccacatcccaagaccctg','cccgaggcgacagttcatcgcccatgacg',
              'acgcttgaccgtcagtgtaagtccg','gaatctcaaaacgcataatgccaata','aatgcgccagtgtaaaagtattgcggat',
              'cgggagacaccttatgtcgcaagatct','ggaaccacatccataacacacgtctc','cacacactctttatcata',
              'tacgcgtgct','cactttcgatag','gtgtggggttttggaacttcagaataga',
              'gtggccagagcgcactatctagt','gccccccgattacgatacacgcctatgct','tcggtcacccatcacgtaaattggagtaat',
              'gggttcgtcccccagttccctcttccc','ttgatggctaggtctgtcgatttaag','gtcttggctgtttccttggagtccgtc',
              'aataggcgcgatgttgtgtgtcaat','acacgcaagccacgtcgtttgta','tacgtaggctgggctgtgcgattgcgtt',
              'agcagtgggatttatagttattta','cgaaagcgaggccatcactggtgaa','gctatcatctggctacaaaaaatagacct',
              'ttccccgtaggagaaccaagagaa','tagcgtgcgttctctactataaga']

>---------------------
>---------------------

identificadores = ['tr|E0SC31|E0SC31_DICD3 Outer membrane exporter of proteases OS=Dickeya dadantii (strain 3937) OX=198628 GN=prtF PE=3 SV=1',
'sp|P23598|PRTF_DICCH Proteases secretion protein PrtF OS=Dickeya chrysanthemi OX=556 GN=prtF PE=3 SV=1',
'tr|A0A0A1HT80|A0A0A1HT80_9PSED ABC-type protease exporter, outer membrane component PrtF/AprF OS=Pseudomonas sp. SHC52 OX=984195 GN=BN844_0269 PE=3 SV=1',
'tr|A0A0C2IEA9|A0A0C2IEA9_9PSED ABC-type protease exporter, outer membrane component PrtF/AprF OS=Pseudomonas batumici OX=226910 GN=UCMB321_2798 PE=3 SV=1',
'tr|A0A0H3BX48|A0A0H3BX48_STRPZ Fibronectin binding protein OS=Streptococcus pyogenes serotype M49 (strain NZ131) OX=471876 GN=prtF PE=1 SV=1',
'tr|A0A0P9LC31|A0A0P9LC31_PSEA0 ABC-type protease exporter, outer membrane component PrtF/AprF OS=Pseudomonas amygdali pv. ciccaronei OX=264452 GN=ALO78_01561 PE=3 SV=1',
'tr|A0A0P9MT55|A0A0P9MT55_9PSED ABC-type protease exporter, outer membrane component PrtF/AprF OS=Pseudomonas caricapapayae OX=46678 GN=ALQ84_02418 PE=3 SV=1',
'tr|A0A0P9Q2D9|A0A0P9Q2D9_9PSED ABC transporter, permease protein OS=Pseudomonas syringae pv. delphinii OX=192088 GN=ALQ08_100846 PE=3 SV=1',
'tr|A0A0P9RGY3|A0A0P9RGY3_9PSED ABC-type protease exporter, outer membrane component PrtF/AprF OS=Pseudomonas ficuserectae OX=53410 GN=ALO69_100221 PE=3 SV=1',
'tr|A0A0P9SV80|A0A0P9SV80_PSESG ABC transporter permease OS=Pseudomonas savastanoi pv. glycinea OX=318 GN=ALO37_01686 PE=3 SV=1'] 

