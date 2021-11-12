# CDS-Dashboard
Coherent Disease Subtyping Dashboard

## Elixir Hackathon Project 2: Boolean Knowledge Graphs to Federate Population-Level Genomic, Imaging and Phenotypic Data

## Code: Please refer to https://github.com/collaborativebioinformatics/CDS-Dashboard for code related to this project

## Project Description

We built two tools based on existing literature.  The first, for clinical diagnostics, estimates the probability that any given sample in a colorectal cancer cohort is subtyped correctly.  The second, for translational researchers and clinicians, suggests potential therapeutic avenues given a colorectal cancer type and variant analysis.  

### Diagnostics tool

Given available validity data, this interactive tool estimates the likelihood of correct subtyping in colorectal cancer, given the Guinney, et al classification systme (https://www.ncbi.nlm.nih.gov/pmc/articles/PMC4636487/), and the data obtained by a number of research or diagnostic datasets.  References for validity measurement of each datatype and combinations thereof are available in the supplementary information file contained in this repo <link>.  It is our hope that this approach -- and code -- can be used to build such interactive tools for many diseases, as well as advise diagnostic groups on how to set up validity assessments.  

### Translational and Clinical tool (RUO)  

Given available drug efficacy data, this interactive tool recommends extant approved drug that may be appropriate for subjects given their CRC subtype classification, and variant information where available.  References for trial data and gene/pathway associations are available in the supplementary information file contained in this repo <link>.  It is our hope that this approach -- and code -- can be used to build such interactive tools for many diseases.  

### Example Use Case: Subtyping of colorectal cancer:

![CMS Diagram](https://github.com/collaborativebioinformatics/CDS-Dashboard/blob/main/nihms-1039672-f0002.jpeg)

Ref: Curr Gastroenterol Rep. 2019 Jan 30; 21(2): 5.

![CRC subtyping Fig 2c](https://github.com/collaborativebioinformatics/CDS-Dashboard/blob/main/Guinney_CRC_subtyping_Fig2c.png)

Nat Med. 2015 Nov; 21(11): 1350–1356.

![Why single cell is important diagram](https://github.com/collaborativebioinformatics/CDS-Dashboard/blob/main/cancers-13-04923-g001%2Cjpeg.jpeg)

Cancers (Basel). 2021 Oct; 13(19): 4923.

#### Treatment options

![Treatment Options](https://github.com/collaborativebioinformatics/CDS-Dashboard/blob/main/Treatment_options_for_subtypes.png)

##### Reference:  https://gut.bmj.com/content/68/3/465.long

### CDS-Dashboard

https://nick-giangreco.shinyapps.io/cds-dashboard/
 
### Landing page

![Landing page](https://github.com/collaborativebioinformatics/CDS-Dashboard/blob/main/New_Landing_Page.png)

### Prototype disease subtyping dashboard for diagnostic researchers

![Researcher Dashboard](https://github.com/collaborativebioinformatics/CDS-Dashboard/blob/main/Researchers_dashboard.png)

### Prototype disease subtyping dashboard for those who want to directly change the bayesian knowledge graph

![Developer Dashboard](https://github.com/collaborativebioinformatics/CDS-Dashboard/blob/main/Developers_dashboard.png)

### Prototype disease subtyping dashboard for translational researchers -- coming soon!

### Data types processed

#### Transcriptome
#### Single cell
#### PRS and single variants (popgen)
#### miRNA
#### Metagenomes (for treatment options subgraph)
#### Epigenomics (coming soon)

### Future directions

We are able to predict appropriate clinical diagnostic combinations that maximize the accuracy of potential treatment options.  Concurrently, we would like to be able to generate an information density graph (radar plot) for putative disease subtypes, highlighting pathways and variants that may be especially relevant to subjects within them.  It is our hope that this work will continue over a number of hackathons as well as more pedestrian software development engagements after oncologist review.  

## Team

Emerson Huitt
Nick Giangreco
Ames Ma
Anthony Costa

### Advisors
Vivian Neilley 
Nuria Queralt Rosinach
Jerven Bolleman
Aina Jene

### Lead(s)

Ben Busby bbusby@dnanexus.com

### Thank you!
