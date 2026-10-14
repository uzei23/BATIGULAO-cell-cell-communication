# LABORATORY ACTIVITY: Cell-to-Cell Communication (GIP–GIPR Signaling Between an Intestinal K Cell and a Pancreatic Beta Cell)


**Name:** BATIGULAO, JEHIAH BLESS T.

**Date completed:** 10/14/2026

**Assigned sender cell:** Enteroendocrine K cell


## 1. Title and Biological Question

**Can an enteroendocrine K cell communicate with a pancreatic beta cell through glucose-dependent insulinotropic polypeptide (GIP) and its receptor GIPR to enhance insulin secretion after nutrient ingestion?**

## PART A. Chosen Sender Cell and Biological Context

* **Sender cell:** Enteroendocrine K cell

* **Location:** Mainly the upper small intestine, including the duodenum and jejunum.

* **Biological context:** Nutrient sensing and postprandial glucose regulation.

* **Why it is a meaningful sender:** K cells are specialized enteroendocrine cells that detect nutrients in the intestinal lumen and release GIP after food ingestion. GIP acts as an incretin hormone that helps
  coordinate intestinal nutrient intake with pancreatic insulin secretion.

* **Signaling type:** Endocrine signaling, because secreted GIP can travel through the bloodstream to act on distant target cells, including pancreatic beta cells.

* **Evidence:** The Human Protein Atlas (HPA) identifies GIP as a secreted protein with intestine-enriched expression and an enteroendocrine-cell expression association. Published literature specifically identifies intestinal K cells as a source of GIP.

* **Limitation:** The HPA expression cluster supports the intestinal and enteroendocrine context but does not, by itself, establish that GIP expression is exclusive to K cells. The K-cell-specific assignment is supported by published literature.





## PART B. Candidate Ligand and Evidence for Sender-Cell Expression

* **Ligand:** GIP, glucose-dependent insulinotropic polypeptide, also historically called gastric inhibitory polypeptide.

* **Gene:** GIP

* **UniProt accession:** P09681

* **Protein function:** GIP is an incretin hormone that enhances glucose-stimulated insulin secretion after nutrient ingestion.

* **Human Protein Atlas findings:**

  * Tissue profile: tissue enriched in the intestine.

  * Tissue RNA expression cluster: small intestine, associated mainly with absorption and digestion.

  * Cell-type specificity: cell-type enriched in neuroendocrine cells.

  * Cell-type expression cluster: enteroendocrine cells, associated mainly with neuropeptide signaling.

  * Predicted location: secreted.

  * Extracellular location: secreted to blood.

  * Blood detection: reported by immunoassay and mass spectrometry.


* **Supporting literature:** Wolfe et al. (2025) describe GIP as a 42-amino-acid hormone synthesized and released from upper-intestinal enteroendocrine K cells in response to glucose or fat ingestion.

* **Why this ligand was selected:** GIP fits the assigned sender cell and provides a plausible signal connecting intestinal nutrient detection with the pancreatic response.

* **Limitations:** HPA annotations support the protein's expression and secreted nature, while the literature supports its K-cell source. Neither source alone proves that a particular K cell communicated with a particular beta cell in a specific experiment.

<img width="592" height="918" alt="01_HPA_GIP_Expression" src="https://github.com/user-attachments/assets/73ba6c5f-c201-48d4-b957-75cd69d4d371" />




## PART C. Receptor and Receiver Cell With Supporting Evidence

* **Receptor:** GIPR, glucose-dependent insulinotropic polypeptide receptor

* **UniProt accession:** P48546

* **Receiver cell:** Pancreatic beta cell

* **Receptor function:** GIPR is a cell-surface, class B G-protein-coupled receptor (GPCR) that binds GIP and initiates intracellular signaling.

* **Biological response:** GIP enhances glucose-stimulated insulin secretion from pancreatic beta cells.

* **Why this receiver was selected:** The pancreatic beta cell is a physiologically appropriate receiver because insulin secretion is one of the established effects of GIP.

