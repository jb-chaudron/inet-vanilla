# inet-vanilla


## Table of contents
* [General Informations](#general-info)
* [General Idea](#aim)
* [Technologies](#technologies)


## General Informations

Graded Project from the Complex Network class took in 2020 in the ENS Lyon.

## General Idea
Using a DataSet of iEEG data, we tried to isolate specific pattern of neural connectivity, depending on the behavioral outcome of the trials.
To form the network, we used Network Based Statistics (Zalesky, Fornito & Bullmore, 2010) on averaged signals over the trials.
Two contacts (intracerebral electrodes) were said functionnaly connected, if their signal averaged signal over the type A behavior trials, was more correlated that than in randomly averaged trials.

Thus this permutation gave us the ability to obtain two networks, where each link represent a functionnal coupling between two electrodes, stronger in this particular condition, than in general.

## Technologies
Project is created with:
* Python
* Google Colab

* Zalesky, A., Fornito, A., & Bullmore, E. T. (2010). Network-based statistic: Identifying differences in brainnetworks.Neuroimage,53(4), 1197–1207.
