# HDB Resale Prices Analysis

Analysis of HDB Resale Prices Dataset (from data.gov.sg)

#### Skills Demonstrated:
- Data Pre-processing (pulling data from APIs, data cleaning, feature engineering, use of geo-coding APIs)
- EDA and Data Visualization
- Analysis and Insights for real-world applications

#### Data: HDB resale property transactions. This comes in several separate datasets, differentiated by the date of the transaction.

We will first have to merge them together, and then use geocoding APIs to obtain the geographic coordinates of a flat’s location given its address (e.g., “Blk 175 Yishun Ave 7” becomes (1.437854, 103.832516)).

#### Objectives: Clear narrative with recommendations answering the following questions:

1. Some members of the public have written to the Straits Times Forum saying that flat sizes have gotten smaller over the years. Is this a fair observation? What data-driven insights can you share with the staffers over at the Ministry of National Development (MND) to help them craft a public response?

2. In this regard, have resale flat prices increased in the towns served by this new line? You might want to use a difference-in-differences model for this task.
One of the Members of Parliament (MP) for Nee Soon GRC has asked the Minister if the negative media coverage on mishaps and crimes in Yishun has subsequently impacted property prices. What data-driven insights can you share to help MND prepare a reply in parliament?
