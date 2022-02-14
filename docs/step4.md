> \<a href=\"<https://user.cyverse.org/>\" target=\"\_blank\"\>CyVerse
> User Portal\</a\>

> \<a href=\"<http://www.cyverse.org/data-store>\"
> target=\"\_blank\"\>Data Store\</a\>

> \<a
> href=\"<https://wiki.cyverse.org/wiki/display/DS/Data+Store+Table+of+Contents>\"
> target=\"blank\"\>Data Store Manual\</a\>

> \<a
> href=\"<https://cyverse-data-store-guide.readthedocs-hosted.com/en/latest/>\"
> target=\"blank\"\>Data Store Guide\</a\>

> \<a href=\"<https://de.cyverse.org/de/>\" target=\"blank\"\>Discovery
> Environment\</a\>

> \<a
> href=\"<https://wiki.cyverse.org/wiki/display/DEmanual/Table+of+Contents>\"
> target=\"blank\"\>DE Manual\</a\>

> \<a
> href=\"<http://learning.cyverse.org/projects/cyverse-discovery-environment-guide/>\"
> target=\"blank\"\>Discovery Environment Guide\</a\>

> \<a href=\"<https://atmo.cyverse.org>\"
> target=\"blank\"\>Atmosphere\</a\>

> \<a
> href=\"<https://wiki.cyverse.org/wiki/display/atmman/Atmosphere+Manual+Table+of+Contents>\"
> target=\"blank\"\>Atmosphere Manual\</a\>

> \<a
> href=\"<https://cyverse-atmosphere-guide.readthedocs-hosted.com/en/latest/>\"
> target=\"blank\"\>Atmosphere Guide\</a\>

> \<a href=\"<https://bisque.cyverse.org/client_service/>\"
> target=\"blank\"\>BisQue\</a\>

> \<a href=\"<https://wiki.cyverse.org/wiki/display/BIS>\"
> target=\"blank\"\>BisQue Manual\</a\>

> \<a href=\"<http://learning.cyverse.org/en/latest/>\"
> target=\"blank\"\>BisQue Guide\</a\>

> \<a href=\"<https://dnasubway.cyverse.org/>\" target=\"blank\"\>DNA
> Subway\</a\>

> \<a
> href=\"<https://cyverse-dnasubway-guide.readthedocs-hosted.com/en/latest/>\"
> target=\"blank\"\>DNA Subway Manual\</a\>

> \<a
> href=\"<https://cyverse-dnasubway-guide.readthedocs-hosted.com/en/latest/>\"
> target=\"blank\"\>DNA Subway Guide\</a\>

> \<a href=\"<https://agaveapi.co>\" target=\"blank\"\>Agave API\</a\>

> \<a href=\"<https://agaveapi.co>\" target=\"blank\"\>Agave Live
> Docs\</a\>

> \<a href=\"<http://learning.cyverse.org/en/latest/>\"
> target=\"blank\"\>Agave Guide\</a\>

> \<a href=\"<https://www.sciapps.org/>\"
> target=\"blank\"\>SciApps\</a\>

> \<a
> href=\"<https://cyverse-sciapps-guide.readthedocs-hosted.com/en/latest/index.html>\"
> target=\"blank\"\>SciApps Manual\</a\>

> \<a
> href=\"<https://cyverse-sciapps-guide.readthedocs-hosted.com/en/latest/index.html>\"
> target=\"blank\"\>SciApps Guide\</a\>

> \<a href=\"<http://ask.iplantcollaborative.org/questions>\"
> target=\"blank\"\>Ask CyVerse\</a\>

> \<a href=\"<http://learning.cyverse.org>\" target=\"blank\"\>CyVerse
> Learning Center\</a\>

> \<a href=\"<https://wiki.cyverse.org>\" target=\"blank\"\>CyVerse
> Wiki\</a\>

> \<a
> href=\"<https://learning.cyverse.org/projects/kallisto_tutorial/en/latest/index.html>\"
> target=\"blank\"\>Kallisto Tutorial\</a\>

\_

