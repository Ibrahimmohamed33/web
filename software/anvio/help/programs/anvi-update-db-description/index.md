---
layout: page
title: anvi-update-db-description [program]
categories: [anvio]
comments: false
image:
  featurerelative: ../../../images/header.png
  display: true
---

Update the description in an anvi&#39;o database.

See **[program help menu](../../../vignette#anvi-update-db-description)** or go back to the **[main page](../../)** of anvi'o programs and artifacts.


{% include _toc.html %}
<div id="svg" class="subnetwork"></div>
{% capture network_path %}{{ "network.json" }}{% endcapture %}
{% capture network_height %}{{ 300 }}{% endcapture %}
{% include _project-anvio-graph.html %}


## Provides

<p style="text-align: left" markdown="1"></p>

## Requires or uses

<p style="text-align: left" markdown="1"><span class="artifact-r">[pan-db](../../artifacts/pan-db)</span> <span class="artifact-r">[profile-db](../../artifacts/profile-db)</span> <span class="artifact-r">[contigs-db](../../artifacts/contigs-db)</span> <span class="artifact-r">[genomes-storage-db](../../artifacts/genomes-storage-db)</span></p>

## Usage


This program allows you to update the description of any anvi'o database with the push of a button (and the writing of an updated description). 

This descirption helps make UIs a little prettier by showing up when you run programs like <span class="artifact-n">[anvi-interactive](/software/anvio/help/programs/anvi-interactive)</span> and <span class="artifact-n">[anvi-summarize](/software/anvio/help/programs/anvi-summarize)</span>. 

Simply write out the description that you would prefer in a plain text file (with markdown syntax) and use this program to update the description of any <span class="artifact-n">[pan-db](/software/anvio/help/artifacts/pan-db)</span>, <span class="artifact-n">[profile-db](/software/anvio/help/artifacts/profile-db)</span>, <span class="artifact-n">[contigs-db](/software/anvio/help/artifacts/contigs-db)</span>, or <span class="artifact-n">[genomes-storage-db](/software/anvio/help/artifacts/genomes-storage-db)</span>: 

<div class="codeblock" markdown="1">
anvi&#45;update&#45;db&#45;description &#45;&#45;description my_description.txt \
                           <span class="artifact&#45;n">[contigs&#45;db](/software/anvio/help/artifacts/contigs&#45;db)</span>
</div>



{:.notice}
Edit [this file](https://github.com/merenlab/anvio/tree/master/anvio/docs/programs/anvi-update-db-description.md) to update this information.


## Additional Resources



{:.notice}
Are you aware of resources that may help users better understand the utility of this program? Please feel free to edit [this file](https://github.com/merenlab/anvio/tree/master/bin/anvi-update-db-description) on GitHub. If you are not sure how to do that, find the `__resources__` tag in [this file](https://github.com/merenlab/anvio/blob/master/bin/anvi-interactive) to see an example.
