---
title: Data Management Plan
layout: page
permalink: /dmp.html
---

# Data Management Plan 

---

## Project Description

This collection features images of fictionalized women in American advertising mediums, spanning 1880 to 1945\. Displaying a variety of products, this collection may prove useful for those in pursuit of a historical understanding of advertising or women in the United States, whether that be for artistic, political, or marketing purposes. The advertisements shown were collected, owned, and digitized by GLAM institutions – galleries, libraries, archives, and museums. The entirety of the images are accessible to the public on these GLAM institution’s online platforms. 

This collection is hosted on GitHub, and accessible through the CollectionBuilder webhost. GitHub is a website that allows users to import, change, store, and share their code; this project is based on the CollectionBuilder Jekyll Template. The metadata is hosted in a CSV file which is stored in GitHub as well. The aspect of this project accessible through the website uses this software to read and create the website, and allows users to traverse its contents by features like subject, product, and location. 

## Delegation of Responsibilities

Throughout this project, both members worked extensively to source, record, and verify objects. Collaboration was key in balancing each members’ skillsets. Together, they altered code, added custom builds to the CollectionBuilder template, and polished the overarching narrative. 

* Kat Lai

Responsible for the vast majority of the ‘verification’ process, Kat did the necessary research into the copyright and rights statements for each item in the collection. She found many of the advertisements, and undertook the task of aesthetic-cohesion, ensuring the items were clear and well-maintained. 

* Ainsley Rayhawk 

Responsible for the majority of item-specific research, Ainsley did the lateral research to understand the origin, use, and medium of the items, as well as determining the locations of manufacturing or estimating unknown dates. Ainsley wrote the description and subject data.

## Anticipated Data

We sourced our data from a variety of galleries, libraries, university archives, and museums. The process initially involved recalling popular brand mascots, but we ran into active trademark restrictions. Sourcing difficulties were further exacerbated as few institutions hosted digitized advertising ephemera, so niche sources and those focusing on American history became particular useful. We continued our pursuit of relevant digital objects by traversing the official GLAMs, using varied metadata and keywords. 

| Item Description | File Type | Size | Items | License(s) | Sources |
| :--------------- | :-------- | :--- | :---- | :--------- | :------ |
| Downloaded images of digitized scans, or photographs, of visual advertising media from GLAM institutions | JPG/JPEG | 19.8 MB | 28 | In Copyright \- Educational Use Permitted, CC BY-NC 4.0,  Public Domain | Waring Library, Harvard Library, The New York Public Library, JSTOR, The State Historical Society of Missouri, National Museum of American History, Folger Shakespeare Library, Railroad Museum of Pennsylvania, Columbia University Libraries, Science History Institute Museum and Library, UC Berkeley Art Museum, Evelyn Lehman Culp Heritage Collection, Temple University Libraries, The Library Company of Philadelphia |

This collection is built upon the CollectionBuilder Jekyll Template, and hosted on GitHub. Additionally, the data shown (e.g. subjects, products, locations) are stored within a CSV file. All necessary tools to edit and access the collection exist within the GitHub repository, requiring GitHub access, Wi-Fi, and beginner coding knowledge for access.  
The items are stored in the institutions we sourced them from, where they are easily accessible to anyone. They are also downloaded in the authors’ computers, and in a folder in the GitHub repository. 

## Documentation and Metadata

The collection data are accessible to users via our GitHub repository and the ‘Metadata’ tab on the CollectionBuilder. Using this tab, the user can click either the Excel or CSV buttons located at the top of the page to download a file containing all of the metadata (including “objectid”, which links the image files to their id in the GitHub repository). To help clarify certain fields, our CollectionBuilder site will also host a data dictionary appendix under the “DMP” tab. 

## Storage and Backup

All digital objects and their respective metadata are currently stored on the GitHub repository, which uses Microsoft’s cloud storage (multiple physical backups). The repository is one of one — if it were deleted, the project would be lost. To prevent this issue, we’ve prepared backups through a Google Drive folder, in addition to each members’ local hard drives. All images are also stored in their GLAM's digital repositories.

