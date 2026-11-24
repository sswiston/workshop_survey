Assessing the efficacy of computational workshops and participatory live coding in evolutionary biology
---

This dataset is associated with Swiston S. K., Kuehne L., Moore R., & Landis M. (2026). Assessing the efficacy of computational workshops and participatory live coding in evolutionary biology. *Frontiers of Biogeography, 19* e209779. https://doi.org/10.21425/fob.19.209779. It contains the surveys, recruitment materials, and code associated with the project. Raw survey responses are excluded for participant privacy.

# Description of the data and file structure

* `pre_workshop_survey` contains a .pdf version of the pre-workshop survey administered to participants via REDCap.
* `post_workshop_survey` contains a .pdf version of the post-workshop survey administered to participants via REDCap.
* `recruitment_materials` contains the emails sent to workshop participants before and after the workshops to recruit them to participate in the survey. It also contains the verbal announcements made to participants during the workshop.
* `codebook.md` contains variable names and descriptions for the survey response data (data not included for privacy)
* `workshop_survey_project.Rmd` contains the R code for processing the survey data, performing statistical tests, and generating plots.
* `workshop_survey_project.html` is the knitted (.html) version of `workshop_survey_project.Rmd`, offering a more user-friendly method of viewing the code and results.

# Sharing/Access information

Links to other publicly accessible locations of the data:

* https://github.com/sswiston/workshop_survey

Code/Software

* The dataset contains an .Rmd file for performing analyses. This file were designed to be run using R version 4.3.1.

Version Changes:

* `2026-11-24` Updated the associated article information, added CC0 license in `LICENSE.md`, added `codebook.md`, and modified `workshop_survey_project.Rmd` to use relative paths instead of absolute paths