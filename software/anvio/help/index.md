---
layout: post
title: Help pages for anvi'o programs and artifacts
categories: [anvio]
comments: false
image:
  featurerelative: images/header.png
  display: true
redirect_from:
    - /help
---

On this page you will find a complete list of anvi'o programs and artifacts.

{:.notice}
Confused by some of the 'omics and/or anvi'o terminology? Check out <a href="http://merenlab.org/vocabulary/"> our vocabulary page</a>.

{:.notice}
Visit <a href="http://merenlab.org/2019/10/07/getting-help/">this page</a> to learn <b>how to get help from the anvi'o community</b>.

{:.notice}
Visit <a href="http://merenlab.org/software/anvio/vignette/">this page</a> to see a complete <b>list of anvi'o programs and their command line arguments</b>.


{% include _project-anvio-version.html %}


<a href="/software/anvio/network/" target="_blank"><img src="/images/anvio-network.png" width="100%" /></a>

{:.notice}
The help contents were last updated on **09 Oct 20 09:27:56** for anvi'o version **6.2-master (esther)**.


{% include _toc.html %}
{% include _join-anvio-slack.html %}


---

## Programs

Listed below a total of 112 programs.


* **[anvi-3dev](programs/anvi-3dev)**: Interactively visualize sequence variants on protein structures.
<span>**Provides**: <span class="artifact-p">[interactive](artifacts/interactive)</span> <span class="artifact-p">[summary](artifacts/summary)</span> / 
<span>**Requires**: <span class="artifact-r">[structure-db](artifacts/structure-db)</span> <span class="artifact-r">[variability-profile-txt](artifacts/variability-profile-txt)</span> <span class="artifact-r">[contigs-db](artifacts/contigs-db)</span> <span class="artifact-r">[profile-db](artifacts/profile-db)</span> <span class="artifact-r">[splits-txt](artifacts/splits-txt)</span>.</span>


* **[anvi-analyze-synteny](programs/anvi-analyze-synteny)**: Extract ngrams, as in &#39;co-occurring genes in synteny&#39;, from genomes.
<span>**Provides**: <span class="artifact-p">[ngrams](artifacts/ngrams)</span> / 
<span>**Requires**: <span class="artifact-r">[genomes-storage-db](artifacts/genomes-storage-db)</span> <span class="artifact-r">[functions](artifacts/functions)</span> <span class="artifact-r">[pan-db](artifacts/pan-db)</span>.</span>


* **[anvi-cluster-contigs](programs/anvi-cluster-contigs)**: A program to cluster items in a merged anvi&#39;o profile using automatic binning algorithms.
<span>**Provides**: <span class="artifact-p">[collection](artifacts/collection)</span> <span class="artifact-p">[bin](artifacts/bin)</span> / 
<span>**Requires**: <span class="artifact-r">[profile-db](artifacts/profile-db)</span> <span class="artifact-r">[contigs-db](artifacts/contigs-db)</span> <span class="artifact-r">[collection](artifacts/collection)</span>.</span>


* **[anvi-compute-completeness](programs/anvi-compute-completeness)**: A script to generate completeness info for a given list of _splits_.
<span>**Provides**:  / 
<span>**Requires**: <span class="artifact-r">[contigs-db](artifacts/contigs-db)</span> <span class="artifact-r">[splits-txt](artifacts/splits-txt)</span> <span class="artifact-r">[hmm-source](artifacts/hmm-source)</span>.</span>


* **[anvi-compute-gene-cluster-homogeneity](programs/anvi-compute-gene-cluster-homogeneity)**: Compute homogeneity for gene clusters.
<span>**Provides**:  / 
<span>**Requires**: <span class="artifact-r">[pan-db](artifacts/pan-db)</span> <span class="artifact-r">[genomes-storage-db](artifacts/genomes-storage-db)</span>.</span>


* **[anvi-compute-genome-similarity](programs/anvi-compute-genome-similarity)**: Export sequences from sequence sources and compute a similarity metric (e.g. ANI). If a Pan Database is given anvi&#39;o will write computed output to misc data tables of Pan Database.
<span>**Provides**: <span class="artifact-p">[genome-similarity](artifacts/genome-similarity)</span> / 
<span>**Requires**: <span class="artifact-r">[external-genomes](artifacts/external-genomes)</span> <span class="artifact-r">[internal-genomes](artifacts/internal-genomes)</span> <span class="artifact-r">[pan-db](artifacts/pan-db)</span>.</span>


* **[anvi-db-info](programs/anvi-db-info)**: Access self tables, display values, or set new ones totally on your own risk.
<span>**Provides**:  / 
<span>**Requires**: <span class="artifact-r">[pan-db](artifacts/pan-db)</span> <span class="artifact-r">[profile-db](artifacts/profile-db)</span> <span class="artifact-r">[contigs-db](artifacts/contigs-db)</span> <span class="artifact-r">[genomes-storage-db](artifacts/genomes-storage-db)</span> <span class="artifact-r">[structure-db](artifacts/structure-db)</span>.</span>


* **[anvi-delete-collection](programs/anvi-delete-collection)**: Remove a collection from a given profile database.
<span>**Provides**:  / 
<span>**Requires**: <span class="artifact-r">[profile-db](artifacts/profile-db)</span> <span class="artifact-r">[collection](artifacts/collection)</span>.</span>


* **[anvi-delete-hmms](programs/anvi-delete-hmms)**: Remove HMM hits from an anvi&#39;o contigs database.
<span>**Provides**:  / 
<span>**Requires**: <span class="artifact-r">[contigs-db](artifacts/contigs-db)</span> <span class="artifact-r">[hmm-source](artifacts/hmm-source)</span> <span class="artifact-r">[hmm-hits](artifacts/hmm-hits)</span>.</span>


* **[anvi-delete-misc-data](programs/anvi-delete-misc-data)**: Remove stuff from &#39;additional data&#39; or &#39;order&#39; tables for either items or layers in either pan or profile databases. OR, remove stuff from the &#39;additional data&#39; tables for nucleotides or amino acids in contigs databases.
<span>**Provides**:  / 
<span>**Requires**: <span class="artifact-r">[pan-db](artifacts/pan-db)</span> <span class="artifact-r">[profile-db](artifacts/profile-db)</span> <span class="artifact-r">[misc-data-items](artifacts/misc-data-items)</span> <span class="artifact-r">[misc-data-layers](artifacts/misc-data-layers)</span> <span class="artifact-r">[misc-data-layer-orders](artifacts/misc-data-layer-orders)</span> <span class="artifact-r">[misc-data-nucleotides](artifacts/misc-data-nucleotides)</span> <span class="artifact-r">[misc-data-amino-acids](artifacts/misc-data-amino-acids)</span>.</span>


* **[anvi-delete-state](programs/anvi-delete-state)**: Delete an anvi&#39;o state from a pan or profile database.
<span>**Provides**:  / 
<span>**Requires**: <span class="artifact-r">[pan-db](artifacts/pan-db)</span> <span class="artifact-r">[profile-db](artifacts/profile-db)</span> <span class="artifact-r">[state](artifacts/state)</span>.</span>


* **[anvi-dereplicate-genomes](programs/anvi-dereplicate-genomes)**: Identify redundant (highly similar) genomes.
<span>**Provides**: <span class="artifact-p">[fasta](artifacts/fasta)</span> / 
<span>**Requires**: <span class="artifact-r">[external-genomes](artifacts/external-genomes)</span> <span class="artifact-r">[internal-genomes](artifacts/internal-genomes)</span> <span class="artifact-r">[fasta](artifacts/fasta)</span>.</span>


* **[anvi-display-contigs-stats](programs/anvi-display-contigs-stats)**: Start the anvi&#39;o interactive interactive for viewing or comparing contigs statistics.
<span>**Provides**: <span class="artifact-p">[contigs-stats](artifacts/contigs-stats)</span> <span class="artifact-p">[interactive](artifacts/interactive)</span> <span class="artifact-p">[svg](artifacts/svg)</span> / 
<span>**Requires**: <span class="artifact-r">[contigs-db](artifacts/contigs-db)</span>.</span>


* **[anvi-display-metabolism](programs/anvi-display-metabolism)**: Start the anvi&#39;o interactive interactive for viewing KEGG metabolism data.
<span>**Provides**: <span class="artifact-p">[interactive](artifacts/interactive)</span> / 
<span>**Requires**: <span class="artifact-r">[contigs-db](artifacts/contigs-db)</span> <span class="artifact-r">[kegg-db](artifacts/kegg-db)</span> <span class="artifact-r">[kegg-functions](artifacts/kegg-functions)</span> <span class="artifact-r">[profile-db](artifacts/profile-db)</span> <span class="artifact-r">[collection](artifacts/collection)</span> <span class="artifact-r">[bin](artifacts/bin)</span>.</span>


