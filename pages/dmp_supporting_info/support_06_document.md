---
layout: page
<!--type: cheat_sheet-->
title: Data documentation during the project
search_exclude: false
contributors: [Svein Høier]
page_id: support_06_document
description: Supporting DMP Information, data collection, data creation, data generation, data production
sidebar: dmp_supporting_info
dsw:
- name: Responsibilities and resources
  uuid: knowledge-models/elixir.no:dsw-km-bott-localization:latest/preview?questionUuid=b1df3c74-0b1f-4574-81c4-4cc2d780c1af
cessda:
- name: Documentation and metadata
  url: https://dmeg.cessda.eu/Data-Management-Expert-Guide/2.-Organise-Document/Documentation-and-metadata
rdmkit:
- name: Documentation and metadata
  url: https://rdmkit.elixir-europe.org/metadata_management
other:
- name: "OpenAIRE: How do I license my research?"
  url: https://www.openaire.eu/how-do-i-license-my-research-data
- name: "Figshare: On choosing licenses"
  url: https://help.figshare.com/article/what-is-the-most-appropriate-licence-for-my-research
- name: "ELIXIR-BE RDM: Data licences"
  url: https://rdm.elixir-belgium.org/data_licences 
turing:
- name: Documentation and Metadata
  url: https://book.the-turing-way.org/reproducible-research/rdm/rdm-metadata
---

{% include callout.html type="tip" content="
**Why is this topic important**\\
>> Understanding, analyzing and reusing data depends on how said data has been documented, structured, named and in other ways described \\
>> The inclusion of metadata, providing data about the data used in a project, secures that data can be properly utilized, both within and beyond your own project \\
>> Interpretation of project results requires an understanding of the data provenance/data lineage, i.e. where the data originates from and how it has been processed \\
>> Data documentation should start as early as possible, and in the form of accompanied structured metadata, ensures that data is accessible \\
" %}

## About this chapter

This chapter includes information about how metadata and other accompanying information will be handled in the active phase of the project. 

## Question-specific guidance

### How will you link data and metadata?

Often there will be multiple ways in which data and metadata can be linked within a project. Basic descriptive techniques will be relevant to many projects: these include structured and consistent naming of files and folders, using a readme-file to provide information, using embedded metadata in files, or using a separate metadata-file (a sidecar file for each file in the dataset). More advanced techniques that may be relevant include using a database system for linking metadata and data, or establishing a data/variable dictionary for the data in the project. 

_Supplementary info: Almost all computer systems will provide some system metadata embedded in files, and provide info on creation date and who has editor or read-only access to the file, for example. Most systems will also provide users with possiblilities of adding user metadata that can be embedded in files, such as descriptive tags._

### Do suitable metadata standards exist for your data?

When planning and embarking on your project, you should familiarize yourself with, and choose, a suitable metadata standard, if one exists. Many research fields have established metadata standards that are widely used within that specific scientific field. Furthermore, most repositories for research data will implement specific standards (often using Dublin Core as a starting point). As such, planned use of an archive will often lead to planned use of specific metadata standards. When in doubt about relevant metadata standards within your field, the Dublin Core standard will often be a good choice.    

### Will you use existing vocabularies/ontologies/terminologies to describe your data?

If you want to facilitate interoperability of your data with data you get from elsewhere, and facilitate re-use of your own data later, it is handy if you use standard ways to encode certain data. Such standard encodings are sometimes called terminologies or ontologies.

_Supplementary info: Please concider what vocabularies, ontologies or terminology that has relevance within your field of research, and apply these to highten precition when describing research data. When in doubt of relevance, please look for usage by others within your field, like in published published journal articles og connected to published datasets._  

### How are the rights of the collected data distributed?

Discuss making agreements regarding usage rights and potential intellectual property rights prior to data collection.
Not all data are covered by The Copyright Act, and some data may be in the form of databases, and may qualify for protection. 
If intellectual property rights are defined through a contract/agreement, make sure to include it in the answer.

_Supplementary info: Defining rights and providing licenses to collected data will often reduce the potential for later conflicts around internal and external use (and reuse) of research data within and after the project period._

### Are there any use restrictions for these data?

Are there any limitations on the data use e.g. only for research on certain types of diseases, sharing only within certain geographical boundaries, etc.?
Describing data use in a formalised way by using the data use ontology (DUO) greatly improves the data reusability. 

_Supplementary info:_


### Will a license be assigned to your data as early as possible? 

It is not always clear to everyone in the project (and outside) what can and can not be done with a data set. It is helpful to associate each data set with a license as early as possible in the project. A data license should ideally be as free as possible: any restriction like 'only for non-commercial use' or 'attribution required' may reduce the reusability and thereby the number of citations. If possible, use a computer-readable and computer actionable license.

_Supplementary info:_

