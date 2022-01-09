OrfPP is a tool that can predict open reading frames (ORFs) including sORFs from populational genomic variants.

OrfPP requires three compulsory inputs: the sequence of reference genome (in fasta format), the genome annotation file (in gtf format) and the nucleotide diversity calculated from genomic variants (in vcf format)

There are five options

--start OrfPP use AUG as the start codon by default. As many non-canonical start codons have been identified in many studies. The users can select other triples as start codons. Codons should be seperated by comma if more than one is used. For example, AUG,UUG,CUG,GUG

--cov The minimum coverage of diversified nucleotides for a canidate ORF. This value should be set between 0-1.

--nCores The number of multiprocesssors. The identification of ORFs could be speed up by using more processors simultaneously.

--outdir The output directory of results.

--prefix The prefix of output files.



