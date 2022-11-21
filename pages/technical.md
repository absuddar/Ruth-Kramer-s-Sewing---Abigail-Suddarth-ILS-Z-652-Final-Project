---
title: Technical Documentation
layout: about
permalink: /technical.html
# Edit the markdown on in this file to describe your collection
# Look in _includes/feature for options to easily add features to the page
---
# Technical Documentation
{% include feature/nav-menu.html sections="Items Chosen;Imaging Standards;Metadata Standards;" %}
## Items Chosen
INSTERT EXPLANATION 
## Imaging Standards
INSERT EXPLANATION

{% include feature/image.html objectid="PICK AN IMAGE" width="50" caption="INSERT A CAPTION" %}

INSERT

## Metadata Standards
INSERT INSTRUCTIONS

Below is an explanation of what Dublin Core and text item type elements are used and what standards have been applied to their input.  
### Dublin Core elements  
#### Title - required, 1 value allowed
INSERT

Examples: INSERT


#### Creator - required, multiple values allowed
INSERT

#### Date - required, 1 value allowed
Date element contains the value of the date of publication which is important to include in any sort of bibliographic item. The dates are formatted according to the [W3C date format](https://www.w3.org/TR/NOTE-datetime) which allows for dates to be inputted in this way:  
- YYYY-MM-DD
- YYYY-MM
- YYYY


#### Publisher - required, 1 value allowed

#### Format - required, 2 values required
The format element has two required values: the number of pages (not including the front and back covers) and the digital format of the item. The number of pages is an Arabic numeral followed by "pp" and the digital format corresponds to the [Internet MIMEtype](https://www.iana.org/assignments/media-types/media-types.xhtml).

Examples: 32pp, pdf  

#### Language - required, multiple values allowed
While all of the items currently in the digital library are in Spanish, other issues of the series sometimes contain significant portions in other languages, such as [Francfort: juguete cómico tetralingue by Vital Aza](https://t.co/ah97YtWLMn?amp=1), which contains dialogue in German, French, Spanish, and Catalan. If that item were to be formally incorporated into the collection (instead of being linked to on the [Other Issues in La Novela Teatral]), it would be appropriate to list other languages in the language field. The values for the language element use the 3-letter language codes listed in the [ISO 639-2](https://en.wikipedia.org/wiki/List_of_ISO_639-2_codes).  

Examples: spa, eng  

#### Description - optional

#### Rights - required, 1 value allowed

#### Identifier - required, 1 value allowed

#### Translator - required if present, multiple values allowed

#### Series - required, 1 value allowed

#### Year (Magazine/Journal) - required, 1 value allowed

#### Number (Magazine/Journal) - required, 1 value allowed

#### Place of Publication - required, 1 value allowed

#### Price - required, 1 value allowed

#### Physical Dimensions - required, 1 value allowed

#### Advertisement - required, multiple values allowed