* **[anvi-display-pan](programs/anvi-display-pan)**: Start an anvi&#39;o server to display a pan-genome.
<span>**Provides**: <span class="artifact-p">[collection](artifacts/collection)</span> <span class="artifact-p">[bin](artifacts/bin)</span> <span class="artifact-p">[interactive](artifacts/interactive)</span> <span class="artifact-p">[svg](artifacts/svg)</span> / 
<span>**Requires**: <span class="artifact-r">[pan-db](artifacts/pan-db)</span> <span class="artifact-r">[genomes-storage-db](artifacts/genomes-storage-db)</span>.</span>


* **[anvi-estimate-genome-completeness](programs/anvi-estimate-genome-completeness)**: Estimate completion and redundancy using domain-specific single-copy core genes.
<span>**Provides**: <span class="artifact-p">[completion](artifacts/completion)</span> / 
<span>**Requires**: <span class="artifact-r">[contigs-db](artifacts/contigs-db)</span> <span class="artifact-r">[profile-db](artifacts/profile-db)</span> <span class="artifact-r">[external-genomes](artifacts/external-genomes)</span> <span class="artifact-r">[collection](artifacts/collection)</span>.</span>


* **[anvi-estimate-metabolism](programs/anvi-estimate-metabolism)**: Reconstructs metabolic pathways and estimates pathway completeness for a given set of contigs.
<span>**Provides**: <span class="artifact-p">[kegg-metabolism](artifacts/kegg-metabolism)</span> / 
<span>**Requires**: <span class="artifact-r">[contigs-db](artifacts/contigs-db)</span> <span class="artifact-r">[kegg-db](artifacts/kegg-db)</span> <span class="artifact-r">[kegg-functions](artifacts/kegg-functions)</span> <span class="artifact-r">[profile-db](artifacts/profile-db)</span> <span class="artifact-r">[collection](artifacts/collection)</span> <span class="artifact-r">[bin](artifacts/bin)</span> <span class="artifact-r">[external-genomes](artifacts/external-genomes)</span> <span class="artifact-r">[internal-genomes](artifacts/internal-genomes)</span> <span class="artifact-r">[metagenomes](artifacts/metagenomes)</span>.</span>


* **[anvi-estimate-scg-taxonomy](programs/anvi-estimate-scg-taxonomy)**: Estimates taxonomy at genome and metagenome level. This program is the entry point to estimate taxonomy for a given set of contigs (i.e., all contigs in a contigs database, or contigs described in collections as bins). For this, it uses single-copy core gene sequences and the GTDB database.
<span>**Provides**: <span class="artifact-p">[genome-taxonomy](artifacts/genome-taxonomy)</span> <span class="artifact-p">[genome-taxonomy-txt](artifacts/genome-taxonomy-txt)</span> / 
<span>**Requires**: <span class="artifact-r">[profile-db](artifacts/profile-db)</span> <span class="artifact-r">[contigs-db](artifacts/contigs-db)</span> <span class="artifact-r">[scgs-taxonomy](artifacts/scgs-taxonomy)</span> <span class="artifact-r">[collection](artifacts/collection)</span> <span class="artifact-r">[bin](artifacts/bin)</span> <span class="artifact-r">[metagenomes](artifacts/metagenomes)</span>.</span>


* **[anvi-estimate-trna-taxonomy](programs/anvi-estimate-trna-taxonomy)**: Estimates taxonomy at genome and metagenome level using tRNA sequences..
<span>**Provides**: <span class="artifact-p">[genome-taxonomy](artifacts/genome-taxonomy)</span> <span class="artifact-p">[genome-taxonomy-txt](artifacts/genome-taxonomy-txt)</span> / 
<span>**Requires**: <span class="artifact-r">[profile-db](artifacts/profile-db)</span> <span class="artifact-r">[contigs-db](artifacts/contigs-db)</span> <span class="artifact-r">[trna-taxonomy](artifacts/trna-taxonomy)</span> <span class="artifact-r">[collection](artifacts/collection)</span> <span class="artifact-r">[bin](artifacts/bin)</span> <span class="artifact-r">[metagenomes](artifacts/metagenomes)</span>.</span>


* **[anvi-export-collection](programs/anvi-export-collection)**: Export a collection from an anvi&#39;o database.
<span>**Provides**: <span class="artifact-p">[collection-txt](artifacts/collection-txt)</span> / 
<span>**Requires**: <span class="artifact-r">[profile-db](artifacts/profile-db)</span> <span class="artifact-r">[collection](artifacts/collection)</span>.</span>


* **[anvi-export-contigs](programs/anvi-export-contigs)**: Export contigs (or splits) from an anvi&#39;o contigs database.
<span>**Provides**: <span class="artifact-p">[contigs-fasta](artifacts/contigs-fasta)</span> / 
<span>**Requires**: <span class="artifact-r">[contigs-db](artifacts/contigs-db)</span>.</span>


* **[anvi-export-functions](programs/anvi-export-functions)**: Export functions of genes from an anvi&#39;o contigs database for a given annotation source.
<span>**Provides**: <span class="artifact-p">[functions-txt](artifacts/functions-txt)</span> / 
<span>**Requires**: <span class="artifact-r">[contigs-db](artifacts/contigs-db)</span> <span class="artifact-r">[functions](artifacts/functions)</span>.</span>


* **[anvi-export-gene-calls](programs/anvi-export-gene-calls)**: Export gene calls from an anvi&#39;o contigs database.
<span>**Provides**: <span class="artifact-p">[gene-calls-txt](artifacts/gene-calls-txt)</span> / 
<span>**Requires**: <span class="artifact-r">[contigs-db](artifacts/contigs-db)</span>.</span>


* **[anvi-export-gene-coverage-and-detection](programs/anvi-export-gene-coverage-and-detection)**: Export gene coverage and detection data for all genes associated with contigs described in a profile database.
<span>**Provides**: <span class="artifact-p">[coverages-txt](artifacts/coverages-txt)</span> <span class="artifact-p">[detection-txt](artifacts/detection-txt)</span> / 
<span>**Requires**: <span class="artifact-r">[profile-db](artifacts/profile-db)</span> <span class="artifact-r">[contigs-db](artifacts/contigs-db)</span>.</span>


* **[anvi-export-items-order](programs/anvi-export-items-order)**: Export an item order from an anvi&#39;o database.
<span>**Provides**: <span class="artifact-p">[misc-data-items-order-txt](artifacts/misc-data-items-order-txt)</span> <span class="artifact-p">[dendrogram](artifacts/dendrogram)</span> <span class="artifact-p">[phylogeny](artifacts/phylogeny)</span> / 
<span>**Requires**: <span class="artifact-r">[pan-db](artifacts/pan-db)</span> <span class="artifact-r">[profile-db](artifacts/profile-db)</span>.</span>


* **[anvi-export-locus](programs/anvi-export-locus)**: This program helps you cut a &#39;locus&#39; from a larger genetic context (e.g., contigs, genomes). By default, anvi&#39;o will locate a user-defined anchor gene, extend its selection upstream and downstream based on the --num-genes argument, then extract the locus to create a new contigs database. The anchor gene must be provided as --search-term, --gene-caller-ids, or --hmm-sources. If --flank-mode is designated, you MUST provide TWO flanking genes that define the locus region (Please see --flank-mode help for more information). If everything goes as plan, anvi&#39;o will give you individual locus contigs databases for every matching anchor gene found in the original contigs database provided. Enjoy your mini contigs databases!.
<span>**Provides**: <span class="artifact-p">[locus-fasta](artifacts/locus-fasta)</span> / 
<span>**Requires**: <span class="artifact-r">[contigs-db](artifacts/contigs-db)</span>.</span>


* **[anvi-export-misc-data](programs/anvi-export-misc-data)**: Export additional data or order tables in pan or profile databases for items or layers.
<span>**Provides**: <span class="artifact-p">[misc-data-items-txt](artifacts/misc-data-items-txt)</span> <span class="artifact-p">[misc-data-layers-txt](artifacts/misc-data-layers-txt)</span> <span class="artifact-p">[misc-data-layer-orders-txt](artifacts/misc-data-layer-orders-txt)</span> <span class="artifact-p">[misc-data-nucleotides-txt](artifacts/misc-data-nucleotides-txt)</span> <span class="artifact-p">[misc-data-amino-acids-txt](artifacts/misc-data-amino-acids-txt)</span> / 
<span>**Requires**: <span class="artifact-r">[pan-db](artifacts/pan-db)</span> <span class="artifact-r">[profile-db](artifacts/profile-db)</span> <span class="artifact-r">[contigs-db](artifacts/contigs-db)</span> <span class="artifact-r">[misc-data-items](artifacts/misc-data-items)</span> <span class="artifact-r">[misc-data-layers](artifacts/misc-data-layers)</span> <span class="artifact-r">[misc-data-layer-orders](artifacts/misc-data-layer-orders)</span> <span class="artifact-r">[misc-data-nucleotides](artifacts/misc-data-nucleotides)</span> <span class="artifact-r">[misc-data-amino-acids](artifacts/misc-data-amino-acids)</span>.</span>


