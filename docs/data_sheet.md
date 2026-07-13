Data set name: PMST Kom Saikul

Data set developer(s): Susie Kanshouwa, Sandra Auderset, Antonia Pauly

Data sheet author(s):Susie Kanshouwa, Sandra Auderset

Others who contributed to this document: Hatfinlay Telien, Karoung Nenghakrei Kom, Seikhohao Karoung


# Motivation

**For what purpose was the dataset created?**

This data set was created to investigate the dynamics of person marking in Saikul Kom and other South-Central Trans-Himalayan languages.
Further background and motivation can be found in Auderset et al. 2026.

**Who created the data set (for example, which team, research group) and on behalf of which entity (for example, company, institution, organization)?**

The data set was created by a team of researchers at the Department of Linguistics at the University of Bern (PI Linda Konnerth) in collaboration with local linguists and language experts in Northeast India.

**Who funded the creation of the data set?**

This work is funded by SNSF (Swiss National Science Foundation) Grant 10000946 to Linda Konnerth at the University of Bern.


# Composition

This Paralex dataset documents paradigms of inflected verb forms as well as pronouns.

**Are forms given as orthographic, phonetic, and or phonemic sequences ?**

Forms are provided as orthographic and phonemic sequences.
The orthography is either the practical one used by the community or a version of the IPA used by linguists and language experts.
For Saikul, it is a version of the community orthography used by speakers.

**How many instances are there in total?**

* Number of inflected forms: 233
* Number of unique inflected forms: 151
* Number of unique scenarios (person, number, TAM, polarity combinations): 162
* Number of inflected forms per paradigm and subparadigm:

|paradigm |epistemic_tag |variants_tag  |analysis_tag   |overabundance_tag |  n|
|:--------|:-------------|:-------------|:--------------|:-----------------|--:|
|pron     |elicited      |unspecified   |               |                  |  7|
|fut.aff  |elicited      |unspecified   |               |                  | 39|
|fut.neg  |elicited      |dialect_var   |               |                  |  2|
|fut.neg  |elicited      |formal        |               |                  |  2|
|fut.neg  |elicited      |informal      |               |fusion            |  2|
|fut.neg  |elicited      |sociolect_var |variable_order |                  | 11|
|fut.neg  |elicited      |sociolect_var |               |optional_plural   |  2|
|fut.neg  |elicited      |sociolect_var |               |                  | 25|
|fut.neg  |elicited      |unspecified   |variable_order |                  |  1|
|fut.neg  |elicited      |unspecified   |               |optional_future   |  1|
|fut.neg  |elicited      |unspecified   |               |optional_plural   |  2|
|fut.neg  |elicited      |unspecified   |               |                  | 32|
|fut.neg  |generated     |dialect_var   |               |                  |  7|
|fut.neg  |generated     |sociolect_var |               |                  |  5|
|fut.neg  |generated     |unspecified   |               |                  |  3|
|nfut.aff |elicited      |dialect_var   |               |                  |  1|
|nfut.aff |elicited      |unspecified   |               |optional_plural   |  1|
|nfut.aff |elicited      |unspecified   |               |                  | 38|
|nfut.neg |elicited      |dialect_var   |               |                  |  5|
|nfut.neg |elicited      |unspecified   |               |optional_plural   |  2|
|nfut.neg |elicited      |unspecified   |               |                  | 35|
|nfut.neg |generated     |dialect_var   |               |                  |  6|
|nfut.neg |generated     |unspecified   |               |                  |  4|


**Language varieties**

* BCP-47 language tag: NA
* Glottocode: komi1270
* Language variety description: Saikul Kom belongs to the Mongtung variety of Kom spoken in Saikul subdivision of Kangpokpi district, Manipur. The Mongtung variety is considered the standard variety of Kom. The Glottocode refers to Kom in general, not specifically to the Saikul variety.

**Does the data pertain to specific dialects, geographical locations, genre, etc ?**

The data is collected from Saikul village, located in Kangpokpi district, Manipur, and belongs to the Mongtung variety of Kom.

**Does the dataset contain all possible instances or is it a sample (not necessarily random) of instances from a larger set?**

