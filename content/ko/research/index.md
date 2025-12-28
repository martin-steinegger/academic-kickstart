+++
title = "연구"
type = "research"
+++

<div class="research-summary">
<p>저희 연구실에서는 빅데이터를 활용하는 알고리즘과 기계학습을 결합하여 알려지지 않은 미생물 군집에 대한 통찰력을 얻는 새로운 계산 방법을 제시하고 활용 가능한 프로그램 및 도구를 개발합니다.</p>
<ul>
  <li>시퀀스 검색, 클러스터링 및 서열 조립을 위한 알고리즘 개발</li>
  <li>시퀀싱 데이터를 활용한 병원체 검출</li>
  <li>메타유전체 분석</li>
  <li>단백질 기능 및 구조 예측</li>
</ul>
</div>

<div class="methods-layout">
<div class="methods-aside">
<h2>소프트웨어</h2>
</div>
<div class="methods-list">
<div class="research-methods">
<div class="method-item">
<div class="method-logo">
<img src="/img/mmseqs2_logo.png" alt="MMseqs2 logo">
</div>
<div class="method-body">
<p><b>MMseqs2</b> (Many-against-Many sequence searching)는 사이즈가 큰 단백질 및 DNA, RNA 서열 세트를 검색하고 클러스터링하는 소프트웨어 모음입니다. MMseqs2는 BLAST보다 10000배 빠르게 실행되며, PSI-BLAST와 동일한 민감도 (sensitivity)를 유지한 채 400배 이상의 향상된 속도로 프로파일 검색을 수행 할 수 있습니다.</p>
</div>
</div>

<div class="method-item">
<div class="method-logo">
<img src="/img/colabfold_logo.png" alt="ColabFold logo">
</div>
<div class="method-body">
<p><b>ColabFold</b>는 쉽고 빠르고 간편하게 단백질 구조를 예측할 수 있는 환경을 제공합니다. MMseqs2를 사용하여 AlphaFold 시스템보다 16배 빠르게 multiple sequence alignment를 생성하는 모듈을 탑재한 AlphaFold2 및 RoseTTAFold를 사용하여 단백질 구조를 보다 빠르게 예측할 수 있습니다.</p>
</div>
</div>

<div class="method-item">
<div class="method-logo">
<img src="/img/foldseek_logo.png" alt="Foldseek logo">
</div>
<div class="method-body">
<p><b>Foldseek</b> is a software suite for searching and clustering protein structures. It is 600,000 times faster than the fastest state-of-the-art aligners. Allowing to query millions of structures in seconds.</p>
</div>
</div>

<div class="method-item">
<div class="method-logo">
<img src="/img/linclust_logo.png" alt="Linclust logo">
</div>
<div class="method-body">
<p><b>Linclust</b> is a method that can cluster sequences down to 50% pairwise sequence similarity and its runtime scales linearly with the input set size, not quadratically as in conventional algorithms. It is &gt;1000 times faster compared to its competitors.</p>
</div>
</div>

<div class="method-item">
<div class="method-logo">
<img src="/img/plass_logo.png" alt="Plass logo">
</div>
<div class="method-body">
<p><b>Plass</b> is a software to assemble short read sequencing data on a protein level. The main purpose of Plass is the assembly of complex metagenomic datasets. It assembles 10 times more protein residues in soil metagenomes than Megahit.</p>
</div>
</div>

<div class="method-item">
<div class="method-logo">
<img src="/img/conterminator_logo.png" alt="Conterminator logo">
</div>
<div class="method-body">
<p><b>Conterminator</b> is an efficient method for detecting incorrectly labeled sequences across kingdoms by an exhaustive all-against-all sequence comparison.</p>
</div>
</div>
</div>
</div>
</div>