* **[anvi-export-splits-and-coverages](programs/anvi-export-splits-and-coverages)**: Export split or contig sequences and coverages across samples stored in an anvi&#39;o profile database. This program is especially useful if you would like to &#39;bin&#39; your splits or contigs outside of anvi&#39;o and import the binning results into anvi&#39;o using `anvi-import-collection` program.
<span>**Provides**: <span class="artifact-p">[contigs-fasta](artifacts/contigs-fasta)</span> <span class="artifact-p">[coverages-txt](artifacts/coverages-txt)</span> / 
<span>**Requires**: <span class="artifact-r">[profile-db](artifacts/profile-db)</span> <span class="artifact-r">[contigs-db](artifacts/contigs-db)</span>.</span>


* **[anvi-export-splits-taxonomy](programs/anvi-export-splits-taxonomy)**: Export taxonomy for splits found in an anvi&#39;o contigs database.
<span>**Provides**: <span class="artifact-p">[splits-taxonomy-txt](artifacts/splits-taxonomy-txt)</span> / 
<span>**Requires**: <span class="artifact-r">[contigs-db](artifacts/contigs-db)</span>.</span>


* **[anvi-export-state](programs/anvi-export-state)**: Export an anvi&#39;o state into a profile database.
<span>**Provides**: <span class="artifact-p">[state-json](artifacts/state-json)</span> / 
<span>**Requires**: <span class="artifact-r">[pan-db](artifacts/pan-db)</span> <span class="artifact-r">[profile-db](artifacts/profile-db)</span> <span class="artifact-r">[state](artifacts/state)</span>.</span>


* **[anvi-export-structures](programs/anvi-export-structures)**: Export .pdb structure files from a structure database.
<span>**Provides**: <span class="artifact-p">[protein-structure](artifacts/protein-structure)</span> / 
<span>**Requires**: <span class="artifact-r">[structure-db](artifacts/structure-db)</span>.</span>


* **[anvi-gen-contigs-database](programs/anvi-gen-contigs-database)**: Generate a new anvi&#39;o contigs database.
<span>**Provides**: <span class="artifact-p">[contigs-db](artifacts/contigs-db)</span> / 
<span>**Requires**: <span class="artifact-r">[contigs-fasta](artifacts/contigs-fasta)</span> <span class="artifact-r">[external-gene-calls](artifacts/external-gene-calls)</span>.</span>


* **[anvi-gen-fixation-index-matrix](programs/anvi-gen-fixation-index-matrix)**: Generate a pairwise matrix of a fixation indices between samples.
<span>**Provides**: <span class="artifact-p">[fixation-index-matrix](artifacts/fixation-index-matrix)</span> / 
<span>**Requires**: <span class="artifact-r">[contigs-db](artifacts/contigs-db)</span> <span class="artifact-r">[profile-db](artifacts/profile-db)</span> <span class="artifact-r">[structure-db](artifacts/structure-db)</span> <span class="artifact-r">[bin](artifacts/bin)</span> <span class="artifact-r">[variability-profile-txt](artifacts/variability-profile-txt)</span> <span class="artifact-r">[splits-txt](artifacts/splits-txt)</span>.</span>


* **[anvi-gen-gene-consensus-sequences](programs/anvi-gen-gene-consensus-sequences)**: Collapse variability for a set of genes across samples.
<span>**Provides**: <span class="artifact-p">[genes-fasta](artifacts/genes-fasta)</span> / 
<span>**Requires**: <span class="artifact-r">[profile-db](artifacts/profile-db)</span> <span class="artifact-r">[contigs-db](artifacts/contigs-db)</span>.</span>


* **[anvi-gen-gene-level-stats-databases](programs/anvi-gen-gene-level-stats-databases)**: A program to compute genes databases for a ginen set of bins stored in an anvi&#39;o collection. Genes databases store gene-level coverage and detection statistics, and they are usually computed and generated automatically when they are required (such as running anvi-interactive with `--gene-mode` flag). This program allows you to pre-compute them if you don&#39;t want them to be done all at once.
<span>**Provides**: <span class="artifact-p">[genes-db](artifacts/genes-db)</span> / 
<span>**Requires**: <span class="artifact-r">[profile-db](artifacts/profile-db)</span> <span class="artifact-r">[contigs-db](artifacts/contigs-db)</span> <span class="artifact-r">[collection](artifacts/collection)</span> <span class="artifact-r">[bin](artifacts/bin)</span>.</span>


* **[anvi-gen-genomes-storage](programs/anvi-gen-genomes-storage)**: Create a genome storage from internal and/or external genomes for a pangenome analysis.
<span>**Provides**: <span class="artifact-p">[genomes-storage-db](artifacts/genomes-storage-db)</span> / 
<span>**Requires**: <span class="artifact-r">[external-genomes](artifacts/external-genomes)</span> <span class="artifact-r">[internal-genomes](artifacts/internal-genomes)</span>.</span>


* **[anvi-gen-phylogenomic-tree](programs/anvi-gen-phylogenomic-tree)**: Generate phylogenomic tree from aligment file.
<span>**Provides**: <span class="artifact-p">[phylogeny](artifacts/phylogeny)</span> / 
<span>**Requires**: <span class="artifact-r">[concatenated-gene-alignment-fasta](artifacts/concatenated-gene-alignment-fasta)</span>.</span>


* **[anvi-gen-structure-database](programs/anvi-gen-structure-database)**: Identifies genes in your contigs database that encode proteins that are homologous to proteins with solved structures. If sufficiently similar homologs are identified, they are used as structural templates to predict the 3D structure of proteins in your contigs database.
<span>**Provides**: <span class="artifact-p">[structure-db](artifacts/structure-db)</span> / 
<span>**Requires**: <span class="artifact-r">[contigs-db](artifacts/contigs-db)</span> <span class="artifact-r">[pdb-db](artifacts/pdb-db)</span>.</span>


* **[anvi-gen-variability-matrix](programs/anvi-gen-variability-matrix)**: Generate a variability matrix (potentially outdated program).
<span>**Provides**:  / 
<span>**Requires**: <span class="artifact-r">[splits-txt](artifacts/splits-txt)</span> <span class="artifact-r">[contigs-db](artifacts/contigs-db)</span>.</span>


* **[anvi-gen-variability-profile](programs/anvi-gen-variability-profile)**: Generate a table that comprehensively summarizes the variability of nucleotide, codon, or amino acid positions. We call these single nucleotide variants (SNVs), single codon variants (SCVs), and single amino acid variants (SAAVs), respectively. Learn more here: http://merenlab.org/2015/07/20/analyzing-variability/.
<span>**Provides**: <span class="artifact-p">[variability-profile-txt](artifacts/variability-profile-txt)</span> / 
<span>**Requires**: <span class="artifact-r">[contigs-db](artifacts/contigs-db)</span> <span class="artifact-r">[profile-db](artifacts/profile-db)</span> <span class="artifact-r">[structure-db](artifacts/structure-db)</span> <span class="artifact-r">[bin](artifacts/bin)</span> <span class="artifact-r">[variability-profile](artifacts/variability-profile)</span> <span class="artifact-r">[splits-txt](artifacts/splits-txt)</span>.</span>


* **[anvi-get-aa-counts](programs/anvi-get-aa-counts)**: Fetches the number of times each amino acid occurs from a contigs database in a given bin, set of contigs, or set of genes.
<span>**Provides**: <span class="artifact-p">[aa-frequencies-txt](artifacts/aa-frequencies-txt)</span> / 
<span>**Requires**: <span class="artifact-r">[splits-txt](artifacts/splits-txt)</span> <span class="artifact-r">[contigs-db](artifacts/contigs-db)</span> <span class="artifact-r">[profile-db](artifacts/profile-db)</span> <span class="artifact-r">[collection](artifacts/collection)</span>.</span>


* **[anvi-get-codon-frequencies](programs/anvi-get-codon-frequencies)**: Get amino acid or codon frequencies of genes in a contigs database.
<span>**Provides**: <span class="artifact-p">[codon-frequencies-txt](artifacts/codon-frequencies-txt)</span> <span class="artifact-p">[aa-frequencies-txt](artifacts/aa-frequencies-txt)</span> / 
<span>**Requires**: <span class="artifact-r">[contigs-db](artifacts/contigs-db)</span>.</span>


* **[anvi-get-enriched-functions-per-pan-group](programs/anvi-get-enriched-functions-per-pan-group)**: A program that takes a pangenome, and a categorical layers additional data item, and generates a table describing functions that are enriched in those groups. If requested, a functional occurrence table across genomes is also generated.
<span>**Provides**: <span class="artifact-p">[functional-enrichment-txt](artifacts/functional-enrichment-txt)</span> / 
<span>**Requires**: <span class="artifact-r">[misc-data-layers](artifacts/misc-data-layers)</span> <span class="artifact-r">[pan-db](artifacts/pan-db)</span> <span class="artifact-r">[genomes-storage-db](artifacts/genomes-storage-db)</span>.</span>


* **[anvi-get-sequences-for-gene-calls](programs/anvi-get-sequences-for-gene-calls)**: A script to get back sequences for gene calls.
<span>**Provides**: <span class="artifact-p">[genes-fasta](artifacts/genes-fasta)</span> / 
<span>**Requires**: <span class="artifact-r">[contigs-db](artifacts/contigs-db)</span> <span class="artifact-r">[genomes-storage-db](artifacts/genomes-storage-db)</span>.</span>


