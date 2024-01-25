# {DataHoover} NHS-R Conf presentation

[![CC BY-SA 4.0][cc-by-sa-shield]][cc-by-sa]

This work is licensed under a
[Creative Commons Attribution-ShareAlike 4.0 International License][cc-by-sa].

[![CC BY-SA 4.0][cc-by-sa-image]][cc-by-sa]

[cc-by-sa]: http://creativecommons.org/licenses/by-sa/4.0/
[cc-by-sa-image]: https://licensebuttons.net/l/by-sa/4.0/88x31.png
[cc-by-sa-shield]: https://img.shields.io/badge/License-CC%20BY--SA%204.0-lightgrey.svg

Presentation on DataHoover package for [NHS-R online conference](https://nhsrcommunity.com/events/nhs-r-nhs-pycom-online-conference-talks-2023-ticket-for-virtual-attendance-on-wednesday-11th-october-2023/), October 2023

## Abstract for the talk

DataHoover is an R package that helps us answer 'customer' queries efficiently and reliably,
and forms a central part of our regular performance reporting workflow.

We needed to be able to pull data into R so we could use it for ad hoc analysis and report generation.
DataHoover helps us do this, either spontaneously at the R console or as part of a pre-set pipeline.

DataHoover's main functions each enable us to ask particular questions of our data, like
"how many babies were born at our hospital last month?"
At its heart, it returns an event list directly from a SQL query.
The event list gives us a detailed view of activity at the level of the individual event or patient.

A second core function bundles up the event list into daily or monthly (etc) summaries.
Finally, DataHoover can run along a config file and generate a bundle of data for multiple measures,
suitable for feeding into a report.

In developing DataHoover we have aimed to balance ease of use with a mild dose of friction that guards against user error.
The presentation will discuss various design decisions we have made for the package.

My presentation will show:
 * how DataHoover helps us meet pressing business needs and respond to customer questions efficiently
 * how we are using it as an example when we advocate for openness and reproducibility within our organisation
 * how we hope the package will become more widely used.

DataHoover: _it might just blow you away!_

![CikVgaqWkAA1zjh](https://github.com/francisbarton/DataHoover-NHS-R/assets/1819920/f1d05054-cd4b-468c-b258-9749e0deb00c)