![Home_Icon](./img/homeicon.png){width="25px" height="25px"}\_ [Learning
Center Home](http://learning.cyverse.org/)

# Walkthrough of DNA Subway Yellow Line - Sequence Detection

Genome prospecting uses a query sequence (DNA or protein of up to 10,000
base pairs/amino acids) to find related sequences in specific genomes or
in a database. A major purpose of genome prospecting is to identify
members of gene or transposon families. DNA Subway uses the TARGeT
workflow, which integrates BLAST searches, multiple sequence alignments,
and tree-drawing utilities. Yellow line uses TARGeT (Tree Analysis of
Related Genes and Transposons) uses either a DNA or amino acid 'seed'
query to: (i) automatically identify and retrieve gene family homologs
from a genomic database, (ii) characterize gene structure and (iii)
perform phylogenetic analysis. Due to its high speed, TARGeT is also
able to characterize very large gene families, including transposable
elements (TEs).
[\[citation\]](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC2699529/)

**Some things to remember about the platform**

-   Yellow Line will return sequences that would normally be excluded
    from a BLAST search of a genome (e.g. repetitive sequences,
    transposons).
-   Yellow Line is implemented only for plant genomes

------------------------------------------------------------------------

## *DNA Subway Yellow Line - Create a Yellow Line Project*

> 1.  Log-in to [DNA Subway](https://dnasubway.cyverse.org/) -
>     unregistered users may \'Enter as Guest\'
>
> 2.  Click 'Prospect Genomes using TARGeT' (Yellow Square)
>
> 3.  Select a sample sequence, or paste in a sequence to search for.
>
>     ::: note
>     ::: title
>     Note
>     :::
>
>     DNA Subway Yellow Line is only implemented to search a limited set
>     of plant genomes.
>     :::
>
> 4.  Provide your project with a title, then Click 'Continue'

### **Example Exercise - Project Creation: mPing Mite element to search plant genomes for an active transposon**

The [mPing MITE
element](https://www.nature.com/nature/journal/v421/n6919/full/nature01214.html)
is an example of an active transposon in rice.
[Transposons](http://www.dnaftb.org/32/animation.html) are a major class
of DNA elements that impact the function of the genome.

> 1.  Create a Yellow Line project following the steps above and using
>     the mPing Mite Element (Oryza sativa/Rice)

## *DNA Subway Yellow Line - Search Plant Genomes with TARGeT*

> 1.  Click and select the genome(s) you wish to search and the click;
>     \'Run\' to search those genomes.
> 2.  Click the \'Alignment Viewer\' button to view the results of the
>     search as a multiple alignment.
> 3.  Click the \'Tree Viewer\' button to view a tree that will group
>     results by similarity.
>
> > ::: tip
> > ::: title
> > Tip
> > :::
> >
> > **Alignment Viewer** Generates an alignment of all search results
> >
> > ![yellow_alignment](./img/dna_subway/yellow_alignment.png){width="420px"
> > height="150px"}
> >
> > **Tree Viewer** Displays the results of sequence matches as a tree,
> > grouped by sequence similarity
> >
> > ![yellow_tree](./img/dna_subway/yellow_tree.png){width="420px"
> > height="300px"}
> >
> > ::: tip
> > ::: title
> > Tip
> > :::
> >
> > **Some Useful Definitions** - **Transposons (DNA, Retroviral,
> > LINES):** Genetic elements which have the ability to be amplified
> > and redistributed within a genome. - **Non-autonomous transposons:**
> > Transposons which lack an active transposase gene, thus requiring
> > help from another transposon to move. - **Autonomous transposons:**
> > Transposons which have a functional transposase and can move within
> > the genome.
> > :::
> > :::

### **Example Exercise - Search Plant Genomes: mPing Mite element**

> 1.  After loading the mPing Mite Element as the query, search the
>     Oryza Sativa genome, and examine the results in the Alignment and
>     Tree Viewers.
> 2.  Repeat this analysis with a new project using the Ping transposase
>     gene and the Ping Transposase protein.

------------------------------------------------------------------------

**Fix or improve this documentation**

-   Search for an answer:
-   Ask us for help: click on the lower right-hand side of the page
-   Report an issue or submit a change:
-   Send feedback: [Tutorials@CyVerse.org](Tutorials@CyVerse.org)

------------------------------------------------------------------------

> ![Home_Icon](./img/homeicon.png){width="25px" height="25px"}\_
> [Learning Center Home](http://learning.cyverse.org/)