* **[anvi-get-sequences-for-gene-clusters](programs/anvi-get-sequences-for-gene-clusters)**: Do cool stuff with gene clusters in anvi&#39;o pan genomes.
<span>**Provides**: <span class="artifact-p">[genes-fasta](artifacts/genes-fasta)</span> <span class="artifact-p">[concatenated-gene-alignment-fasta](artifacts/concatenated-gene-alignment-fasta)</span> <span class="artifact-p">[misc-data-items](artifacts/misc-data-items)</span> / 
<span>**Requires**: <span class="artifact-r">[pan-db](artifacts/pan-db)</span> <span class="artifact-r">[genomes-storage-db](artifacts/genomes-storage-db)</span>.</span>


* **[anvi-get-sequences-for-hmm-hits](programs/anvi-get-sequences-for-hmm-hits)**: Get sequences for HMM hits from many inputs.
<span>**Provides**: <span class="artifact-p">[genes-fasta](artifacts/genes-fasta)</span> <span class="artifact-p">[concatenated-gene-alignment-fasta](artifacts/concatenated-gene-alignment-fasta)</span> / 
<span>**Requires**: <span class="artifact-r">[contigs-db](artifacts/contigs-db)</span> <span class="artifact-r">[profile-db](artifacts/profile-db)</span> <span class="artifact-r">[external-genomes](artifacts/external-genomes)</span> <span class="artifact-r">[internal-genomes](artifacts/internal-genomes)</span> <span class="artifact-r">[hmm-source](artifacts/hmm-source)</span> <span class="artifact-r">[hmm-hits](artifacts/hmm-hits)</span>.</span>


* **[anvi-get-short-reads-from-bam](programs/anvi-get-short-reads-from-bam)**: Get short reads back from a BAM file with options for compression, splitting of forward and reverse reads, etc.
<span>**Provides**: <span class="artifact-p">[short-reads-fasta](artifacts/short-reads-fasta)</span> / 
<span>**Requires**: <span class="artifact-r">[profile-db](artifacts/profile-db)</span> <span class="artifact-r">[contigs-db](artifacts/contigs-db)</span> <span class="artifact-r">[bin](artifacts/bin)</span> <span class="artifact-r">[bam-file](artifacts/bam-file)</span>.</span>


* **[anvi-get-short-reads-mapping-to-a-gene](programs/anvi-get-short-reads-mapping-to-a-gene)**: Recover short reads from BAM files that were mapped to genes you are interested in. It is possible to work with a single gene call, or a bunch of them. Similarly, you can get short reads from a single BAM file, or from many of them.
<span>**Provides**: <span class="artifact-p">[short-reads-fasta](artifacts/short-reads-fasta)</span> / 
<span>**Requires**: <span class="artifact-r">[contigs-db](artifacts/contigs-db)</span> <span class="artifact-r">[bam-file](artifacts/bam-file)</span>.</span>


* **[anvi-get-split-coverages](programs/anvi-get-split-coverages)**: Export splits and the coverage table from database.
<span>**Provides**: <span class="artifact-p">[coverages-txt](artifacts/coverages-txt)</span> / 
<span>**Requires**: <span class="artifact-r">[profile-db](artifacts/profile-db)</span> <span class="artifact-r">[contigs-db](artifacts/contigs-db)</span> <span class="artifact-r">[collection](artifacts/collection)</span> <span class="artifact-r">[bin](artifacts/bin)</span>.</span>


* **[anvi-import-collection](programs/anvi-import-collection)**: Import an external binning result into anvi&#39;o.
<span>**Provides**: <span class="artifact-p">[collection](artifacts/collection)</span> / 
<span>**Requires**: <span class="artifact-r">[contigs-db](artifacts/contigs-db)</span> <span class="artifact-r">[profile-db](artifacts/profile-db)</span> <span class="artifact-r">[pan-db](artifacts/pan-db)</span> <span class="artifact-r">[collection-txt](artifacts/collection-txt)</span>.</span>


* **[anvi-import-functions](programs/anvi-import-functions)**: Parse and store functional annotation of genes.
<span>**Provides**: <span class="artifact-p">[functions](artifacts/functions)</span> / 
<span>**Requires**: <span class="artifact-r">[contigs-db](artifacts/contigs-db)</span> <span class="artifact-r">[functions-txt](artifacts/functions-txt)</span>.</span>


* **[anvi-import-items-order](programs/anvi-import-items-order)**: Import a new items order into an anvi&#39;o database.
<span>**Provides**: <span class="artifact-p">[misc-data-items-order](artifacts/misc-data-items-order)</span> / 
<span>**Requires**: <span class="artifact-r">[pan-db](artifacts/pan-db)</span> <span class="artifact-r">[profile-db](artifacts/profile-db)</span> <span class="artifact-r">[misc-data-items-order-txt](artifacts/misc-data-items-order-txt)</span> <span class="artifact-r">[dendrogram](artifacts/dendrogram)</span> <span class="artifact-r">[phylogeny](artifacts/phylogeny)</span>.</span>


* **[anvi-import-misc-data](programs/anvi-import-misc-data)**: Populate additional data or order tables in pan or profile databases for items and layers, OR additional data in contigs databases for nucleotides and amino acids (the Swiss army knife-level serious stuff).
<span>**Provides**: <span class="artifact-p">[misc-data-items](artifacts/misc-data-items)</span> <span class="artifact-p">[misc-data-layers](artifacts/misc-data-layers)</span> <span class="artifact-p">[misc-data-layer-orders](artifacts/misc-data-layer-orders)</span> <span class="artifact-p">[misc-data-nucleotides](artifacts/misc-data-nucleotides)</span> <span class="artifact-p">[misc-data-amino-acids](artifacts/misc-data-amino-acids)</span> / 
<span>**Requires**: <span class="artifact-r">[pan-db](artifacts/pan-db)</span> <span class="artifact-r">[profile-db](artifacts/profile-db)</span> <span class="artifact-r">[contigs-db](artifacts/contigs-db)</span> <span class="artifact-r">[misc-data-items-txt](artifacts/misc-data-items-txt)</span> <span class="artifact-r">[dendrogram](artifacts/dendrogram)</span> <span class="artifact-r">[phylogeny](artifacts/phylogeny)</span> <span class="artifact-r">[misc-data-layers-txt](artifacts/misc-data-layers-txt)</span> <span class="artifact-r">[misc-data-layer-orders-txt](artifacts/misc-data-layer-orders-txt)</span> <span class="artifact-r">[misc-data-nucleotides-txt](artifacts/misc-data-nucleotides-txt)</span> <span class="artifact-r">[misc-data-amino-acids-txt](artifacts/misc-data-amino-acids-txt)</span>.</span>


* **[anvi-import-state](programs/anvi-import-state)**: Import an anvi&#39;o state into a profile database.
<span>**Provides**: <span class="artifact-p">[state](artifacts/state)</span> / 
<span>**Requires**: <span class="artifact-r">[pan-db](artifacts/pan-db)</span> <span class="artifact-r">[profile-db](artifacts/profile-db)</span> <span class="artifact-r">[state-json](artifacts/state-json)</span>.</span>


* **[anvi-import-taxonomy-for-genes](programs/anvi-import-taxonomy-for-genes)**: Import gene-level taxonomy into an anvi&#39;o contigs database.
<span>**Provides**: <span class="artifact-p">[gene-taxonomy](artifacts/gene-taxonomy)</span> / 
<span>**Requires**: <span class="artifact-r">[contigs-db](artifacts/contigs-db)</span> <span class="artifact-r">[gene-taxonomy-txt](artifacts/gene-taxonomy-txt)</span>.</span>


* **[anvi-import-taxonomy-for-layers](programs/anvi-import-taxonomy-for-layers)**: Import layers-level taxonomy into an anvi&#39;o additional layer data table in an anvi&#39;o single-profile database.
<span>**Provides**: <span class="artifact-p">[layer-taxonomy](artifacts/layer-taxonomy)</span> / 
<span>**Requires**: <span class="artifact-r">[single-profile-db](artifacts/single-profile-db)</span> <span class="artifact-r">[layer-taxonomy-txt](artifacts/layer-taxonomy-txt)</span>.</span>


* **[anvi-init-bam](programs/anvi-init-bam)**: Sort/Index BAM files.
<span>**Provides**: <span class="artifact-p">[bam-file](artifacts/bam-file)</span> / 
<span>**Requires**: <span class="artifact-r">[raw-bam-file](artifacts/raw-bam-file)</span>.</span>


* **[anvi-inspect](programs/anvi-inspect)**: Start an anvi&#39;o inspect interactive interface.
<span>**Provides**: <span class="artifact-p">[interactive](artifacts/interactive)</span> / 
<span>**Requires**: <span class="artifact-r">[profile-db](artifacts/profile-db)</span> <span class="artifact-r">[contigs-db](artifacts/contigs-db)</span> <span class="artifact-r">[bin](artifacts/bin)</span>.</span>


