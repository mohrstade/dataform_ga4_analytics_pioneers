# Dataform GA4 Demo Repository - Analytics Pioneers Training

Demo GA4 Dataform project created and used in the Analytics Pioneers Dataform training. https://analytics-pioneers.com/community-trainings/ <br>
This repository is subject to change with every Analytics Pioneers Dataform training.

Uses the GA4 demo data provided by the Google Merchandise Store to generate a data pipeline. A user defined function (UDF) will calculate a channel grouping which is similar to Googles own solution in the GA4 interface. In the view ga4_channels_agg the UDF is used to enrich the GA4 date with the provided channel grouping. 
<br><br>
Compiled Graph:
<br><br>
<img width="1093" alt="image" src="https://user-images.githubusercontent.com/117280013/221579144-87609961-9cb1-40c4-a05a-23b3a041f865.png">
<br><br>
Will generate the following structure in BigQuery:
<br><br>
<img width="270" alt="image" src="https://user-images.githubusercontent.com/117280013/221578822-f7f896fd-e1e8-477c-bf74-5a728629cc4b.png">
