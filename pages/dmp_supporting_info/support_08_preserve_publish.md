---
layout: page
<!--type: cheat_sheet-->
title: Archiving and publishing data
search_exclude: false
contributors: [Leif Longva, Jenny Ostrop]
page_id: support_08_preserve_publish
description: Supporting DMP Information, preservation strategy, preserve data, data preservation, publish data, data publication, repository, open access, closed access, data sharing
sidebar: dmp_supporting_info
dsw:
- name: Archiving and publishing data
  uuid: knowledge-models/elixir.no:dsw-km-bott-localization:latest/preview?questionUuid=a549d10b-aa46-4c0c-863f-30219ac5ecce
cessda:
- name: Archive & Publish
  url: https://dmeg.cessda.eu/Data-Management-Expert-Guide/6.-Archive-Publish
rdmkit:
- name: Data publication
  url: https://rdmkit.elixir-europe.org/data_publication
- name: Identifiers
  url: https://rdmkit.elixir-europe.org/identifiers
turing:
- name: Sharing and Archiving Data
  url: https://book.the-turing-way.org/reproducible-research/rdm/rdm-sharing
other:
- name: "GOFair: FAIR principles"
  url: https://www.go-fair.org/fair-principles/
---

{% include callout.html type="tip" content="
**Why is this topic important**\\
>> Your data is valuable – they should be available for reuse.\\
>> Archiving data is also a way to ensure availability of data for yourself at a later time point, e.g. after switching affiliations.\\
>> Rich metadata will make your data findable through search engines. Good documentation and structured metadata will enable others to understand the information held in your data and enable data reuse.\\
>> Research funders and academic publishers commonly require data underlying a study to be available ('as open as possible').\\
>> Increasingly, archiving FAIR data is viewed as equally important as publishing other research output, in the assessment of research.\\
" %}

## About this chapter
Research data should be archived and preserved, for the benefit of future research and to ensure research transparency. Data should be archived as open as possible and as closed as necessary, as the guiding principle of research funders and others states. This chapter will assist you in walking through the planning steps of making your data available in line with the FAIR principles, including selecting an archive to publish your data (or, if needed, archiving with access restrictions) and providing appropriate metadata.

The chapter includes both questions that should be considered at the initial stage of the DMP, and questions to be answered towards the end of the research project to plan the fate of data in the project, whether they will be deposited in a research data archive, preserved in other ways, or in certain cases will be discarded.

### Trustworthy research data archives
An important issue is to identify the best suited archive to be used for your data. There are different types of archives you may use for your data. Some are designed to suit data from specific subject areas. These may use metadata standards and metadata schema that are best suited to capture important information on data from such a specific subject area. Then there are institutional data achives. These archives are designed to capture data from any subject area the institution handles. Have a look whether your institution offers such an archiving service. A benefit for you in chosing an institutional archive would be that your institution has good user support to ensure the quality of your archived data. Furthermore, there are 'catch all' archives, meaning archives where both scholarly publications as well as data may be archived. If you do not have access to use a data archive, you may consider to use a catch all archive like [Zenodo](https://zenodo.org/).

You may browse or search for suitable archives in the [re3data registry](https://www.re3data.org/), which is a registry of data archives. The [FAIRsharing service](https://fairsharing.org/) is also a useful a searchable resource that holds information on data archives, as well as standards and data policies. You are advised to choose a so-called trustworthy archive for your data. Look for the [Core Trust Seal](https://www.coretrustseal.org/) which certifies that the archive in question operates in accordance with the Core trust Seal quality criteria, both in terms of its financial foundation and its quality assuring data curation routines.
<!-- *brief introduction to discipline-specific, institutional and generic research data archives. Explain re3data and FAIRSharing.* -->

### Restricted access to research data
Some data should not be made openly available, according to law regulations (including the General Data Protection Regulation (GDPR)) and/or ethical considerations. These may be data with person identifying information, or data that are sensitive for other reasons (national security or business information). It is still important to archive such data, to ensure their long term preserving. These data thus need to be archived with restricted access. In Norway, the [Sikt archive](https://sikt.no/en/archiving-research-data) may be suitable for this. 

[FEGA (Federated European Genome-phenome Archive)](https://ega.elixir.no/) is another archive that may be suitable. FEGA is designed to help researchers securely store, access, and share sensitive human data across multiple countries, while adhering to local privacy regulations such as the GDPR.

[CLARINO](https://repo.clarino.uib.no/xmlui/) may also be mentioned here. CLARINO is Norway's part of the European CLARIN infrastructure network, which stands for Common Language Resources and Technology Infrastructure. CLARINO includes a platform where researchers can store, share, and access language data in standardized formats. This also includes access with restricted access, since language research easily includes person identifying data.

[Data Use Ontology](https://www.ga4gh.org/product/data-use-ontology-duo/) is a service that may be useful for data that can not be openly available. This service is especially developed for sensitive human data.
<!-- *mention Data Use Ontology, Data Use Conditions* -->

### Persistent identifiers
When deciding where to archive your data, make suere you chose an archive where your dataset is assigned a persistent identifier (PID). Two commonly used PIDs are Digital Object Identifier (DOI) and handle. With a PID assigned, you are guaranteed that your dataset may be referred to with correct identifier for findability. The (not uncommon) problem of urls that stop working for some reason is then avoided. Archives assigning DOIs is also a sign of quality, since there is minimum requirements to the metadata schema used in order to achieve a DOI.
<!-- *what does the term mean and why are they important* -->

## Question-specific guidance

### Can all datasets become completely open over time?
Research data should be made available at an early stage and latest at publication. However, there can be reasons to delay data publication with an embargo period or (some of) your data is of a nature that should not be made openly available. The chapter 'Legal and ethical aspects' may help to identify criteria for deciding whether part of your data need to be restricted from public access. Consider whether such parts may be anonymized or aggregated so that such a version of your data can be openly available. Data that cannot be openly available, may still be made available with restricted access. In this case it is particularly important to be aware of required steps from project start.

If certain datasets can not be made available or only be made available under restricted access conditions, please explain why, clearly separating legal and contractual reasons from intentional restrictions.


### Identify archive(s) for publishing datasets
*add figure for flow chart*

This question, and its sub-questions, will assist you in finding archive(s)/repository(-ies) suitable to deposit your data.

Where do you plan to archive you research data? Remember that this can also include project results that you are not immediately thinking of as 'data'.
As archive choice often decides over metadata standards to be followed, it is advisable to investigate this question early in the project. [Re3data](https://www.re3data.org/) and [FAIRsharing](https://fairsharing.org/) are registries that may help identifying suitable repositories.

Timely archiving of datasets in [trustworthy repositories](/pages/support_08_preserve_publish#trustworthy-research-data-archives) is recommended. Depending on the study and the type of data, it may be appropriate to archive everything in one repository or archiving different parts in different repositories that will link to the related datasets. 

Evaluate which archive(s) will be most relevant for your datasets, using the following the decision tree:

    1) Does your dataset contain personal data or sensitive information?
    [If yes, investigate discipline-specific or generic archives with restricted access]

    2) Do journals or funders require that specific archives will be used or is there disciplinary conventions?
    [If yes, make yourself familiar with the recommendations and use discipline-specific archives]

    3) Can you use an institutional archive?
    [If yes, use your institutional archive]

    If none of the above applies, use a generic research data archive.

In some cases it is important to contact the research data archive beforehand. 

<!-- *elaborate*
*make sure trustworthy repository is explained in terms and linked to* -->

### List data that you have deleted or will delete
Determining which data are of value and should be preserved or whether data need to or can be deleted, is a decision that should be taken actively. If data(sets) are deleted, they can be listed in this question, including a brief description of the reasons for deletion.

There may be legal (e.g. defined by the Health Research Act) or contractual obligations to delete data.

Generally, institutions and research funders set requirements to retain data for a given period. For example, the Research Council of Norway "has stipulated as a requirement that research data must be stored in a safe and secure manner for a minimum of 10 years" [(Policy for Open Science, 2020)](https://www.forskningsradet.no/siteassets/forskningspolitisk-radgivning/apen-forskning/nfr-policy-open-science-eng.pdf). On the other hand, the Research Council of Norway states that research projects "should explicitly address how research data that are not considered to have long-term value should be managed, or if relevant destroyed, after a certain period of time."[(Policy for for Open Access to Research
Data, 2017)](https://www.forskningsradet.no/siteassets/forskningspolitisk-radgivning/apen-forskning/nfr-policy-open-science-eng.pdf)

Yet, it can be worthwhile to consider which data in a project are not of value (e.g. data from failed experiments), only have intermediate value (e.g. during data analysis) and which data should be preserved long-term, particularly if storage of large amounts of data is associated with significant costs.


### List datasets that you have archived or will archive
Archiving of datasets includes the deposition of datasets in a research data archive, openly or with restricted access, and equipped with a persistent identifier (PID) as well as data that should be preserved but not published. Research data should be made available at an early stage, following the principles as "as open as possible, as closed as necessary". According to the guidelines by Research Council of Norway should data underlying scientific articles be made accessible latest at publication. Other research data should be made accessible within a reasonable amount of time, and never later than three years after the project has ended [(Policy for open access to research data, 2017)](https://www.forskningsradet.no/contentassets/e4cd6d2c23cf49d4989bb10c5eea087a/the-research-council-of-norways-policy-for-open-access-to-research-data.pdf).

Several sub-questions allow to refer to information in other DMP chapters or external databases. Alternatively, it is always possible to enter a free-text answer.

#### Which metadata and documentation accompanies the dataset?
Explain to the best of your knoledge what metadata (what metadata standard) is used for your dataset.
Metadata is structured information about a dataset (or a document). _How to_ structure the information is done in various ways. Different metadata schemas are designed to capture the information, and such a schema is called a metadata standard. A metadata standard may be designed to suit a subject domain or a specific research area. There are, naturally, different information needs to describe a dataset with biological data, compared to a dataset which revolves on social sciences.
A metadata schema may capture information by the use of controlled vocabularies. That way, information will be standardised and not be disrupted by different persons using different words or typology for same issues. Such a standardisation will preferably make use of ontologies from a subject domain, and metadata standards will thus often be subject specific. The use of controlled vocabularies and ontologies will increase the quality and findability of the archived data.
Note that you here may reuse the answer from chapter VI: 'Data documentation during the project'.
<!-- *write something about standards and use of ontologies* -->

#### Where has the data been archived?
*write something about preservation strategy if you are NOT using a trustworthy repository*

#### Under what license will the dataset be made available?
*write something about license selection*

### FAIR data checklist
No matter whether your data may be published openly or not, it is always a question of making your data FAIR - or rather as FAIR as possible. FAIR is an acronym for Findable, Accessible, Interoperable, Reusable and the [FAIR principles (2016)](/pages/support_08_preserve_publish#further-resources] describe a set of criteria to be met.\
The checklist can assist you in remembering the relevant elements:
* Archived datasets have persistent identifiers
* Archived datasets are indexed and findable in search engines
* Rich metadata is available for the archived datasets
* Metadata remains available even if data should be deleted
* Conditions for accessing the archived datasets are specified
* The file formats used in archived datasets support interoperability
* Controlled vocabularies/ontologies are used to describe data and datasets
* Datasets link to related information where relevant
* Datasets are assigned a license that define conditions for reuse
* The archive will guarantee future availability and reuse of the datasets

There are also online tools available for this purpose:
* [FAIRAware by DANS](https://fairaware.dans.knaw.nl/)


### If applicable: List research software/computational models/simulations you will be publishing
Research software as project result is related to research data, yet more dynamic. Research software can be anything from a few lines of code to a professionally developed software package.
The FAIR for Research Software (FAIR4RS) principles have been adapted from the FAIR principles to fit the characteristics of software/code ([Barker et al. 2022, doi: 10.1038/s41597-022-01710-x](https://doi.org/10.1038/s41597-022-01710-x), [Lamprecht et al. 2020, doi: 10.3233/DS-190026](https://doi.org/10.3233/DS-190026)).

Parts of these considerations are taken from the [Elixir Software Management Plan](https://smw.dsw.elixir-europe.org/wizard/knowledge-models/smw:smp:0.0.18) [CC-BY 4.0](https://creativecommons.org/licenses/by/4.0/)

Further reading:
* [fair-software.nl: Five recommendations for FAIR software](https://fair-software.nl/home/)
* [Code Refinery: Social coding and open software - What can you do to get credit for your code and to allow reuse](https://coderefinery.github.io/social-coding/)
* [Software Carpentry: Version control with git - Open Science](https://swcarpentry.github.io/git-novice/10-open.html)
* [Turing way: Open source software](https://book.the-turing-way.org/reproducible-research/open/open-source)
* [Turing way: Licensing](https://book.the-turing-way.org/reproducible-research/licensing.html)
* [FAIRCookbook: Software Licensing](https://w3id.org/faircookbook/FCB033)
