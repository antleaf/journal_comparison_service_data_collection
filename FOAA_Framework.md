# FOAA Spreadsheet

Paul Walk, 2022-03-28

## Column Definitions

### ISSN Print

**Requirement:** Only one of:

* ISSN Print

* ISSN Electronic

* ISSN Linking

* Journal DOI

**Validation:** Valid ISSN

**JATS mapping:** /journal-meta/issn[@publication-format="print"]

***

### ISSN Electronic

**Requirement:** Only one of:

* ISSN Print

* ISSN Electronic

* ISSN Linking

* Journal DOI

**Validation:** Valid ISSN

**JATS mapping:** /journal-meta/issn[@publication-format="electronic"]

***

### ISSN Linking

**Requirement:** Only one of:

* ISSN Print

* ISSN Electronic

* ISSN Linking

* Journal DOI

**Validation:** Valid ISSN

**JATS mapping:** /journal-meta/issn-l

***

### Journal DOI

**Requirement:** Only one of:

* ISSN Print

* ISSN Electronic

* ISSN Linking

* Journal DOI

**Validation:** Valid DOI

**JATS mapping:** /journal-meta/journal-id[@journal-id-type="doi"]

***

### Journal Title

**Requirement:** Required

***

### Cluster

**Requirement:** Optional

**Guidance:** A simple text column to allow a label to be used to indicate that certain titles belong together as a "logical" cluster.

***

### Discipline

**Requirement:** Required

**Validation:** Numeric value from https://read.oecd-ilibrary.org/science-and-technology/frascati-manual-2015_9789264239012-en#page60 or one of the following:

* all disciplines
* all STEM disciplines
* all HSS disciplines

***

### Owner ROR ID

**Requirement:** Optional

**Validation:** Valid ROR ID

**Guidance:** Where the publication is owned by an organisation other than the publisher (e.g. a Learned Society) then the owner's ROR ID should be supplied - see https://ror.org/facts/ for further information

***

### Publisher ROR ID

**Requirement:** Optional

**Validation:** Valid ROR ID

**Guidance:** ROR ID of the organisation which is responsible for publishing the title. See https://ror.org/facts/ for further information

***

### In-house or Outsourced Journal Operations?
**Requirement:** Required

**Validation:** One of:

* In-house
* Out-sourced

**Guidance:** 

***
### Rejection Rate

**Requirement:** Required

**Validation:** Percentage as a number with two decimal places. A period (dot) should be used as the decimal separator.

**Guidance:** Desk rejection rate for reporting period (year)

***

### Discounts and Waivers Policy

**Requirement:** Required

**Validation:** Valid URL including protocol (http or https) or "none"

**Guidance:** A link to the publisher's publicly available policy for APC waivers and discounts, or an indication there is none.

***

### Agreements

**Requirement:** Required

**Validation:** Valid URL including protocol (http or https) or "none"

***

### Journal Operations

**Requirement:** Required

**Validation:** Percentage as a number with two decimal places. A period (dot) should be used as the decimal separator. Must be less than or equal to 100.00

**Guidance:**  This might include aspects such as:
* Journal support and submission system
* Platform development and maintenance
* Helpdesk and other support staff

***

### Publication

**Requirement:** Required

**Validation:** Percentage as a number with two decimal places. A period (dot) should be used as the decimal separator. Must be less than or equal to 100.00

**Guidance:** This might include aspects such as:

* Triaging
* Organisation peer review
* Other editorial assistance, e.g:
  * Indexing
  * Archiving
  * Typsetting
  * Copy-editing
  * Language editing
  * Proofreading


***

### Fees

**Requirement:** Required

**Validation:** Percentage as a number with two decimal places. A period (dot) should be used as the decimal separator. Must be less than or equal to 100.00

**Guidance:** This might include aspects such as:

 * Scientific editors fees
 * Scholarly societies fees

***

### Communication

**Requirement:** Required

**Validation:** Percentage as a number with two decimal places. A period (dot) should be used as the decimal separator. Must be less than or equal to 100.00

**Guidance:** This might include aspects such as:
* Dissemination
* PR & Marketing
* Community support
* Advocacy

***

### General

**Requirement:** Optional

**Validation:** Percentage as a number with two decimal places. A period (dot) should be used as the decimal separator. Must be less than or equal to 100.00

**Guidance:** This might include aspects such as:
* Management & administration
* Other business costs
* Taxes

However, this category is optional, since these general costs may have already been distributed between the other categories.

***

### Surplus / Other Revenue

**Requirement:** Optional

**Validation:** Percentage as a number with two decimal places. A period (dot) should be used as the decimal separator. Must be less than or equal to 100.00

**Guidance:** This category is optional, since the surplus may have already been distributed between the other categories.
***

### Discounts & Waivers

**Requirement:** Required

**Validation:** Percentage as a number with two decimal places. A period (dot) should be used as the decimal separator. Must be less than or equal to 100.00

**Guidance:** If there are no Discounts & Waivers, please enter 0.00

***

### Average APC

**Requirement:** Required

**Validation:** Number with two decimal places. A period (dot) should be used as the decimal separator. No thousand separator should be used.

**Guidance:** This is the average APC for this journal. All percentages of the other costed columns must add up to 100%.

***

### Notes

**Requirement:** Optional

**Validation:** None - although long text may be truncated for display purposes in the web-application

**Guidance: **For brief notes about the title - for example to indicate that the title was recently acquired and so may not have a full year's data.

***

