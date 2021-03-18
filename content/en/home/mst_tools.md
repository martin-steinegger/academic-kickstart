+++

headless = true  # This file represents a page section.
active = true  # Activate this widget? true/false
weight = 80  # Order that this section will appear.

title = "Methods"
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
    <p><b>MMseqs2</b> (Many-against-Many sequence searching) is a software suite to search and cluster huge protein and nucleotide sequence sets. MMseqs2 can run 10000 times faster than BLAST. It can perform profile searches with the same sensitivity as PSI-BLAST at over 400 times its speed.
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
    <p><b>Linclust</b> is a method that can cluster sequences down to 50% pairwise sequence similarity and its runtime scales linearly with the input set size, not  quadratically as in conventional algorithms. It is >1000 times faster compared to its competitors.
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
    <p><b>Plass</b> is a software to assemble short read sequencing data on a protein level. The main purpose of Plass is the assembly of complex metagenomic datasets. It assembles 10 times more protein residues in soil metagenomes than Megahit. 
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
      <b>Conterminator</b> is an efficient method for detecting incorrectly labeled sequences across kingdoms by an exhaustive all-against-all sequence comparison.
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


