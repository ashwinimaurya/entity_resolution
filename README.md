# Entity Resolution at Scale: Mapping 100+ million customer's account to customer identity

### Abstract

Customer Identity is at core of many businesses. This becomes very complex in presence of over 100 million customers, especially when most of Personal Identifiable Information (PII) are missing or have invalid values. At Albertsons, we use PII info along with engagement data, item level transactions, payments, and third party to map these club card numbers at customer and household level. We develop various methodologies1 and pipelines for data processing , feature engineering, predictive modeling, id elevation and stamping. These algorithms are scalable and quite robust in the sense that the generated shopper id (customer level mapping) and hhid (household level ids) are invariant to change in when new cards are added to the pool. Model is packaged as python package and deployed in production. The analysis of about 100+ million card numbers shows about reduction of 9% card numbers to customer id, and reduction of about 16% from card numbers to household id.

Please refer this document for more details.

https://github.com/ashwinimaurya/entity_resolution/blob/main/Albertsons_ID_Graph_Publix.pdf

Copyright © 2023, Ashwini Maurya, Albertsons Companies.
The development entity resolution framework, its methodology, technical details and algorithmic
implementations are Albertsons propriety material and therefore not available to public.


Corresponding author(s): Ashwini Maurya, Albertsons Companies, ashwini.maurya@albertsons.com
