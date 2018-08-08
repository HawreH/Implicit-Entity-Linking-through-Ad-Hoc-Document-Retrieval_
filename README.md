# Resources for Performing Implicit Entity Linking through Ad Hoc Retrieval

# Overview
This repository includes some of the resources gathered and codes written for performing [Implicit Entity Linking through Ad Hoc Retrieval](http://ls3.rnet.ryerson.ca/?page_id=16&key=asonam2018&src=citations.bib) published in [IEEE/ACM International Conference on Social Networks Analysis and Mining (ASONAM 2018)](http://asonam.cpsc.ucalgary.ca/2018/).

## Neural Embedding-Based Measure of Similarity (NEMS)
The folder named *NEMS Feature* contains the source codes-in Python- for the extraction of our proposed *Neural Embedding-based Measure of Similarity (NEMS)* feature. It also contains two *.txt* files, namely ReadMe and Requirements, which explain the execution steps and library requirements, respectively.<br>
Moreover, output of our trained models queried by entities are provided in a subfolder named *Query Outputs*. The outputs are saved in *.pickle* files and their names indicate the entity used as the query.

### Sample Output
For instance, for the entity *Ethan Hawke*, the output of our feature is as follows: 
<p allign="center">
{'text': '**Ethan Hawke**', 'head': 'hawke', 'count': 743, 'key': 'Ethan_Hawke|ENT', <br>
'results': [{...,<br>
{'score': 0.9872463576346568, 'head': 'linklater', 'count': 620, 'key': 'Richard_Linklater|ENT', 'text': 'Richard Linklater'}, <br> 
{'score': 0.9973005056381226, 'head': 'woodley', 'count': 903, 'key': 'Shailene_Woodley|ENT', 'text': 'Shailene Woodley'}, <br>
{'score': 0.9975419044494629, 'head': 'adams', 'count': 808, 'key': 'Amy_Adams|ENT', 'text': 'Amy Adams'}, <br>
...]<br>
</p>

## User-Generated Content and Tagger Output
The folder named *Resources* includes the gathered user-generated content which were used in our experiments. Specifically, user reviews for *Movies* and *Books* are provided in *.txt* files. File names indicate the title of the entities for which they contain reviews. Moreover, the output of the off-the-shelf entity taggers, i.e. *TagMe* and *AIDA*, for the aforementioned collections of documents are also contained in the pertinent folders. Again, file names indicate the title of the entities for which they contain reviews.

## SPARQL Outputs
Last but not least, under the *Resources* folder the output of *SPARQL* queries made by entities found in the tweets are rendered in two *.txt* files with the following delimiter format: 


<p align="center">
'entity' \t 'DBpedia_URL<sub>1</sub>', \t , 'DBpedia_URL<sub>2</sub>', \t, ..., 'DBpedia_URL<sub>N</sub>'
</p>



# Citation
```
<pre>
<b>Refernce</b>:
</pre>
Hawre Hosseini; Tam T. Nguyen and Ebrahim Bagheri *Implicit Entity Linking through Ad-hoc Retrieval*. In [IEEE/ACM International Conference on Social Networks Analysis and Mining (ASONAM 2018)](http://asonam.cpsc.ucalgary.ca/2018/), 2018.

**Bibtex entry**:

@inproceedings{asonam2018,
		author    = {Hawre Hosseini and Tam T. Nguyen and Ebrahim Bagheri},
		title     = {Implicit Entity Linking through Ad-hoc Retrieval},
		booktitle = {IEEE/ACM International Conference on Social Networks Analysis and Mining (ASONAM 2018)},
		year      = {2018},
		url       = {http://asonam.cpsc.ucalgary.ca/2018/}
}

```
