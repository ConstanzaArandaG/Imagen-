# Informe Nº3 #
##Constanza Aranda##

**Parte 1: El artículo genoma**

1.¿Cuántos Sequencing Projects y Analysis Projects hay depositados en GOLD? ¿Cuál es la diferencia entre ambos?

**R: Hay 215.124 Sequencing Projects y 174.491 Analysis Projects. Sequencing Projects es el organismo individual o de muestra que se  dedica a la secuencicion y Analysis es el procesamiento informatico de Sequencing Prejects, describe como se realizaron el ensamblaje y la anotacion del proyecto secuencia.** [https://gold.jgi.doe.gov/](https://gold.jgi.doe.gov/)

2.¿Cuál es el dominio más representado en la base de datos, archea, bacteria, eukaryote, o virus?

**R: El dominio más representado en la base de datos son las bacterias.** [https://gold.jgi.doe.gov/statistics](https://gold.jgi.doe.gov/statistics)

3.¿Cuáles son los phyla más representados entre los proyectos de genomas bacterianos en la base de datos?

**R: Los phyla mas representados entre los proyectos de genoma bacterianos en la base de datos son: Actinobacteria, Firmicutes, Proteobacteria.** [https://gold.jgi.doe.gov/statistics](https://gold.jgi.doe.gov/statistics)

4.¿A qué tipo de proyectos pertenece la mayor cantidad de genomas bacterianos depositados en GOLD? (tipo de proyecto, se refiere al tópico de la investigación, por ejemplo, salud humana, ambiental, etc.)

**R:La mayor cantidad de genomas bacterianos pertenecen a proyectos médicos.** [https://gold.jgi.doe.gov/statistics](https://gold.jgi.doe.gov/statistics)



5.¿Cuál es el artículo original del genoma? (en el cual se reporta la sequenciación y ensamble del genoma)

**R: El artículo original del genomas es de Prüfer, K., Munch, K., Hellmann, I., Akagi, K., Miller, J. R., Walenz, B., … Pääbo, S. (2012). The bonobo genome compared with the chimpanzee and human genomes. Nature, 486(7404), 527–531. http://doi.org/10.1038/nature11128.** [https://www.ncbi.nlm.nih.gov/pmc/articles/PMC3498939/#](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC3498939/#)

6.Explica, qué es el N50, L50, y NG50.

**R: El N50 puede describirse como una estadística mediana ponderada de tal manera que el 50% de todo el conjunto está contenido en contigs o andamios iguales o mayores que este valor. L50 se define como el menor número de contigs cuya suma de longitud produce N50. La estadística NG50 es igual a N50, excepto que es el 50% del tamaño del genoma conocido o estimado que debe ser de la longitud NG50 o más. Esto permite comparaciones significativas entre diferentes conjuntos. En el caso típico en que el tamaño del conjunto no es más que el tamaño del genoma, la estadística NG50 no será más que la estadística N50.** [https://en.wikipedia.org/wiki/N50,_L50,_and_related_statistics](https://en.wikipedia.org/wiki/N50,_L50,_and_related_statistics)

7.¿Cuál es el propósito de calcular estas estadísticas?

**R: El propósito de calcular estas estadísticas es para ver el  ensamblaje del genoma, especialmente en referencia a las longitudes del contigs dentro de un ensamblaje en borrador.** [https://en.wikipedia.org/wiki/N50,_L50,_and_related_statistics](https://en.wikipedia.org/wiki/N50,_L50,_and_related_statistics) 

8.¿Cuántos contigs conforman el genoma del Bonobo? ¿Cuál es el N50 y L50 del genoma? (responde basado en los contigs)

**R: 121,356 contings conforman el genoma del Bonobo. El N50 es de 66,676 y el L50  es de 11,048.** [https://www.ncbi.nlm.nih.gov/assembly/GCF_000258655.2](https://www.ncbi.nlm.nih.gov/assembly/GCF_000258655.2)

9.¿Cuál es el largo total y porcentaje de GC del genoma del Bonobo? ¿Qué quieren decir o qué indican éstos valores?

**R: El largo total es de 3286.64 Mb y el porcentaje de GC del genoma del Bonobo es de 42.3185%. El porcentaje de CG  representa la cantidad de pares Guanina-Citosina en el genoma que está siendo investigado y la longitud nos indica la totalidad del material genetico.** [https://www.ncbi.nlm.nih.gov/genome/?term=txid9597[orgn]](https://www.ncbi.nlm.nih.gov/genome/?term=txid9597[orgn])

10.¿Qué tipo de tecnología se uso para secuenciar el genoma del Bonobo? ¿Qué método (programa o algorítmo bioinformático) se usó para ensamblar el genoma?

**R: Illumina GAIIx se utiliza como tecnologia para secuenciar el genoma del Bonobo y se utilizo Celera Assembler software para el ensamblar el genoma.**
[https://www.ncbi.nlm.nih.gov/pmc/articles/PMC3498939/](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC3498939/)



**Parte 2: Predicción de genes**

11.Describe los resultados obtenidos. ¿Cuántos ORFs o genes encontró ORFfinder? ¿En qué hebra están codificados? ¿De qué largo son los ORFs predichos? ¿Algunos de ellos se sobreponen (fíjate en la posición de inicio [start] y término [stop])?

**R: Se encontró 7 ORFs. En la hebra conductura se encuentra ORF1, ORF2 y ORF3, y en la hebra retrasada ORF4, ORF5 ORF6 y ORF7. ORF1 mide 909 nt, ORF2 mide 78 nt, ORF3 mide 99 nt, ORF4 mide 441 nt, ORF5 mide 405 nt, ORF6 mide 84 nt y ORF7 mide 144 nt. Si se sobreponen, ORF1 se sobrepone con ORF7, ORF4 se sobrepone con ORF6 Y ORF2, ORF5 se sobreponde con ORF3.** [https://www.ncbi.nlm.nih.gov/orffinder/](https://www.ncbi.nlm.nih.gov/orffinder/)

12.¿Qué tipo de programa es ORFfinder, Ab initio o por homología?

**R: ORFfinder es de un tipo de programa ab initio, ya que parte de una  secuencia de DNA y busca señales equivocadas como codondes de inicio/termino.** [file:///C:/Users/Constanza/Downloads/c03_2018_2.pdf](file:///C:/Users/Constanza/Downloads/c03_2018_2.pdf)
 

13.¿A qué organismo pertenece la secuencia en cuestión?

**R: La secuencia en cuestión pertenece a *Haemophilus influenzae*.** [https://blast.ncbi.nlm.nih.gov/Blast.cgi](https://blast.ncbi.nlm.nih.gov/Blast.cgi)

14.¿Qué gen(s) está(n) codificados en la secuencia?

**R: Los genes que estan codificados en la secuencia son formate dehydrogenase accessory protein FdhE, ribosomal-protein-alanine N-acetyltransferase y DNA polymerase III subunit psi.** [https://blast.ncbi.nlm.nih.gov/Blast.cgi](https://blast.ncbi.nlm.nih.gov/Blast.cgi), [https://blast.ncbi.nlm.nih.gov/Blast.cgi](https://blast.ncbi.nlm.nih.gov/Blast.cgi) y [https://blast.ncbi.nlm.nih.gov/Blast.cgi](https://blast.ncbi.nlm.nih.gov/Blast.cgi)

15.Tomando en cuenta la evidencia que acumulaste usando ORFfinder y BLAST. ¿Cuál o cuáles ORFs predichos por ORFfinder dirías tú que son o es el correcto(s)?

**R: Los ORF más correctos serian los ORF1 y ORF7, ya que tienen un mayor score.**