<div class="research-publications">
  <div class="pub-layout">
    <div class="pub-aside">
      <h2>주요 논문</h2>
      <div class="research-legend">
        <div>*: First author</div>
        <div>†: Corresponding author</div>
        <div>Lab members in bold</div>
      </div>
    </div>
    <div class="pub-list">
      <div class="pub-item">
        <strong>Kim W.</strong>*, <strong>Mirdita M.</strong>, <strong>Levy K.E.</strong>, <strong>Gilchrist C.L.M.</strong>, Schweke H., Söding J., Levy E.D.†, <strong>Steinegger M.</strong>† (2025) Rapid and sensitive protein complex alignment with Foldseek-Multimer, <em>Nature Methods</em>
        <a href="https://www.biorxiv.org/content/10.1101/2024.04.14.589414v1">[preprint]</a>
        <a href="https://www.nature.com/articles/s41592-025-02593-7">[journal]</a>
        <a href="https://github.com/steineggerlab/foldseek">[software]</a>
      </div>
      <div class="pub-item">
        <strong>Kim J.</strong>*, <strong>Steinegger M.</strong>† (2024) Metabuli: sensitive and specific metagenomic classification via joint analysis of amino acid and DNA, <em>Nature Methods</em>
        <a href="https://www.biorxiv.org/content/10.1101/2023.05.31.543018v2">[preprint]</a>
        <a href="https://www.nature.com/articles/s41592-024-02273-y">[journal]</a>
        <a href="https://github.com/steineggerlab/Metabuli">[software]</a>
        <a href="https://www.nature.com/articles/s41592-024-02273-y.epdf?sharing_token=je_2D5Su0-xVOSjuKSAXF9RgN0jAjWel9jnR3ZoTv0M7gE7NDF_xi_3sW8QdRiwfSJNwqaXItSoeCvr7cvcoQxKLt0oROgWc6urmki9tP80cXEuHPN0D7b4y9y3i8Yv7sZw8MxxhAj7W6p9eZE2zaK3eozdOkXvwADVfso9cXIM%3D">[pdf]</a>
      </div>
      <div class="pub-item">
        Barrio-Hernandez I.*, <strong>Yeo J.</strong>*, Jänes J., <strong>Mirdita M.</strong>, <strong>Gilchrist C.L.M.</strong>, Wein T., Varadi M., Velankar S., Beltrao P.†, <strong>Steinegger M.</strong>† (2023) Clustering predicted structures at the scale of the known protein universe, <em>Nature</em>
        <a href="https://www.biorxiv.org/content/10.1101/2023.03.09.531927v1">[preprint]</a>
        <a href="https://www.nature.com/articles/s41586-023-06510-w">[journal]</a>
        <a href="https://foldseek.com">[software]</a>
      </div>
      <div class="pub-item">
        van Kempen M.*, <strong>Kim S.S.</strong>*, <strong>Tumescheit C.</strong>, <strong>Mirdita M.</strong>, Lee J., <strong>Gilchrist C.L.M.</strong>, Söding J., <strong>Steinegger M.</strong> (2023) Fast and accurate protein structure search with Foldseek, <em>Nature Biotechnology</em>
        <a href="https://www.biorxiv.org/content/10.1101/2022.02.07.479398v5">[preprint]</a>
        <a href="https://www.nature.com/articles/s41587-023-01773-0">[journal]</a>
        <a href="https://foldseek.com">[software]</a>
      </div>
      <div class="pub-item">
        <strong>Mirdita M.</strong>*†, Schütze K., Moriwaki Y., Heo L., Ovchinnikov S.†, <strong>Steinegger M.</strong>† (2022) ColabFold: making protein folding accessible to all, <em>Nature Methods</em>
        <a href="https://www.biorxiv.org/content/10.1101/2021.08.15.456425v3">[preprint]</a>
        <a href="https://www.nature.com/articles/s41592-022-01488-1">[journal]</a>
        <a href="https://colabfold.com">[software]</a>
      </div>
      <div class="pub-item">
        <strong>Steinegger M.</strong>*, Salzberg S.L.† (2020) Terminating contamination: large-scale search identifies more than 2,000,000 contaminated entries in GenBank, <em>Genome Biology</em>
        <a href="https://www.biorxiv.org/content/10.1101/2020.01.26.920173v1">[preprint]</a>
        <a href="https://genomebiology.biomedcentral.com/articles/10.1186/s13059-020-02023-1">[journal]</a>
        <a href="https://github.com/martin-steinegger/conterminator">[software]</a>
      </div>
      <div class="pub-item">
        <strong>Steinegger M.</strong>*, Meier M., Mirdita M., Vöhringer H., Haunsberger S.J., Söding J.† (2019) HH-suite3 for fast remote homology detection and deep protein annotation, <em>BMC Bioinformatics</em>
        <a href="https://www.biorxiv.org/content/10.1101/560029v1">[preprint]</a>
        <a href="https://bmcbioinformatics.biomedcentral.com/articles/10.1186/s12859-019-3019-7">[journal]</a>
        <a href="https://github.com/soedinglab/hh-suite">[software]</a>
      </div>
      <div class="pub-item">
        <strong>Steinegger M.</strong>*†, Mirdita M., Söding J.† (2019) Protein-level assembly increases protein sequence recovery from metagenomic samples manyfold, <em>Nature Methods</em>
        <a href="https://www.biorxiv.org/content/10.1101/386110v2">[preprint]</a>
        <a href="https://www.nature.com/articles/s41592-019-0437-4">[journal]</a>
        <a href="https://github.com/soedinglab/plass">[software]</a>
      </div>
      <div class="pub-item">
        <strong>Steinegger M.</strong>*†, Söding J.† (2018) Clustering huge protein sequence sets in linear time, <em>Nature Communications</em>
        <a href="https://www.biorxiv.org/content/10.1101/104034v4">[preprint]</a>
        <a href="https://www.nature.com/articles/s41467-018-04964-5">[journal]</a>
        <a href="https://github.com/soedinglab/mmseqs2">[software]</a>
      </div>
      <div class="pub-item">
        <strong>Steinegger M.</strong>*, Söding J.† (2017) MMseqs2: Sensitive protein sequence searching for the analysis of massive data sets, <em>Nature Biotechnology</em>
        <a href="https://www.biorxiv.org/content/10.1101/079681v5.full">[preprint]</a>
        <a href="https://www.nature.com/articles/nbt.3988">[journal]</a>
        <a href="https://github.com/soedinglab/mmseqs2">[software]</a>
      </div>
    </div>
  </div>
</div>
