# TranslatorHierarchy

The [NCATS Translator](https://ncats.nih.gov/research/research-activities/translator) project
needs a hierarchy of biomedical concepts to use for various purposes.
[Ubergraph](https://github.com/INCATools/ubergraph/) is designed to merge a bunch of ontologies
to produce a unified hierarchy and export the results into RDF.
The TranslatorHierarchy tool will provide the tooling necessary to:
    1.  Customize Ubergraph for Translator's needs by configuring the ontologies to be merged
        and relations to be used.
    2.  Transform the resulting RDF into a simplified representation that can be used by Translator
        components.

## Setup
