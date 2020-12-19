# Bioinformatics Sequence Alignment

This is a sequence alignment project for aligning protein sequences and scoring it according to a
 set of rules. On top of this, it has to run as efficiently as possible with regard to runtime. 

It will read in two sequences from text files which are passed in as parameters when running the 
script, e.g. `python sequence_alignment.py file1.txt file2.txt` It will print out an optimal 
alignment of these two sequences, the score and the run time. 

## Scoring

For matching:
- `+4` `A`
- `+3` `C`
- `+2` `G` 
- `+1` `T`
- `-3` for mismatch
- `-2` for gap