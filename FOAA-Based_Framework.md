# cOAlition S adaptation of the Fair Open Access Alliance (FOAA) Breakdown of Publication Services and Fees

Version 1.0, 2022-04-11

This documentation supports the collection of price and transparency data from publishers for the *cOAlitions S Journal Comparison Service*, using the spreadsheet with filename `Journal_Comparison_Service_Data_Collection_FOAA_v1.0.xlsx` . This document describes each of the columns in that spreadsheet, with some guidance on how to enter data.

## Column Definitions

### ISSN

**Requirement:** Required

**Validation:** Valid ISSN

***

### Journal Title

**Requirement:** Required

***

### Cluster

**Requirement:** Optional

**Guidance:** If you have a range of titles that are very similar to one another, and all the data provided for these would be within ±5%, then it is acceptable to average across these titles. In this case you would enter each journal in its own row and provide the same data for each title in the group. You would then complete this column to indicate which rows have been grouped together to calculate the average figures reported.

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

### APC List Price Range Lower

**Requirement:** Required

**Validation:** Number with two decimal places. A period (dot) should be used as the decimal separator. No thousand separator should be used.

**Guidance: **The lower price of any APC list price range for primary research articles. If there is just a single APC list price enter the same number in both *APC List Price Range Lower* and *APC List Price Range Higher*.

If no APC is charged, please indicate this by entering 0.00

***

### APC List Price Range Higher

**Requirement:** Required

**Validation:** Number with two decimal places. A period (dot) should be used as the decimal separator. No thousand separator should be used.

**Guidance: **The higher price of any APC list price range for primary research articles. If there is just a single APC list price enter the same number in both *APC List Price Range Lower* and *APC List Price Range Higher*.

If no APC is charged, please indicate this by entering 0.00

***

### APC List Price Currency

**Requirement:** Required

**Validation:** Valid ISO 4217:2015 alphabetic currency code

**Guidance:** Active currency codes can be found at https://en.wikipedia.org/wiki/ISO_4217#Active_codes

Please enter a value here (e.g. "USD"), even if the APC values in the previous two columns are 0.00

***

### APC Waiver Discount Policy

**Requirement:** Optional

**Validation:** Valid URL including protocol (http or https)

**Guidance:** A link to the publisher's publicly available policy for APC waivers and discounts.

***

### Subscription List Price Range Lower

**Requirement:** Required

**Validation:** Number with two decimal places. A period (dot) should be used as the decimal separator. No thousand separator should be used.

**Guidance:** The lower price of any subscription list price range for primary research articles. If there is just a single subscription list price enter the same number in both *Subscription List Price Range Lower* and *Subscription List Price Range Higher*.

This includes fees paid by libraries through models such as Subscribe to Open, Community Action Publishing, and library membership.

If no Subscription is charged, please indicate this by entering 0.00

***

### Subscription List Price Range Higher

**Requirement:** Required

**Validation:** Number with two decimal places. A period (dot) should be used as the decimal separator. No thousand separator should be used.

**Guidance:** The higher price of any subscription list price range for primary research articles. If there is just a single subscription list price enter the same number in both *Subscription List Price Range Lower* and *Subscription List Price Range Higher*.

This includes fees paid by libraries through models such as Subscribe to Open, Community Action Publishing, and library membership.

If no Subscription is charged, please indicate this by entering 0.00

***

### Subscription List Price For Member of The Association of American Universities

**Requirement:** Required

**Validation:** Number with two decimal places. A period (dot) should be used as the decimal separator. No thousand separator should be used.

**Guidance:** This is a required field. To facilitate comparison of list prices between publishers, please tell us the subscription list price for a typical research-intensive university in the US. If there is no subscription price, please enter 0.00

***

### Subscription List Price Currency

**Requirement:** Required

**Validation:** Valid ISO 4217:2015 alphabetic currency code

**Guidance:** Active currency codes can be found at https://en.wikipedia.org/wiki/ISO_4217#Active_codes

Please enter a value here (e.g. "USD"), even if the subscription values in the previous three columns are 0.00

***

### Subscription Discount Policy

**Requirement:** Optional

**Validation:** Valid URL including protocol (http or https).