## Data Sharing

The contents of this project are accessible for perusal within the CollectionBuilder website, where the metadata can be downloaded as a sheet. The template and upholding code is accessible through the GitHub repository, where all of the images are also uploaded. Every item in the collection, including those in copyright, are usable for non-commercial purposes, and can be downloaded from their GLAM source.

## Period of Data Retention

This website and its repository will be actively maintained for debugging purposes and minor stylistic changes. Beyond April 2026, care will transition to casual upkeep to ensure it’s viewable until June 2027  — meaning no further updates or edits. The items, including the metadata sheet and images, will still be stored in a Google Drive folder even if the site is no longer operational. 

## Licensing and Ethical Issues

Due to business trademarks, there’s a wide variety of intellectual property rights represented in our collection. Beyond the ones accessible in the public domain, we feature objects In Copyright, In Copyright \- Educational Use Permitted, No Copyright - United States, and Creative Commons Attribution\-Noncommercial 4.0. For certain copyright restrictions, we had to make some judgement calls on the basis of fair use:
* Originally sourced from GLAMs, all of our advertisements were available to download with zero restrictions
* Some advertising ephemera predate the 1930s, and/or were produced by abandoned trademarks (defunct companies)
* We are using these objects for educational, non-commercial purposes 

## Data Dictionary

| field | definition | example |
| :---- | :--------- | :------ |
| objectid | Unique identifier assigned to each object to make object referencing easier for CollectionBuilder. It consists of the subject focal point (“women”), “ad” (short for “advertising”), and a number (denotes no particular order)  | womenads15 |
| filename | Name of file and file type extension as-is stored in the folder.  Our naming convention includes the abbreviated company name, and the product being sold | antikamnia\_painmeds.jpeg |
| title | Name of the object, sourced as-is from the GLAM or a simplified version for clarity  | “Faith” |
| creator | The company or group whose product is advertised | Antikamnia Chemical Company |
| producer | Artist, Manufacturer, or Host (may be Unknown) | Graphic Co. Lith |
| product | The item being advertised or sold | Medicine |
| mediumadvert | The medium by which the advertisement is displayed | Trade card |
| date | The year known or best estimated of the advertisement's creation | 1898 |
| daterange | The years, added or subtracted from the 'date' field, that give a range of error | 5 |
| description | A few sentences describing the visual characteristics of the advertisement | "A card with a nun looking towards the moon, seemingly praying. The moon is a pain relief pill. On the bottom it says "Faith" in quotes, handwritten. On the top it says "First in Relief of Pain". The nun has rosy cheeks." |
| subject | Characteristics identified in the item, especially which overlap with other items, separated by semicolons (Number of women, themes, visual traits, product type, etc) | "solo woman;nun;faith;religion;pail treatment;treatment;health;pharmaceutical;drug;card;lithograph;" |
| location | The state in the United States in which the manufacturers sponsor (often primary factory for the creator) resided | Missouri |
| city | The city in which the manufacturers sponsor (often primary factory for the creator) resided | St. Louis |
| longitude | The longitude of the City, State of the item | -74.006015 |
| latitude | The latitude of the City, State of the item | 40.712728 |
| type | The format for the uploaded content (all are images) | StillImage |
| format | The download format for the image (all are jpg or jpeg) | image/jpeg |
| language  | The language used in the item | US-Eng |
| righttstatement | A hyperlink to the rights that the item are under | https://rightsstatements.org/page/InC/1.0/?language=en |
| rights | The human readable form of the rights statement | Public Domain |
| citation | The APA format citation for each item | "Digital Collections, Science History Institute Museum & Library. (ca. 1898). Trade Card for the Antikamnia Chemical Company's pain relief product with nun. Retrieved from https://digital.sciencehistory.org/works/q811kk83q" |

