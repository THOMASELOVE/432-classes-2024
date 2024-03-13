# 432 Class 23: 2024-04-11

[Main Website](https://thomaselove.github.io/432-2024/) | [Calendar](https://thomaselove.github.io/432-2024/calendar.html) | [Syllabus](https://thomaselove.github.io/432-syllabus-2024/) | [Notes](https://thomaselove.github.io/432-notes/) | [Contact Us](https://thomaselove.github.io/432-2024/contact.html) | [Canvas](https://canvas.case.edu) | [Data and Code](https://github.com/THOMASELOVE/432-data) | [Sources](https://github.com/THOMASELOVE/432-classes-2024/tree/main/sources)
:-----------: | :--------------: | :----------: | :---------: | :-------------: | :-----------: | :------------: |:------:
for everything | for deadlines | expectations | from Dr. Love | ways to get help | lab submission | for downloads | to read

## Today's Slides

Class | Date | HTML | Word | Quarto .qmd | Recording
:---: | :--------: | :------: | :------: | :------: | :-------------:
23 | 2024-04-11 | **[Slides 23](https://thomaselove.github.io/432-slides-2024/slides23.html)** | *[Word 23](https://thomaselove.github.io/432-slides-2024/slides23w.docx)* | **[Code 23](https://github.com/THOMASELOVE/432-slides-2024/blob/main/slides23.qmd)** | Visit [Canvas](https://canvas.case.edu/), select **Zoom** and **Cloud Recordings**

## Announcements

1. Grades and feedback on Lab 7 should be posted **by class time** to our Course Grading Roster on the Shared Drive.
2. There is no Minute Paper this week.

## Today's Agenda

Using the tidymodels approach to build linear models

## The `tidymodels` packages

Today we're introducing the **tidymodels** set of packages. 

1. The [tidymodels website](https://www.tidymodels.org/), in particular the [Get Started](https://www.tidymodels.org/start/) tutorials, and the [Learn section](https://www.tidymodels.org/learn/), which has additional information on performing analyses, tuning models, and developing custom approaches, among other things.
    - Core tidymodels packages include [broom](https://broom.tidymodels.org/), [rsample](https://rsample.tidymodels.org/), [recipes](https://recipes.tidymodels.org/), [parsnip](https://parsnip.tidymodels.org/), [workflows](https://workflows.tidymodels.org/), [tune](https://tune.tidymodels.org/), [yardstick](https://yardstick.tidymodels.org/), and [dials](https://dials.tidymodels.org/).
2. Max Kuhn and Julia Silge's book [Tidy Modeling with R](https://www.tmwr.org/) which has been my main way to learn about these approaches.
3. For videos with great `tidymodels` examples, try [Julia Silge's YouTube page](https://www.youtube.com/c/JuliaSilge/videos). I'll highlight...
    - [Model student debt inequality with tidymodels](https://www.youtube.com/watch?v=4ayOjlRv8bA) from 2021-02-12
    - [Get started with tidymodels and classification of penguin data](https://www.youtube.com/watch?v=z57i2GVcdww) from 2020-07-28
    - [Predict astronauts' mission duration with tidymodels and bootstrap aggregation](https://www.youtube.com/watch?v=rzfTA3xi-W0) from 2020-07-15
    - [Data preprocessing and resampling using tidymodels](https://www.youtube.com/watch?v=s3TkvZM60iU) from 2020-03-10
    - [Get started with tidymodels using vaccination rate data](https://www.youtube.com/watch?v=E2Ld3QdXYZo) from 2020-02-25
4. You may be interested in Bruna Wundervald's [An introduction to the tidymodels package](http://brunaw.com/tidymodels-webinar/slides/slides.html#1) slides, too.

## Sources from Today's Slides

In addition to those listed above, I also draw from:

- Andrew Gelman, Jennifer Hill and Aki Vehtari [Regression and Other Stories](https://avehtari.github.io/ROS-Examples/), 2020.
- Eric Vittinghoff, David V. Glidden, Stephen C. Shiboski and Charles E. McCulloch [Regression Methods in Biostatistics](https://github.com/THOMASELOVE/432-2022/blob/main/references/pdf/Vittinghoff_et_al_Regression_Methods_in_Biostatistics_2e_protected.pdf), 2nd Edition, 2012.

## A few thoughts on the adjusted R-square statistic

In linear regression work, the "adjusted R-square" statistic attempts to use the same data to fit the model and evaluate it, through applying a penalty based on the number of coefficient estimates that need to be developed and the sample size. This summary is somewhat interesting, and has some value occasionally. However, I usually avoid placing much weight on summary statistic "adjusted R-square" to describe the predictive quality of a model, in favor of a validated R-square statistic, which might include:

- the "optimism-corrected" results of a bootstrap validation (as in `validate` for an `ols` fit)
- the r-square value observed when applying a model fit in a training sample to holdout data in a test sample
- some other cross-validated r-square statistic, as can be developed using the `rsample` and `yardstick` packages (see, for example, Chapters 9 and 10 in [Tidy Modeling with R](https://www.tmwr.org/).

So my main point is that I wouldn't use adjusted R-square much (if at all) in linear regression, instead using a better method to assess predictive power in linear regression.

## What should I be working on?

- [Quiz 2](https://github.com/THOMASELOVE/432-quizzes-2024/tree/main/quiz2) will be available to you on Thursday 2024-04-18 at 5 PM, and is due when the [Calendar](https://thomaselove.github.io/432-2024/calendar.html) says it is.
- [Lab 8](https://thomaselove.github.io/432-2024/lab8.html) is due Monday 2024-04-29 at noon.
- [Project B](https://thomaselove.github.io/432-2024/projB.html)

## One Last Thing

To come.
