---
layout: page
title: anvi-delete-misc-data [program]
categories: [anvio]
comments: false
image:
  featurerelative: ../../../images/header.png
  display: true
---

Remove stuff from &#39;additional data&#39; or &#39;order&#39; tables for either items or layers in either pan or profile databases. OR, remove stuff from the &#39;additional data&#39; tables for nucleotides or amino acids in contigs databases.

See **[program help menu](../../../vignette#anvi-delete-misc-data)** or go back to the **[main page](../../)** of anvi'o programs and artifacts.


{% include _toc.html %}
<div id="svg" class="subnetwork"></div>
{% capture network_path %}{{ "network.json" }}{% endcapture %}
{% capture network_height %}{{ 300 }}{% endcapture %}
{% include _project-anvio-graph.html %}


## Provides

<p style="text-align: left" markdown="1"></p>

## Requires or uses

<p style="text-align: left" markdown="1"><span class="artifact-r">[pan-db](../../artifacts/pan-db)</span> <span class="artifact-r">[profile-db](../../artifacts/profile-db)</span> <span class="artifact-r">[misc-data-items](../../artifacts/misc-data-items)</span> <span class="artifact-r">[misc-data-layers](../../artifacts/misc-data-layers)</span> <span class="artifact-r">[misc-data-layer-orders](../../artifacts/misc-data-layer-orders)</span> <span class="artifact-r">[misc-data-nucleotides](../../artifacts/misc-data-nucleotides)</span> <span class="artifact-r">[misc-data-amino-acids](../../artifacts/misc-data-amino-acids)</span></p>

## Usage


After you've added misc-data of some kind (<span class="artifact-n">[misc-data-items](/software/anvio/help/artifacts/misc-data-items)</span>, <span class="artifact-n">[misc-data-layers](/software/anvio/help/artifacts/misc-data-layers)</span>, <span class="artifact-n">[misc-data-layer-orders](/software/anvio/help/artifacts/misc-data-layer-orders)</span>, <span class="artifact-n">[misc-data-nucleotides](/software/anvio/help/artifacts/misc-data-nucleotides)</span>, or <span class="artifact-n">[misc-data-amino-acids](/software/anvio/help/artifacts/misc-data-amino-acids)</span>) using <span class="artifact-n">[anvi-import-misc-data](/software/anvio/help/programs/anvi-import-misc-data)</span>, you can **delete that data and remove it from the interactive interface** using this program. 

This program will release your data into the ether, never to be seen again. If you would like to first export it into a text file (so that it can be seen again), you can do so with <span class="artifact-n">[anvi-export-misc-data](/software/anvio/help/programs/anvi-export-misc-data)</span>. 

This program only works on data that is listed as an available key (most often because it was previously imported by the user). To view available keys, call either

<div class="codeblock" markdown="1">
anvi&#45;delete&#45;misc&#45;data &#45;p <span class="artifact&#45;n">[profile&#45;db](/software/anvio/help/artifacts/profile&#45;db)</span> \
                      &#45;&#45;target&#45;data&#45;table items|layers|layer_orders \
                      &#45;&#45;list&#45;available&#45;keys
</div>

or 

<div class="codeblock" markdown="1">
anvi&#45;delete&#45;misc&#45;data &#45;c <span class="artifact&#45;n">[contigs&#45;db](/software/anvio/help/artifacts/contigs&#45;db)</span> \
                      &#45;&#45;target&#45;data&#45;table nucleotides|amino_acids \
                      &#45;&#45;list&#45;available&#45;keys
</div>

where you choose the appropriate option for the `taget-data-table`. 

If your misc-data is associated with a specific data group, you can provide that data group to this program with the `-D` flag. 

## Data types you can delete 

### From a pan-db or profile-db: items, layers, layer orders

**From a <span class="artifact-n">[pan-db](/software/anvio/help/artifacts/pan-db)</span> or <span class="artifact-n">[profile-db](/software/anvio/help/artifacts/profile-db)</span>, you can delete**

- items data (<span class="artifact-n">[misc-data-items](/software/anvio/help/artifacts/misc-data-items)</span>) 

<div class="codeblock" markdown="1">
anvi&#45;delete&#45;misc&#45;data &#45;p <span class="artifact&#45;n">[profile&#45;db](/software/anvio/help/artifacts/profile&#45;db)</span> \
                      &#45;&#45;target&#45;data&#45;table items \
                      &#45;&#45;keys&#45;to&#45;remove key_1
</div>

- layers data (<span class="artifact-n">[misc-data-layers](/software/anvio/help/artifacts/misc-data-layers)</span>)

<div class="codeblock" markdown="1">
anvi&#45;delete&#45;misc&#45;data &#45;p <span class="artifact&#45;n">[pan&#45;db](/software/anvio/help/artifacts/pan&#45;db)</span> \
                      &#45;&#45;target&#45;data&#45;table layers \
                      &#45;&#45;keys&#45;to&#45;remove key_2,key_3
</div>

- layer orders data (<span class="artifact-n">[misc-data-layer-orders](/software/anvio/help/artifacts/misc-data-layer-orders)</span>)

<div class="codeblock" markdown="1">
anvi&#45;delete&#45;misc&#45;data &#45;p <span class="artifact&#45;n">[profile&#45;db](/software/anvio/help/artifacts/profile&#45;db)</span> \
                      &#45;&#45;target&#45;data&#45;table layer_orders \
                      &#45;&#45;keys&#45;to&#45;remove key_4
</div>

### From a contigs-db: nucleotide and amino acid data

**From a <span class="artifact-n">[contigs-db](/software/anvio/help/artifacts/contigs-db)</span>, you can delete**

- nucleotide data (<span class="artifact-n">[misc-data-nucleotides](/software/anvio/help/artifacts/misc-data-nucleotides)</span>)

<div class="codeblock" markdown="1">
anvi&#45;delete&#45;misc&#45;data &#45;c <span class="artifact&#45;n">[contigs&#45;db](/software/anvio/help/artifacts/contigs&#45;db)</span> \
                      &#45;&#45;target&#45;data&#45;table nucleotides \
                      &#45;&#45;keys&#45;to&#45;remove key_1
</div>

- amino acid data (<span class="artifact-n">[misc-data-amino-acids](/software/anvio/help/artifacts/misc-data-amino-acids)</span>)

<div class="codeblock" markdown="1">
anvi&#45;delete&#45;misc&#45;data &#45;c <span class="artifact&#45;n">[contigs&#45;db](/software/anvio/help/artifacts/contigs&#45;db)</span> \
                      &#45;&#45;target&#45;data&#45;table amino_acids \
                      &#45;&#45;keys&#45;to&#45;remove key_2
</div>


{:.notice}
Edit [this file](https://github.com/merenlab/anvio/tree/master/anvio/docs/programs/anvi-delete-misc-data.md) to update this information.


## Additional Resources


* [Working with anvi&#39;o additional data tables](http://merenlab.org/2017/12/11/additional-data-tables/#views-items-layers-orders-some-anvio-terminology)


{:.notice}
Are you aware of resources that may help users better understand the utility of this program? Please feel free to edit [this file](https://github.com/merenlab/anvio/tree/master/bin/anvi-delete-misc-data) on GitHub. If you are not sure how to do that, find the `__resources__` tag in [this file](https://github.com/merenlab/anvio/blob/master/bin/anvi-interactive) to see an example.
