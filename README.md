# protein-encoding-projects 
#1. CreatePredictor_AAINDEX_based 
Protein encoding for mashine learning tasks &amp; predictor's testing methods
Archive CreatePredictor_AAINDEX_based.zip contain c++ program text, for creating predictors by protein sequence.
Predictors based on aminoacid's phisical & chemical properties from databese AAINDEX*.

File TEST\CowardVariables.task is a simple example of tume file for creating predictor's set. 

Аfter program execution, TEST\CowardVariables.task is created, which contains predictor values ​​for sequence "RAPRARAKALRLLLKLLKLLSRYWVRVKRLLL"
given with the testing procedure CowardVariables_test::first_test()



*. Kawashima S., Pokarowski P., Pokarowska M., Kolinski A., Katayama T., Kanehisa M. 2008. AAindex: amino acid index database, progress report 2008. Nucleic Acids Res. 36, D202-205. 

#2. sda  - Stepwise discriminant analysis
A model of discrimination is built step-by-step. Specifically, at each step all variables are reviewed and evaluated to determine which one will contribute most to the discrimination between groups. Archeve sda.zip contain c++ program text, and test data files. 

Files ex.dat ex.names are required for program testing

For detain read README.md from sda.zip

#3 The program performs protein chain assignment by Protein Block according to RMSD & RMSDA metrics. Input - standard PDB file.
For detain read README.md from PB_RMSD_release
