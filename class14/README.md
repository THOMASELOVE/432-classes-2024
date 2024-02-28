# 432 Class 14: 2024-02-29

[Main Website](https://thomaselove.github.io/432-2024/) | [Calendar](https://thomaselove.github.io/432-2024/calendar.html) | [Syllabus](https://thomaselove.github.io/432-syllabus-2024/) | [Notes](https://thomaselove.github.io/432-notes/) | [Contact Us](https://thomaselove.github.io/432-2024/contact.html) | [Canvas](https://canvas.case.edu) | [Data and Code](https://github.com/THOMASELOVE/432-data) | [Sources](https://github.com/THOMASELOVE/432-classes-2024/tree/main/sources)
:-----------: | :--------------: | :----------: | :---------: | :-------------: | :-----------: | :------------: |:------:
for everything | for deadlines | expectations | from Dr. Love | ways to get help | lab submission | for downloads | to read

## Today's Slides

Class | Date | HTML | Word | Quarto .qmd | Recording
:---: | :--------: | :------: | :------: | :------: | :-------------:
14 | 2024-02-29 | **[Slides 14](https://thomaselove.github.io/432-slides-2024/slides14.html)** | *[Word 14](https://thomaselove.github.io/432-slides-2024/slides14w.docx)* | **[Code 14](https://github.com/THOMASELOVE/432-slides-2024/blob/main/slides14.qmd)** | Visit [Canvas](https://canvas.case.edu/), select **Zoom** and **Cloud Recordings**

## Announcements

1. We'll discuss Quiz 1 today in class. The answer sketch is on our Shared Drive in the Quiz 1 materials ... Quiz 1 Answer Sketch folder - it's called **432_sketch_results_quiz1_2024.html**, and you should also have an email from me (sent yesterday to your CWRU email) with details on your score for each item.
    - The items we will discuss in class today are items **Q02, Q03, Q05, Q09, Q19, Q20, Q22, Q23** and **Q25**, and the document I'll use to help with that discussion is also in that same directory in our Shared Drive. It's called **z_432_quiz1_items_for_discussion_2024_02-28.html**
    - If, **after class**, you have questions about your grade or anything else related to Quiz 1, please email me (at `Thomas dot Love` at `case dot edu`) by one week from today (2024-03-07) at Noon. After that, I'm going to treat the review of the Quiz as complete.
3. In doing [Lab 5](https://thomaselove.github.io/432-2024/lab5.html), due Tuesday at noon, there are a couple of small things I think might be clarified a bit, so I'll talk about those in class today. 

## Time to Event Data

Materials on time-to-event outcomes are found in Chapters 29-31 of our [Course Notes](https://thomaselove.github.io/432-notes/). This is a very brief introduction to the topic, and we will continue to discuss survival analysis and Cox regression in classes 21 and 22 of this course. My department also offers a full-semester course (PQHS 435) every spring in Survival Analysis, which goes into much more detail.

- I also recommend [this PDF guide by David Diez on Survival Analysis in R from OpenIntro](https://www.openintro.org/book/surv_in_r/), which provides the `OISurv` package.
- I strongly recommend you look at the (7-minute) video "[Survival Curves: Showing More by Showing Less](https://www.youtube.com/watch?v=EoIB_Obddrk)" on YouTube posted by Frank Harrell, which explains the logic behind several tools in the `rms` package which let you interact with a graph and a non-parametric survival function which saves a little more information than the usual Kaplan-Meier plot.
- The **survminer** package is where you can find the **ggsurvplot** approach we'll take today. 
- For more customization of plots like the Kaplan-Meier curves we'll build today, visit <https://rpkgs.datanovia.com/survminer/> or <https://github.com/kassambara/survminer/>. 
    - For instance, they provide a [PDF cheat sheet](https://rpkgs.datanovia.com/survminer/survminer_cheatsheet.pdf) which was pretty helpful to me.
- You may also be interested in learning more about concordance in survival analysis (and in general) [from this vignette](https://cran.r-project.org/web/packages/survival/vignettes/concordance.pdf) (pdf).

## What Should I Be Working On?

1. [Lab 5](https://thomaselove.github.io/432-2024/lab5.html) is due Tuesday 2024-03-05 at noon.
2. The [Project A portfolio](https://thomaselove.github.io/432-2024/projA.html) is due **Monday** 2024-03-18 at noon (immediately after Spring Break.)
3. Now is also a good time to work on [Lab 8](https://thomaselove.github.io/432-2024/lab8.html).

## One Last Thing

![](https://imgs.xkcd.com/comics/goodharts_law.png)  Source: [XKCD](https://xkcd.com/2899)
