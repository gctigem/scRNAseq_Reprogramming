# Cellular population dynamics shape the route to human pluripotency
#### Francesco Panariello<sup>1,&</sup>, Onelia Gagliano<sup>2,3,4,&</sup>, Camilla Luni<sup>5,6,&</sup>, Antonio Grimaldi<sup>1,&</sup>, Silvia Angiolillo<sup>2,3</sup>, Wei Qin<sup>2,3,5</sup>, Anna Manfredi<sup>1,7</sup>, Patrizia Annunziata<sup>1,7</sup>, Shaked Slovin<sup>1</sup>, Lorenzo Vaccaro<sup>1</sup>, Sara Riccardo<sup>1,7</sup>, Valentina Bouche<sup>1</sup>, Manuela Dionisi<sup>1,7</sup>, Marcello Salvi<sup>1,7</sup>, Sebastian Martewicz<sup>5</sup>, Manli Hu<sup>5</sup>, Meihua Cui<sup>5</sup>, Hannah Stuart<sup>2,3</sup>, Cecilia Laterza<sup>2,3</sup>, Giacomo Baruzzo<sup>8</sup>, Geoffrey Schiebinger<sup>9</sup>, Barbara Di Camillo<sup>8,10,11</sup>, Davide Cacchiarelli<sup>1,12,13,*</sup>, Nicola Elvassore<sup>2,3,4,5,*</sup>

<sup>1</sup> Telethon Institute of Genetics and Medicine (TIGEM), Armenise/Harvard Laboratory of Integrative Genomics, Pozzuoli, Italy </br>
<sup>2</sup> Dept. of Industrial Engineering, University of Padova, Padova, Italy </br>
<sup>3</sup> Veneto Institute of Molecular Medicine (VIMM), Padova, Italy </br>
<sup>4</sup> Stem Cell and Regenerative Medicine Section, GOS Institute of Child Health, University College London, London, UK </br>
<sup>5</sup> Shanghai Institute for Advanced Immunochemical Studies (SIAIS), ShanghaiTech University, Shanghai, China </br>
<sup>6</sup> Dept. of Civil, Chemical, Environmental and Materials Engineering (DICAM), University of Bologna, Bologna, Italy </br>
<sup>7</sup> Next Generation Diagnostic srl, Pozzuoli, Italy </br>
<sup>8</sup> Dept. of Information Engineering, University of Padova, Padova, Italy </br>
<sup>9</sup> Dept. of Mathematics, University of British Columbia, Vancouver, Canada </br>
<sup>10</sup> Department of Comparative Biomedicine and Food Science, University of Padova, Padova, Italy </br>
<sup>11</sup> CRIBI Biotechnology Center, University of Padova, Padova, Italy </br>
<sup>12</sup> Department of Translational Medicine, University of Naples “Federico II”, Naples, Italy </br>
<sup>13</sup> School for Advanced Studies, Genomics and Experimental Medicine Program, University of Naples “Federico II”, Naples, Italy </br>
<sup>&</sup> These authors contributed equally: Francesco Panariello, Onelia Gagliano, Camilla Luni & Antonio Grimaldi </br>
<sup>*</sup> These authors jointly supervised this work: Davide Cacchiarelli, Nicola Elvassore </br>

## Table of content
<li><a href="## Abstract">Abstract</a></li>
<li><a href="#dim">Dimensionality Reduction</a></li>


## Abstract
Human cellular reprogramming to induced pluripotency is still an inefficient process, which has hindered studying the role of critical intermediate stages. Here we take advantage of high efficiency reprogramming in microfluidics and temporal multi-omics to identify and resolve distinct sub-populations and their interactions. We perform secretome analysis and single-cell transcriptomics to show functional extrinsic pathways of protein communication between reprogramming sub-populations and the re-shaping of a permissive extracellular environment. We pinpoint the HGF/MET/STAT3 axis as a potent enhancer of reprogramming, which acts via HGF accumulation within the confined system of microfluidics, and in conventional dishes needs to be supplied exogenously to enhance efficiency. Our data suggest that human cellular reprogramming is a transcription factor-driven process that it is deeply dependent on extracellular context and cell population determinants. 

## Contents of the article
1. Introduction

2. Results
    1. Development of a temporal multi-omic approach to study human cell reprogramming in microfluidics
    2. Embryonic ECM accumulates during reprogramming
    3. Dynamics of extrinsic regulatory signals during reprogramming
    4. Resolving cell population heterogeneity during reprogramming
    5. Signalling contributions from different cellular subpopulations
    6. Reprogramming fates interact through different ligand-receptor pairs
    7. HGF-MET crosstalk functionally sustains the acquisition of pluripotency through STAT3
    
3. Discussion

<h2><a name="dim">Dimensionality Reduction</a></h2>
We reduced dimensionality of our single-cell expression data taking advantage of the Force Layout Embedding (FLE). In our manuscript, we used forceatlas2 (v1.0.3). Since this function was deprecated, we recommend the following <a href="https://nbviewer.jupyter.org/github/broadinstitute/wot/blob/master/notebooks/Notebook-1-FLE-cell_sets-gene_sets.ipynb">Tutorial to compute dimensionality reduction using <i>pegasus</i></a>
