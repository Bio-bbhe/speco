# speco
Short Peptide and Enzyme Co-Occurrence analysis pipeline
Speco requires prodigal-short,hmmsearch, bigscape and fasttree. If <20000 bp sequence exists, multiple non-coding nucleotide "N" will be concatenated in the 3-end accordingly in order to be processed by prodigal-short. Usage example:python3 speco.py -p PF00067 -l 20 -m 100 -t orf -u 2 -d 2 -i /data/lab/ -o /data/lab/output

