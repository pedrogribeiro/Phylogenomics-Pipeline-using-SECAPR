# Phylogenomics-Pipeline-using-SECAPR
This repository contains the main steps of a phylogenomics pipeline, from raw data to maximum-likelihood phylogenetic inference, using mostly the program SECAPR (Andermann et al., 2018; Ribeiro et al., 2021) but also others. It is based on a loci kit of 406 conserved butterfly protein coding loci (Espeland et al., 2018 - full reference in README), but should work the same for any loci reference dataset.

The ideia here is to provide a very simple guide, mostly to beginners, on how to obtain a phylogenetic tree with most of its steps run within the SECAPR pipeline. It does not require any coding specifically, but it requires at least basic knowledge on using the command line (i.e., how to create directories, navigate them, etc). I will provide specific information about each step directly at the scripts, so that is why most of them will be somehow separated for each program or step. I will also provide one summarized script that merges everything together. I would not recommend putting the assebmly step together with the others since it usually requires much more time and resources.

SECAPR is a semi-automated pipeline for the processing of whole-genome sequencing and target capture data, with the specific intention of phylogenenetic usage. Since it works as an environment containing all the necessary programs with a simple installation, and has straightforward commands to use all of its suites, it is recommended for all sorts of users, even those with very basic experience with the command line.  

SECAPR is still fully working as of February 2025. Nonetheless, it seems that its documentation has not been updated at https://antonellilab.github.io/seqcap_processor/. In this repository, I am using the latest version 2.2.3. The arguments for each secapr command differ from that of the documentation.

Importantly, I will keep the scripts narrowed down to the commands used, since each person might use them at different clusters with different queueing systems and requirements. 
Also, note that of course you will need to change the paths provided to your needs, mine are just examples.







