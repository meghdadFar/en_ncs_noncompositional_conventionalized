
This is a dataset of English noun compounds that are annotated with judgments on 
non-compositionality and conventionalization.  

======================================================================================

This repository consists of the following files: 
instances_judgments/conv-judgments.csv 
instances_judgments/noncomp-judgments.csv
README

Below is the description of these files:
 

(1) instances_judgments/judgments/conv-judgments.csv: Contains 1042 English noun compounds and 4 conventionalization 
judgments for each compound. Conventionalization judgments are of three types:

 1: conventionalized 
 0: non-conventionalized
 x: conventionalized due to non-compositionality 

(2) instances_judgments/noncomp-judgments.csv: Contains the same 1042 English noun compounds and 4 non-compositionality 
judgments for each compound. Non-compositionality judgments are of two types:

 1: non-compositional
 0: compositional


Example: 

conv-judgments.csv @ line 68: board game 1 x 1 1
noncomp-judgments.csv @ line 68: board game 0 1 0 0


For more details please refer to our article: "A Multiword Expression Datset: Annotating 
Non-Compositionality and Conventionalization for English Noun Compounds"


======================================================================================

Creators:

Meghdad Farahmand: meghdad.farahmand@unige.ch

Aaron Smith: aaron.smith@lingfil.uu.se

Joakim Nivre: joakim.nivre@lingfil.uu.se

======================================================================================


You can cite this dataset under:


@inproceedings{farahmandSmithNivre2015data,
	Author = {Farahmand, Meghdad and Smith, Aaron and Nivre, Joakim},
	Booktitle = {Proceedings of the 11th Workshop on Multiword Expressions (MWE-NAACL 2015)},
	Date-Added = {2015-05-26 13:27:46 +0000},
	Date-Modified = {2015-05-26 13:27:46 +0000},
	Organization = {Association for Computational Linguistics},
	Title = {A Multiword Expression Dataset: Annotating Non-Compositionality and Conventionalization for English Noun Compounds},
	Year = {2015}}

======================================================================================

Acknowledgments: 

We provide a dataset of English noun compounds which are annotated with four expert judgments on non-compositionality and conventionalization. The compounds were extracted from Wikipedia, which was cleaned and then POS-tagged by Stanford POS-tagger. 
We conducted a manual assessment of the automatically generated data and removed wrongly-tagged instances, infrequent instances, and other kinds of discrepancies; however, we believe that about 5% of the data may still be wrongly POS-tagged or occur with a very low frequency. This is due to the large size of the set, human error, and a workflow consisting of various procedures performed by different (and often not readily compatible) tools and programs. 
The user of the data should be aware of the presence of a (small number of) discrepant instances. Nevertheless, almost certainly these instances (that constitute about 5% of the data) are among the compounds which are judged by the majority as neither non-compositional nor conventionalized (i.e., annotated with 0s). 

======================================================================================

License: 

This dataset is created by Meghdad Farahmand, Aaron Smith and Joakim Nivre,
used under CC-BY SA 3.0 (http://creativecommons.org/licenses/by/3.0/).

