<p align="center">
<img src="logo.svg" alt="DNA Spider-Web" title="DNASpiderWeb" width="40%"/>
</p>

---

# SPECTRA and DNA Spider-Web
As a genetic material, DNA has become an attractive medium for storing digital information gradually.
In recent years, a growing number of functional biochemical operations and storage environments were introduced, 
biochemical constraints are not confined to long single-nucleotide repeats and abnormal GC content.
However, trade-offs between information density and compatibility to biochemical operations and algorithms require in-depth investigation, 
to create transcoding algorithms considering novel biochemical constraints and their combinations.
Here, we construct a simple calculator, called [**SPECTRA**](https://github.com/HaolingZHANG/DNASpiderWeb/blob/main/dsw/evaluator.py), 
to make use of the spectral radius to compute the density-compatibility trade-off under arbitrary local biochemical constraints.
Based on [**SPECTRA**](https://github.com/HaolingZHANG/DNASpiderWeb/blob/main/pipelines/step_1_generate.py), 
we design an automatic generator, 
named [**SPIDER-WEB**](https://github.com/HaolingZHANG/DNASpiderWeb/blob/main/dsw/generator.py), 
to create corresponding graph-based algorithms 
which could be used directly or served as a benchmark for artificial algorithm design.
Through this work, applicable algorithms with appropriate density-compatibility trade-off under arbitrary local biochemical constraints could be generated in an automated way. 
It is also suggested that more kinds of biochemical constraints can be further investigated as more complex operations would be needed in future DNA storage systems.