* **[anvi-interactive](programs/anvi-interactive)**: Start an anvi&#39;o server for the interactive interface.
<span>**Provides**: <span class="artifact-p">[collection](artifacts/collection)</span> <span class="artifact-p">[bin](artifacts/bin)</span> <span class="artifact-p">[interactive](artifacts/interactive)</span> <span class="artifact-p">[svg](artifacts/svg)</span> / 
<span>**Requires**: <span class="artifact-r">[profile-db](artifacts/profile-db)</span> <span class="artifact-r">[single-profile-db](artifacts/single-profile-db)</span> <span class="artifact-r">[contigs-db](artifacts/contigs-db)</span> <span class="artifact-r">[genes-db](artifacts/genes-db)</span> <span class="artifact-r">[bin](artifacts/bin)</span> <span class="artifact-r">[view-data](artifacts/view-data)</span> <span class="artifact-r">[dendrogram](artifacts/dendrogram)</span> <span class="artifact-r">[phylogeny](artifacts/phylogeny)</span>.</span>


* **[anvi-matrix-to-newick](programs/anvi-matrix-to-newick)**: Takes a distance matrix, returns a newick tree.
<span>**Provides**: <span class="artifact-p">[dendrogram](artifacts/dendrogram)</span> / 
<span>**Requires**: <span class="artifact-r">[view-data](artifacts/view-data)</span>.</span>


* **[anvi-merge](programs/anvi-merge)**: Merge multiple anvio profiles.
<span>**Provides**: <span class="artifact-p">[profile-db](artifacts/profile-db)</span> <span class="artifact-p">[misc-data-items-order](artifacts/misc-data-items-order)</span> / 
<span>**Requires**: <span class="artifact-r">[single-profile-db](artifacts/single-profile-db)</span> <span class="artifact-r">[contigs-db](artifacts/contigs-db)</span>.</span>


* **[anvi-merge-bins](programs/anvi-merge-bins)**: Merge a given set of bins in an anvi&#39;o collection.
<span>**Provides**:  / 
<span>**Requires**: <span class="artifact-r">[pan-db](artifacts/pan-db)</span> <span class="artifact-r">[profile-db](artifacts/profile-db)</span> <span class="artifact-r">[collection](artifacts/collection)</span> <span class="artifact-r">[bin](artifacts/bin)</span>.</span>


* **[anvi-meta-pan-genome](programs/anvi-meta-pan-genome)**: Convert a pangenome into a metapangenome.
<span>**Provides**: <span class="artifact-p">[metapangenome](artifacts/metapangenome)</span> / 
<span>**Requires**: <span class="artifact-r">[internal-genomes](artifacts/internal-genomes)</span> <span class="artifact-r">[pan-db](artifacts/pan-db)</span> <span class="artifact-r">[genomes-storage-db](artifacts/genomes-storage-db)</span>.</span>


* **[anvi-oligotype-linkmers](programs/anvi-oligotype-linkmers)**: Takes an anvi&#39;o linkmers report, generates an oligotyping output.
<span>**Provides**: <span class="artifact-p">[oligotypes](artifacts/oligotypes)</span> / 
<span>**Requires**: <span class="artifact-r">[linkmers-txt](artifacts/linkmers-txt)</span>.</span>


* **[anvi-pan-genome](programs/anvi-pan-genome)**: An anvi&#39;o program to compute a pangenome from an anvi&#39;o genome storage.
<span>**Provides**: <span class="artifact-p">[pan-db](artifacts/pan-db)</span> <span class="artifact-p">[misc-data-items-order](artifacts/misc-data-items-order)</span> / 
<span>**Requires**: <span class="artifact-r">[genomes-storage-db](artifacts/genomes-storage-db)</span>.</span>


* **[anvi-profile](programs/anvi-profile)**: Creates a single anvi&#39;o profile database.                    When it is run on a BAM file, depending on the user parameters, the program quantifies                   coverage per nucleotide position (and averages them  per contig), calculates                   single-nucleotide, single-codon, and single-amino acid variants, as well as structural variants                   such as insertion and deletions and stores these data into appropriate tables.
<span>**Provides**: <span class="artifact-p">[single-profile-db](artifacts/single-profile-db)</span> <span class="artifact-p">[misc-data-items-order](artifacts/misc-data-items-order)</span> <span class="artifact-p">[variability-profile](artifacts/variability-profile)</span> / 
<span>**Requires**: <span class="artifact-r">[bam-file](artifacts/bam-file)</span> <span class="artifact-r">[contigs-db](artifacts/contigs-db)</span>.</span>


* **[anvi-refine](programs/anvi-refine)**: Start an anvi&#39;o interactive interactive to manually curate or refine a genome, whether it is a metagenome-assembled, single-cell, or an isolate genome.
<span>**Provides**: <span class="artifact-p">[bin](artifacts/bin)</span> / 
<span>**Requires**: <span class="artifact-r">[profile-db](artifacts/profile-db)</span> <span class="artifact-r">[contigs-db](artifacts/contigs-db)</span> <span class="artifact-r">[bin](artifacts/bin)</span>.</span>


* **[anvi-rename-bins](programs/anvi-rename-bins)**: Rename all bins in a given collection (so they have pretty names).
<span>**Provides**: <span class="artifact-p">[collection](artifacts/collection)</span> <span class="artifact-p">[bin](artifacts/bin)</span> / 
<span>**Requires**: <span class="artifact-r">[collection](artifacts/collection)</span> <span class="artifact-r">[bin](artifacts/bin)</span> <span class="artifact-r">[profile-db](artifacts/profile-db)</span> <span class="artifact-r">[contigs-db](artifacts/contigs-db)</span>.</span>


* **[anvi-report-linkmers](programs/anvi-report-linkmers)**: Reports sequences stored in one or more BAM files that cover one of more specific nucleotide positions in a reference.
<span>**Provides**: <span class="artifact-p">[linkmers-txt](artifacts/linkmers-txt)</span> / 
<span>**Requires**: <span class="artifact-r">[bam-file](artifacts/bam-file)</span>.</span>


* **[anvi-run-hmms](programs/anvi-run-hmms)**: This program deals with populating tables that store HMM hits in an anvi&#39;o contigs database.
<span>**Provides**: <span class="artifact-p">[hmm-hits](artifacts/hmm-hits)</span> / 
<span>**Requires**: <span class="artifact-r">[contigs-db](artifacts/contigs-db)</span> <span class="artifact-r">[hmm-source](artifacts/hmm-source)</span>.</span>


* **[anvi-run-interacdome](programs/anvi-run-interacdome)**: Run InteracDome on a contigs database.
<span>**Provides**: <span class="artifact-p">[binding-frequencies](artifacts/binding-frequencies)</span> / 
<span>**Requires**: <span class="artifact-r">[contigs-db](artifacts/contigs-db)</span> <span class="artifact-r">[interacdome-data](artifacts/interacdome-data)</span>.</span>


* **[anvi-run-kegg-kofams](programs/anvi-run-kegg-kofams)**: Run KOfam HMMs on an anvi&#39;o contigs database.
<span>**Provides**: <span class="artifact-p">[kegg-functions](artifacts/kegg-functions)</span> <span class="artifact-p">[functions](artifacts/functions)</span> / 
<span>**Requires**: <span class="artifact-r">[contigs-db](artifacts/contigs-db)</span> <span class="artifact-r">[kegg-db](artifacts/kegg-db)</span>.</span>


* **[anvi-run-ncbi-cogs](programs/anvi-run-ncbi-cogs)**: Run NCBI&#39;s COGs to associate genes in an anvi&#39;o contigs database with functions. COGs database was been designed as an attempt to classify proteins from completely sequenced genomes on the basis of the orthology concept. It is no longer actively developed, however, it is still very effective for daily needs. You may want to consider Pfams or the eggNOG database for more comprehensive functional insights.
<span>**Provides**: <span class="artifact-p">[functions](artifacts/functions)</span> / 
<span>**Requires**: <span class="artifact-r">[contigs-db](artifacts/contigs-db)</span> <span class="artifact-r">[cogs-data](artifacts/cogs-data)</span>.</span>


* **[anvi-run-pfams](programs/anvi-run-pfams)**: Run Pfam on Contigs Database.
<span>**Provides**: <span class="artifact-p">[functions](artifacts/functions)</span> / 
<span>**Requires**: <span class="artifact-r">[contigs-db](artifacts/contigs-db)</span> <span class="artifact-r">[pfams-data](artifacts/pfams-data)</span>.</span>


* **[anvi-run-scg-taxonomy](programs/anvi-run-scg-taxonomy)**: The purpose of this program is to affiliate single-copy core genes in an anvi&#39;o contigs database with taxonomic names. A properly setup local SCG taxonomy database is required for this program to perform properly. After its successful run, `anvi-estimate-scg-taxonomy` will be useful to estimate taxonomy at genome-, collection-, or metagenome-level).
<span>**Provides**: <span class="artifact-p">[scgs-taxonomy](artifacts/scgs-taxonomy)</span> / 
<span>**Requires**: <span class="artifact-r">[contigs-db](artifacts/contigs-db)</span> <span class="artifact-r">[scgs-taxonomy-db](artifacts/scgs-taxonomy-db)</span>.</span>


