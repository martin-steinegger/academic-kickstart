+++
title = "연구"
type = "research"
+++

<div class="research-summary">
<p>저희 연구실은 빅데이터 알고리즘과 기계학습을 결합하여 빠르게 증가하는 생물학적 서열과 구조의 세계를 이해하기 위한 새로운 계산 방법을 개발합니다. 데이터베이스 전체 규모에서 단백질과 유전체를 검색, 클러스터링, 어셈블리, 예측할 수 있는 빠르고 오픈소스 기반의 도구를 만들어, 방대한 유전체·단백질체 데이터를 미생물 군집에서부터 단백질 구조 세계의 체계화에 이르기까지 생물학적 통찰로 전환합니다.</p>

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
<h3 class="method-category-title">서열 검색 및 클러스터링</h3>

<div class="method-item">
<div class="method-logo">
<img src="/img/mmseqs2_logo.png" alt="MMseqs2 logo" class="method-char">
<img src="/img/mmseqs2_anim.svg" alt="MMseqs2: a query sequence searched against a database of sequences" class="method-anim">
</div>
<div class="method-body">
<p><b>MMseqs2</b> (Many-against-Many sequence searching)는 사이즈가 큰 단백질 및 DNA, RNA 서열 세트를 검색하고 클러스터링하는 소프트웨어 모음입니다. BLAST보다 월등히 빠르게 실행되며, PSI-BLAST 수준의 민감도(sensitivity)를 유지하면서 프로파일 검색을 훨씬 빠르게 수행합니다.</p>
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
<h3 class="method-category-title">단백질 구조</h3>

<div class="method-item">
<div class="method-logo">
<img src="/img/folddisco_logo.png" alt="Folddisco logo" class="method-char">
<img src="/img/folddisco_anim.svg" alt="Folddisco: distant residues connecting into a structural motif" class="method-anim">
</div>
<div class="method-body">
<p><b>Folddisco</b>는 서열상으로 멀리 떨어진 잔기로 이루어진 촉매 부위나 결합 포켓과 같은 불연속적 구조 모티프(discontinuous structural motif)를 색인하고 검색하여, 수백만 개의 단백질 구조에서 모티프를 빠르게 질의할 수 있도록 합니다.</p>
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
<p><b>FoldMason</b>은 단백질의 다중 구조 정렬(multiple structure alignment)을 대규모로 정확하게 구축하는 도구로, 구조 정보를 활용하여 서열 기반 방법으로는 정렬하기 어려운 수천 개의 원거리 상동 단백질을 정렬하고 그들의 진화적 관계를 재구성합니다.</p>
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
<p><b>Foldseek-Multimer</b>는 Foldseek을 확장하여 단백질 복합체를 정렬하고 검색하며, 예측된 복합체 전체 규모에서 다중 사슬 구조를 빠르고 민감하게 비교할 수 있도록 합니다.</p>
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
<p><b>AFDB Clusters</b>는 Foldseek 클러스터링을 AlphaFold 단백질 구조 데이터베이스 전체에 적용하여, 예측된 단백질 세계를 구조적 클러스터로 묶어 기존에 알려지지 않은 단백질 패밀리와 그 관계를 밝혀냅니다.</p>
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
<p><b>ColabFold</b>는 단백질 구조를 쉽고 빠르게 예측할 수 있는 환경을 제공합니다. AlphaFold2 및 RoseTTAFold에 MMseqs2 기반의 빠른 multiple sequence alignment 생성을 결합하여, 기존 AlphaFold 시스템보다 월등히 빠르게 구조를 예측합니다.</p>
<div class="method-refs"><div class="method-ref"><strong>Mirdita M.</strong>*†, Schütze K., Moriwaki Y., Heo L., Ovchinnikov S.†, <strong>Steinegger M.</strong>† (2022) ColabFold: making protein folding accessible to all, <em>Nature Methods</em> <a href="https://www.biorxiv.org/content/10.1101/2021.08.15.456425v3">[preprint]</a> <a href="https://www.nature.com/articles/s41592-022-01488-1">[journal]</a> <a href="https://colabfold.com">[software]</a></div>
</div>
</div>
</div>

</div>

<div class="method-category">
<h3 class="method-category-title">메타지노믹스</h3>

<div class="method-item">
<div class="method-logo">
<img src="/img/metabuli_logo.png" alt="Metabuli logo" class="method-char">
<img src="/img/metabuli_anim.svg" alt="Metabuli: reads sorted down a taxonomy tree" class="method-anim">
</div>
<div class="method-body">
<p><b>Metabuli</b>는 아미노산과 DNA 서열을 함께 분석하는 메타지놈 분류 도구로, 아미노산 검색의 높은 민감도와 DNA 수준의 높은 특이도를 결합하여 복잡한 시료의 분류학적 프로파일링을 수행합니다.</p>
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
