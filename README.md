Supplementary code for the manuscript: **"The effect of nutrient deprivation on early life small intestine mucosal microbiome and host proteome"**  
The code for specific figures can be found as follows:  

**Figure 3** and **Figure 4B**: All code is in `16S-beta-meta analysis.Rmd`.  

**Proteomic work**: All relevant code is the `proteomics_final_analysis` folder:  
* `proteomics analysis.rmd` contains the code for using `normalyzer` package to log-transform the data.
* `final limma analysis.rmd` contains the code for DA analysis of the data using `limma`. The code to create **Figure 4A** and **Figure 5A,B** can be found here.
* `proteomics_network.rmd` contains all the code for protein correlation and clustering work. The code to create **Figure 5C** and *Figure S2** can be found here.
* `looking for innate immune and AMPs in the proteomics data.Rmd` contains all the code for looking for specfic protein groups/families in our data.
