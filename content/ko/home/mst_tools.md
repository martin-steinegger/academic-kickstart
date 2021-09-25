+++

headless = true  # This file represents a page section.
active = true  # Activate this widget? true/false
weight = 80  # Order that this section will appear.

title = "소프트웨어"
subtitle = ""

[design.background]
  # Apply a background color, gradient, or image.
  #   Uncomment (by removing `#`) an option to apply it.
  #   Choose a light or dark text color by setting `text_color_light`.
  #   Any HTML color name or Hex value is valid.
  
  # Background color.
  # color = "navy"
  
  # Background gradient.
  # gradient_start = "DeepSkyBlue"
  # gradient_end = "SkyBlue"
  
  # Background image.
  # image = "background.jpg"  # Name of image in `static/img/`.
  # image_darken = 0.6  # Darken the image? Range 0-1 where 0 is transparent and 1 is opaque.

  # Text color (true=light or false=dark).
  # text_color_light = true  
  
[advanced]
 # Custom CSS. 
 css_style = ""
 
 # CSS class.
 css_class = ""
+++

<style>
* {
  box-sizing: border-box;
}

.columnEqL {
  float: left;
  width: 50%;
  padding: 0px;
}

.columnEqR {
  float: right;
  width: 50%;
  padding: 0px;
}

.columnWide {
  float: left;
  width: 60%;
  padding: 5px;
}

.columnNarrow {
  float: left;
  width: 40%;
  padding: 5px;
}

.center-badge {
  display: flex;
  flex-direction: column;
  justify-content: space-around;
}

li.no-scale:hover {
  transform: none;
}

</style>

<div>
  <div class="columnWide">
    <p><b>MMseqs2</b> (Many-against-Many sequence searching)는 사이즈가 큰 단백질 및 DNA, RNA 서열 세트를 검색하고 클러스터링하는 소프트웨어 모음입니다. MMseqs2는 BLAST보다 10000배 빠르게 실행되며, PSI-BLAST와 동일한 민감도 (sensitivity)를 유지한 채 400배 이상의 향상된 속도로 프로파일 검색을 수행 할 수 있습니다.
      <ul class="network-icon" aria-hidden="true">
          <li>
            <a href="https://github.com/soedinglab/mmseqs2" target="_blank" rel="noopener">
              <i class="fab fa-github big-icon"></i>
            </a>
          </li>
          <li class="center-badge no-scale">
            <a href="https://biocontainers.pro/#/tools/mmseqs2"><img src="https://img.shields.io/endpoint?url=https%3A%2F%2Fmmseqs.com%2Fbiocontainer.php%3Fcontainer%3Dmmseqs2"/></a>
            <a href="https://anaconda.org/bioconda/mmseqs2"><img src="https://img.shields.io/conda/dn/bioconda/mmseqs2.svg?style=flag&label=BioConda%20install" alt="Install from BioConda"></a> 
          </li>
     </ul>
       </ul>
    </p>
  </div>
  <div class="columnNarrow">
    <img src="/img/mmseqs2_logo.png" style="width: 227px">
  </div>
</div>

<div>
  <div class="columnWide">
    <p><b>ColabFold</b>는 쉽고 빠르고 간편하게 단백질 구조를 예측할 수 있는 환경을 제공합니다. MMseqs2를 사용하여 AlphaFold 시스템보다 16배 빠르게 MSA*를 생성하는 모듈을 탑재한 AlphaFold2 및 RoseTTAFold를 사용하여 단백질 구조를 보다 빠르게 예측할 수 있습니다.
      <ul class="network-icon" aria-hidden="true">
          <li>
            <a href="https://github.com/sokrypton/ColabFold" target="_blank" rel="noopener">
              <i class="fab fa-github big-icon"></i>
            </a>
          </li>
     </ul>
       </ul>
    </p>
  </div>
  <div class="columnNarrow">
    <img src="/img/colabfold_logo.png" style="width: 227px">
  </div>
</div>


<div>
  <div class="columnWide">
    <p><b>Linclust</b>는 여러 시퀀스들을 쌍방향 서열 유사도 (pairwise sequencing similarity) 50% 범위 이내로 클러스터링 할 수 있는 소프트웨어입니다. 실행 시간은 기존 알고리즘이 세트 크기의 제곱에 비례하는데 비해, Linclust는 입력된 세트 크기에 따라 선형으로 증가하며 다른 툴들에 비해 1000배 이상 빠릅니다.
      <ul class="network-icon" aria-hidden="true">
        <li>
          <a href="https://github.com/soedinglab/mmseqs2" target="_blank" rel="noopener">
            <i class="fab fa-github big-icon"></i>
          </a>
        </li>
        <li class="center-badge no-scale">
          <a href="https://biocontainers.pro/#/tools/mmseqs2"><img src="https://img.shields.io/endpoint?url=https%3A%2F%2Fmmseqs.com%2Fbiocontainer.php%3Fcontainer%3Dmmseqs2"/></a>  
          <a href="https://anaconda.org/bioconda/mmseqs2"><img src="https://img.shields.io/conda/dn/bioconda/mmseqs2.svg?style=flag&label=BioConda%20install" alt="Install from BioConda"></a>                 
        </li>
     </ul>
  </p>
  </div>
  <div class="columnNarrow">
	  <img src="/img/linclust_logo.png" style="width: 227px">
  </div>
</div>

<div>
  <div class="columnWide">
    <p><b>Plass</b>는 단백질 수준에서 짧은 리드 길이의 시퀀싱 데이터를 조립 (assemebly for short read sequencing) 하는 소프트웨어입니다. Plass의 주요 목적은 복잡한 메타 유전체 데이터 세트를 조립하는 것입니다. Megahit과 비교했을 때, 토양 메타 유전체 데이터에서 10배 더 많은 단백질 서열을 조립합니다.
      <ul class="network-icon" aria-hidden="true">
        <li>
          <a href="https://github.com/soedinglab/plass" target="_blank" rel="noopener">
            <i class="fab fa-github big-icon"></i>
          </a>
        </li>
        <li class="center-badge no-scale">
          <a href="https://anaconda.org/bioconda/plass"><img src="https://img.shields.io/conda/dn/bioconda/plass.svg?style=flag&label=BioConda%20install" alt="Install from BioConda"></a> 
        </li>
      </ul>
    </p>
  </div>
  <div class="columnNarrow">
    <img src="/img/plass_logo.png" style="width: 227px">
  </div>
</div>

<br>

<div>
  <div class="columnWide">
    <p>
      <b>Conterminator</b>는 포괄적인 전체 시퀀스 비교 (all-against-all comparison)를 통해 계 (Kingdom) 수준에서 잘못 라벨링된 서열을 감지하는 효율적인 방법입니다.
      <ul class="network-icon" aria-hidden="true">
        <li>
          <a href="https://github.com/martin-steinegger/conterminator" target="_blank" rel="noopener">
            <i class="fab fa-github big-icon"></i>
          </a>
        </li>
        <li class="center-badge no-scale">
          <a href="https://anaconda.org/bioconda/conterminator"><img src="https://img.shields.io/conda/dn/bioconda/conterminator.svg?style=flag&label=BioConda%20install" alt="Install from BioConda"></a> 
        </li>
      </ul>
     </p>
  </div>
  <div class="columnNarrow">
    <img src="/img/conterminator_logo.png" style="width: 227px">
  </div>
</div>


