# Informe Nº2 #
## Constanza Aranda ##

**Parte 1: Colectar genes homólogos**

1.¿Qué función cumple el gen SRY?

**R: Esta proteína es el factor determinante de los testículos (TDF), que inicia la determinación del sexo masculino. Las mutaciones en este gen dan lugar a mujeres XY con disgenesia gonadal (síndrome de Swyer); la translocación de parte del cromosoma Y que contiene este gen al cromosoma X causa el síndrome XX masculino.** [https://www.ncbi.nlm.nih.gov/gene/6736](https://www.ncbi.nlm.nih.gov/gene/6736) 

2.¿Cuántos genes ortólogos están anotados en esa base de datos?
 
**R: 29 organismos tienen ortólogos con gen humano SRY.**
[https://www.ncbi.nlm.nih.gov/gene/?Term=ortholog_gene_6736[group]](https://www.ncbi.nlm.nih.gov/gene/?Term=ortholog_gene_6736[group])
 
**Parte 2: Alineamiento múltiple**

3.¿Qué es el EMBL-EBI?

**R: Instituto Europeo de Bioinformática (EMBL-EBI) es un centro de investigación en bioinformática que brinda datos biológicos públicos del mundo a través de una gama de servicios y herramientas, realiza investigaciones básicas y proporcionan capacitación profesional en bioinformática.** [https://www.ebi.ac.uk/about](https://www.ebi.ac.uk/about)  

4.¿Cuál es el programa que ellos ofrecen que funciona mejor para secuencias de proteínas?

**R: MUSCLE es el programa que ofrece una función mejor para secuencias de proteínas** [https://www.ebi.ac.uk/Tools/msa/](https://www.ebi.ac.uk/Tools/msa/)

5.¿Qué otros tipo de herramientas ofrece EMBL-EBI?

**R:
- Nueva herramienta de MSA que utiliza árboles de guía sembrados y técnicas de perfil de perfil HMM para generar alineaciones. Adecuado para alineaciones medianas y grandes.
- Herramienta MSA muy rápida que se concentra en las regiones locales. Adecuado para grandes alineaciones.
- Herramienta MSA que usa transformadas rápidas de Fourier. Adecuado para alineaciones medianas y grandes.
- Transforme un resultado de Búsqueda de similitud de secuencia en una Alineación de secuencia múltiple o vuelva a formatear una Alineación de secuencia múltiple mediante el programa MView.
- Herramienta MSA basada en consistencia que intenta mitigar los riesgos de los métodos de alineación progresiva. Adecuado para pequeñas alineaciones.
- El EBI tiene un nuevo programa de alineamiento de secuencia múltiple que tiene en cuenta la filogenia y hace uso de información evolutiva para ayudar a colocar inserciones y eliminaciones.** [https://www.ebi.ac.uk/Tools/msa/](https://www.ebi.ac.uk/Tools/msa/)


6.¿Cuál es el costo de abrir un gap?

**R: El costo del gap es de 1,53.** [https://www.ebi.ac.uk/Tools/msa/mafft/](https://www.ebi.ac.uk/Tools/msa/mafft/)

7.¿Cuál es el costo de extender un gap?

**R: El costo de extender un gen es de 0,123.** [https://www.ebi.ac.uk/Tools/msa/mafft/](https://www.ebi.ac.uk/Tools/msa/mafft/)


8.¿Cuál es la longitud total del alineamiento?

**R: La longitud de alineamiento es de 1910.**  ![](https://github.com/ConstanzaArandaG/Imagen-/blob/master/pantallazo.png?raw=true)


9.¿Cuál es la especie cuyo gen SRY está más relacionado con el gen SRY de humanos?

**R: La especie cuyo gen SRY esta mas relacionado con el gen SRY de la especie Humana es *Piliocolobus tephrosceles* y esto lo sabemos porque tiene menos divisiones en el arbol filogenetico.** [https://www.ebi.ac.uk/Tools/services/web/toolresult.ebi?jobId=mafft-I20180816-161729-0604-2555610-p1m&analysis=phylotree](https://www.ebi.ac.uk/Tools/services/web/toolresult.ebi?jobId=mafft-I20180816-161729-0604-2555610-p1m&analysis=phylotree)

10.¿Cuál es el más lejano?

**R: El gen mas lejano es el de la especie *Desmodus rotundus*.** [https://www.ebi.ac.uk/Tools/services/web/toolresult.ebi?jobId=mafft-I20180816-163935-0140-40818466-p2m&analysis=phylotree](https://www.ebi.ac.uk/Tools/services/web/toolresult.ebi?jobId=mafft-I20180816-163935-0140-40818466-p2m&analysis=phylotree)

11.¿Cuál es la especie cuyo gen SRY es más cercana a la del burro?

**R: La especie cuyo gen esta mas cercano al del burro es *Equus przewalskii*.** [https://www.ebi.ac.uk/Tools/services/web/toolresult.ebi?jobId=mafft-I20180816-163935-0140-40818466-p2m&analysis=phylotree](https://www.ebi.ac.uk/Tools/services/web/toolresult.ebi?jobId=mafft-I20180816-163935-0140-40818466-p2m&analysis=phylotree)


12.¿Cómo esperas que sea el alineamiento si el costo de abrir un gap aumenta? ¿Y si disminuye?
 
**R: Al aumentar el costo de abrir gaps el alineamiento disminuye y si disminuye el costo de abrir gaps el alineamineto aumenta.** 

13.¿Cómo esperas que sea el alineamiento si el costo de extender un gap aumenta? ¿Y si disminuye?

**R: Al aumentar el costo de extender gaps el alinemaiento disminuye y si dismunuye el costo de extender gaps el alineamiento aumentaria.**


14.¿Cuál fue el efecto de aumentar el costo de abrir un gap en la longitud total del alineamiento?

**R: Al aunmentar el costo de gap de 1,53 a 2,0 la longitud del alineamiento dismunuyo a 1895.** ![](https://github.com/ConstanzaArandaG/Imagen-/blob/master/pregunta%2014.png?raw=true)


15.Prueba lo mismo, pero esta vez disminuyendo al mínimo el costo de extender un gap. Describe cómo cambia el alineamiento.

**R: Al disminuir el costo minimo de externder un gap que fue de 0,0 se puede ver que la longitud del alineamiento aumento a 1989.** ![](https://github.com/ConstanzaArandaG/Imagen-/blob/master/pregunta%2015.png?raw=true)

**Parte 3: Diseño de partidores**


16.Agrega a tu informe una lista de los "LEFT PRIMER" y "RIGHT PRIMER" que obtuviste usando Primer3.

**R: Left primer: AGAGTGAAGCGACCCATGAA-TTACAGGCCATGCACAGAGA-GGATAGAGTGAAGCGACCCA-AGATGCTGCCGAAGAATTGC-CGAAGATGCTGCCGAAGAAT. 
 Righ primer: TCTCTGTGCATGGCCTGTAA-CTTGAGTGTGTGGCTTTCGT-TTTCTCTCTGTGCATGGCCT-GCTTTGTCCAGTGGCTGTAG-CTACAGCTTTGTCCAGTGGC.** [http://primer3.ut.ee/cgi-bin/primer3/primer3web_results.cgi](http://primer3.ut.ee/cgi-bin/primer3/primer3web_results.cgi)



17.Indica los partidores forward y reverse que escogiste y explica por qué son la mejor opción para amplificar el gen SRY de humano.

**R: Los mejores partidores son forward primer: Pr0001 y reverse primer: Pr0004, ya que cumple con el porcentage de GC de 50-60%, la TM de 55-80°C y puede llevar a la formación de dimeros.** [http://primer3.ut.ee/cgi-bin/primer3/primer3web_results.cgi](http://primer3.ut.ee/cgi-bin/primer3/primer3web_results.cgi)  ![](https://github.com/ConstanzaArandaG/Imagen-/blob/master/Pregunta%2017.png?raw=true)

18.¿Cuál es el largo del amplicón? ¿Y la temperatura de annealing sugerida?

**R: El largp de la amplificación es de 350 nucleotidos y la temperatura sugerida es de 55°C.** ![](https://github.com/ConstanzaArandaG/Imagen-/blob/master/Pregunta%2017.png?raw=true)