+++
title = "Research"
type = "research"
+++

<div class="research-summary">
<p>Our group develops novel computational methods that combine big-data algorithms and machine learning to make sense of the ever-growing universe of biological sequences and structures. We build fast, open-source tools that search, cluster, assemble, and predict proteins and genomes at the scale of entire databases — turning massive genomic and proteomic datasets into biological insight, from microbial communities to the organization of the protein structure universe.</p>

</div>

<div class="methods-layout">
<div class="methods-aside">
<div class="research-legend">
<div>*: First author</div>
<div>†: Corresponding author</div>
<div>Lab members in bold</div>
</div>
</div>
<div class="methods-list">
<div class="research-methods">

<div class="method-category">
<h3 class="method-category-title">Sequence search &amp; clustering</h3>

<div class="method-item">
<div class="method-logo">
<img src="/img/mmseqs2_logo.png" alt="MMseqs2 logo" class="method-char">
<img src="/img/mmseqs2_anim.svg" alt="MMseqs2: a query sequence searched against a database of sequences" class="method-anim">
</div>
<div class="method-body">
<p><b>MMseqs2</b> (Many-against-Many sequence searching) is a software suite to search and cluster huge protein and nucleotide sequence sets, running orders of magnitude faster than BLAST while matching PSI-BLAST sensitivity in profile searches.</p>
<div class="method-refs"><div class="method-ref"><strong>Steinegger M.</strong>*, Söding J.† (2017) MMseqs2: Sensitive protein sequence searching for the analysis of massive data sets, <em>Nature Biotechnology</em> <a href="https://www.biorxiv.org/content/10.1101/079681v5.full">[preprint]</a> <a href="https://www.nature.com/articles/nbt.3988">[journal]</a> <a href="https://github.com/soedinglab/mmseqs2">[software]</a></div>
<div class="method-ref">Kallenborn F.*, Chacón A.*, Hundt C., Sirelkhatim H., Didi K., <strong>Cha S.</strong>, Dallago C., <strong>Mirdita M.</strong>, Schmidt B., <strong>Steinegger M.</strong>† (2025) GPU-accelerated homology search with MMseqs2, <em>Nature Methods</em> <a href="https://www.nature.com/articles/s41592-025-02819-8">[journal]</a> <a href="https://github.com/soedinglab/MMseqs2">[software]</a></div>
</div>
</div>
</div>

<div class="method-item">
<div class="method-logo">
<img src="/img/linclust_logo.png" alt="Linclust logo" class="method-char">
<img src="/img/linclust_anim.svg" alt="Linclust: members linking to cluster representatives" class="method-anim">
</div>
<div class="method-body">
<p><b>Linclust</b> clusters huge sequence sets with a runtime that scales linearly with input size — not quadratically as in conventional algorithms — making it orders of magnitude faster than comparable methods.</p>
<div class="method-refs"><div class="method-ref"><strong>Steinegger M.</strong>*†, Söding J.† (2018) Clustering huge protein sequence sets in linear time, <em>Nature Communications</em> <a href="https://www.biorxiv.org/content/10.1101/104034v4">[preprint]</a> <a href="https://www.nature.com/articles/s41467-018-04964-5">[journal]</a> <a href="https://github.com/soedinglab/mmseqs2">[software]</a></div>
</div>
</div>
</div>

</div>

<div class="method-category">
<h3 class="method-category-title">Protein structure</h3>

<div class="method-item">
<div class="method-logo">
<img src="/img/folddisco_logo.png" alt="Folddisco logo" class="method-char">
<img src="/img/folddisco_anim.svg" alt="Folddisco: distant residues connecting into a structural motif" class="method-anim">
</div>
<div class="method-body">
<p><b>Folddisco</b> indexes and searches discontinuous structural motifs — such as catalytic sites and binding pockets whose residues are distant in sequence — enabling fast motif queries across millions of protein structures.</p>
<div class="method-refs"><div class="method-ref"><strong>Kim H.</strong>*, <strong>Kim R.S.</strong>, <strong>Mirdita M.</strong>, <strong>Yoon J.</strong>, <strong>Steinegger M.</strong>† (2026) Structural motif search across the protein universe with Folddisco, <em>Nature Biotechnology</em> <a href="https://www.nature.com/articles/s41587-026-03162-9">[journal]</a> <a href="https://github.com/steineggerlab/folddisco">[software]</a></div>
</div>
</div>
</div>

