---
title: GDC

language_tabs:
  - php
  - javascript
  - whatever

toc_footers:
  - <a href='mailto:mailto:support%40gdc.nci.nih.gov'>Contact GDC</a>
  - <a href='https://twitter.com/NCIGDC_Updates'>GDC Twitter</a>

includes:
  - errors

search: true
---

# Welcome to GDC

NCI’s Genomic Data Commons (GDC) provides the cancer research community with a unified data repository that enables data sharing across cancer genomic studies in support of precision medicine. GDC supports several cancer genome programs at the NCI Center for Cancer Genomics (CCG), including The Cancer Genome Atlas (TCGA), Therapeutically Applicable Research to Generate Effective Treatments (TARGET), and the Cancer Genome Characterization Initiative (CGCI).

The mission of GDC is to provide the cancer research community with a unified data repository as essential infrastructure for integrating basic biological knowledge with medical histories and health outcomes of individual patients.

The National Cancer Institute (NCI) Center for Cancer Genomics (CCG) was established to lead the NCI effort in generating critical datasets for cataloging the genomic alteration in human tumors.

# Access Data

> To authorize, use this code:

```ruby
require 'kittn'

api = Kittn::APIClient.authorize!('meowmeowmeow')
```

```python
import kittn

api = kittn.authorize('meowmeowmeow')
```

```shell
# With shell, you can just pass the correct header with each request
curl "api_endpoint_here"
  -H "Authorization: meowmeowmeow"
```

> Make sure to visit GDC

The GDC Data Portal is a groundbreaking tool that enables a better understanding of cancer biology by allowing researchers to:

* Search and query genomic data
* Download data directly from the web browser or download large volumes of data using a high performance data transfer tool
* Analyze cancer data sets including clinical information, genomic characterization data, and high level sequence analysis of the tumor genomes

`Hi, there`

<aside class="notice">
This is a notice <code>GDC</code>.
</aside>

# Submit Data

## GDC Data Submission Portal

```ruby
require 'kittn'

api = Kittn::APIClient.authorize!('meowmeowmeow')
api.kittens.get
```

```python
import kittn

api = kittn.authorize('meowmeowmeow')
api.kittens.get()
```

```shell
curl "http://example.com/api/kittens"
  -H "Authorization: meowmeowmeow"
```

> The above command returns JSON structured like this:

```json
[
  {
    "id": 1,
    "name": "Fluffums",
    "breed": "calico",
    "fluffiness": 6,
    "cuteness": 7
  },
  {
    "id": 2,
    "name": "Isis",
    "breed": "unknown",
    "fluffiness": 5,
    "cuteness": 10
  }
]
```

> The GDC Data Submission Portal offers a user-friendly web form for data submission.

Register dbGaP Project in GDC | Create Data Using Standard GDC Data Types and File Format Specifications | Validate and Submit Data to the GDC Data Submission Portal | Validate and Submit Files to the GDC Data Transfer Tool
---------- | ---------- | ---------- | ----------
The GDC Data Submission Portal allows users to submit data associated with projects registered in dbGaP. Information on registering a project in dbGaP is available at Obtaining Access to Submit Data. | GDC defines standard Data Types and File Formats for data submission. Users can submit clinical, biospecimen, and molecular data in the standard data format in support of data validation and harmonization. | The GDC Data Submission Portal allows users to validate their data prior to submission using data validation tools. Users can load data into their project and select to validate each data file. The data validation tool provides users with the validation status. Only data that passes validation is submitted to the GDC. | The GDC Data Transfer Tool provides a high performance data submission client for uploading large molecular data files. User's can validate the files using data validation tools prior to submission.


<aside class="success">
Detailed instructions for GDC Data Submission Portal key features are available in the GDC Data Submission Portal User's Guide. Information on GDC Data Submission Portal Releases is available in the GDC Data Submission Portal Release Notes.
</aside>

![One pic](https://gdc.gwu.local.oicr.on.ca/files/public/image/gdc-submission-webform-placeholder.jpg)

## GDC Data Transfer Tool

```ruby
require 'kittn'

api = Kittn::APIClient.authorize!('meowmeowmeow')
api.kittens.get(2)
```

```python
import kittn

api = kittn.authorize('meowmeowmeow')
api.kittens.get(2)
```

```shell
curl "http://example.com/api/kittens/2"
  -H "Authorization: meowmeowmeow"
```

> The above command returns JSON structured like this:

```json
{
  "id": 2,
  "name": "Isis",
  "breed": "unknown",
  "fluffiness": 5,
  "cuteness": 10
}
```

GDC provides a standard client-based mechanism in support of high performance data downloads and submission.

The raw sequence files, typically stored as BAM or FASTQ, make up the bulk of data. The size for a single file can vary greatly depending on the specific analysis; However, some of the whole genome BAM files in The Cancer Genome Atlas (TCGA) reach sizes of 200-300 GB. In such cases, a high performance data download and submission client is essential.

Below are basic instructions and links for downloading the GDC Data Transfer Tool. For additional instructions, please visit the [GDC Data Transfer Tool User's Guide](https://gdc.gwu.local.oicr.on.ca/access-data/gdc-data-transfer-tool-users-guide).

<aside class="warning"> Error </aside>

> Downloading the GDC Data Transfer Tool

### System Recommendations

The system recommendations for using the GDC Data Transfer Tool are as follows:

* OS: Linux (Ubuntu 14.x), Mac OS (Mavericks, Yosemite), Windows (Windows7)
* CPU: At least eight 64-bit cores, Intel or AMD
* RAM: At least 8 GiB
* Storage: Enterprise-class storage system capable of ≥1 Gb/s (Gigabit per second) write throughput and sufficient free space for BAM files - which are generally 10-20 GBs in size (or larger) - is recommended for good performance but not required

### Binary Distributions

Links to the binary distributions for supported platforms are provided below.

* OS X x64
* Ubuntu x64
* Windows x64

### Release Notes

Release Notes are available on the [GDC Data Transfer Tool Release Notes](https://gdc.gwu.local.oicr.on.ca/node/8300/) page.

### Support

Please visit the [GDC Help Desk](https://gdc.gwu.local.oicr.on.ca/support)

