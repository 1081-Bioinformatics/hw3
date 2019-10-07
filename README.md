# hw3
<your name + student ID>
## Description

* Write R or Python script to perform global or local alignment.
* Creating your own script with your student ID, ie. hw3_105753026.R.
* In this program, library Biostrings is only used to parse fasta file.

## File

* hw3_ref.R: You can start from this reference code, and try to write your own comment in English.
* pam100.txt
* pam250.txt
* test.fasta
* read_save_fasta.R: An example of reading and saving fasta file with Biostrings library.
* result.txt: An example of output file in FASTA format.

## Parameters

* input: fasta file (ex. test.fasta)
* score: score file (ex. pam250.txt)
* aln: global|local
* gap: gap score
* output: .fasta file

## Command

Executing your code with the following command.

```R
Rscript hw3_studentID.R --input test.fasta --score pam250.txt --aln global --gap -10 --output test_output.fasta
```
You should output your answer into fasta format.

## Evaluation

10 testing data

```R
Rscript hw3_studentID.R --input test1.fasta --score pam250.txt --aln global --gap -10 --output test1_output.fasta
Rscript hw3_studentID.R --input test2.fasta --score pam100.txt --aln local --gap -8 --output test2_output.fasta
Rscript hw3_studentID.R --input data/test3.fasta --score pam/pam1.txt --aln local --gap -5 --output out/test3_output.fasta
```

Correct answer gets 10 points of each testing data.

### Penalty

* High code similarity to others: YOUR SCORE = 0