* **[anvi-run-trna-taxonomy](programs/anvi-run-trna-taxonomy)**: The purpose of this program is to affiliate tRNA gene sequences in an anvi&#39;o contigs database with taxonomic names. A properly setup local tRNA taxonomy database is required for this program to perform properly. After its successful run, `anvi-estimate-scg-taxonomy` will be useful to estimate taxonomy at genome-, collection-, or metagenome-level)..
<span>**Provides**: <span class="artifact-p">[trna-taxonomy](artifacts/trna-taxonomy)</span> / 
<span>**Requires**: <span class="artifact-r">[contigs-db](artifacts/contigs-db)</span> <span class="artifact-r">[trna-taxonomy-db](artifacts/trna-taxonomy-db)</span>.</span>


* **[anvi-scan-trnas](programs/anvi-scan-trnas)**: Identify and store tRNA genes in a contigs database.
<span>**Provides**: <span class="artifact-p">[hmm-hits](artifacts/hmm-hits)</span> / 
<span>**Requires**: <span class="artifact-r">[contigs-db](artifacts/contigs-db)</span>.</span>


* **[anvi-search-functions](programs/anvi-search-functions)**: Search functions in an anvi&#39;o contigs database or genomes storage. Basically, this program searches for one or more search terms you define in functional annotations of genes in an anvi&#39;o contigs database, and generates multiple reports. The default report simply tells you which contigs contain genes with functions matching to serach terms you used, useful for viewing in the interface. You can also request a much more comprehensive report, which gives you anything you might need to know for each hit and serach term.
<span>**Provides**: <span class="artifact-p">[functions-txt](artifacts/functions-txt)</span> / 
<span>**Requires**: <span class="artifact-r">[contigs-db](artifacts/contigs-db)</span> <span class="artifact-r">[genomes-storage-db](artifacts/genomes-storage-db)</span>.</span>


* **[anvi-setup-interacdome](programs/anvi-setup-interacdome)**: Setup InteracDome data.
<span>**Provides**: <span class="artifact-p">[interacdome-data](artifacts/interacdome-data)</span> / 
<span>**Requires**: .</span>


* **[anvi-setup-kegg-kofams](programs/anvi-setup-kegg-kofams)**: Download and setup KEGG KOfam HMM profiles.
<span>**Provides**: <span class="artifact-p">[kegg-db](artifacts/kegg-db)</span> / 
<span>**Requires**: .</span>


* **[anvi-setup-ncbi-cogs](programs/anvi-setup-ncbi-cogs)**: Download and setup NCBI&#39;s Clusters of Orthologous Groups database.
<span>**Provides**: <span class="artifact-p">[cogs-data](artifacts/cogs-data)</span> / 
<span>**Requires**: .</span>


* **[anvi-setup-pdb-database](programs/anvi-setup-pdb-database)**: Setup or update an offline database of representative PDB structures clustered at 95%.
<span>**Provides**: <span class="artifact-p">[pdb-db](artifacts/pdb-db)</span> / 
<span>**Requires**: .</span>


* **[anvi-setup-pfams](programs/anvi-setup-pfams)**: Download and setup Pfam data from the EBI.
<span>**Provides**: <span class="artifact-p">[pfams-data](artifacts/pfams-data)</span> / 
<span>**Requires**: .</span>


