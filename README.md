# CDS-Dashboard
Coherent Disease Subtyping Dashboard

## Elixir Hackathon Project 2: Boolean Knowledge Graphs to Federate Population-Level Genomic, Imaging and Phenotypic Data

## Code: Please refer to https://github.com/collaborativebioinformatics/CDS-Dashboard for code related to this project

## Abstract (original project plan)

We will build a usable proof-of-concept tool that indicates what data is available for the federation of multiple datatypes (e.g. multi-omic data) in population-scale analyses. This will differ from existing efforts insofar as not all input data must be sensu strictu fair. To achieve this goal, we will work with three example repositories; UKBioBank (scrambled data), Federated EGA (only that available in surface level API) and refine.bio. We will do a light level of NLP/Metadata Harmonization to establish disease pairing and then build a POC UI that will notify investigators of technical and regulatory requirements to proceed with the experiment (i.e. where they need to bring particular tools, and which DACs they need to apply to for the raw data, if relevant). We will also implement flexible variant annotation to extend our analysis based on existing knowledge bases. Our stretch goal will be to integrate these analyses with our current work (partially in other biohackathons) related to both graph genomes and clinical reporting.

## Concise results (what we actually produced) 

### Example Use Case: Subtyping of colorectal cancer:

![CMS Diagram](https://github.com/collaborativebioinformatics/CDS-Dashboard/blob/main/nihms-1039672-f0002.jpeg)

Ref: Curr Gastroenterol Rep. 2019 Jan 30; 21(2): 5.

![CRC subtyping Fig 2c](https://github.com/collaborativebioinformatics/CDS-Dashboard/blob/main/Guinney_CRC_subtyping_Fig2c.png)

Nat Med. 2015 Nov; 21(11): 1350–1356.

![Why single cell is important diagram](https://github.com/collaborativebioinformatics/CDS-Dashboard/blob/main/cancers-13-04923-g001%2Cjpeg.jpeg)

Cancers (Basel). 2021 Oct; 13(19): 4923.

### Subtypes (subgraphs) of type

#### Example -- TIL infiltrated/MMR as subgraphs of type 1.  

#### Treatment options

![Treatment Options](https://github.com/collaborativebioinformatics/CDS-Dashboard/blob/main/Treatment_options_for_subtypes.png)

##### Reference:  https://gut.bmj.com/content/68/3/465.long

### Landing page

![Landing page](https://github.com/collaborativebioinformatics/CDS-Dashboard/blob/main/New_Landing_Page.png)

### Prototype disease subtyping dashboard for diagnostic researchers

![Researcher Dashboard](https://github.com/collaborativebioinformatics/CDS-Dashboard/blob/main/Researchers_dashboard.png)

![Contribution graph](https://github.com/collaborativebioinformatics/CDS-Dashboard/blob/main/Clin_diagnostics_graph_github.png)

### Prototype disease subtyping dashboard for "developers"

![Developer Dashboard](https://github.com/collaborativebioinformatics/CDS-Dashboard/blob/main/Developers_dashboard.png)

### Prototype disease subtyping dashboard for translational researchers -- coming soon!

### Data types processed

#### Transcriptome
#### Single cell
#### PRS and single variants (popgen)
#### miRNA (thanks FederatedEGA!)
#### Metagenomes (for treatment options subgraph)
#### Epigenomics (coming soon)

## Team

Emerson Huitt
Nick Giangreco
Ames Ma
Anthony Costa

### Advisors
Vivian Neilley 
Nuria Queralt Rosinach
Jerven Bolleman

### Lead(s)

Ben Busby bbusby@dnanexus.com

### Acknowledgements

#### Thanks to Aina for help with Federated EGA.  Thanks to her colleagues for being patient with me interrupting their zoom call this morning.  

### Thank you!