* **Supporting literature:** Parthier et al. (2007) reported the structure of human GIPR's extracellular domain bound to GIP(1–42), supporting the direct ligand–receptor relationship. Wolfe et al. (2025) review
  GIP's role in incretin physiology and insulin secretion.

* **Limitation:** The receiver-cell choice is supported by established biology. A database annotation alone does not demonstrate receptor expression or signaling activity in every pancreatic beta cell under every condition.


**Checkpoint sentence:** The enteroendocrine K cell releases GIP into the circulation, and GIP can bind GIPR on a pancreatic beta cell, enhancing glucose-stimulated insulin secretion.


## OmniPath Findings

OmniPath was used to examine ligand annotations and directed molecular interactions relevant to the proposed model.


* **GIP:** UniProt P09681; annotated as secreted and as a ligand in the displayed intercellular communication annotations.

* **GIPR:** UniProt P48546; annotated as a transmembrane, plasma-membrane and cell-surface protein.

* **GIP → GIPR:** The interaction was listed in the results, with sources including Baccin2019, CellCall, CellChatDB and other integrated resources. The displayed result reported 31 references.

* **GIPR → GNAS:** GIPR-associated entries involving GNAS were also present, consistent with GPCR signaling through heterotrimeric G proteins.

* **Interpretation:** These annotations support the proposed ligand–receptor pair and the receptor's connection to G-protein signaling.

* **Limitation:** OmniPath integrates information from multiple resources. Its interaction records do not independently prove that GIP–GIPR signaling occurs in the exact sender–receiver cell pair proposed here.

<img width="1598" height="928" alt="02_OMNIPATH_GIP_GIPR_INTERACTION" src="https://github.com/user-attachments/assets/86020dd6-27d2-44c3-abea-a64f24f81e04" />

<img width="1600" height="926" alt="03_OMNIPATH_GIP_GIPR_INTERCELL" src="https://github.com/user-attachments/assets/fafbd91d-f6ec-4bb8-8f79-eabddd42822c" />



## PART D. STRING Network Interpretation

* **Query protein:** GIPR

* **Organism:** *Homo sapiens*

* **Network size:** 11 nodes and 55 edges

* **Average node degree:** 10

* **Average local clustering coefficient:** 1

* **Expected number of edges:** 16

* **PPI enrichment p-value:** 6.5 × 10⁻¹⁵

<img width="632" height="821" alt="04_string_network" src="https://github.com/user-attachments/assets/edbc3fdb-068d-4153-82fa-5523cb1e8adb" />


### Network proteins and relevant association scores

| Protein | STRING score | Relevance to the proposed model                                                                |
| ------- | -----------: | ---------------------------------------------------------------------------------------------- |
| GIP     |        0.999 | The proposed ligand for GIPR                                                                   |
| GNB1    |        0.990 | G-protein beta subunit                                                                         |
| GNG2    |        0.979 | G-protein gamma subunit                                                                        |
| GNAS    |        0.962 | G-protein alpha subunit associated with GPCR signaling and cAMP regulation                     |
| GNB4    |        0.913 | G-protein beta subunit                                                                         |
| GNB3    |        0.911 | G-protein beta subunit                                                                         |
| GNB5    |        0.909 | G-protein beta subunit                                                                         |
| GNB2    |        0.909 | G-protein beta subunit                                                                         |
| GNG13   |        0.906 | G-protein gamma subunit                                                                        |
| GCG     |        0.981 | Glucagon, a related peptide hormone; its presence does not mean it is the ligand in this model |


### Network statistics interpretation

The PPI enrichment p-value of 6.5 × 10⁻¹⁵ indicates that the proteins in the network have significantly more associations than expected for a random set of proteins under STRING's model. This supports the idea that the proteins are functionally related.

The network contains 11 nodes and 55 edges. For an undirected network with 11 nodes, 55 is the maximum possible number of pairwise edges. Therefore, the reported statistics describe a fully connected network. The screenshot and network settings should be checked to confirm that this is the network actually generated and that the reported values correspond to the displayed nodes.

