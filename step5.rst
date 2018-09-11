|CyVerse logo|_

|Home_Icon|_
`Learning Center Home <http://learning.cyverse.org/>`_


Walkthrough of DNA Subway Blue Line - DNA Barcoding and Phylogenetics
---------------------------------------------------------------------

You can analyze relationships between DNA sequences by comparing them to a
set of sequences you have compiled yourself, or by comparing your sequences
to other that have been published in database such as GenBank
(National Center for Biotechnology Information). Generating a phylogenetic
tree from DNA sequences derived from related species can also allow you
to draw inferences about how these species may be related. By sequencing
variable sections of DNA (barcode regions) you can also use the Blue
Line to help you identify an unknown species, or publish a DNA barcode for a
species you have identified, but  which is not represented in published
databases like GenBank.

**Some things to remember about the platform**

- Wet lab protocols and other resources are available at `http://dnabarcoding101.org/ <http://dnabarcoding101.org/>`_
- The DNA Barcoding 101 site also contains information on low-cost sequencing
  for U.S.-based educators.


----

*DNA Subway Blue Line - Create a Barcoding Project*
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
  1. Log-in to `DNA Subway <https://dnasubway.cyverse.org/>`_ - unregistered users may 'Enter as Guest'

     .. tip::
         Only registered users submitting novel, high-quality sequences will be
         able to submit sequence to GenBank

  2. Choose a project type:
      - Phlogenetics: build phylogenetic trees from any DNA, protein, or mtDNA sequence)
      - Barcoding: DNA Barcoding for plants (rbcL), animals (COI),
        bacteria (16S), and fungi (ITS)

  3. Under 'Select Sequence Source' select a sequence buy uploading either a
     FASTA file or AB1 Sanger sequencing tracefile; pasting in a sequence in
     FASTA format, or selecting and importing a trace file from DNALC. If
     you do not have a file, you may select any of the available sample sequences.

  4. Name your project, and give a description if desired; click 'Continue.'

**Example Exercise - Create a Project: Common Trees**
``````````````````````````````````````````````````````
This project will contain sample sequences from some common trees.


  1. Log-in to `DNA Subway`_ - unregistered users may 'Enter as Guest'

  2. Click ‘Determine Sequence Relationships.’ (Blue Square)

  3. Select project type ‘Barcoding: rbcL.’

  4. Select sample sequence 'rbcL sample1'.

  5. Provide your project with a title, then Click ‘Continue.’


----

*DNA Subway Blue Line - View and Clean Barcoding Sequence Data*
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**A. View Sequencing Trace File**

If you provided AB1 trace files, or imported files from DNALC, you will be able
to view the sequence electropherogram.

  1. Click ‘Sequence Viewer’ to show a list of your sequences.

  2. Click on a sequence name to show the sequences’ trace file.

    |blue_trace|

**B. Trim sequence, reverse complement and pair**

By default, DNA Subway assumes that all reads are in the forward orientation,
and displays an ‘F’ to the right of the sequence. If any sequence is not in that
orientation, click the “F” to reverse compliment the sequence. The sequence will
display an “R” to indicate the change.

  1. Click ‘Sequence Trimmer.’

  2. Click ‘Sequence Trimmer’ again to examine to changes made in the sequence

  3. Click ‘Pair Builder.’

  4. Select the check boxes next to the sequences that represent bidirectional
     reads of the same sequence set. Alternatively Select the ‘Auto Pair’
     function and verify the pairs generated.

  5. As necessary, Reverse Compliment sequences that were sequenced in the
     reverse orientation by clicking the ‘F’ next to the sequence name. The
     ‘F’ will become an ‘R’ to indicate the sequence has been reverse
     complimented.

  6.  Save the created pairs.

**C. Build a consensus sequence**
This step remove poor quality areas at the 5’ and/or 3’ ends of the consensus
sequence.

  1. Click on “Trim Consensus.” Scroll left and right in the consensus editor
     window to identify what string of nucleotides from the consensus sequence
     you want to trim.

  2. Click on the last consensus sequence nucleotide that you want to trim.
     A red line will indicate what nucleotides will be removed from the
     consensus sequences.

  3. Click “Trim.” A new “Consensus Editor” window will pop up displaying the
     trimmed sequences.

