---
layout: page
title: anvi-summarize [program]
categories: [anvio]
comments: false
image:
  featurerelative: ../../../images/header.png
  display: true
---

Summarizer for anvi&#39;o pan or profile db&#39;s. Essentially, this program takes a collection id along with either a profile database and a contigs database or a pan database and a genomes storage and generates a static HTML output for what is described in a given collection. The output directory will contain almost everything any downstream analysis may need, and can be displayed using a browser without the need for an anvi&#39;o installation. For this reason alone, reporting summary outputs as supplementary data with publications is a great idea for transparency and reproducibility.

See **[program help menu](../../../vignette#anvi-summarize)** or go back to the **[main page](../../)** of anvi'o programs and artifacts.


{% include _toc.html %}
<div id="svg" class="subnetwork"></div>
{% capture network_path %}{{ "network.json" }}{% endcapture %}
{% capture network_height %}{{ 300 }}{% endcapture %}
{% include _project-anvio-graph.html %}


## Provides

<p style="text-align: left" markdown="1"><span class="artifact-p">[summary](../../artifacts/summary)</span></p>

## Requires or uses

<p style="text-align: left" markdown="1"><span class="artifact-r">[profile-db](../../artifacts/profile-db)</span> <span class="artifact-r">[contigs-db](../../artifacts/contigs-db)</span> <span class="artifact-r">[collection](../../artifacts/collection)</span> <span class="artifact-r">[pan-db](../../artifacts/pan-db)</span> <span class="artifact-r">[genomes-storage-db](../../artifacts/genomes-storage-db)</span></p>

## Usage


Anvi-summarize lets you look at a **comprehensive overview of your <span class="artifact-n">[collection](/software/anvio/help/artifacts/collection)</span>** and its many statistics that anvi'o has calculated. 

It will create a folder called `SUMMARY` that contains many different summary files, including an HTML output that conviently displays them all for you. This folder will contain anything a future user might use to import your collection, so it's useful to send to others or transfer an entire anvi'o collection and all of its data. 

In a little more detail, this program will   
* generate <span class="artifact-n">[fasta](/software/anvio/help/artifacts/fasta)</span> files containing your original contigs.   
* estimate various stats about each of your bins, including competition, redundacy, and information about all of your <span class="artifact-n">[hmm-hits](/software/anvio/help/artifacts/hmm-hits)</span>    
* generate various tab-delimited matrix files with information about your bins across your samples, including various statistics.   

## Running anvi-summarize 

### Running on a profile database

A standard run of anvi-summarize on a <span class="artifact-n">[profile-db](/software/anvio/help/artifacts/profile-db)</span> will look something like this:

<div class="codeblock" markdown="1">
anvi&#45;summarize &#45;c <span class="artifact&#45;n">[contigs&#45;db](/software/anvio/help/artifacts/contigs&#45;db)</span> \
               &#45;p <span class="artifact&#45;n">[profile&#45;db](/software/anvio/help/artifacts/profile&#45;db)</span> \
               &#45;o MY_SUMMARY \
               &#45;C <span class="artifact&#45;n">[collection](/software/anvio/help/artifacts/collection)</span>
</div>

This will name the output directory `MY_SUMMARY` instead of the standard `SUMMARY`. 

When running on a profile database, you also have options to 
* output very accurate (but intensely processed) coverage and detection data for each gene (using `--init-gene-coverages`)
* edit your contig names so that they contain the name of the bin that the contig is in (using `--reformat-contig-names`)
* also display the amino acid sequeunces for your gene calls.  (using `--report-aa-seqs-for-gene-calls`)

### Running on a pan database

When running on a <span class="artifact-n">[pan-db](/software/anvio/help/artifacts/pan-db)</span>, you'll want to instead provide the associated genomes storage database. 

<div class="codeblock" markdown="1">
anvi&#45;summarize &#45;g <span class="artifact&#45;n">[genomes&#45;storage&#45;db](/software/anvio/help/artifacts/genomes&#45;storage&#45;db)</span> \
               &#45;p <span class="artifact&#45;n">[pan&#45;db](/software/anvio/help/artifacts/pan&#45;db)</span> \
               &#45;C <span class="artifact&#45;n">[collection](/software/anvio/help/artifacts/collection)</span> 
</div>

You can also choose to display DNA sequences for your gene clusters instead of amino acid sequences with the flag `--report-DNA-sequences`

### Other notes

If you're unsure what collections are in your database, you can run this program with the flag `--list-collections` or by running <span class="artifact-n">[anvi-show-collections-and-bins](/software/anvio/help/programs/anvi-show-collections-and-bins)</span>.

You can also use the flag `--quick-summary` to get a less comprehensive summary with a much shorter processing time. 


{:.notice}
Edit [this file](https://github.com/merenlab/anvio/tree/master/anvio/docs/programs/anvi-summarize.md) to update this information.


## Additional Resources



{:.notice}
Are you aware of resources that may help users better understand the utility of this program? Please feel free to edit [this file](https://github.com/merenlab/anvio/tree/master/bin/anvi-summarize) on GitHub. If you are not sure how to do that, find the `__resources__` tag in [this file](https://github.com/merenlab/anvio/blob/master/bin/anvi-interactive) to see an example.
