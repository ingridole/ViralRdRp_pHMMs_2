## Supplementary_Dataset_1.xlsx
Excel sheet of all 15,044 putative virus-derived RdRp ORFs with associated data. Details are provided in the README sheet of the Excel spreadsheet.

## Supplementary_Dataset_2.xlsx
Excel sheet containing the results of our BLAST (Altschul et al., 1990; Camacho et al., 2009) and HHSearch (Steinegger et al., 2019) verification of putative viral ORFs. Details are provided in the README sheet of the Excel spreadsheet.

## Supplementary_Dataset_3_cluster_trees
PhyML (Guindon & Gascuel, 2003; Guindon et al., 2010) phylogenetic trees of the different groups of classified virus-derived RdRp sequences. Core trimmed RdRp sequences were compared using Biopython pairwise global alignment (pw.align.globalxx(sequence1, sequence2, one_alignment_only=True) and, where pairwise amino acid identities were ≥ 99.5%, the shorter of two sequences was removed.

#### Subdirectories:
* tree_files:
	* `*.tre` - nexus format tree file compatible with FigTree; sequences renamed as
     seq1, seq2, ...
  	* `*.names.txt` - key linking seq1, seq2, ... tags to accession numbers and NCBI
     description lines

* alignments: core RdRp sequence alignments used to generate trees

* png_files: png images of phylogenetic trees

* svg_files: svg images of phylogenetic trees

## Supplementary_Dataset_4_pHMMs_and_alignments
Supplementary Dataset 4 is our full set of family level pHMMs, available in the repository [Viral_RdRp_pHMMs](https://github.com/ingridole/ViralRdRp_pHMMs)