* **[anvi-setup-scg-taxonomy](programs/anvi-setup-scg-taxonomy)**: The purpose of this program is to download necessary information from GTDB (https://gtdb.ecogenomic.org/), and set it up in such a way that your anvi&#39;o installation is able to assign taxonomy to single-copy core genes using `anvi-run-scg-taxonomy` and estimate taxonomy for genomes or metagenomes using `anvi-estimate-scg-taxonomy`).
<span>**Provides**: <span class="artifact-p">[scgs-taxonomy-db](artifacts/scgs-taxonomy-db)</span> / 
<span>**Requires**: .</span>


* **[anvi-setup-trna-taxonomy](programs/anvi-setup-trna-taxonomy)**: The purpose of this program is to setup necessary databases for tRNA genes collected from GTDB (https://gtdb.ecogenomic.org/), genomes in your local anvi&#39;o installation so taxonomy information for a given set of tRNA sequences can be identified using `anvi-run-trna-taxonomy` and made sense of via `anvi-estimate-trna-taxonomy`)..
<span>**Provides**: <span class="artifact-p">[trna-taxonomy-db](artifacts/trna-taxonomy-db)</span> / 
<span>**Requires**: .</span>


* **[anvi-show-collections-and-bins](programs/anvi-show-collections-and-bins)**: A script to display collections stored in an anvi&#39;o profile or pan database.
<span>**Provides**:  / 
<span>**Requires**: <span class="artifact-r">[pan-db](artifacts/pan-db)</span> <span class="artifact-r">[profile-db](artifacts/profile-db)</span>.</span>


* **[anvi-show-misc-data](programs/anvi-show-misc-data)**: Show all misc data keys in all misc data tables.
<span>**Provides**:  / 
<span>**Requires**: <span class="artifact-r">[pan-db](artifacts/pan-db)</span> <span class="artifact-r">[profile-db](artifacts/profile-db)</span> <span class="artifact-r">[contigs-db](artifacts/contigs-db)</span>.</span>


* **[anvi-split](programs/anvi-split)**: Split an anvi&#39;o pan or profile database into smaller, self-contained pieces. Provide either a genomes-storage and pan database or a profile and contigs database pair, and you&#39;ll get back directories of individual projects for each bin  that can be treated as smaller anvi&#39;o projects.
<span>**Provides**: <span class="artifact-p">[split-bins](artifacts/split-bins)</span> / 
<span>**Requires**: <span class="artifact-r">[profile-db](artifacts/profile-db)</span> <span class="artifact-r">[contigs-db](artifacts/contigs-db)</span> <span class="artifact-r">[genomes-storage-db](artifacts/genomes-storage-db)</span> <span class="artifact-r">[pan-db](artifacts/pan-db)</span> <span class="artifact-r">[collection](artifacts/collection)</span>.</span>


* **[anvi-summarize](programs/anvi-summarize)**: Summarizer for anvi&#39;o pan or profile db&#39;s. Essentially, this program takes a collection id along with either a profile database and a contigs database or a pan database and a genomes storage and generates a static HTML output for what is described in a given collection. The output directory will contain almost everything any downstream analysis may need, and can be displayed using a browser without the need for an anvi&#39;o installation. For this reason alone, reporting summary outputs as supplementary data with publications is a great idea for transparency and reproducibility.
<span>**Provides**: <span class="artifact-p">[summary](artifacts/summary)</span> / 
<span>**Requires**: <span class="artifact-r">[profile-db](artifacts/profile-db)</span> <span class="artifact-r">[contigs-db](artifacts/contigs-db)</span> <span class="artifact-r">[collection](artifacts/collection)</span> <span class="artifact-r">[pan-db](artifacts/pan-db)</span> <span class="artifact-r">[genomes-storage-db](artifacts/genomes-storage-db)</span>.</span>


* **[anvi-trnaseq](programs/anvi-trnaseq)**: An anvi&#39;o script to process a tRNA-seq dataset, generating a tRNA-seq database..
<span>**Provides**: <span class="artifact-p">[trnaseq-db](artifacts/trnaseq-db)</span> / 
<span>**Requires**: .</span>


* **[anvi-update-db-description](programs/anvi-update-db-description)**: Update the description in an anvi&#39;o database.
<span>**Provides**:  / 
<span>**Requires**: <span class="artifact-r">[pan-db](artifacts/pan-db)</span> <span class="artifact-r">[profile-db](artifacts/profile-db)</span> <span class="artifact-r">[contigs-db](artifacts/contigs-db)</span> <span class="artifact-r">[genomes-storage-db](artifacts/genomes-storage-db)</span>.</span>


* **[anvi-update-structure-database](programs/anvi-update-structure-database)**: Add or re-run genes from an already existing structure database. All settings used to generate your database will be used in this program.
<span>**Provides**:  / 
<span>**Requires**: <span class="artifact-r">[contigs-db](artifacts/contigs-db)</span> <span class="artifact-r">[structure-db](artifacts/structure-db)</span>.</span>


* **[anvi-script-add-default-collection](programs/anvi-script-add-default-collection)**: A script to add a &#39;DEFAULT&#39; collection in an anvi&#39;o pan or profile database with a bin named &#39;EVERYTHING&#39; that describes all items available in the profile database.
<span>**Provides**: <span class="artifact-p">[collection](artifacts/collection)</span> <span class="artifact-p">[bin](artifacts/bin)</span> / 
<span>**Requires**: <span class="artifact-r">[pan-db](artifacts/pan-db)</span> <span class="artifact-r">[profile-db](artifacts/profile-db)</span> <span class="artifact-r">[contigs-db](artifacts/contigs-db)</span>.</span>


* **[anvi-script-augustus-output-to-external-gene-calls](programs/anvi-script-augustus-output-to-external-gene-calls)**: Takes in gene calls by AUGUSTUS v3.3.3, generates an anvi&#39;o external gene calls file. It may work well with other versions of AUGUSTUS, too. It is just no one has tested the script with different versions of the program.
<span>**Provides**: <span class="artifact-p">[external-gene-calls](artifacts/external-gene-calls)</span> / 
<span>**Requires**: <span class="artifact-r">[augustus-gene-calls](artifacts/augustus-gene-calls)</span>.</span>


* **[anvi-script-calculate-pn-ps-ratio](programs/anvi-script-calculate-pn-ps-ratio)**: This program calculates for each gene the ratio of pN/pS (the metagenomic analogy of dN/dS; see doi:10.1038/nature11711 and doi:10.7717/peerj.2959) based on metagenomic read recruitment, however, unlike standard pN/pS calculations, it relies on codons rather than nucleotides for accurate estimations of synonimity.
<span>**Provides**:  / 
<span>**Requires**: <span class="artifact-r">[contigs-db](artifacts/contigs-db)</span> <span class="artifact-r">[variability-profile-txt](artifacts/variability-profile-txt)</span>.</span>


* **[anvi-script-compute-ani-for-fasta](programs/anvi-script-compute-ani-for-fasta)**: Run ANI between contigs in a single FASTA file.
<span>**Provides**: <span class="artifact-p">[genome-similarity](artifacts/genome-similarity)</span> / 
<span>**Requires**: <span class="artifact-r">[fasta](artifacts/fasta)</span>.</span>


* **[anvi-script-estimate-genome-size](programs/anvi-script-estimate-genome-size)**: A program to estimate the size of the actual population genome to which a MAG belongs.
<span>**Provides**:  / 
<span>**Requires**: <span class="artifact-r">[contigs-db](artifacts/contigs-db)</span>.</span>


* **[anvi-script-filter-fasta-by-blast](programs/anvi-script-filter-fasta-by-blast)**: Filter FASTA file according to BLAST table (remove sequences with bad BLAST alignment).
<span>**Provides**: <span class="artifact-p">[contigs-fasta](artifacts/contigs-fasta)</span> / 
<span>**Requires**: <span class="artifact-r">[contigs-fasta](artifacts/contigs-fasta)</span> <span class="artifact-r">[blast-table](artifacts/blast-table)</span>.</span>


* **[anvi-script-gen-distribution-of-genes-in-a-bin](programs/anvi-script-gen-distribution-of-genes-in-a-bin)**: Quantify the detection of genes in genomes in metagenomes to identify the environmental core. This is a helper script for anvi&#39;o metapangenomic workflow.
<span>**Provides**:  / 
<span>**Requires**: <span class="artifact-r">[contigs-db](artifacts/contigs-db)</span> <span class="artifact-r">[profile-db](artifacts/profile-db)</span> <span class="artifact-r">[collection](artifacts/collection)</span> <span class="artifact-r">[bin](artifacts/bin)</span>.</span>


* **[anvi-script-gen-hmm-hits-matrix-across-genomes](programs/anvi-script-gen-hmm-hits-matrix-across-genomes)**: A simple script to generate a TAB-delimited file that reports the frequency of HMM hits for a given HMM source across contigs databases.
<span>**Provides**: <span class="artifact-p">[hmm-hits-matrix-txt](artifacts/hmm-hits-matrix-txt)</span> / 
<span>**Requires**: <span class="artifact-r">[external-genomes](artifacts/external-genomes)</span> <span class="artifact-r">[internal-genomes](artifacts/internal-genomes)</span> <span class="artifact-r">[hmm-source](artifacts/hmm-source)</span> <span class="artifact-r">[hmm-hits](artifacts/hmm-hits)</span>.</span>


* **[anvi-script-gen-pseudo-paired-reads-from-fastq](programs/anvi-script-gen-pseudo-paired-reads-from-fastq)**: Take a FASTQ file and convert it into 2 FASTQ files. Each read from the original FASTQ file halved, where one half is put in the R1 FASTQ and the other half is reverse complemented and put in the R2 FASTQ. If you&#39;ve ended up here, things have clearly not gone very well for you, and as I write this sentence, I wholeheartedly sympathize.
<span>**Provides**: <span class="artifact-p">[short-reads-fasta](artifacts/short-reads-fasta)</span> / 
<span>**Requires**: <span class="artifact-r">[short-reads-fasta](artifacts/short-reads-fasta)</span>.</span>


* **[anvi-script-gen-short-reads](programs/anvi-script-gen-short-reads)**: Generate short reads from contigs. Useful to reconstruct mock data sets from already assembled contigs.
<span>**Provides**: <span class="artifact-p">[short-reads-fasta](artifacts/short-reads-fasta)</span> / 
<span>**Requires**: <span class="artifact-r">[configuration-ini](artifacts/configuration-ini)</span>.</span>


* **[anvi-script-gen_stats_for_single_copy_genes.py](programs/anvi-script-gen_stats_for_single_copy_genes.py)**: A simple script to generate info from search tables, given a contigs-db.
<span>**Provides**: <span class="artifact-p">[genes-stats](artifacts/genes-stats)</span> / 
<span>**Requires**: .</span>


* **[anvi-script-get-coverage-from-bam](programs/anvi-script-get-coverage-from-bam)**: Get nucleotide-level, contig-level, or bin-level coverage values from a BAM file.
<span>**Provides**: <span class="artifact-p">[coverages-txt](artifacts/coverages-txt)</span> / 
<span>**Requires**: <span class="artifact-r">[bam-file](artifacts/bam-file)</span> <span class="artifact-r">[collection-txt](artifacts/collection-txt)</span>.</span>


* **[anvi-script-get-hmm-hits-per-gene-call](programs/anvi-script-get-hmm-hits-per-gene-call)**: A simple script to generate a TAB-delimited file gene caller IDs and their HMM hits for a given HMM source.
<span>**Provides**: <span class="artifact-p">[functions-txt](artifacts/functions-txt)</span> / 
<span>**Requires**: <span class="artifact-r">[contigs-db](artifacts/contigs-db)</span> <span class="artifact-r">[hmm-source](artifacts/hmm-source)</span> <span class="artifact-r">[hmm-hits](artifacts/hmm-hits)</span>.</span>


* **[anvi-script-get-short-reads-matching-something](programs/anvi-script-get-short-reads-matching-something)**: You give this program one or more FASTQ files and a short sequence, and it returns all short reads from the FASTQ file that matches to it. The purpose of this is to get back short reads that may be extending into hypervariable regions of genomes, resulting a decreased mappability of short reads in the metagenome given a reference. You often see those areas of genomes as significant dips in coverage, and in most cases with a large number of SNVs. When you provide the downstream conserved sequence, this program allows you to take a better look at those regions at the short read level without any mapping.
<span>**Provides**: <span class="artifact-p">[short-reads-fasta](artifacts/short-reads-fasta)</span> / 
<span>**Requires**: <span class="artifact-r">[fasta](artifacts/fasta)</span>.</span>


* **[anvi-script-merge-collections](programs/anvi-script-merge-collections)**: Generate an additional data file from multiple collections.
<span>**Provides**:  / 
<span>**Requires**: <span class="artifact-r">[contigs-db](artifacts/contigs-db)</span> <span class="artifact-r">[collection-txt](artifacts/collection-txt)</span>.</span>


* **[anvi-script-process-genbank](programs/anvi-script-process-genbank)**: This script takes a GenBank file, and outputs a FASTA file, as well as two additional TAB-delimited output files for external gene calls and gene functions that can be used with the programs `anvi-gen-contigs-database` and `anvi-import-functions`.
<span>**Provides**: <span class="artifact-p">[contigs-fasta](artifacts/contigs-fasta)</span> <span class="artifact-p">[external-gene-calls](artifacts/external-gene-calls)</span> <span class="artifact-p">[functions-txt](artifacts/functions-txt)</span> / 
<span>**Requires**: <span class="artifact-r">[genbank-file](artifacts/genbank-file)</span>.</span>


* **[anvi-script-process-genbank-metadata](programs/anvi-script-process-genbank-metadata)**: This script takes the &#39;metadata&#39; output of the program `ncbi-genome-download` (see https://github.com/kblin/ncbi-genome-download for details), and processes each GenBank file found in the metadata file to generate a FASTA file, as well as genes and functions files for each entry. Plus, it autmatically generates a FASTA TXT file descriptor for anvi&#39;o snakemake workfloes. So it is a multi-talented program like that.
<span>**Provides**: <span class="artifact-p">[contigs-fasta](artifacts/contigs-fasta)</span> <span class="artifact-p">[functions-txt](artifacts/functions-txt)</span> <span class="artifact-p">[external-gene-calls](artifacts/external-gene-calls)</span> / 
<span>**Requires**: .</span>


* **[anvi-script-reformat-fasta](programs/anvi-script-reformat-fasta)**: Reformat FASTA file (remove contigs based on length, or based on a given list of deflines, and/or generate an output with simpler names).
<span>**Provides**: <span class="artifact-p">[contigs-fasta](artifacts/contigs-fasta)</span> / 
<span>**Requires**: <span class="artifact-r">[fasta](artifacts/fasta)</span>.</span>


* **[anvi-script-snvs-to-interactive](programs/anvi-script-snvs-to-interactive)**: Take the output of anvi-gen-variability-profile, prepare an output for interactive interface.
<span>**Provides**: <span class="artifact-p">[interactive](artifacts/interactive)</span> / 
<span>**Requires**: <span class="artifact-r">[variability-profile-txt](artifacts/variability-profile-txt)</span>.</span>


* **[anvi-script-variability-to-vcf](programs/anvi-script-variability-to-vcf)**: A script to convert SNV output obtained from anvi-gen-variability-profile to the standard VCF format.
<span>**Provides**: <span class="artifact-p">[vcf](artifacts/vcf)</span> / 
<span>**Requires**: <span class="artifact-r">[variability-profile-txt](artifacts/variability-profile-txt)</span>.</span>



## Artifacts

A total of 92 artifacts.

* <span style="line-height: 25px;"><span class="artifact-n">[pan-db](artifacts/pan-db)</span> <span class="artifact-n">[contigs-db](artifacts/contigs-db)</span> <span class="artifact-n">[trnaseq-db](artifacts/trnaseq-db)</span> <span class="artifact-n">[fasta](artifacts/fasta)</span> <span class="artifact-n">[contigs-fasta](artifacts/contigs-fasta)</span> <span class="artifact-n">[configuration-ini](artifacts/configuration-ini)</span> <span class="artifact-n">[external-gene-calls](artifacts/external-gene-calls)</span> <span class="artifact-n">[concatenated-gene-alignment-fasta](artifacts/concatenated-gene-alignment-fasta)</span> <span class="artifact-n">[short-reads-fasta](artifacts/short-reads-fasta)</span> <span class="artifact-n">[genes-fasta](artifacts/genes-fasta)</span> <span class="artifact-n">[bam-file](artifacts/bam-file)</span> <span class="artifact-n">[protein-structure](artifacts/protein-structure)</span> <span class="artifact-n">[raw-bam-file](artifacts/raw-bam-file)</span> <span class="artifact-n">[locus-fasta](artifacts/locus-fasta)</span> <span class="artifact-n">[structure-db](artifacts/structure-db)</span> <span class="artifact-n">[pdb-db](artifacts/pdb-db)</span> <span class="artifact-n">[kegg-db](artifacts/kegg-db)</span> <span class="artifact-n">[single-profile-db](artifacts/single-profile-db)</span> <span class="artifact-n">[profile-db](artifacts/profile-db)</span> <span class="artifact-n">[genes-db](artifacts/genes-db)</span> <span class="artifact-n">[genomes-storage-db](artifacts/genomes-storage-db)</span> <span class="artifact-n">[contigs-stats](artifacts/contigs-stats)</span> <span class="artifact-n">[svg](artifacts/svg)</span> <span class="artifact-n">[bin](artifacts/bin)</span> <span class="artifact-n">[collection](artifacts/collection)</span> <span class="artifact-n">[collection-txt](artifacts/collection-txt)</span> <span class="artifact-n">[hmm-source](artifacts/hmm-source)</span> <span class="artifact-n">[hmm-hits](artifacts/hmm-hits)</span> <span class="artifact-n">[completion](artifacts/completion)</span> <span class="artifact-n">[cogs-data](artifacts/cogs-data)</span> <span class="artifact-n">[pfams-data](artifacts/pfams-data)</span> <span class="artifact-n">[misc-data-items-txt](artifacts/misc-data-items-txt)</span> <span class="artifact-n">[misc-data-items](artifacts/misc-data-items)</span> <span class="artifact-n">[misc-data-layers-txt](artifacts/misc-data-layers-txt)</span> <span class="artifact-n">[misc-data-layers](artifacts/misc-data-layers)</span> <span class="artifact-n">[misc-data-nucleotides-txt](artifacts/misc-data-nucleotides-txt)</span> <span class="artifact-n">[misc-data-nucleotides](artifacts/misc-data-nucleotides)</span> <span class="artifact-n">[misc-data-amino-acids-txt](artifacts/misc-data-amino-acids-txt)</span> <span class="artifact-n">[misc-data-amino-acids](artifacts/misc-data-amino-acids)</span> <span class="artifact-n">[genome-similarity](artifacts/genome-similarity)</span> <span class="artifact-n">[misc-data-layer-orders-txt](artifacts/misc-data-layer-orders-txt)</span> <span class="artifact-n">[misc-data-layer-orders](artifacts/misc-data-layer-orders)</span> <span class="artifact-n">[misc-data-items-order-txt](artifacts/misc-data-items-order-txt)</span> <span class="artifact-n">[misc-data-items-order](artifacts/misc-data-items-order)</span> <span class="artifact-n">[dendrogram](artifacts/dendrogram)</span> <span class="artifact-n">[metapangenome](artifacts/metapangenome)</span> <span class="artifact-n">[oligotypes](artifacts/oligotypes)</span> <span class="artifact-n">[linkmers-txt](artifacts/linkmers-txt)</span> <span class="artifact-n">[phylogeny](artifacts/phylogeny)</span> <span class="artifact-n">[gene-calls-txt](artifacts/gene-calls-txt)</span> <span class="artifact-n">[binding-frequencies](artifacts/binding-frequencies)</span> <span class="artifact-n">[interacdome-data](artifacts/interacdome-data)</span> <span class="artifact-n">[functions](artifacts/functions)</span> <span class="artifact-n">[functions-txt](artifacts/functions-txt)</span> <span class="artifact-n">[functional-enrichment-txt](artifacts/functional-enrichment-txt)</span> <span class="artifact-n">[kegg-functions](artifacts/kegg-functions)</span> <span class="artifact-n">[interactive](artifacts/interactive)</span> <span class="artifact-n">[view-data](artifacts/view-data)</span> <span class="artifact-n">[layer-taxonomy](artifacts/layer-taxonomy)</span> <span class="artifact-n">[layer-taxonomy-txt](artifacts/layer-taxonomy-txt)</span> <span class="artifact-n">[gene-taxonomy](artifacts/gene-taxonomy)</span> <span class="artifact-n">[gene-taxonomy-txt](artifacts/gene-taxonomy-txt)</span> <span class="artifact-n">[genome-taxonomy](artifacts/genome-taxonomy)</span> <span class="artifact-n">[genome-taxonomy-txt](artifacts/genome-taxonomy-txt)</span> <span class="artifact-n">[scgs-taxonomy-db](artifacts/scgs-taxonomy-db)</span> <span class="artifact-n">[scgs-taxonomy](artifacts/scgs-taxonomy)</span> <span class="artifact-n">[trna-taxonomy-db](artifacts/trna-taxonomy-db)</span> <span class="artifact-n">[trna-taxonomy](artifacts/trna-taxonomy)</span> <span class="artifact-n">[external-genomes](artifacts/external-genomes)</span> <span class="artifact-n">[internal-genomes](artifacts/internal-genomes)</span> <span class="artifact-n">[metagenomes](artifacts/metagenomes)</span> <span class="artifact-n">[coverages-txt](artifacts/coverages-txt)</span> <span class="artifact-n">[detection-txt](artifacts/detection-txt)</span> <span class="artifact-n">[variability-profile](artifacts/variability-profile)</span> <span class="artifact-n">[variability-profile-txt](artifacts/variability-profile-txt)</span> <span class="artifact-n">[codon-frequencies-txt](artifacts/codon-frequencies-txt)</span> <span class="artifact-n">[aa-frequencies-txt](artifacts/aa-frequencies-txt)</span> <span class="artifact-n">[fixation-index-matrix](artifacts/fixation-index-matrix)</span> <span class="artifact-n">[summary](artifacts/summary)</span> <span class="artifact-n">[split-bins](artifacts/split-bins)</span> <span class="artifact-n">[state](artifacts/state)</span> <span class="artifact-n">[ngrams](artifacts/ngrams)</span> <span class="artifact-n">[state-json](artifacts/state-json)</span> <span class="artifact-n">[kegg-metabolism](artifacts/kegg-metabolism)</span> <span class="artifact-n">[augustus-gene-calls](artifacts/augustus-gene-calls)</span> <span class="artifact-n">[genes-stats](artifacts/genes-stats)</span> <span class="artifact-n">[vcf](artifacts/vcf)</span> <span class="artifact-n">[blast-table](artifacts/blast-table)</span> <span class="artifact-n">[splits-txt](artifacts/splits-txt)</span> <span class="artifact-n">[genbank-file](artifacts/genbank-file)</span> <span class="artifact-n">[splits-taxonomy-txt](artifacts/splits-taxonomy-txt)</span> <span class="artifact-n">[hmm-hits-matrix-txt](artifacts/hmm-hits-matrix-txt)</span>.</span>
