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

![Why single cell is important diagram](https://github.com/collaborativebioinformatics/CDS-Dashboard/blob/main/cancers-13-04923-g001%2Cjpeg.jpeg)

Cancers (Basel). 2021 Oct; 13(19): 4923.

### Prototype disease subtyping dashboard for researchers

### Prototype disease subtyping dashboard for clinicians

### Prototype disease subtyping dashboard for "developers"

## Team

Emerson Huitt
Nick Giangreco
Ames Ma
Anthony Costa
Vivian Neilley 

### Lead(s)

Ben Busby bbusby@dnanexus.com

## Expected outcomes

MVP of boolean knowledge graph
+ RNAseq
+ Federated EGA
UI directing API calls
Docker images for tool portability
Integration with/establishment of Enhanced Variant Sets
Integration with Flexible Variant Annotation Platforms
Integration with open clinical reporting system

## Expected audience

### Researchers

### Clinicians