**Example Exercise - View and Clean Barcoding Sequence Data: Common Trees**
````````````````````````````````````````````````````````````````````````````

Following the Viewing steps for the 'rbcL sample1' sample above, answer
the following *discussion questions*:

  1. What do you notice about the electropherogram peaks and quality scores at
     nucleotide positions labeled “N”?

  2. Where do the ‘N’s’ in the sequence tend to be distributed, and why?

----

*DNA Subway Blue Line - Find Matches with BLAST*
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

DNA Subway Blue Line will search a local copy of a BLAST databases to check for
published matches in GenBank.

  .. tip::
      At the end of the BLAST results page, you can see the latest update to the
      DNA Subway BLAST database.

  1. Click ‘BLASTN' then click the 'BLAST' link to BLAST the sequence of
     interest. When the search is completed a 'View' link will appear.

  2. Examine the BLAST matches for candidate identification. Clicking the
     species name given in the BLAST hit will also give additional
     information/photos of the listed species.

  3. If desired, select the check box next to any hit, and select ‘Add BLAST hits
     to project’ to add selected sequences to your project.

     |blue_blast|


**Example Exercise - Find Matches with BLAST: Common Trees**
`````````````````````````````````````````````````````````````

Following the BLAST steps for the 'rbcL sample1' sample above, answer
the following *discussion questions*:

  1. BLAST will return the closest matches present in GenBank. Will you be able
     to identify an unknown species using BLAST alone? Why or why not?

----

*DNA Subway Blue Line - Add Reference Data*
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

Depending on the project type you have created, you will have access to
additional sequence data that may be of interest. For example, if you are doing
a DNA barcoding project using the rbcL gene, samples of rbcL sequence from major
plant groups (Angiosperms, Gymnosperms, etc.) will be provided. Choose any data
set to add it to your analysis; you will be able to include or exclude individual
sequences within the set in the next step.

  1. Click ‘Reference Data.’

  2. Select sequences of your choice.

  3. Click ‘Add ref data’ to add the data to your project.

**Example Exercise - Add Reference Data: Common Trees**
``````````````````````````````````````````````````````````

  1. Complete the 'Reference Data' step using the 'Common Plants' sample data.


----

*DNA Subway Blue Line - Build a Multiple Sequence Alignment and Phylogenetic Tree*
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

**A. Build a multiple sequence alignment and phylogenetic tree**

  1. Click ‘Select Data.’

  2. Select any and all sequences you wish to add to your tree.

  3. Click ‘Save.” to select data

  4. Click ‘MUSCLE.’ to run the MUSCLE program.

  5. Click ‘MUSCLE’ again to open the sequence alignment window.

  6. Examine the alignment and then select the 'Trim Alignment' link in the upper-left of the Alignment viewer'

    |blue_align|

**B. Build phylogenetic tree**

  1. Click 'PHYLIP NJ' and then click again to examine a neighbor-joining tree

    |blue_nj|

  2. Click 'PHYLIP ML' and then click again to examine a maximum-likelihood tree

    |blue_ml|


**Example Exercise - Build a Multiple Sequence Alignment and Phylogenetic Tree: Common Trees**
````````````````````````````````````````````````````````````````````````````````````````````````
Following the Alignment and Phylogenetic Tree steps for the 'rbcL sample1' sample above, answer
the following *discussion questions*:

  1. What relationship do you see between sequences that have more mutations
     (align less well with majority of sequences) in the alignment and the
     lengths of a sequences’ branch on the tree?

  2. Do you see differences in the phylogenetic tree generated by the
     Neighbor-joining vs. Maximum likelihood method?


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
.. |blue_trace| image:: ./img/dna_subway/blue_trace.png
    :width: 400
    :height: 200
.. |blue_blast| image:: ./img/dna_subway/blue_blast.png
    :width: 400
    :height: 200
.. |blue_align| image:: ./img/dna_subway/blue_align.png
    :width: 400
    :height: 200
.. |blue_nj| image:: ./img/dna_subway/blue_nj.png
    :width: 400
    :height: 200
.. |blue_ml| image:: ./img/dna_subway/blue_ml.png
    :width: 400
    :height: 200
