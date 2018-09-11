|CyVerse logo|_

|Home_Icon|_
`Learning Center Home <http://learning.cyverse.org/>`_


Walkthrough of DNA Subway Yellow Line - Sequence Detection
----------------------------------------------------------

Genome prospecting  uses  a  query  sequence  (DNA  or  protein of  up  to
10,000 base pairs/amino  acids)  to  find  related  sequences  in  specific
genomes  or  in  a database.  A  major  purpose  of  genome  prospecting  is  to
identify  members  of gene  or  transposon  families. DNA  Subway uses  the
TARGeT  workflow,  which integrates  BLAST  searches,  multiple  sequence
alignments,  and  tree-drawing utilities. Yellow line uses TARGeT (Tree Analysis
of Related Genes and Transposons) uses either a DNA or amino acid ‘seed’ query
to: (i) automatically identify and retrieve gene family homologs from a
genomic database, (ii) characterize gene structure and (iii) perform phylogenetic
analysis. Due to its high speed, TARGeT is also able to characterize very large
gene families, including transposable elements (TEs). `[citation] <https://www.ncbi.nlm.nih.gov/pmc/articles/PMC2699529/>`_

**Some things to remember about the platform**

- Yellow Line will return sequences that would normally be excluded from a
  BLAST search of a genome (e.g. repetitive sequences, transposons).
- Yellow Line is implemented only for plant genomes

----

*DNA Subway Yellow Line - Create a Yellow Line Project*
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

  1. Log-in to `DNA Subway <https://dnasubway.cyverse.org/>`_ - unregistered users may 'Enter as Guest'

  2. Click ‘Prospect Genomes using TARGeT’ (Yellow Square)

  3. Select a sample sequence, or paste in a sequence to search for.

     .. note::
        DNA Subway Yellow Line is only implemented to search a limited set of
        plant genomes.

  4. Provide your project with a title, then Click ‘Continue’


**Example Exercise - Project Creation: mPing Mite element to search plant genomes for an active transposon**
`````````````````````````````````````````````````````````````````````````````````````````````````````````````

The `mPing MITE element <https://www.nature.com/nature/journal/v421/n6919/full/nature01214.html>`_
is an example of an active transposon in rice. `Transposons <http://www.dnaftb.org/32/animation.html>`_
are a major class of DNA elements that impact the function of the genome.

  1. Create a Yellow Line project following the steps above and using the
     mPing Mite Element (Oryza sativa/Rice)


*DNA Subway Yellow Line - Search Plant Genomes with TARGeT*
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

  1. Click and select the genome(s) you wish to search and the click; 'Run' to
     search those genomes.

  2. Click the 'Alignment Viewer' button to view the results of the search as
     a multiple alignment.

  3. Click the 'Tree Viewer' button to view a tree that will group results by
     similarity.

   .. tip::

       **Alignment Viewer**
       Generates an alignment of all search results

       |yellow_alignment|


       **Tree Viewer**
       Displays the results of sequence matches as a tree, grouped by sequence similarity

       |yellow_tree|

       .. tip::

           **Some Useful Definitions**
           - **Transposons (DNA, Retroviral, LINES):** Genetic elements which
           have the ability to be amplified and redistributed within a genome.
           - **Non-autonomous transposons:** Transposons which lack an active
           transposase gene, thus requiring help from another transposon to move.
           - **Autonomous transposons:** Transposons which have a functional
           transposase and can move within the genome.


**Example Exercise - Search Plant Genomes: mPing Mite element**
````````````````````````````````````````````````````````````````

   1. After loading the mPing Mite Element as the query, search the Oryza Sativa
      genome, and examine the results in the Alignment and Tree Viewers.

   2. Repeat this analysis with a new project using the Ping transposase gene
      and the Ping Transposase protein.

----

**Fix or improve this documentation:**

- On Github: `Repo link <https://github.com/CyVerse-learning-materials/dnasubway_guide>`_
- Send feedback: `Tutorials@CyVerse.org <Tutorials@CyVerse.org>`_

----

  |Home_Icon|_
  `Learning Center Home <http://learning.cyverse.org/>`_

.. |CyVerse logo| image:: ./img/cyverse_rgb.png
    :width: 500
    :height: 100
.. _CyVerse logo: http://learning.cyverse.org/
.. |Home_Icon| image:: ./img/homeicon.png
    :width: 25
    :height: 25
.. _Home_Icon: http://learning.cyverse.org/
.. |yellow_alignment| image:: ./img/dna_subway/yellow_alignment.png
    :width: 420
    :height: 150
.. |yellow_tree| image:: ./img/dna_subway/yellow_tree.png
    :width: 420
    :height: 300
