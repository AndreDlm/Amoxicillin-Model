# Amoxicillin-Model
Whole-body PBPK model of intravenously administered amoxicillin in adults, pregnant women and postpartum women

### Repository Files

Within this repository, we distribute a whole-body PBPK models of intravenously administered amoxicillin in adults, pregnant women and postpartum women. Details on model building and evaluation have been published previously [[1](#References)].

This repository contains a PK-Sim<sup>®</sup> file with amoxicillin simulations in adults and another PK-Sim<sup>®</sup> file with simulations in pregnant women and postpartum women. 

The postpartum anatomy and physiology is not integrated in the PK-Sim<sup>®</sup> database. Therefore, this repository also contains the MoBi<sup>®</sup> file with the postpartum model structure (please note that this model is not correctly parameterized in terms of the postpartum anatomy and physiology) and a csv file with the anatomical and physiological parameters of 2000 postpartum individuals. Both files can used for importing and running a postpartum population simulation in PK-Sim<sup>®</sup>.

### Version Information

PK-Sim Version 8.0

### Code of Conduct

Everyone interacting in the Open Systems Pharmacology community (codebases, issue trackers, chat rooms, mailing lists etc.) is expected to follow the Open Systems Pharmacology [code of conduct](https://github.com/Open-Systems-Pharmacology/Suite/blob/master/CODE_OF_CONDUCT.md#contributor-covenant-code-of-conduct).

### License

The model is distributed under the [GPLv2 License](https://github.com/Open-Systems-Pharmacology/Suite/blob/develop/LICENSE).

### Reference

[1][ Dallmann, A., Himstedt, A., Solodenko, J. et al. Integration of physiological changes during the postpartum period into a PBPK framework and prediction of amoxicillin disposition before and shortly after delivery. J Pharmacokinet Pharmacodyn (2020).](https://doi.org/10.1007/s10928-020-09706-z)