STRING scores indicate confidence in functional associations. They should not be interpreted as percentages or as proof that each pair directly binds.

### Relevant functional enrichment

| Enriched term                                                    | Reported result                               | Relevance                                                  |
| ---------------------------------------------------------------- | --------------------------------------------- | ---------------------------------------------------------- |
| Gastric inhibitory peptide signaling pathway (GO:0038192)        | 2 of 2; p = 0.00027                           | Directly relevant to GIP signaling                         |
| Adenylate cyclase-activating GPCR signaling pathway (GO:0007189) | 6 of 169; p = 1.00 × 10⁻⁶                     | Consistent with GPCR signaling through G proteins and cAMP |
| GPCR signaling pathway (GO:0007186)                              | 11 of 1,207; p = 5.39 × 10⁻¹⁰                 | Supports the receptor-associated signaling context         |
| Heterotrimeric G-protein complex (GO:0005834)                    | 8 of 35; p = 1.22 × 10⁻¹⁷                     | Consistent with the G-protein subunits in the network      |
| Positive regulation of insulin secretion                         | Shown in the Biological Process visualization | Consistent with the expected physiological response        |



### Interpretation and limitations

The GIP–GIPR association score of 0.999 and GNAS score of 0.962 support the proposed relationship between GIPR and G-protein signaling. The enriched GIP signaling, GPCR signaling and heterotrimeric G-protein terms are consistent with the proposed mechanism.

Other enriched terms, such as dopamine receptor signaling, may appear because different pathways share signaling components. Their enrichment does not establish that the GIP model directly participates in every listed pathway.

STRING supports functional associations and pathway context, but it does not independently establish the full sequence of events in a specific K cell and pancreatic beta cell.



## PART E. IntAct Validation

IntAct was used to examine experimental evidence for the physical interaction between GIP and GIPR.

### Recorded interaction evidence

| Item                        | Record                                                                                         |
| --------------------------- | ---------------------------------------------------------------------------------------------- |
| Interacting molecules       | GIPR (UniProt P48546) and GIP (UniProt P09681)                                                 |
| Organism                    | *Homo sapiens*                                                                                 |
| Host/experimental context   | In vitro                                                                                       |
| Publication                 | PMID 17715056                                                                                  |
| Publication title           | *Crystal structure of the incretin-bound extracellular domain of a G protein-coupled receptor* |
| Reported interaction type   | Direct interaction                                                                             |
| Detection methods displayed | CD; X-ray diffraction; isothermal titration calorimetry (ITC)                                  |
| Interaction accessions      | EBI-15653930, EBI-15653952 and EBI-15654015                                                    |
| MI score displayed          | 0.62 for the listed records                                                                    |



The IntAct results provide experimental support for a direct molecular interaction between GIP and GIPR. The publication reports a structure of the human GIP receptor extracellular domain in complex with its ligand, GIP(1–42), and the database lists records associated with different detection methods.

The three records should not be counted as three independent biological relationships because they refer to the same ligand–receptor pair and publication. The MI score is a database interaction score, not a percentage probability.

This evidence supports the molecular compatibility of the ligand and receptor. However, the records do not, by themselves, demonstrate that the interaction occurred in the exact sender and receiver cells used in this model.

<img width="1917" height="926" alt="05_IntAct_GIP_GIPR_Interaction" src="https://github.com/user-attachments/assets/d7395570-4c2b-4357-a60d-5f0f19050bfa" />


## PART F. Final Model and Interpretation

### Proposed signaling model

**Nutrient ingestion → enteroendocrine K-cell nutrient sensing → GIP secretion → transport through the bloodstream → GIP binding to GIPR on a pancreatic beta cell → G-protein activation → adenylyl cyclase and increased cAMP → PKA and Epac2/RAPGEF4 signaling → enhanced glucose-stimulated insulin secretion.**

### Interpretation 

