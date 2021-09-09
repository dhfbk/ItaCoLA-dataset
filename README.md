# ItaCola

## Italian Corpus of Linguistic Acceptability

--------------



### Authors

[Daniela Trotta](https://dh.fbk.eu/author/daniela/), [Raffaele Guarasci](https://www.icar.cnr.it/persone/guarasci/), [Elisa Leonardelli](https://dh.fbk.eu/author/elisa/), [Sara Tonelli](https://dh.fbk.eu/author/sara/)



### Introduction

The Italian Corpus of Linguistic Acceptability includes almost 10k sentences taken from linguistic literature with a binary annotation made by the original authors themselves. The work is inspired by [CoLA](https://nyu-mll.github.io/CoLA/)[^1].



#### Paper

Read the paper at [LINK TO BE ADDED]()



### Download

Download ItaCola from this [LINK TO BE ADDED]()



#### Citation

> Trotta D., Guarasci R., Leonardelli E., Tonelli S. *Monolingual and Cross-Lingual Acceptability Judgments with the Italian CoLA corpus*. To appear in Findings of EMNLP 2021.

### Data Description



#### Sources

Sources come from different sources extracted from the linguistic literature, covering a wide range of topics.

| Source Legend           | Topic                            |
| ----------------------- | -------------------------------- |
| D-Agostino_1983[^2]     | locative constructions           |
| D-Agostino_1992[^3]     | discourse analysis               |
| Elia-et-al_1981[^4]     | lexicon and syntactic structures |
| Elia_1982[^5]           | locative adverbs and idioms      |
| Graffi-Scalise_2002[^6] | theoretical linguistics          |
| Graffi_1994[^7]         | syntax                           |
| Graffi_2008[^8]         | generative grammar               |
| Jezek_2003[^9]          | verb classification              |
| Simone-Masini_2013[^10] | theoretical linguistics          |
| Vietri_1985[^11]        | idiomatic expressions            |
| Vietri_2004[^12]        | lexicon-grammar approach         |
| Vietri_2017[^13]        | anticausative sentences          |



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

Download the annotated sentences from this [LINK TO BE ADDED]()

#### Split

- `train`: 7762 sentences
- `test`:  976 sentences
- `dev`: 948 sentences

####Data Format

Each line in the .tsv files consists of 3 tab-separated columns.

- Column 1:	the source of the sentence 
- Column 2:	the acceptability judgment label (0=unacceptable, 1=acceptable)
- Column 3:	the sentence.



#### Corpus Sample

| Source          | Judgement | Sentence                                                     |
| --------------- | --------- | ------------------------------------------------------------ |
| Graffi_1994     | 1         | Questa donna mi ha colpito. (*That women impressed me*)      |
| Vietri_2017     | 1         | Alice ha fatto terrorizzare Francesco da quell'uomo. (*Alice made Francesco terrified of the man.*) |
| Elia-et-al_1981 | 00        | Il ministro è dal ritiro del passaporto. (*The minister is from passport withdrawal*) |
| Vietri_2004     | 1         | Edoardo ne ride. (*Edward laughs about it*)                  |
| Vietri_2004     | 0         | Francesco lo detesta mangiare. (*Francesco it hates to eat*) |





[^1]: Alex Warstadt, Amanpreet Singh, Samuel R. Bowman; *Neural Network Acceptability Judgments*. Transactions of the Association for Computational Linguistics. 2019; 7 625–641.
[^2]: Emilio D’Agostino. 1983. Le*ssico e sintassi dellecostruzioni locative: materiali per la didattica dell’italiano*. Liguori.
[^3]: Emilio D’Agostino. 1992. An*alisi del discorso: metodi descrittivi dell’italiano d’uso*. Loffredo.
[^4]: Annibale Elia, Maurizio Martinelli, and Emilio d’Agostino. 1981. L*essico e strutture sintattiche: introduzione alla sintassi del verbo italiano*. Liguori Napoli.
[^5]: Annibale Elia. 1982. *Avverbi ed espressioni idiomatiche di carattere locativo*. Studi di Grammatica Italiana Firenze, 11:327–379.
[^6]: Giorgio Graffi and Sergio Scalise. 2002. *Le lingue e il linguaggio. Introduzione alla linguistica*. Il Mulino, Bologna, Italy.
[^7]: Giorgio Graffi. 1994. *Le strutture del linguaggio. Sintassi*. Il Mulino, Bologna, Italy.
[^8]: Giorgio Graffi. 2008. *Che cos’è la grammatica generativa*. Carocci editore, Roma, Italy
[^9]: Elisabetta Jezek. 2003. *Classi di verbi tra semantica e sintassi*. Edizioni ETS, Pisa, Italy.
[^10]: Raffaele Simone and Francesca Masini. 2013. *Nuovi fondamenti di linguistica*. McGraw Hill.
[^11]: Simonetta Vietri. 2004. *Lessico-grammatica dell’italiano. Metodi, descrizioni e applicazioni*. UTET Università.
[^12]: Simonetta Vietri. 2014. *Idiomatic constructions in Italian: a lexicon-grammar approach*, volume 31. John Benjamins Publishing Company.
[^13]: Simonetta Vietri. 2017. *Usi verbali dell’italiano: le frasi anticausative*. Carocci editore.


