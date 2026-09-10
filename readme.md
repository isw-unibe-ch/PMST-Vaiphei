# Person Marking in South-Central Trans-Himalayan: Vaiphei

This PARALEX set contains person markers in Vaiphei, including inflected verbal forms and pronouns. It constitutes part of the PMST (Person Marking in South-Central Trans-Himalayan) database.
The PMST database is a collection of person forms from a broad sample of South-Central Trans-Himalayan languages collected with a common methodology and published as PARALEX sets. PMST sets can be used both for describing and analyzing language-internal distributions and for comparison of person forms.

The general design principles of PMST are described in Auderset et al. 2026. Files and columns are described here only where they deviate from the PARALEX standard.
For more details about the data, please consult the data\_sheet.md in the docs folder.

* PMST diverges most from the PARALEX standard and design principles in that the verb forms are abstract and do not contain a lexical verb stem. In its place, we use Σ as a placeholder (as is common in Trans-Himalayan linguistics). This means that the data set cannot be used to study variation in verb stems or inflectional classes.
* The source\_form column in the forms file contains the data exactly as it appears in the source. This may include a lexical verb stem (listed in lexemes). In the orthographic and phonological representation, the lexical verb is replaced by a Σ. This placeholder also appears in the graphemes and sounds files for validation purposes.
* The lexemes file is kept relatively minimal and only lists each lexical stem in orthographic form and its meaning. This is because we do not always have access to forms with stems. For pronouns, "no\_stem" is indicated in the lexeme column in the forms file and verb forms without a stem are labeled "abstract\_entry". These are also listed in the lexemes file (for validation purposes).
* To facilitate comparison across PMST data sets, each file has an additional column with a language identifier. This means that files can be combined from different PMST sets without losing information.
* The morphs file contains a list of all morphs that appear in the data set (apart from the stem) in tokenized IPA. For each morph there is a list of all the forms and cells it appears in.
* The docs folder contains the data sheet with more extensive description of how the data was gathered.

## Additional information specific to Vaiphei

* Mapping between database paradigm labels and Vaiphei descriptive labels (Suantak 2013):
Database label = Language-specific descriptive label
fut = future
nfut = simple aspect
* Gaps: In the 1.pl.incl.fut.neg, 1.pl.incl.3.sg.fut.neg and 1.pl.incl.3.pl.fut.neg scenarios the expected forms for the pua\_neg paradigm are not attested. In their place hortative forms are found, which are hence tagged via the "hort" tag.
* Tone: Vaiphei has contrastive tone, but a thorough analysis is pending, which is why tone is not marked in the source forms.
* Tags:

  * lou\_neg and pua\_neg: For the negative future two different paradigms are attested, exhibiting negation via *lou* and *pua* respectively. These are tagged accordingly as "lou\_neg" and "pua\_neg". For negative non-future only one paradigm is attested (negation via *pua*). Since it does not contrast with another paradigm, no tagging was added here.
  * optional\_hun: In transitive scenarios with a speech-act participant object argument, a morph *hun* (alternatively *hung*) can optionally be added immediately before the verb stem. The semantics of *hun/hung* are unclear at this point. A tag "optional\_hun" has been added for the relevant scenarios.
* Optional marking: In certain discourse contexts, Vaiphei speakers tend to omit person marking altogether in colloquial speech, suggesting some kind of optionality of person marking. Since the extent of this is, however, currently unclear, this phenomenon was not included in the database.



## References

Auderset, Sandra, Hunter L. Brown, Jonathan Reich, Pascal Gerber, Muhammad Zakaria, and Linda Konnerth. 2026. “A Database of Person Marking in South-Central Trans-Himalayan”. *Journal of Open Humanities Data* 12 (1): 58. https://doi.org/10.5334/johd.505.



Suantak, Khawlsonkim. 2013. Vaiphei phonetics, phonology and morphology: a descriptive study. PhD thesis. Shillong: North-Eastern Hill University.

