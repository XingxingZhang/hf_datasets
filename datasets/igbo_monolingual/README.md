---
annotations_creators:
- found
language_creators:
- found
languages:
- ig
licenses:
- unknown
multilinguality:
- monolingual
size_categories:
  bbc-igbo:
  - 1K<n<10K
  eze_goes_to_school:
  - n<1K
  igbo-radio:
  - n<1K
  jw-books:
  - n<1K
  jw-nt-igbo:
  - n<1K
  jw-ot-igbo:
  - n<1K
  jw-teta:
  - n<1K
  jw-ulo_nche:
  - n<1K
  jw-ulo_nche_naamu:
  - n<1K
source_datasets:
- original
task_categories:
- sequence-modeling
task_ids:
- language-modeling
paperswithcode_id: null
---

# Dataset Card for Igbo Monolingual Dataset

## Table of Contents
- [Dataset Description](#dataset-description)
  - [Dataset Summary](#dataset-summary)
  - [Supported Tasks and Leaderboards](#supported-tasks-and-leaderboards)
  - [Languages](#languages)
- [Dataset Structure](#dataset-structure)
  - [Data Instances](#data-instances)
  - [Data Fields](#data-fields)
  - [Data Splits](#data-splits)
- [Dataset Creation](#dataset-creation)
  - [Curation Rationale](#curation-rationale)
  - [Source Data](#source-data)
  - [Annotations](#annotations)
  - [Personal and Sensitive Information](#personal-and-sensitive-information)
- [Considerations for Using the Data](#considerations-for-using-the-data)
  - [Social Impact of Dataset](#social-impact-of-dataset)
  - [Discussion of Biases](#discussion-of-biases)
  - [Other Known Limitations](#other-known-limitations)
- [Additional Information](#additional-information)
  - [Dataset Curators](#dataset-curators)
  - [Licensing Information](#licensing-information)
  - [Citation Information](#citation-information)
  - [Contributions](#contributions)

## Dataset Description

- **Homepage:** https://github.com/IgnatiusEzeani/IGBONLP/tree/master/ig_monoling
- **Repository:** https://github.com/IgnatiusEzeani/IGBONLP/tree/master/ig_monoling
- **Paper:** https://arxiv.org/abs/2004.00648

### Dataset Summary

A dataset is a collection of Monolingual Igbo sentences.

### Supported Tasks and Leaderboards

[More Information Needed]

### Languages

Igbo (ig)

## Dataset Structure

### Data Instances

Here is an example from the bb-igbo config:
```
{'content': 'Ike Ekweremmad???\n\nIke ???da j?????? ot??? nkeji banyere oke ogbugbu na-eme n\'ala Naijiria agw???la Ekweremmad???\n\nOsote onye-isi nd??? ome-iwu Na???jir???a b??? Ike Ekweremadu ekwuola na ike agw???la nd??? S???nat??? iji otu nkeji daraj?????? akwanyere nd??? egburu n\'ime oke ???gbaghara d??? na Na???jir???a oge ??? bula.\n\nEkweremadu  kat???r??? mwakp??? na ogbugbu nd??? Na???jir???a aka ha d??? ???cha nke nd??? Fulani na-ach??? ehi mere, kwuo na ike agw???la nd??? ome- iwu ???kwanyere ha ugwu n\'otu nkeji\'\n\nCheta n\'otu ???z???ka gara-aga ka emere akwam ozu mmad??? ruru iri asaa egburu na Local G??????menti Logo na Guma nke Benue Steeti, e be ihe kariri mmad??? iri ise ka ak???k??? kwuru n\'egburu na Taraba Steeti.\n\nEkweremadu gosiri iwe gbasara ogbugbu nd??? mmad??? na nzuk??? nd??? ome-iwu n\'???b???ch??? taa, kwuo na Na???jir???a ga-ebu ???z??? nwe udo na nchekwa, tupu e kwuowa okwu iwulite obodo.\n\n??? s???r???:  "Nd??? ome-iwu ab???gh??? s??? ???s??? nd??? ihe a met???tara, kama nd??? Na???jir???a niile.\n\n\'Ike agw???la any??? iji otu nkeji d??? j?????? maka nkwanye ugwu. Ihe any??? ch???r??? b??? udo na nchekwa tupu echewa ech???ch??? nwuli obodo."',
 'date': '2018-01-19T17:07:38Z',
 'description': "N'ihi oke ogbugbu nd??? mmad??? na Na???jir???a gbagburu gburu, osota onyeisi nd??? ome-iwu Na???jir???a b??? Ike Ekweremadu ekwuola na ihe Na???jiria ch???r??? b??? nchekwa tara ???ch???ch???, tupu ekwuwa okwu ihe ???z???.",
 'headline': 'Ekweremadu: Ike agw???la nd??? ???l??? ome iwu',
 'source': 'https://www.bbc.com/igbo/42712250',
 'tags': [],
 'title': 'Ekweremadu: Ike agw???la nd??? ???l??? ome iwu'}
```

### Data Fields

For config 'eze_goes_to_school':
  - format, title, chapters

For config 'bbc-igbo' :
  - source, title, description, date (Missing date values replaced with empty strings), headline, content, tags (Missing tags replaced with empty list)

For config 'igbo-radio':
  - source, headline, author, date, description, content

For config 'jw-ot-igbo':
  - format, title, chapters

For config 'jw-nt-igbo':
  - format, title, chapters

For config 'jw-books': 
  - title, content, format, date (Missing date values replaced with empty strings)

For config 'jw-teta': 
  -  title, content, format, date (Missing date values replaced with empty strings)

For config 'jw-ulo_nche': 
  - title, content, format, date (Missing date values replaced with empty strings)

For config 'jw-ulo_nche_naamu':
  - title, content, format, date (Missing date values replaced with empty strings)


### Data Splits
| bbc-igbo  | eze_goes_to_school |igbo-radio| jw-books|jw-nt-igbo| jw-ot-igbo | jw-teta |jw-ulo_nche |jw-ulo_nche_naamu
| ------------- |:-------------:|:-------------:|:-------------:|:-------------:|:-------------:|:-------------:|:-------------:|:-------------:|
|  1297     | 1     | 440   | 48     | 27     | 39 | 37 | 55 | 88

## Dataset Creation

### Curation Rationale

[More Information Needed]

### Source Data

#### Initial Data Collection and Normalization

[More Information Needed]

#### Who are the source language producers?

[More Information Needed]

### Annotations

#### Annotation process

[More Information Needed]

#### Who are the annotators?

[More Information Needed]

### Personal and Sensitive Information

[More Information Needed]

## Considerations for Using the Data

### Social Impact of Dataset

[More Information Needed]

### Discussion of Biases

[More Information Needed]

### Other Known Limitations

[More Information Needed]

## Additional Information

### Dataset Curators

[More Information Needed]

### Licensing Information

[More Information Needed]

### Citation Information

@misc{ezeani2020igboenglish,  
title={Igbo-English Machine Translation: An Evaluation Benchmark},  
author={Ignatius Ezeani and Paul Rayson and Ikechukwu Onyenwe and Chinedu Uchechukwu and Mark Hepple},  
year={2020},  
eprint={2004.00648},  
archivePrefix={arXiv},  
primaryClass={cs.CL}  
}

### Contributions

Thanks to [@purvimisal](https://github.com/purvimisal) for adding this dataset.