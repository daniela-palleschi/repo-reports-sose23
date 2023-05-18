# repo-reports-sose23

Materials for a block course "Reproducible analysis reports with eye-tracking reading time data" (summer semester 2023)

From the course AGNES:

> This course will provide students with the skills and know-how needed to create reproducible reports and presentations of eye-tracking reading data. A brief introduction will be given into common measures in eye-tracking reading and the importance of developing a reproducible workflow, followed by hands-on exercises in RStudio with the R programming language. The main skills developed include data wrangling (with the tidyverse package), data visualisation (with the ggplot2 package), and running and communicating descriptive and inferential statistics. By the end of the course, students will be able to apply what they learned to a variety of data types in both academic and professional settings. This course is aimed at students who have some practical experience with R and RStudio, although this is not a strict requirement. Students who cannot bring their own laptop to class should contact the instructor as early as possible, so an alternative laptop can be organised. The language of instruction is English.

## Folder structure

- `cheatsheets/`  R cheatsheets
- `codebook/`     codebook for data files
- `data/`         data for lectures
- `mats/`         teaching materials
  - `day1/`       day 1 materials
  - `day2/`       day 2 materials
  - `day3/`       day 3 materials
  - `day4/`       day 4 materials
  - `day5/`       day 5 materials
- `media/`        figures/videos for slides
- `my_eye_only/`  data prep (do not share)
- `renv/`         R environment
- `setup/`        setup tips
- `syllabus/`     syllabus
- `to delete/`    temporary holding of unimportant files

# Notes for future self

Day 1:

- mats don't really need much work;
- Welcome: okay
- Reproducibility: okay, but
  + a bit more time setting up Quarto docs (and practice with headers, code chunks, rendering) is needed
- Eye-tracking reading: maybe could be beefed up a bit?
  + add definitions of different measures, spend more time with it
- First dataset: okay, but:
  + maybe introduce workflow stuff (instead of in Day 2)
  + maybe introduce magrittr pipe on Day 1 (et_dataset) instead of in Day 2 (wrangling)

Day 2: 

- Workflow: good, but:
  + maybe should come before/during et_dataset topic on Day 1
- Data Wrangling: good but:
  + a bit long
  + students did individual work from tidyverse verbs section onward, a few made it to `group_by`
- Data Visualisation: mats could be improved for clarity/structure
  + students didn't finish materials, will continue in Day 3

Day 3:

- first session was used to catch-up on Data Viz (individual work-through of mats)
- Lin Reg1 (simple reg):
- Lin Reg2 (multiple reg):

Report assignment

- too much for 1LP, changed it to be worth 2LP (and only assignment)
- next time either make it shorter, or keep it as only assignment