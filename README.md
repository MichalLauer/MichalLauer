# Hello there 👨‍🔬

I'm a student from Czechia who is passionate about math, statistics, and Data Science. This repo holds some of my work
that showcases how I go around data analysis and coding in general.

## Data Analyst Associate certification 🐕‍

- **Tool:** RMarkdown  
- **Packages:** readr, dplyr, forcats, skimr, ggplot2, glue, stringr, tidytext
- **Output:** Written analysis

[Pet Box Subscription](https://github.com/MichalLauer/PetBoxSubscription) analysis is a descriptive analysis of a pet store, which was done for my [Data Analyst Associate](http://laumi.me/DA-DAA) certification. This analysis aims to identify pet owners who could purchase stuff every month (food, toys, medical supplies...). The data is read with `readr` and wrangled with `dplyr`. As most characteristics are factors, I heavily relied on `forcats` to simplify my work. Data visualization is done with `ggplot2` and `skimr`. When working with text, I applied `glue` for string interpolation and `stringr` for text manipulation. For advanced graphs, I used `tidytext`'s facet functions.

My final submission consisted of a written report for Data Scientists at Data Camp, who reviewed my proposal and reviewed that the analysis meets current industry standards. You can view it in [my DataCamp workspace](https://app.datacamp.com/workspace/w/a3a8ffa5-3924-4746-9f40-5e9c8648c245).

## Professional Data Analyst certification 💸

- **Tool:** RMarkdown  
- **Packages:** dplyr, tidyr, ggplot2, patchwork, gtsummary
- **Output:** Oral presentation with PowerPoint slides

My second [Data Analyst certificate](https://laumi.me/DA-DAP) was achieved with my analysis on a made-up [insurance company](https://github.com/MichalLauer/TravelAssured). This analysis mainly aims to identify which customers are buying insurance and what their characteristics are. Coding and data interpretation is done in `R Markdown`. The data is wrangled and transformed using `dplyr` and `tidyr`. Data visualization is put together using `ggplot2` and `patchwork`. The final tables are beautified with `gtsummary`.

The analysis was presented orally to Data Scientist from DataCamp, who reviewed my presentation and verbal communication. My video presentation is not available; however, the PowerPoint presentation can be downloaded from my [Github repo](https://github.com/MichalLauer/TravelAssured/tree/main/docs).

## Data Scientist Associate certification 🧘🏽‍♀️

- **Tool:** DataCamp Notebook
- **Packages:** readr, dplyr, glue, ggplot2, tidymodels
- **Output:** Written submission

To recieve the [Data Scientist Associate certification](https://laumi.me/DA-DSA), I created a report that first reads (`readr`) and wrangles (`dplyr`, `glue`) data about a made-up fitness center. After set domain restrictions are validated and applied, data is explored using `ggplot2`. To predict the number of people in a fitness class, I used various packages from the `Tidymodels` family.

First model created uses Ridge regression from the `glmnet` package. *Alpha* was validated using 10-cross validation. The second model uses Random forest to predict the number of customers. Parameters were tune()'d using 10-cross validation. The final submission can be seen on my [DataCamp workspace](https://app.datacamp.com/workspace/w/2e343ebe-50c6-4eb6-bd28-72eda90bce4f).
