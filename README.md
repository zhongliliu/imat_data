The files in this directory were used to train the ML models of superconductivity.
And then the machine learning (ML) models were used to predict the critical 
temperatures (Tc) of our screened ~ 2500 layered crystals from the ICSD database.

The file Tc_expt.csv contains our purified experimental Tc data from the Supercon 
database, which was used as the original big data for the ML. 

The file descriptors.txt contains the descriptors used to train the ML models, which
are made from the chemical information in the Tc_expt.csv file.

The file targets.txt contains all the Tc data for each superconductor corresponding
to the materials listed in each line of the descriptors.txt file.
