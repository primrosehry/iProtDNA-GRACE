# iProtDNA-GRACE
# Project tree
- data<br>
  - PDNA-316_label.fasta<br>
  - PDNA-316_sequence.fasta<br>
  - PDNA-335_label.fasta<br>
  - PDNA-335_sequence.fasta<br>
  - PDNA-41_label.fasta<br>
  - PDNA-41_sequence.fasta<br>
  - PDNA-52_label.fasta<br>
  - PDNA-52_sequence.fasta<br>
  - PDNA-543_label.fasta<br>
  - PDNA-543_sequence.fasta<br>
- esm2.py<br>
- esmfold.py<br>
- distance_matrix.py<br>
- Dataset.py<br>
- Focal_Loss.py<br>
- GRACE_classifier.py<br>
- README.md<br>
# Requirements
- torch=2.0.0+cu118<br>
- torch-geometric=2.3.0<br>
- torch-scatter=2.1.1+pt20cu118<br>
- torch-sparse=0.6.17+pt20cu118<br>
- torchvision=0.15.1+cu118<br>
- scikit-learn<br>
- scipy=1.10.1<br>
- PyGCL=0.1.2<br>
- dgl=1.1.0<br>
- biopython<br>
- numpy<br>
- tqdm<br>
# Usage
If you want to reproduce our model, please obtain the protein PDB file and use the 'esm2_t48_15B_UR50D' model to generate the residue features, then construct the graph data based on the distances between atoms, and finally input them into 'GRACE_classifier.py' to predict the binding properties of protein residues to DNA.<br>
&bull;`GRACE_classifier.py`<br>

