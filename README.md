# CRISPR_mini_project
Open the NCBI database.
Search for the gene of interest (e.g., TP53).<img width="1385" height="899" alt="image" src="https://github.com/user-attachments/assets/4edbbc9b-8068-4d8a-8555-a21cfa2b0498" /> 
Download the gene sequence in FASTA format.
Save the downloaded FASTA file with an appropriate name.
Copy the FASTA sequence.
Paste/import the sequence into SnapGene for visualization and annotation.

**Design Guides Using CHOPCHOP**
Open CHOPCHOP.
Paste the target gene sequence or enter the target gene.
Select the organism (e.g., Homo sapiens).
Choose the desired CRISPR enzyme/system, such as:
1. Cas9
2. Cas12a
3. Cas12b
Choose the desired editing option (e.g., activation/editing if applicable).
Run the search to identify target sites.

**Download Guide Data**
Download the generated guide RNA data.
Copy and paste the guide information into Excel.

**Filter Candidate Guides**

Filter guides based on scoring parameters such as:
GC content: 40–60%
Self-complementarity: 0 (minimal secondary structure)
Efficiency score: preferably > 50
Additional off-target or mismatch criteria as required.
Select the most suitable guide(s).

**Visualize Guides in SnapGene**
Open the selected guide in SnapGene Viewer.
Identify and annotate the PAM sequence: Add a feature, Name and color-code it
Add the guide RNA feature:Select direction/orientation, Name and color-code the guide

**Confirm Guide Specificity Using BLAST**

To verify that the guide targets the correct organism and minimize off-target effects:
Copy the selected guide sequence. Paste the sequence into BLAST.
Enter/select the target organism. Exclude the chosen organism (as written in notes) or check against other organisms to assess off-target binding.
Run BLAST.

**Confirmation**
Evaluate BLAST results to confirm guide specificity and suitability.