<div class="method-item">
<div class="method-logo">
<img src="/img/foldmason_logo.png" alt="FoldMason logo" class="method-char">
<img src="/img/foldmason_anim.svg" alt="FoldMason: backbones sliding into a multiple structure alignment" class="method-anim">
</div>
<div class="method-body">
<p><b>FoldMason</b> builds accurate multiple structure alignments of proteins at scale, leveraging structural information to align thousands of remote homologs that elude sequence-based methods and to reconstruct their evolutionary relationships.</p>
<div class="method-refs"><div class="method-ref"><strong>Gilchrist C.L.M.</strong>*†, <strong>Mirdita M.</strong>, <strong>Steinegger M.</strong>† (2026) Multiple protein structure alignment at scale with FoldMason, <em>Science</em> <a href="https://www.science.org/doi/10.1126/science.ads6733">[journal]</a> <a href="https://github.com/steineggerlab/foldmason">[software]</a></div>
</div>
</div>
</div>

<div class="method-item">
<div class="method-logo">
<img src="/img/foldseek_logo.png" alt="Foldseek-Multimer logo" class="method-char">
<img src="/img/foldseek_multimer_anim.svg" alt="Foldseek-Multimer: chains assembling into a protein complex" class="method-anim">
</div>
<div class="method-body">
<p><b>Foldseek-Multimer</b> extends Foldseek to align and search protein complexes, enabling rapid and sensitive comparison of multi-chain structures across the entire predicted complex universe.</p>
<div class="method-refs"><div class="method-ref"><strong>Kim W.</strong>*, <strong>Mirdita M.</strong>, <strong>Levy K.E.</strong>, <strong>Gilchrist C.L.M.</strong>, Schweke H., Söding J., Levy E.D.†, <strong>Steinegger M.</strong>† (2025) Rapid and sensitive protein complex alignment with Foldseek-Multimer, <em>Nature Methods</em> <a href="https://www.biorxiv.org/content/10.1101/2024.04.14.589414v1">[preprint]</a> <a href="https://www.nature.com/articles/s41592-025-02593-7">[journal]</a> <a href="https://github.com/steineggerlab/foldseek">[software]</a></div>
</div>
</div>
</div>

