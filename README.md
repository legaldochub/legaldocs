The goal of this repository is to allow our community to create an open source set of configruable legal documents aimed at startups.

Think LegalZoom, but free...and open source...and cooler.

All documents will be written in markdown, allowing to easily integrate into any templating/form engine to allow simple functionality.

You may submit a pull request if you would like to contribute.

## Library of Documents
We are hoping to upload the following documents over the next few weeks
* Non Disclosure Agreemenet 
* Non Disclosure + Non Complete Agreement
* Advisor Agreement
* Convertible Debt Note
* S Corporation Bylaws
* LLC Corporation Operating Agreement
* Senior Debt Note
* Investor Agreement
* Contractor Contract
* Website Development Contract

## Convensions: 
Any editable field should be represented as `{{fieldName}}` so that it can be filled with a templating engine. Inside the braces the fieldName must be in camelCase, have no spaces, and be a valid JS variable name,

For example:
```
The plaintif, {{plaintifName}}, is suing the defendant {{defendantName}} for {{suingAmount}}
```

Any signature fields or signature date fields must be represented by a continual set of underscores

```

Plaintif

_______________________________
Signature

{{plaintifName}}

________________________________
Date
```

## Why Open Source Legal Documents?
* More eyes = better documents
* Reuse language (why write the same things twice)
* Built by engineers: integrate programatically with


## Maintainers
* Anatoliy Zaslavskiy (nycitt): Technical maintainer
* Andrea Casillas: Legal maintainer 
* Dilli Bhatta: Legal maintainer 
