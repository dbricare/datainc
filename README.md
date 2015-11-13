# Reducing risk in drug development by incorporating gene-disease association

### Introduction

Over the last few decades, pharmaceutical companies have made significant progress in biochemical synthesis and can now generate vast quantities of potential therapeutics. Unfortunately, identifying relevant disease-causing molecular targets within the body is still a tedious and burdensome process. Fortunately, new tools in the form of genomic analyses are now gaining widespread acceptance and have the potential to dramatically improve molecular target indentification. 

Many non-communicable diseases share a common mechanistic origin. In the body, genes carry information that dictate the structure and amount of proteins that must be synthesized for proper biological function. Environmental or hereditary factors can causes errors in gene encoding that lead to undesirable changes in these proteins. The constituents of these synthesis pathways represent the "molecular targets" drug researchers are seeking. By identifying the appropriate malfunctioning protein pathway, an effective drug therapy can be developed. 

With recent technological advancements in genetic sequencing, a multitude of publicly-available databases now exist that describe in detail the link between genes, molecular targets, and disease. However, this information is organized in non-standard formats and accessed through various file downloads, web APIs, or form-based queries making it difficult to use. Furthermore, once drug researchers select a target, there is still critical research on the business-side to be performed to ensure profitability of the fully-developed pharmaceutical.

I propose a project that will mate business and technical risk analysis to assist pharmaceutical companies in selecting drug development strategies that maximize the return on their R&D investment. In the first phase, I plan to compile all available gene-disease data into a central repository and develop an appropriate metric to identify the strongest gene-diseases links. In the second phase, I will search public health databases to find the rates of incidence for common and rare diseases with well-established genetic links and estimate market values. In the final phase, I will combine these two analyses to develop a list of gene targets and disease areas ranked by highest likelihood of achieving financial and technical success.

This data-based approach has significant advantages over traditional laboratory methods for drug discovery. Analyzing human genetics data bypasses time-consuming and costly preclinical experiments with cell culture and animal models. In addition, verified gene-disease associations provide researchers with <i>a priori</i> information that targeting a specific biological molecule or pathway will prove effective at treating the disease of interest. Thus reducing the risk of unsuccessful R&D efforts.

## Phase I
https://github.com/dbricare/datainc/blob/master/genediseasedata.ipynb

## Phase II
https://github.com/dbricare/datainc/blob/master/agingdata.ipynb