The dataset contains all person forms found in the language, both verbal indexes and pronouns. Hortative forms were not included in the dataset (see below for explanation).

**Is any information missing from individual instances?**

No.

**Are there any errors, sources of noise, or redundancies in the dataset?**

No.

**Is the dataset self-contained, or does it link to or otherwise rely on external resources (for example, websites, tweets, other datasets)?**

The dataset is self-contained.

**If linking to vocabularies from other databases (such as databases of features, cells, sounds, languages, or online dictionaries), were there any complex decisions in the matching of entries from this dataset to those of the vocabularies (eg. inexact language code) ?**

NA

**Does the dataset contain data that might be considered confidential (for example, data that is protected by legal privilege or by doctor-patient confidentiality, data that includes the content of individuals' non-public communications)?**

The dataset pertains to small or indigenous language communities, namely those of the Kom people in Manipur.
The data are published here with the consent of the community.


# Collection process.

**What is provenance for each table (lexemes, cells, forms, frequencies, sounds, features), as well as for segmentation marks if any ? Are any information derived from other datasets ?**

The data comes from fieldwork conducted by Susie Kanshouwa. Specific forms were taken from a combination of a text corpus, elicitation, and field notes. This work also forms the basis for the segmentation.

**How were paradigms separated (eg. in the case of homonyms or variants)? What theoretical or practical choices were made?**

Design principles and theoretical choices implemented for this data set are explained in Auderset et al. 2026.

**How was the paradigm structure (set and labels of paradigm cells) decided? What theoretical or practical choices were made?**

Design principles and theoretical choices implemented for this data set are explained in Auderset et al. 2026.

**What is the expertise of the contributors with the documented language ?**

Susie Kanshouwa: linguist specializing in South-Central Trans-Himalayan, and currently working on a documentation project of Kom language and its varieties

Hatfinlay Telien: native speaker (language consultant) and Ph.D. scholar in history

Karoung Nenghakrei Kom: native speaker (language consultant)

Seikhohao Karoung: native speaker (language consultant)

**Who was involved in the data collection process (for example, students, crowdworkers, contractors) and how were they compensated (for example, how much were crowdworkers paid)?**

Only the contributors listed at the beginning of this file.

**Over what timeframe was the data collected?**

The data was collected predominantly in fall and winter 2025.


# Preprocessing/cleaning/labeling.

**How were the inflected forms obtained ?**

All forms were collected from speakers. See above.

**How were the phonological or phonemic transcriptions obtained?**

The phonological transcriptions were generated with the qlcData package in R using an orthography profile that maps graphemes to IPA.
The mappings are based on the phonological analysis of the language.

**If relevant, how were the forms segmented?**

Manually based on expert knowledge.

**Was any preprocessing/cleaning/labeling of the data done (for example, discretization or bucketing, tokenization, part-of-speech tagging, SIFT feature extraction, removal of instances, processing of missing values, cleaning of labels, mapping between vocabularies, etc)?**

No.

**Was the "raw" data saved in addition to the preprocessed/cleaned/labeled data (for example, to support unanticipated future uses)?**

Yes (not publicly available yet).

**Is the software that was used to preprocess/clean/label the data available?**

The data was prepared for Paralex with the open source software R using RStudio.


# Uses

**Has the dataset been used for any published work already?**

No.

**What (other) tasks could the dataset be used for?**

It can be used for descriptive and comparative analyses.

**Are there tasks for which the dataset should not be used?**

No.


# Distribution.

**Will the dataset be distributed to third parties outside of the entity (for example, company, institution, organization) on behalf of which the dataset was created?**

No.

**How will the dataset be distributed (for example, tarball on website, API, GitHub)?**

The dataset is available on GitHub at X and on Zenodo as part of the Paralex collection at X.

**Will the dataset be distributed under a copyright or other intellectual property (IP) license, and/or under applicable terms of use (ToU)?**

The dataset is distributed under a CC-BY-SA 4.0 license.


# Maintenance

**If others want to extend/augment/build on/contribute to the dataset, is there a mechanism for them to do so?**

For suggestions or error reports please open an issue on GitHub.