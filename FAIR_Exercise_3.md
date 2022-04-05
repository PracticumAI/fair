---
title: "FAIR Data in AI/ML: Exercise 3"
date: 2022-04-05
image: '/https://raw.githubusercontent.com/PracticumAI/practicumai.github.io/0bae6dc26b5f7f3f75bcc994f2192d1499f926a8/images/icons/noun_Data_green.svg'
image-width: 80px
image-height: 80px
layout: full_page
---

In [exercise 1](/fair/FAIR_Exercise_1/), we explored common issues with how data are organized in spreadsheets. We also provided a [handout](../handouts/L04_DataEntry_Handout.pdf) and the [Broman and Woo 2018 paper](https://www.tandfonline.com/doi/full/10.1080/00031305.2017.1375989) with some best practices in organizing data in spreadsheets.

Then, in [exercise 2](/fair/FAI_Exercise_2/), we explored the challenges with finding data associated with published literature and introduced the [FAIR principles](https://docs.google.com/presentation/d/1ikukDeyxKa4RCfpH0ehNa35lMbVNawwXaPA_XbGgaBs/edit?usp=sharing).

Now we turn to the process of making data available in **data repositories**.

## Data repositories

![Screenshot of the NIH Office of Data Science Strategy website on Biomedical Data Repositories and Knowledgebases](../images/NIH_ODSS.screenshot.png)

> Accessible, well-maintained, and efficiently operated data resources are critical enablers of modern biomedical research. ([NIH ODSS](https://datascience.nih.gov/data-ecosystem/biomedical-data-repositories-and-knowledgebases))

Beyond biomedical research, **any** data-based research requires accessible, well-maintained and efficiently operated data resources.

![Image with the Clive Humby quote "Data is the new oil!"](../images/data_is_the_new_oil.png)

While Clive Humby was thinking of marketing and business, data are more and more central to modern research.

With much of academic research funded through tax dollars, government funding agencies have started requiring making data produced through their funding available, with appropriate authentication and authorization, to further research. To facilitate making data available, an ecosystem of data repositories has grown, allowing researchers to deposit, cite, find and reuse data.

### Domain-Specific vs. Generalist Repositories

Many domains have established one or more data repositories to house data associated with studies in that particular domain. These domain-specific repositories can be tailored for the best practices for particular types of data, for example [GenBank](https://www.ncbi.nlm.nih.gov/genbank/) is "the NIH genetic sequence database, an annotated collection of all publicly available DNA sequences." Other domain specific repositories are available in many disciplines and are typically a best first choice for depositing data.

Often researchers have data that do not fit well in a single, or any, domain specific data repositories. Or raw data may be in a domain specific repository, but analyzed or combined datasets may be of value and can be deposited in generalist repositories. These repositories contain a wide array of data and while they maintain flexibility in the data types and formats deposited, this flexibility can reduce findability and reusability. One example of a generalist repository is [Zenodo](https://zenodo.org/).

Developed by [CERN](https://home.cern/) (the home of the Large Hadron Collider) and funded by the European Union, Zenodo is one of the leading generalist data repositories, with datasets ranging from physics to ecology and biomedicine.

## Student Instructions

In this exercise we will work with data in both a domain-specific and a generalist repository.

### Domain-specific repository

1. Visit this listing of [Domain-specific repositories](https://www.nlm.nih.gov/NIHbmic/domain_specific_repositories.html) maintained by NIH.
  * Browse the list of repisitories and identify some that may be of interest to you.
1. For this exercise, we will use the [National Sleep Research Resource](https://sleepdata.org/)
   * Our fitness tracker developer has realized that there is significant interest in tracking sleep patterns and wants to see what data are available to support linking sleep patterns to health.
1. Starting at [https://sleepdata.org/](https://sleepdata.org/), locate the main page for the Sleep Heart Health Study.
   * How did you get there?
1. [Here's the page](https://sleepdata.org/datasets/shhs) we were trying to find.
   * Did you find the same page? [![Screentshot of the Sleep Heart Health Study page](../images/sleep_heart_study.png)](https://sleepdata.org/datasets/shhs)
1. Look through the [metadata on the page](https://sleepdata.org/datasets/shhs). Are you able to answer these questions?
   * How were the data collected?
   * When were the data collected?
   * How would you cite the data if you used them?
   * How would you get access to the data?
   * Any metadata you think is missing?
1. Overall, if you were a sleep researcher, how useful do you think the National Sleep Research Resource would be?

### Generalist repository

1. Visit the listing of [Generalist repositories](https://www.nlm.nih.gov/NIHbmic/generalist_repositories.html) maintained by NIH.
   * How many of these do you recognize?
1. For this exercise, we will use [Zenodo](https://zenodo.org/)
1. Enter the search term "sleep heart" and search. ![Screenshot of searching for "sleep heart" in Zenodo](../images/zenodo_sleep_heart.png)
1. Scroll down to the "Type" selection box on the left and select "Dataset" ![Screenshot of the Type selection box showing the Dataset option selected](../images/zenodo_dataset.png)
1. Select a dataset (does not necessarily need to be related to our fitness tracker) and answer the same questions
1. Look through the metadata on the page. Are you able to answer these questions?
   * How were the data collected?
   * When were the data collected?
   * How would you cite the data if you used them?
   * How would you get access to the data?
   * Any metadata you think is missing?
1. Overall, if you were a sleep researcher, how useful do you think Zenodo would be?
1. Using Zenodo, think of some other search terms you may be interested in. Are you able to find information related to that in Zenodo?