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

/* Clear floats after the columns */
.row:after {
  content: "";
  display: table;
  clear: both;
}
</style>

<div class="row">
  <div class="columnWide">
    <p><b>MMseqs2</b> (Many-against-Many sequence searching) is a software suite to search and cluster huge protein and nucleotide sequence sets. MMseqs2 can run 10000 times faster than BLAST. It can perform profile searches with the same sensitivity as PSI-BLAST at over 400 times its speed.
      <ul class="network-icon" aria-hidden="true">
          <li>
            <a href="https://github.com/soedinglab/mmseqs2" target="_blank" rel="noopener">
              <i class="fab fa-github big-icon"></i>
            </a>
          </li>
       </ul>
    </p>
  </div>
  <div class="columnNarrow">
    <img src="img/mmseqs2_logo.png" style="width: 227px">
  </div>
</div>

<br>

<div class="row">
  <div class="columnWide">
    <p><b>Linclust</b> a method that can cluster sequences down to 50% pairwise sequence similarity and its run time scales linearly with the input set size, not nearly quadratically as in conventional algorithms. It is >1000 times faster compared to its competitors.
      <ul class="network-icon" aria-hidden="true">
        <li>
          <a href="https://github.com/soedinglab/mmseqs2" target="_blank" rel="noopener">
            <i class="fab fa-github big-icon"></i>
          </a>
        </li>
     </ul>
  </p>
  </div>
  <div class="columnNarrow">
	  <img src="img/linclust_logo.png" style="width: 227px">
  </div>
</div>

<br>

<div class="row">
  <div class="columnWide">
    <p><b>Plass</b> is a software to assemble short read sequencing data on a protein level. The main purpose of Plass is the assembly of complex metagenomic datasets. It assembles 10 times more protein residues in soil metagenomes than Megahit. 
      <ul class="network-icon" aria-hidden="true">
        <li>
          <a href="https://github.com/soedinglab/plass" target="_blank" rel="noopener">
            <i class="fab fa-github big-icon"></i>
          </a>
        </li>
      </ul>
    </p>
  </div>
  <div class="columnNarrow">
    <img src="img/plass_logo.png" style="width: 227px">
  </div>
</div>

<br>

<div class="row">
  <div class="columnWide">
    <p>
      <b>Conterminator</b> is an efficient method for detecting incorrectly labeled sequences across kingdoms by an exhaustive all-against-all sequence comparison.
      <ul class="network-icon" aria-hidden="true">
        <li>
          <a href="https://github.com/martin-steinegger/conterminator" target="_blank" rel="noopener">
            <i class="fab fa-github big-icon"></i>
          </a>
        </li>
      </ul>
     </p>
  </div>
  <div class="columnNarrow">
    <img src="img/conterminator_logo.png" style="width: 227px">
  </div>
</div>