<!-- placeholder logo (reusing Foldseek's) until dedicated art exists; animation is dedicated -->
<div class="method-item">
<div class="method-logo">
<img src="/img/foldseek_logo.png" alt="AFDB Clusters logo (placeholder)" class="method-char">
<img src="/img/afdb_clusters_anim.svg" alt="AFDB Clusters: predicted structures grouped by shape into structural clusters" class="method-anim">
</div>
<div class="method-body">
<p><b>AFDB Clusters</b> applies Foldseek clustering to the entire AlphaFold Protein Structure Database, grouping the predicted protein universe into structural clusters that reveal previously unseen protein families and their relationships.</p>
<div class="method-refs"><div class="method-ref">Barrio-Hernandez I.*, <strong>Yeo J.</strong>*, Jänes J., <strong>Mirdita M.</strong>, <strong>Gilchrist C.L.M.</strong>, Wein T., Varadi M., Velankar S., Beltrao P.†, <strong>Steinegger M.</strong>† (2023) Clustering predicted structures at the scale of the known protein universe, <em>Nature</em> <a href="https://www.biorxiv.org/content/10.1101/2023.03.09.531927v1">[preprint]</a> <a href="https://www.nature.com/articles/s41586-023-06510-w">[journal]</a> <a href="https://foldseek.com">[software]</a></div>
</div>
</div>
</div>

<div class="method-item">
<div class="method-logo">
<img src="/img/foldseek_logo.png" alt="Foldseek logo" class="method-char">
<img src="/img/foldseek_anim.svg" alt="Foldseek: query structure scanning a database and finding a match" class="method-anim">
</div>
<div class="method-body">
<p><b>Foldseek</b> is a software suite for searching and clustering protein structures, orders of magnitude faster than state-of-the-art structural aligners — letting you query millions of structures in seconds.</p>
<div class="method-refs"><div class="method-ref">van Kempen M.*, <strong>Kim S.S.</strong>*, <strong>Tumescheit C.</strong>, <strong>Mirdita M.</strong>, Lee J., <strong>Gilchrist C.L.M.</strong>, Söding J.†, <strong>Steinegger M.</strong>† (2023) Fast and accurate protein structure search with Foldseek, <em>Nature Biotechnology</em> <a href="https://www.biorxiv.org/content/10.1101/2022.02.07.479398v5">[preprint]</a> <a href="https://www.nature.com/articles/s41587-023-01773-0">[journal]</a> <a href="https://foldseek.com">[software]</a></div>
</div>
</div>
</div>

<div class="method-item">
<div class="method-logo">
<img src="/img/colabfold_logo.png" alt="ColabFold logo" class="method-char">
<img src="/img/colabfold_anim.svg" alt="ColabFold: sequence alignment folding into a protein structure" class="method-anim">
</div>
<div class="method-body">
<p><b>ColabFold</b> is an easy-to-use environment for fast protein structure prediction. It pairs AlphaFold2 and RoseTTAFold with fast MMseqs2-based MSA generation, making predictions orders of magnitude faster than the standard AlphaFold system.</p>
<div class="method-refs"><div class="method-ref"><strong>Mirdita M.</strong>*†, Schütze K., Moriwaki Y., Heo L., Ovchinnikov S.†, <strong>Steinegger M.</strong>† (2022) ColabFold: making protein folding accessible to all, <em>Nature Methods</em> <a href="https://www.biorxiv.org/content/10.1101/2021.08.15.456425v3">[preprint]</a> <a href="https://www.nature.com/articles/s41592-022-01488-1">[journal]</a> <a href="https://colabfold.com">[software]</a></div>
</div>
</div>
</div>

</div>

<div class="method-category">
<h3 class="method-category-title">Metagenomics</h3>

<div class="method-item">
<div class="method-logo">
<img src="/img/metabuli_logo.png" alt="Metabuli logo" class="method-char">
<img src="/img/metabuli_anim.svg" alt="Metabuli: reads sorted down a taxonomy tree" class="method-anim">
</div>
<div class="method-body">
<p><b>Metabuli</b> is a metagenomic classification tool that jointly analyzes amino acid and DNA sequences, combining the sensitivity of amino-acid searches with the specificity of DNA-level resolution to taxonomically profile complex samples.</p>
<div class="method-refs"><div class="method-ref"><strong>Kim J.</strong>*, <strong>Steinegger M.</strong>† (2024) Metabuli: sensitive and specific metagenomic classification via joint analysis of amino acid and DNA, <em>Nature Methods</em> <a href="https://www.biorxiv.org/content/10.1101/2023.05.31.543018v2">[preprint]</a> <a href="https://www.nature.com/articles/s41592-024-02273-y">[journal]</a> <a href="https://github.com/steineggerlab/Metabuli">[software]</a></div>
</div>
</div>
</div>

<div class="method-item">
<div class="method-logo">
<img src="/img/conterminator_logo.png" alt="Conterminator logo" class="method-char">
<img src="/img/conterminator_anim.svg" alt="Conterminator: flagging a cross-kingdom contaminant" class="method-anim">
</div>
<div class="method-body">
<p><b>Conterminator</b> is an efficient method for detecting incorrectly labeled sequences across kingdoms by an exhaustive all-against-all sequence comparison.</p>
<div class="method-refs"><div class="method-ref"><strong>Steinegger M.</strong>*†, Salzberg S.L.† (2020) Terminating contamination: large-scale search identifies more than 2,000,000 contaminated entries in GenBank, <em>Genome Biology</em> <a href="https://www.biorxiv.org/content/10.1101/2020.01.26.920173v1">[preprint]</a> <a href="https://genomebiology.biomedcentral.com/articles/10.1186/s13059-020-02023-1">[journal]</a> <a href="https://github.com/steineggerlab/conterminator">[software]</a></div>
</div>
</div>
</div>

<div class="method-item">
<div class="method-logo">
<img src="/img/plass_logo.png" alt="Plass logo" class="method-char">
<img src="/img/plass_anim.svg" alt="Plass: short reads merging into a contig" class="method-anim">
</div>
<div class="method-body">
<p><b>Plass</b> assembles short-read sequencing data at the protein level, targeting complex metagenomes. It recovers many times more protein residues from soil metagenomes than nucleotide assemblers such as Megahit.</p>
<div class="method-refs"><div class="method-ref"><strong>Steinegger M.</strong>*†, <strong>Mirdita M.</strong>, Söding J.† (2019) Protein-level assembly increases protein sequence recovery from metagenomic samples manyfold, <em>Nature Methods</em> <a href="https://www.nature.com/articles/s41592-019-0437-4">[journal]</a> <a href="https://github.com/soedinglab/plass">[software]</a></div>
</div>
</div>
</div>

</div>

</div>
</div>
</div>