This model proposes that an enteroendocrine K cell in the upper small intestine communicates with a pancreatic beta cell through the hormone GIP. The Human Protein Atlas supports the intestinal and enteroendocrine expression context of GIP and identifies it as a secreted protein. Published literature further establishes that K cells release GIP in response to nutrient ingestion. These findings support the selection of GIP as the signaling molecule and endocrine signaling as the communication type.

OmniPath lists GIP as a ligand, GIPR as a cell-surface receptor, and GIP–GIPR as an interaction supported by multiple integrated sources. STRING associates GIPR with GIP and G-protein signaling components, including GNAS, and reports enrichment of GIP signaling, GPCR signaling and the heterotrimeric G-protein complex. IntAct provides experimental evidence for direct interaction between GIP and GIPR.

The proposed downstream mechanism is that GIPR activates G-protein signaling, stimulating adenylyl cyclase and increasing cAMP. cAMP-dependent signaling through PKA and Epac2 can enhance glucose-stimulated insulin secretion in pancreatic beta cells. The ligand–receptor relationship and the physiological role of GIP are strongly supported by the combined database and literature evidence. However, the complete pathway in the exact sender–receiver cell pair remains a model assembled from multiple sources, rather than a direct demonstration from one experiment. STRING associations and database annotations alone cannot establish cell-specific signaling.

<img width="1536" height="1024" alt="09_GIP–GIPR Cell Communication Pathway" src="https://github.com/user-attachments/assets/65c4d71e-94c0-4b99-b744-44bb3e5d2553" />


## Required Evidence Recorded

| Item                       | Records                                                                                                                                                |
| -------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------ |
| Sender cell                | Enteroendocrine K cell in the upper small intestine; associated with nutrient sensing and GIP secretion                                                |
| Signal/ligand              | GIP, UniProt P09681; HPA supports intestinal and enteroendocrine expression context, secretion and blood detection; literature supports K-cell release |
| Receptor                   | GIPR, UniProt P48546; annotated as a cell-surface GPCR                                                                                                 |
| Receiver cell              | Pancreatic beta cell; established physiological target of GIP                                                                                          |
| Signaling type             | Endocrine signaling through a secreted hormone carried in the circulation                                                                              |
| OmniPath                   | GIP annotated as secreted/ligand; GIPR annotated as transmembrane/cell surface; GIP → GIPR listed with 31 references in the recorded results           |
| STRING                     | 11 nodes, 55 edges, average node degree 10, clustering coefficient 1, expected edges 16, PPI enrichment p = 6.5 × 10⁻¹⁵                                |
| STRING functional partners | GIP (0.999), GNB1 (0.990), GNG2 (0.979), GNAS (0.962), and additional G-protein subunits                                                               |
| STRING enrichment          | GIP signaling, GPCR signaling, adenylate cyclase-activating GPCR signaling and heterotrimeric G-protein complex                                        |
| IntAct                     | GIP–GIPR; PMID 17715056; in vitro direct interaction records; detection methods include X-ray diffraction and ITC; MI score 0.62                       |
| Final model                | K cell → GIP → bloodstream → GIPR on pancreatic beta cell → G-protein/cAMP signaling → enhanced glucose-stimulated insulin secretion                   |

## Laboratory Activity Questions

### 1. What sender cell did you choose, and in what tissue or biological context does it act?

I chose the enteroendocrine K cell, which is found mainly in the upper small intestine. It detects nutrients after food ingestion and releases GIP, helping coordinate nutrient intake with pancreatic insulin secretion.

### 2. What signaling molecule did you identify, and what evidence supports its production or presentation by the sender cell?

The selected ligand is GIP (UniProt P09681). HPA reports intestinal and enteroendocrine expression associations and identifies GIP as a secreted protein detected in blood. Published literature specifically identifies K cells as a source of GIP.

### 3. What receptor receives the signal, and which receiver cell did you select?

The receptor is GIPR (UniProt P48546), a cell-surface G-protein-coupled receptor. The receiver cell is a pancreatic beta cell, where GIP enhances glucose-stimulated insulin secretion.

