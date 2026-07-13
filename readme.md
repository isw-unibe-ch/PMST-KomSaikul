# Person Marking in South-Central Trans-Himalayan: Saikul Kom

This PARALEX set contains person markers in Saikul Kom, including inflected verbal forms and pronouns. It constitutes part of the PMST (Person Marking in South-Central Trans-Himalayan) database.
The PMST database is a collection of person forms from a broad sample of South-Central Trans-Himalayan languages collected with a common methodology and published as PARALEX sets. PMST sets can be used both for describing and analyzing language-internal distributions and for comparison of person forms.

The general design principles of PMST are described in Auderset et al. 2026. Files and columns are described here only where they deviate from the PARALEX standard.
For more details about the data, please consult the data\_sheet.md in the docs folder.

* PMST diverges most from the PARALEX standard and design principles in that the verb forms are abstract and do not contain a lexical verb stem. In its place, we use Σ as a placeholder (as is common in Trans-Himalayan linguistics). This means that the data set cannot be used to study variation in verb stems or inflectional classes.
* The source\_form column in the forms file contains the data exactly as it appears in the source. This may include a lexical verb stem (listed in lexemes). In the orthgoraphic and phonological representation, the lexical verb is replaced by a Σ. This placeholder also appears in the graphemes and sounds files for validation purporses.
* The lexemes file is kept relatively minimal and only lists each lexical stem in orthographic form and its meaning. This is because we do not always have access to forms with stems. For pronouns, "no\_stem" is indicated in the lexeme column in the forms file and verb forms without a stem are labeled "abstract\_entry". These are also listed in the lexemes file (for validation purposes).
* To facilitate comparison across PMST data sets, each file has an additional column with a language identifier. This means that files can be combined from different PMST sets without losing information.
* The morphs file contains a list of all morphs that appear in the data set (apart from the stem) in tokenized IPA. For each morph there is a list of all the forms and cells it appears in.
* The docs folder contains the data sheet with more extensive description of how the data was gathered. It also contains csv tables with matrix layouts of the paradigms (similar to what we usually find in published sources) and a plot showing the distribution of each morph across most relevant grammatical categories.

## Additional information specific to Saikul Kom

* Tone: Tone is unmarked as the tonal analysis is yet to be done.
* Variation in this dataset:
  * a) colloquial (spoken/informal/fast speech) vs formal (written/formal/slow speech): e.g.: nuŋ vs ni-uŋ vs niŋ-uŋ in 1>2/3 in future negative construction
  * b) sociolect variation between tin vs niŋ in 2>1/3 and 3>2 in future negative construction
  * c) free variation between the 1SG/1PL object marker a- and ei- in 2/3>1 negative construction
  * d) optional plural in 3PL>2 and 2>3PL in negative construction
  * e) variable order between hei-ning and ning-hei in 3PL>1/2 and 2>3PL negative construction


## References

Auderset, Sandra, Hunter L. Brown, Jonathan Reich, Pascal Gerber, Muhammad Zakaria, and Linda Konnerth. 2026. “A Database of Person Marking in South-central Trans-himalayan”. *Journal of Open Humanities Data* 12 (1): 58. https://doi.org/10.5334/johd.505.