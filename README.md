# DBpred: A deep learning-based method for the prediction of DNA interacting residues in a protein

**DBpred** is a high-precision computational tool developed to predict DNA-interacting residues in a protein sequence. Understanding these interactions is vital, as they govern fundamental biological processes such as gene transcription,
regulation, and splicing. DBpred addresses the limitations of traditional methods by employing advanced deep-learning architectures to identify specific binding sites when 3D structures are unavailable.

**Web Server:** https://webs.iiitd.edu.in/raghava/dbpred/


## Citation

Patiyal, S., Dhall, A., & Raghava, G. P. S. (2022).
**A deep learning-based method for the prediction of DNA interacting residues in a protein.** *Briefings in Bioinformatics*, 23(5), bbac322.
https://doi.org/10.1093/bib/bbac322

This dataset and tool can also be found on Zenodo at

## About the Research

The specific identification of residues that contact DNA is a major challenge in structural biology and bioinformatics. DBpred utilizes deep learning to capture complex patterns within protein sequences that signify a propensity for DNA binding.

* **Training Dataset:** The models were trained on a large-scale dataset of **646 DNA-binding proteins**, containing 15,636 DNA-interacting and 298,503 non-interacting residues.
* **Evaluation:** The performance was rigorously validated on an independent dataset of 46 proteins, ensuring the model generalizes well to proteins with low sequence similarity (<30%) to the training set.



## Key Features

### 1. Advanced Deep Learning Architectures

* **CNN and LSTM:** The tool employs Convolutional Neural Networks (CNN) to capture local sequence patterns and Long Short-Term Memory (LSTM) networks to understand long-range dependencies within the protein chain.
* **Hybrid Models:** Combines different architectures to maximize the precision of residue-level predictions.

### 2. Comprehensive Input Features

* **Evolutionary Information:** Incorporates Position-Specific Scoring Matrices (PSSM) to identify conserved residues likely involved in DNA contact.
* **Structural and Chemical Properties:** Integrates information such as amino acid composition and physicochemical properties to enhance prediction accuracy.

### 3. Integrated Web Services

* **Residue Prediction:** Users can submit a protein sequence to identify specific amino acids that are predicted to interact with DNA.
* **Probability Mapping:** Provides a score for each residue, allowing researchers to prioritize specific sites for site-directed mutagenesis or further experimental study.


## Applications

* **Functional Genomics:** Annotating the binding sites of transcription factors and other DNA-binding proteins in newly sequenced genomes.
* **Drug Design:** Identifying critical residues at the protein-DNA interface to design small molecules that can modulate gene expression.
* **Mutation Analysis:** Predicting how mutations in DNA-binding residues might disrupt essential biological functions or lead to disease.


## Contact & Authors

**Prof. Gajendra P. S. Raghava** (Corresponding Author)

raghava@iiitd.ac.in

Department of Computational Biology, Indraprastha Institute of Information Technology (IIIT Delhi), New Delhi, India.


## Support

The development of DNARes was supported by the **Department of Biotechnology (DBT)** and the **Council of Scientific and Industrial Research (CSIR)**, Government of India. Infrastructure and facilities were provided by **IIIT-Delhi**.
