Step 3: Expression analysis
===========================

Step live from: Tuesday April 23nd, 5 pm Eagle Time (6 pm CET/5 pm BST/noon ET/9 am PT)

In bringing high-throughput to the masses, microarrays were a big breakthrough in –omics. One key application of microarrays is the measurement of gene expression, and for many years such data featured prominently in Genome Biology. In the last three years or so, however, a switch to RNA-seq data has been very apparent in gene expression studies, as part of the unstoppable tide of the NGS revolution. And this has been great news for bioinformaticians! New data types means demand for new analysis methods, and so a whole new wave of expression analysis tools have emerged, including the widely used DEseq and the Cloud-based Myrna, both of which we published in Genome Biology.

Of course, new analysis tools create a secondary demand for new visualization software, and so even more good news for bioinformaticians (we have also published examples of these tools in Genome Biology, including ExpressionPlot and ggbio).

**The challenge**

For the Step 3 challenge, we have simulated a pair (t1 and t2) of RNA-seq experiments in E. coli. One gene in particular has a transcript that is more differentially expressed (between the two experiments) than any other. In an ideal world, we would have biological replicates for each condition but, hey, this isn't an ideal world.

The reads are paired-end so t1.1.fq and t1.2.fq come from the first condition, and t2.1.fq and t2.2.fq come from the second. The included gene annotation file (ecoli.ptt) marks the genes relevant to the experiment.

Once you have identified the gene, you can use its gene name to form the URL for Step 4, the dreaded penultimate step! For example, if the gene were to be 'thrL' (thr operon leader peptide), then Step 4's URL would be: http://genomebiology.com/about/update/DNA60_THRL

Archived from: http://genomebiology.com/about/update/DNA60_THESECRETQFLIFE
