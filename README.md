# speco
Short Peptide and Enzyme Co-Occurrence analysis pipeline
Speco requires prodigal-short,hmmsearch, bigscape and fasttree. If <20000 bp sequence exists, multiple non-coding nucleotide "N" will be concatenated in the 3-end accordingly in order to be processed by prodigal-short. Usage example:python3 speco.py -p PF00067 -l 20 -m 100 -t orf -u 2 -d 2 -i /data/lab/ -o /data/lab/output

Below is workflow of speco.

<img src="https://user-images.githubusercontent.com/82441159/175210002-078ddb69-27ca-45e6-875f-4bf6a3117652.png" width="100" height="100">

