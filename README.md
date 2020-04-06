# Deron_GIS_Portfolio
A collection of GIS work completed at Carnegie Mellon University.

# About me

A native of Lancaster, PA, I have lived, worked, and studied in Pittsburgh since 2014. My work seeks to preserve and promote free expression in all forms, from the personal to the political to the artistic.

I studied political science, sociology, and legal studies at Pitt. While studying I worked with the ACLU of Pennsylvania to advance the civil liberties of those incarcerated in the Commonwealth. From there I served as an editorial intern at SampsoniaWay.org, City of Asylum's online magazine, helping give voice to writers around the world who fight against censorship and oppression.

I then spent two and a half years working on staff at City of Asylum as the organization transitioned from the alley where it was formed to its new home and venue at Alphabet City. In their new space, I oversaw the production of over 200 readings, concerts, film screenings, and community events which sought to elevate lesser-heard voices and promote cross-cultural exchange.

Now I am pursuing my master's degree in public policy and management at the Heinz College at Carnegie Mellon University with a focus on data analytics. I hope to use the tools and skills I acquire in this program to ensure access to public services for all and address inadequacies in the legal system, such as bias in criminal justice and a lack of meaningful digital privacy protections.

# What I hope to learn

In this class I hope to learn how to better utilize geospatial data to solve public issues. Much of our lives are lived in the physical world, and the physical space in which problems regarding public services manifest matter. To that end I hope to learn to utilize tools that exist outside the expensive ESRI ecosystem, so that they may be utilized by under-resourced people, communities, and organizations.

I also hope to learn to better develop my ArcGIS Pro skills to glean additional insight from the datasets I've worked with in the past. This could include mapping local areas to identify food and transit deserts.

I also want to learn how to utilize GIS in a larger context. I understand many project have a GIS component to them yet may not be fully geospatial, so learning how to utilize these tools within a larger context would also prove useful.

# Portfolio

## Opioid Crisis Data in Mapbox
In order to understand how to use open-source tools instead of relying solely on ArcGIS Pro, I developed [this Mapbox style](https://api.mapbox.com/styles/v1/nathanderon/ck8omkovz1z3j1iqhha8wdgvo.html?fresh=true&title=copy&access_token=pk.eyJ1IjoibmF0aGFuZGVyb24iLCJhIjoiY2s4bnZ4ZTFxMDFlbDNmcWc2dnVlNTl4dCJ9.MUch7BBkOExavWKYDckufA) which uses CDC data and shapefiles from the US Census to visualize prescription rates and opioid overdose death rates across the country. These maps were meant to mimic those published by the CDC themselves, [here](https://www.cdc.gov/drugoverdose/maps/rxcounty2017.html) and [here](https://www.cdc.gov/drugoverdose/data/statedeaths/drug-overdose-death-2017.html).

This exercise showed me that a lot of visualization tasks can be done relatively painlessly in open-source tools such as Mapbox. While I did not find the interface very intuitive, I did not find ArcGIS intuitive at first either--GIS tools seem to take some time to understand regardless of the publisher. I did not engage in any analysis here, but visualization took roughly 20 minutes or so and allowed me to create professional maps on a free platform.

This task highlighted for me how different tools can be strung together to create a low-cost workflow when needed. While much of the pre-processing for this task could be done in ArcGIS Pro, I could also complete the joins and data cleaning in Python and visualize in Mapbox. While perhaps a bit time consuming, this provides a good workaround for person use or if working at under-resourced organizations. 
