# 432 Class 20: 2024-03-28

[Main Website](https://thomaselove.github.io/432-2024/) | [Calendar](https://thomaselove.github.io/432-2024/calendar.html) | [Syllabus](https://thomaselove.github.io/432-syllabus-2024/) | [Notes](https://thomaselove.github.io/432-notes/) | [Contact Us](https://thomaselove.github.io/432-2024/contact.html) | [Canvas](https://canvas.case.edu) | [Data and Code](https://github.com/THOMASELOVE/432-data) | [Sources](https://github.com/THOMASELOVE/432-classes-2024/tree/main/sources)
:-----------: | :--------------: | :----------: | :---------: | :-------------: | :-----------: | :------------: |:------:
for everything | for deadlines | expectations | from Dr. Love | ways to get help | lab submission | for downloads | to read

## Today's Slides

Class | Date | HTML | Word | Quarto .qmd | Recording
:---: | :--------: | :------: | :------: | :------: | :-------------:
20 | 2024-03-28 | **[Slides 20](https://thomaselove.github.io/432-slides-2024/slides20.html)** | *[Word 20](https://thomaselove.github.io/432-slides-2024/slides20.docx)* | **[Code 20](https://github.com/THOMASELOVE/432-slides-2024/blob/main/slides20.qmd)** | Visit [Canvas](https://canvas.case.edu/), select **Zoom** and **Cloud Recordings**

## Announcements

1. Feedback on the Minute Paper after Class 19 is now available at <https://bit.ly/432-2024-min-19-feedback>.
2. The Lab 6 answer sketch has been posted to our Shared Drive. Grades and feedback on Lab 6 will be posted next Tuesday.
3. I hope to complete Project A reviews tonight. Progress so far [is summarized here](https://github.com/THOMASELOVE/432-classes-2024/blob/main/projectA/portfolio_review.md). We'll see if I hit my deadline or not.
4. Thank you to those of you who responded to "Bonus: How to Be a Modern Scientist question #2" on Campuswire (note 131) which I'll close up at 3 PM today (I extended the deadline until then.)
5. Regarding using rootograms effectively and getting topmodels to run on a Mac with R 4.3.3, there is a Campuswire note (#151) from Gazi Shamita describing one solution. That approach has now worked for at least two people. I will try to tackle this further over the weekend, if I can find the time. 
6. I have edited [the Project B instructions](https://thomaselove.github.io/432-2024/projB.html), to (1) replace the Fall 2022 link with the [Fall 2023 link to NHANES instructions from 431](https://thomaselove.github.io/431-projectB-2023/data2.html), and (2) as follows...

The model for your second outcome must use a different approach than you used for Outcome 1. For this model, you can use any of the three options above, or you may use:

- A linear or binary logistic model fit using a Bayesian engine (*new*) via the tidymodels package, or
- (*new*) A linear model fit by selecting candidate predictors using the lasso, or
- (*new*) A linear regression model that uses survey weights, or
- (*new*) A robust linear model that uses robust standard errors.

## Our Starting Point for Today

- [An Introduction to Hierarchical Modeling (Visual Explanation)](http://mfviz.com/hierarchical-models/) by [Michael Freeman](http://mfviz.com/)

## Other Resources for Hierarchical Data Mentioned in the Class 20 Slides

- [Generalized Linear Mixed Models FAQ](https://bbolker.github.io/mixedmodels-misc/glmmFAQ.html) by Ben Bolker and others. Other work by Ben Bolker includes...
    - [Some notes on (generalized) linear mixed models](https://bbolker.github.io/morelia_2018/notes/glmm.html)
    - [Some worked examples of these models](https://bbolker.github.io/mixedmodels-misc/ecostats_chap.html)
- [The Introduction to Mixed Models from Environmental Computing](http://environmentalcomputing.net/mixed-models/) folks at the University of New South Wales, Australia.
- [Workshop on Linear mixed effects models from the Quebec Centre for Biodiversity Science](https://wiki.qcbs.ca/r_workshop6) developed by Catherine Baltazar, Dalal Hanna and Jacob Ziegler
- [A useful bibliography of mixed effect regression models](https://joelemartinez.com/2015/07/14/mixed-effect-models/) by Joel Eduardo Martinez
- [Using `sjPlot` in R to summarize Mixed Models in HTML tables](https://strengejacke.github.io/sjPlot/articles/tab_mixed.html) and [Using `sjPlot` to Plot Model Estimates](https://strengejacke.github.io/sjPlot/articles/plot_model_estimates.html)
- [UCLA example using mixed effects logistic regression](https://stats.idre.ucla.edu/r/dae/mixed-effects-logistic-regression/)

## What Should I Be Working On?

1. [Lab 7](https://thomaselove.github.io/432-2024/lab7.html) is due at noon Tuesday 2024-04-02.
2. The [Project B proposal form](https://bit.ly/432-2024-projectB-proposal-form) is due at noon on Wednesday 2024-04-10.
3. It's never too early to work on [Lab 8](https://thomaselove.github.io/432-2024/lab8.html), although it's not due until Monday 2024-04-29 at noon.
    - Here is the [Lab 8 work](https://github.com/THOMASELOVE/432-classes-2024/tree/main/lab8) by students in 432 to date.

## Some Machine Learning Sources from Frank Harrell (and friends)

I've been asked to talk a bit about machine learning, so I'll send you to my main sources.

- Frank Harrell's [Road Map for Choosing Between Statistical Modeling and Machine Learning](https://www.fharrell.com/post/stat-ml/)
- Drew Levy on [Navigating Statistical Modeling and Machine Learning](https://www.fharrell.com/post/stat-ml2/) is a great follow-up discussion of Frank's main post.
- Frank also has a video of a talk called [Musings on Statistical Models vs. Machine Learning in Health Research](https://www.fharrell.com/talk/mlhealth/) available.
- Another helpful video on some related issues from Frank is [Controversies in Predictive Modeling, Machine Learning, and Validation](https://www.fharrell.com/talk/stratos19/).

## One Last Thing.

From [On the 12th Day of Christmas, a Statistician Sent to Me...](https://www.bmj.com/content/379/bmj-2022-072883)

![](figures/christmas7.png)

