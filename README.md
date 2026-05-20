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
Select the organism (e.g., Homo sapiens). <img width="1581" height="933" alt="Screenshot 2026-05-20 094915" src="https://github.com/user-attachments/assets/e479bee1-28ff-49ea-a758-b5edfbe6e7b7" />

Choose the desired CRISPR enzyme/system, such as:
1. Cas9
2. Cas12a
3. Cas12b
Choose the desired editing option (e.g., activation/editing if applicable).
Run the search to identify target sites. <img width="1213" height="788" alt="Screenshot 2026-05-20 094941" src="https://github.com/user-attachments/assets/25dfb079-239b-45f3-9552-e4d3d4b88a7b" />


**Download Guide Data**
Download the generated guide RNA data.<img width="1867" height="959" alt="Screenshot 2026-05-20 095800" src="https://github.com/user-attachments/assets/fdcab42d-3103-4d49-8600-8e82c71c2b5e" />

Copy and paste the guide information into Excel. <img width="1914" height="574" alt="Screenshot 2026-05-20 100044" src="https://github.com/user-attachments/assets/59828d06-89a7-4f10-854c-7f41cdafbffe" />


**Filter Candidate Guides**

Filter guides based on scoring parameters such as:
GC content: 40–60%
Self-complementarity: 0 (minimal secondary structure)
Efficiency score: preferably > 50
Additional off-target or mismatch criteria as required.
Select the most suitable guide(s).

**Visualize Guides in SnapGene**
Open the selected guide in SnapGene Viewer or benchling.<img width="1370" height="830" alt="Screenshot 2026-05-20 100217" src="https://github.com/user-attachments/assets/45704010-25f7-47e5-899e-e58808c27154" /> 
Identify and annotate the PAM sequence: Add a feature, Name and color-code it 
Add the guide RNA feature:Select direction/orientation, Name and color-code the guide <img width="1350" height="747" alt="Screenshot 2026-05-20 095330" src="https://github.com/user-attachments/assets/e1879326-b5d1-41c9-8b92-7366761109c6" />


**Confirm Guide Specificity Using BLAST**

To verify that the guide targets the correct organism and minimize off-target effects:
Copy the selected guide sequence. Paste the sequence into BLAST.
Enter/select the target organism. Exclude the chosen organism (as written in notes) or check against other organisms to assess off-target binding.
Run BLAST. <img width="1836" height="915" alt="Screenshot 2026-05-20 100529" src="https://github.com/user-attachments/assets/e99fcf41-9925-490c-88b1-d2bc992d2251" />


**Confirmation**
Evaluate BLAST results to confirm guide specificity and suitability. <img width="1606" height="889" alt="Screenshot 2026-05-20 101424" src="https://github.com/user-attachments/assets/260e0e31-de99-4283-9814-c44192d89341" />
<img width="1649" height="958" alt="Screenshot 2026-05-20 101449" src="https://github.com/user-attachments/assets/071abbaa-f94c-483c-a782-e3a20d6f2be4" />


