# Information Power Framework Spreadsheet

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

**Requirement:** Required

**Validation:** Valid ROR ID

**Guidance:** ROR ID of the organisation which is responsible for publishing the title. See https://ror.org/facts/ for further information

***
### APC List Price Range Lower
**Requirement:** Required

**Validation:** Number with two decimal places. A period (dot) should be used as the decimal separator. No thousand separator should be used.

**Guidance: **The lower price of any APC list price range for primary research articles. If there is just a single APC list price enter the same number in both *APC List Price Range Lower* and *APC List Price Range Higher*

***
### APC List Price Range Higher
**Requirement:** Required

**Validation:** Number with two decimal places. A period (dot) should be used as the decimal separator. No thousand separator should be used.

**Guidance: **The higher price of any APC list price range for primary research articles. If there is just a single APC list price enter the same number in both *APC List Price Range Lower* and *APC List Price Range Higher*

***
### APC List Price Currency
**Requirement:** Required

**Validation:** Valid ISO 4217:2015 alphabetic currency code

**Guidance:** Active currency codes can be found at https://en.wikipedia.org/wiki/ISO_4217#Active_codes

***
### APC Waiver Discount Policy
**Requirement:** Required

**Validation:** Valid URL including protocol (http or https) or "none"

**Guidance:** A link to the publisher's publicly available policy for APC waivers and discounts, or an indication there is none.

***
### Subscription List Price Range Lower
**Requirement:** Required

**Validation:** Number with two decimal places. A period (dot) should be used as the decimal separator. No thousand separator should be used.

**Guidance:** The lower price of any subscription list price range for primary research articles. If there is just a single subscription list price enter the same number in both *Subscription List Price Range Lower* and *Subscription List Price Range Higher*

***
### Subscription List Price Range Higher
**Requirement:** Required

**Validation:** Number with two decimal places. A period (dot) should be used as the decimal separator. No thousand separator should be used.

**Guidance:** The higher price of any subscription list price range for primary research articles. If there is just a single subscription list price enter the same number in both *Subscription List Price Range Lower* and *Subscription List Price Range Higher*

***
### Subscription List Price For Member of The Association of American Universities

**Requirement:** Required

**Validation:** Number with two decimal places. A period (dot) should be used as the decimal separator. No thousand separator should be used.

**Guidance:** To facilitate comparison of prices between publishers.

***

### Subscription List Price Currency

**Requirement:** Required

**Validation:** Valid ISO 4217:2015 alphabetic currency code

**Guidance:** Active currency codes can be found at https://en.wikipedia.org/wiki/ISO_4217#Active_codes

***
### Subscription Discount Policy
**Requirement:** Required

**Validation:** Valid URL including protocol (http or https) or "none"

**Guidance:** A link to the publisher's publicly available policy for discounting subscription prices, or an indication there is none.

***
### Price Transparency Context
**Requirement:** Optional

**Validation:** Valid URL including protocol (http or https)

**Guidance:** An opportunity for publishers to provide additional context for customers wish to know how they have compiled data for the framework, or providing additional insight into how to interpret the figures

***
### Research Articles Published
**Requirement:** Required

**Validation:** Integer

**Guidance:** Number of research articles published in reporting period. Exclude author corrections, corrigendum, errata, editorials, and reviews.

***
### Acceptance Rate
**Requirement:** Required

**Validation:** Percentage as a number with two decimal places. A period (dot) should be used as the decimal separator.

**Guidance:** Acceptance rate for reporting period.

***
### Desk Rejection Rate
**Requirement:** Required

**Validation:** Percentage as a number with two decimal places. A period (dot) should be used as the decimal separator.

**Guidance:** Desk rejection rate for reporting period.

***
### Issue Publication Frequency
**Requirement:** Required

**Validation:** One of:

* Annual
* Bimonthly
* Semiweekly
* Daily
* Biweekly
* Semiannual
* Biennial
* Triennial
* Three times a week
* Three times a month
* Monthly
* Quarterly
* Semimonthly
* Three times a year
* Weekly
* Continuously updated
* Other

**Guidance:** Choose one from:

* Annual (=one per year)
* Bimonthly (=one every two months)
* Semiweekly (=two per week)
* Daily (=one per day)
* Biweekly (=one ever two weeks)
* Semiannual (=two per year)
* Biennial (=one every two years)
* Triennial (=one every three years)
* Three times a week
* Three times a month
* Monthly
* Quarterly
* Semimonthly (=two per month)
* Three times a year
* Weekly
* Continuously updated
* Other

***
### Median Number Reviews
**Requirement:** Required

**Validation:** Integer

**Guidance:** Median number of reviews for research articles in reporting period (year).

***
### Median Time Submission To First Decision
**Requirement:** Required

**Validation:** Number with two decimal places. A period (dot) should be used as the decimal separator. No thousand separator should be used.

