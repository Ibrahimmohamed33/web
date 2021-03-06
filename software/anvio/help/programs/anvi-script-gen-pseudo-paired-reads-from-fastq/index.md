---
layout: page
title: anvi-script-gen-pseudo-paired-reads-from-fastq [program]
categories: [anvio]
comments: false
image:
  featurerelative: ../../../images/header.png
  display: true
---

Take a FASTQ file and convert it into 2 FASTQ files. Each read from the original FASTQ file halved, where one half is put in the R1 FASTQ and the other half is reverse complemented and put in the R2 FASTQ. If you&#39;ve ended up here, things have clearly not gone very well for you, and as I write this sentence, I wholeheartedly sympathize.

See **[program help menu](../../../vignette#anvi-script-gen-pseudo-paired-reads-from-fastq)** or go back to the **[main page](../../)** of anvi'o programs and artifacts.


{% include _toc.html %}
<div id="svg" class="subnetwork"></div>
{% capture network_path %}{{ "network.json" }}{% endcapture %}
{% capture network_height %}{{ 300 }}{% endcapture %}
{% include _project-anvio-graph.html %}


## Provides

<p style="text-align: left" markdown="1"><span class="artifact-p">[short-reads-fasta](../../artifacts/short-reads-fasta)</span></p>

## Requires or uses

<p style="text-align: left" markdown="1"><span class="artifact-r">[short-reads-fasta](../../artifacts/short-reads-fasta)</span></p>

## Usage


{:.notice}
**No one has described the usage of this program** :/ If you would like to contribute, please see previous examples [here](https://github.com/merenlab/anvio/tree/master/anvio/docs/programs), and feel free to add a Markdown formatted file in that directory named "anvi-script-gen-pseudo-paired-reads-from-fastq.md". For a template, you can use the markdown file for `anvi-gen-contigs-database`. THANK YOU!


## Additional Resources



{:.notice}
Are you aware of resources that may help users better understand the utility of this program? Please feel free to edit [this file](https://github.com/merenlab/anvio/tree/master/bin/anvi-script-gen-pseudo-paired-reads-from-fastq) on GitHub. If you are not sure how to do that, find the `__resources__` tag in [this file](https://github.com/merenlab/anvio/blob/master/bin/anvi-interactive) to see an example.