**Guidance:** A link to the publisher's publicly available policy for discounting subscription prices.

***

### In-house or Outsourced Journal Operations?
**Requirement:** Required

**Validation:** One of:

* In-house
* Out-sourced
* Both

**Guidance:** 

***
### Rejection Rate

**Requirement:** Required

**Validation:** Percentage as a number with two decimal places. A period (dot) should be used as the decimal separator. If the rejection rate is unknown, please enter 0.00

**Guidance:** Desk rejection rate for reporting period (year)

***

### Discounts and Waivers Policy

**Requirement:** Optional

**Validation:** Valid URL including protocol (http or https)

**Guidance:** A link to the publisher's publicly available policy for APC waivers and discounts.

***

### Price Breakdown: Journal Operations

**Requirement:** Required

**Validation:** Percentage as a number with two decimal places. A period (dot) should be used as the decimal separator. Must be less than or equal to 100.00, and greater than or equal to 0.00
The values of the *Price Breakdown:* columns must add up to 100.00 or 0.00 in total

**Guidance:**  This might include aspects such as:
* Journal support and submission system
* Platform development and maintenance
* Helpdesk and other support staff

***

### Price Breakdown: Publication

**Requirement:** Required

**Validation:** Percentage as a number with two decimal places. A period (dot) should be used as the decimal separator. Must be less than or equal to 100.00, and greater than or equal to 0.00
The values of the *Price Breakdown:* columns must add up to 100.00 or 0.00 in total

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

### Price Breakdown: Fees

**Requirement:** Required

**Validation:** Percentage as a number with two decimal places. A period (dot) should be used as the decimal separator. Must be less than or equal to 100.00, and greater than or equal to 0.00
The values of the *Price Breakdown:* columns must add up to 100.00 or 0.00 in total

**Guidance:** This might include aspects such as:

 * Scientific editors fees
 * Scholarly societies fees

If you do not pay any fees, please enter 0.00 in this field

***

### Price Breakdown: Communication

**Requirement:** Required

**Validation:** Percentage as a number with two decimal places. A period (dot) should be used as the decimal separator. Must be less than or equal to 100.00, and greater than or equal to 0.00
The values of the *Price Breakdown:* columns must add up to 100.00 or 0.00 in total

**Guidance:** This might include aspects such as:

* Dissemination
* PR & Marketing
* Community support
* Advocacy

***

### Price Breakdown: General

**Requirement:** Required

**Validation:** Percentage as a number with two decimal places. A period (dot) should be used as the decimal separator. Must be less than or equal to 100.00, and greater than or equal to 0.00
The values of the *Price Breakdown:* columns must add up to 100.00 or 0.00 in total

**Guidance: ** This is a required field. Please enter as a percentage with two decimal places. 
Items covered by this heading include:
•	Management & administration
•	Other business costs
•	Taxes

If these general costs may have already been distributed between the other categories, please enter 0.00 for this field

***

### Price Breakdown: Surplus / Other Revenue

**Requirement:** Required

**Validation:** Percentage as a number with two decimal places. A period (dot) should be used as the decimal separator. Must be less than or equal to 100.00, and greater than or equal to 0.00
The values of the *Price Breakdown:* columns must add up to 100.00 or 0.00 in total

**Guidance:** This is a required field. Please enter as a percentage with two decimal places.
Use this field to indicate % of the price for surpluses or other revenue. If the surplus has already been distributed between the other categories, please enter 0.00 for this field.

***

### Price Breakdown: Discounts & Waivers

**Requirement:** Required

**Validation:** Percentage as a number with two decimal places. A period (dot) should be used as the decimal separator. Must be less than or equal to 100.00, and greater than or equal to 0.00
The values of the *Price Breakdown:* columns must add up to 100.00 or 0.00 in total

**Guidance:** This is a required field. Please enter as a percentage with two decimal places. 
Use this field to indicate % of the price allocated to support discounts and waivers. If there are no Discounts & Waivers, please enter 0.00 for this field.

***

### Notes

**Requirement:** Optional

**Validation:** None - although long text may be truncated for display purposes in the web-application

**Guidance: **For brief notes about the title - for example to indicate that the title was recently acquired and so may not have a full year's data.

***