**Guidance:** Median time in days from submission to first decision in reporting period (year). Decision means whether to reject or send for peer review. Include papers decided on the basis of assessment by in-house prepublication teams, editorial boards, editorial boards and external referees, or subeditors.

***
### Median Time Peer Review
**Requirement:** Required

**Validation:** Number with two decimal places. A period (dot) should be used as the decimal separator. No thousand separator should be used.

**Guidance:** Median time in days that the submitted article is under review using the NISO definition of article versions (https://www.niso.org/publications/niso-rp-8-2008-jav) in reporting period (year).

***
### Median Time Acceptance To Publication
**Requirement:** Required

**Validation:** Number with two decimal places. A period (dot) should be used as the decimal separator. No thousand separator should be used.

**Guidance:** Median time in days from the time a manuscript is accepted to the time the version of record is available using the NISO definition of article versions (https://www.niso.org/publications/niso-rp-8-2008-jav) in reporting period (year).

***
### Counter 5 Unique Item Requests
**Requirement:** Required

**Validation: **Integer

**Guidance:** The data should be aggregated across customers to provide global usage figures.

***
### Counter 5 Total Item Requests
**Requirement:** Required

**Validation: **Integer

**Guidance:** The data should be aggregated across customers to provide global usage figures.

***
### Price Breakdown: Journal Community Development
**Requirement:** Required

**Validation:** Percentage as a number with two decimal places. A period (dot) should be used as the decimal separator. Must be less than or equal to 100.00

The values of the *Price Breakdown:* columns must add up to 100.00 in total.

**Guidance:** i.e. identifying need for the journal, aims and scope development, investment in funding for field, editorial board costs, commissioning content, competitor analysis, benchmarking, policy development, portfolio development.

***
### Price Breakdown: Journal Submission On First Decision
**Requirement:** Required

**Validation:** Percentage as a number with two decimal places. A period (dot) should be used as the decimal separator. Must be less than or equal to 100.00

The values of the *Price Breakdown:* columns must add up to 100.00 in total.

**Guidance:** i.e. triaging [NB this line is separated from the next in order to accommodate the Open Platform publishing model]

***
### Price Breakdown: Peer Review
**Requirement:** Required

**Validation:** Percentage as a number with two decimal places. A period (dot) should be used as the decimal separator. Must be less than or equal to 100.00

**Guidance:** Please do not factor in time or resources donated by editors or reviewers; please include specialist reviews; e.g. recruiting and training peer reviewers and the editors who work with them, peer review management and tracking systems. If the journal operates post-publication peer review please enter 0.00.

***
### Price Breakdown: Services Acceptance Publication
**Requirement:** Required

**Validation:** Percentage as a number with two decimal places. A period (dot) should be used as the decimal separator. Must be less than or equal to 100.00

**Guidance:** i.e. copyediting, formatting, typesetting, proofreading, assigning and depositing DOIs, XML file conversion (if content is not born XML), tagging, quality assurance checks, integration with a&I databases/aggregators/repositories/APC management systems, figure re-lettering or other improvements, dealing with article enhancements such as video abstracts, proofing process and author engagement around this, issue compilation, issue line up, printing, alignment with synchronous articles, vendor management, article pipeline management; addition of ORCIDs and other IDs to support funder/institutional disambiguation, checking references, design.

***
### Price Breakdown: Services Post Publication
**Requirement:** Required

**Validation:** Percentage as a number with two decimal places. A period (dot) should be used as the decimal separator. Must be less than or equal to 100.00

**Guidance:** i.e. handling ethical queries, provision of usage statistics, longterm preservation and access, reader services, postage, inventory and stock control

***
### Price Breakdown: Platform Development Support
**Requirement:** Required

**Validation:** Percentage as a number with two decimal places. A period (dot) should be used as the decimal separator. Must be less than or equal to 100.00

**Guidance:** i.e. platform, platform vendor management, hosting, systems development, systems support. One off development costs should be amortized over 3 years, and figures in reporting period specified by reporting-period-start and report-period-end included.

***
### Price Breakdown: Sales Marketing
**Requirement:** Required

**Validation:** Percentage as a number with two decimal places. A period (dot) should be used as the decimal separator. Must be less than or equal to 100.00

**Guidance:** i.e. sales teams, sales administration,legal costs for contracts, integration with and promotion on social media networks, sponsorship

***
### Price Breakdown: Author Customer Support
**Requirement:** Required

**Validation:** Percentage as a number with two decimal places. A period (dot) should be used as the decimal separator. Must be less than or equal to 100.00

**Guidance: **i.e. helpdesk, usage/impact/other reports, training, author queries about copyright or CC licenses

***

### Notes

**Requirement:** Optional

**Validation:** None - although long text may be truncated for display purposes in the web-application

**Guidance: **For brief notes about the title - for example to indicate that the title was recently acquired and so may not have a full year's data.

***