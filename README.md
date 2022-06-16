
This repository contains the annotated datasets of the papers:

[1.](# 1.) [Daniela Trotta](https://dh.fbk.eu/author/daniela/), [Raffaele Guarasci](https://www.icar.cnr.it/persone/guarasci/), [Elisa Leonardelli](https://dh.fbk.eu/author/elisa/), [Sara Tonelli](https://dh.fbk.eu/author/sara/). **Monolingual and Cross-Lingual Acceptability Judgments with the Italian CoLA corpus.** In *Findings of EMNLP 2021*.

[[cite]](#citation) [[read the paper]](https://aclanthology.org/2021.findings-emnlp.250/)

2. [Federico Bonetti](https://dh.fbk.eu/author/federicob/), [Elisa Leonardelli](https://dh.fbk.eu/author/elisa/), [Daniela Trotta](https://dh.fbk.eu/author/daniela/), [Raffaele Guarasci](https://www.icar.cnr.it/persone/guarasci/), [Sara Tonelli](https://dh.fbk.eu/author/sara/). **Work Hard, Play Hard: Collecting Acceptability Annotations through a 3D Game** In *Proceedings of Language Resources and Evaluation Conference In LREC 2022. ELRA, 2022*.

[[cite]](#citation2) (*paper upcoming*) 

--------------
# 1. Monolingual and Cross-Lingual Acceptability Judgments with the Italian CoLA corpus





### Authors

[Daniela Trotta](https://dh.fbk.eu/author/daniela/), [Raffaele Guarasci](https://www.icar.cnr.it/persone/guarasci/), [Elisa Leonardelli](https://dh.fbk.eu/author/elisa/), [Sara Tonelli](https://dh.fbk.eu/author/sara/)



### Introduction

The Italian Corpus of Linguistic Acceptability includes almost 10k sentences taken from linguistic literature with a binary annotation made by the original authors themselves. The work is inspired by [CoLA](https://nyu-mll.github.io/CoLA/)<sup>1</sup>.



#### Paper

Read the paper at https://aclanthology.org/2021.findings-emnlp.250/



### Download

Download ItaCola from this [ItaCoLA_dataset.tsv](ItaCoLA_dataset.tsv)



#### Citation

> Trotta D., Guarasci R., Leonardelli E., Tonelli S. *Monolingual and Cross-Lingual Acceptability Judgments with the Italian CoLA corpus*. In Findings of EMNLP 2021.

### Data Description



#### Sources

Sources come from different sources extracted from the linguistic literature, covering a wide range of topics.

| Source Legend           | Topic                            |
| ----------------------- | -------------------------------- |
| D-Agostino_1983<sup>2</sup>     | locative constructions           |
| D-Agostino_1992<sup>3</sup>     | discourse analysis               |
| Elia-et-al_1981<sup>4</sup>     | lexicon and syntactic structures |
| Elia_1982<sup>5</sup>           | locative adverbs and idioms      |
| Graffi-Scalise_2002<sup>6</sup>| theoretical linguistics          |
| Graffi_1994<sup>7</sup>        | syntax                           |
| Graffi_2008<sup>8</sup>        | generative grammar               |
| Jezek_2003<sup>9</sup>         | verb classification              |
| Simone-Masini_2013<sup>10</sup> | theoretical linguistics          |
| Vietri_1985<sup>11</sup>       | idiomatic expressions            |
| Vietri_2004<sup>12</sup>        | lexicon-grammar approach         |
| Vietri_2017<sup>13</sup>       | anticausative sentences          |

#### Data Format

ItaCola is split into:

- `train`: 7801 sentences
- `dev`: 946 sentences
- `test`:  975 sentences

Each line in the `.tsv` files consists of 5 tab-separated columns.

- Column 1: an unique ID
- Column 2:	the source of the sentence 
- Column 3:	the acceptability judgment label (0=unacceptable, 1=acceptable)
- Column 4:	the sentence
- Column 5: the split to which the sentence belongs


#### Corpus Sample

| UniqueID | Source          | Judgement | Sentence                                                     | Split |
| -------- | --------------- | --------- | ------------------------------------------------------------ | ----- |
| 3        | Graffi_1994     | 1         | Questa donna mi ha colpito. (*That women impressed me*)      | train |
| 5784     | Vietri_2017     | 1         | Alice ha fatto terrorizzare Francesco da quell'uomo. (*Alice made Francesco terrified of the man.*) | train |
| 8307     | Vietri_2004     | 0         | Quell'architetto ha alcuni progettato musei. (*That architect has some designed museums.*) | dev   |
| 9206     | Elia-et-al_1981 | 0         | Il ministro è dal ritiro del passaporto. (*The minister is from passport withdrawal*) | test  |
| 9366     | Vietri_2004     | 1         | Edoardo ne ride. (*Edward laughs about it*)                  | test  |

#### Annotation

Part of the dataset has been manually annotated with 9 linguistic phenomena.

| Phenomenon             |
| ---------------------- |
| Cleft constructions    |
| Copular constructions  |
| Subject-Verb Agreement |
| Wh-islands violations  |
| Simple                 |
| Question               |
| Auxiliary              |
| Bind                   |
| Indefinite pronouns    |

File containing annotated sentences can be downloaded from this [ItaCoLA_dataset_phenomenon](ItaCoLA_dataset_phenomenon.tsv). Every annotated sentence in this file is linked to main one through the unique id. The `.tsv` file has a structure similar to the main corpus, but each phenomenon is represented in a column (1 if present, 0 if not present).



#### citation2
Federico Bonetti, Elisa Leonardelli, Daniela Trotta, Raffaele Guarasci, and Sara Tonelli. Work Hard, Play Hard: Collecting Acceptability Annotations through a 3D Game [In Press]. In Proceedings of Language Resources and Evaluation Conference (LREC 2022). ELRA, 2022.

#### References

1. Alex Warstadt, Amanpreet Singh, Samuel R. Bowman; *Neural Network Acceptability Judgments*. Transactions of the Association for Computational Linguistics. 2019; 7 625–641.
2. Emilio D’Agostino. 1983. Le*ssico e sintassi dellecostruzioni locative: materiali per la didattica dell’italiano*. Liguori.
3. Emilio D’Agostino. 1992. An*alisi del discorso: metodi descrittivi dell’italiano d’uso*. Loffredo.
4. Annibale Elia, Maurizio Martinelli, and Emilio d’Agostino. 1981. L*essico e strutture sintattiche: introduzione alla sintassi del verbo italiano*. Liguori Napoli.
5. Annibale Elia. 1982. *Avverbi ed espressioni idiomatiche di carattere locativo*. Studi di Grammatica Italiana Firenze, 11:327–379.
6. Giorgio Graffi and Sergio Scalise. 2002. *Le lingue e il linguaggio. Introduzione alla linguistica*. Il Mulino, Bologna, Italy.
7. Giorgio Graffi. 1994. *Le strutture del linguaggio. Sintassi*. Il Mulino, Bologna, Italy.
8. Giorgio Graffi. 2008. *Che cos’è la grammatica generativa*. Carocci editore, Roma, Italy
9. Elisabetta Jezek. 2003. *Classi di verbi tra semantica e sintassi*. Edizioni ETS, Pisa, Italy.
10. Raffaele Simone and Francesca Masini. 2013. *Nuovi fondamenti di linguistica*. McGraw Hill.
11. Simonetta Vietri. 2004. *Lessico-grammatica dell’italiano. Metodi, descrizioni e applicazioni*. UTET Università.
12. Simonetta Vietri. 2014. *Idiomatic constructions in Italian: a lexicon-grammar approach*, volume 31. John Benjamins Publishing Company.
13. Simonetta Vietri. 2017. *Usi verbali dell’italiano: le frasi anticausative*. Carocci editore.

