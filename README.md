# Entity Resolution at Scale: Mapping 100+ million customer's account to customer identity

### Abstract

Customer identity is at core of many businesses. This becomes very complex in presence of over 100 million customers, especially when most of Personally Identifiable Information (PII) are missing or have invalid values. At Albertsons, we use PII info along with engagement data, item level transactions, payments, and third party data to map customer accounts at both individual shopper and household levels. We develop various methodologies1 and pipelines for data processing , feature engineering, predictive modeling, id elevation and stamping. These algorithms are scalable and quite robust in the sense that the generated shopper id (customer level mapping) i) uniquely maps to individual customer, ii) is time invariant, iii) is invariant to customer’s additional accounts, and iv) invariant to updated PII at a future point in time. Model is packaged as python package and deployed in production. The analysis of about 100+ million card numbers shows reduction of approximately 9% from customers accounts to shopper id, and reduction of approximately 16% from customer accounts to household ids.

Please refer this document for more details.

https://github.com/ashwinimaurya/entity_resolution/blob/main/Albertsons_ID_Graph_Publix.pdf

Copyright © 2023, Ashwini Maurya, Albertsons Companies.
The development entity resolution framework, its methodology, technical details and algorithmic
implementations are Albertsons propriety material and therefore not available to public.


Corresponding author(s): Ashwini Maurya, Albertsons Companies, ashwini.maurya@albertsons.com