### 4. What type of cell-to-cell signaling is represented: paracrine, endocrine, autocrine, or contact-dependent?

The model represents endocrine signaling because GIP is secreted by intestinal K cells and can travel through the bloodstream to act on pancreatic beta cells at a distant location.

### 5. Which proteins in your STRING network appear most relevant to the receptor-associated response? Explain briefly.

GIP had the highest functional association score with GIPR (0.999), and GNAS had a score of 0.962. GNAS and the G-protein beta and gamma subunits are relevant because they participate in GPCR-associated signaling. STRING scores represent confidence in functional associations, not necessarily direct physical binding.

### 6. What enriched pathway or biological process is consistent with your proposed mechanism?

Relevant results include the gastric inhibitory peptide signaling pathway (GO:0038192), adenylate cyclase-activating GPCR signaling (GO:0007189), the GPCR signaling pathway (GO:0007186), and the heterotrimeric G-protein complex (GO:0005834). Positive regulation of insulin secretion also appeared in the Biological Process visualization.

### 7. What did IntAct show for the molecular interaction you examined? What type of evidence was reported?

IntAct listed GIP–GIPR interaction records associated with PMID 17715056. The records include direct-interaction evidence and methods such as X-ray diffraction and isothermal titration calorimetry. They support the molecular interaction but do not independently demonstrate signaling in the exact cell pair.

### 8. Which parts of your final model are strongly supported, and which parts remain an inference?

The GIP–GIPR interaction and the physiological role of GIP in enhancing insulin secretion are supported by published evidence and database records. The complete cell-specific sequence from K-cell release through G-protein/cAMP signaling to insulin secretion is a synthesis of multiple sources. Its occurrence in a specific pair of cells was not directly tested in this activity.

### 9. What cellular response is expected in the receiver cell, and why?

The expected response is enhanced glucose-stimulated insulin secretion by the pancreatic beta cell. GIP binds GIPR and activates intracellular signaling that potentiates insulin secretion when glucose is present.

## References and Database Links

1. Wolfe, M. M., Boylan, M. O., & Chin, W. W. (2025). Glucose-dependent insulinotropic polypeptide in incretin physiology: Role in health and disease. *Endocrine Reviews, 46*(4), 479–500. 

   PubMed: (https://pubmed.ncbi.nlm.nih.gov/39951489/)

3. Parthier, C., Kleinschmidt, M., Neumann, P., Rudolph, R., Manhart, S., Schlenzig, D., Fanghaenel, J., Rahfeld, J. U., Demuth, H. U., & Stubbs, M. T. (2007). Crystal structure of the incretin-bound extracellular domain of a G protein-coupled receptor. *Proceedings of the National Academy of Sciences, 104*(35), 13942–13947. https://doi.org/10.1073/pnas.0706404104
   PubMed: https://pubmed.ncbi.nlm.nih.gov/17715056/

4. Human Protein Atlas. GIP (glucose-dependent insulinotropic polypeptide) gene and protein expression. (https://www.proteinatlas.org/ENSG00000159224-GIP)

5. Human Protein Atlas. GIPR (glucose-dependent insulinotropic polypeptide receptor) gene and protein expression. https://www.proteinatlas.org/ENSG00000010310-GIPR

6. OmniPath. Integrated molecular interaction and intercellular communication resources. (https://explore.omnipathdb.org/search?q=GIP%2C+&tab=interactions&species=9606)

7. STRING. Protein association networks and functional enrichment analysis. https://string-db.org/cgi/network?taskId=bEPJGRKCzEB1&sessionId=b1h965ATau9D

8. IntAct. Molecular interaction database. https://www.ebi.ac.uk/intact/search?query=EBI-15653881

9. UniProt. GIP, accession P09681. https://www.uniprot.org/uniprotkb/P09681

10. UniProt. GIPR, accession P48546. https://www.uniprot.org/uniprotkb/P48546
