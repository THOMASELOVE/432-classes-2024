# 432 Class 16: 2024-03-07

[Main Website](https://thomaselove.github.io/432-2024/) | [Calendar](https://thomaselove.github.io/432-2024/calendar.html) | [Syllabus](https://thomaselove.github.io/432-syllabus-2024/) | [Notes](https://thomaselove.github.io/432-notes/) | [Contact Us](https://thomaselove.github.io/432-2024/contact.html) | [Canvas](https://canvas.case.edu) | [Data and Code](https://github.com/THOMASELOVE/432-data) | [Sources](https://github.com/THOMASELOVE/432-classes-2024/tree/main/sources)
:-----------: | :--------------: | :----------: | :---------: | :-------------: | :-----------: | :------------: |:------:
for everything | for deadlines | expectations | from Dr. Love | ways to get help | lab submission | for downloads | to read

## Today's Slides

Class | Date | HTML | Word | Quarto .qmd | Recording
:---: | :--------: | :------: | :------: | :------: | :-------------:
16 | 2024-03-07 | **[Slides 16](https://thomaselove.github.io/432-slides-2024/slides16.html)** | *[Word 16](https://thomaselove.github.io/432-slides-2024/slides16w.docx)* | **[Code 16](https://github.com/THOMASELOVE/432-slides-2024/blob/main/slides16.qmd)** | Visit [Canvas](https://canvas.case.edu/), select **Zoom** and **Cloud Recordings**

## Announcements

1. Feedback on the Minute Paper after Class 15 [is available now](https://bit.ly/432-2024-min-15-feedback).
2. The Answer Sketch for Lab 5 is posted to our Shared Drive.
3. **Next week (March 11-15) is CWRU Spring Break**
    - We will not hold TA office hours on March 9-15.
    - TA office hours will end on Friday 2024-03-08, and then return on *Saturday* 2024-03-16, a day earlier than originally planned. **Note this big change.**
    - Campuswire will remain open throughout Spring Break, and Dr. Love will review and answer all unanswered questions once per day.
    - Our next class (class 17) will be held on Tuesday 2024-03-19.
4. **Note this HUGE change.** Your [Project A Portfolio](https://thomaselove.github.io/432-2024/projA.html#the-project-a-portfolio) is now due at noon on **Tuesday** 2024-03-19. 
    - We made this change (moving the deadline back 24 hours) so that you could take better advantage of TA office hours on Saturday, Sunday *and* Monday preceding the submission deadline.
    - The rules on late Project A portfolio work are unchanged - [see the details here](https://thomaselove.github.io/432-2024/projA.html#deadlines) and I hope this will keep you from pleading for extensions.
    - All of my remaining advice I shared [in Class 15](https://github.com/THOMASELOVE/432-classes-2024/tree/main/class15#a-few-project-a-tips).
6. There are two new posts on [Campuswire](https://campuswire.com/) from me (numbers 80 and 81.) Take a look at them today, if you can.

## On getting rid of labels from SAS, SPSS or other software within R

The [haven package](https://haven.tidyverse.org/index.html) has two good tools I have used for this task...

- [zap_labels()](https://haven.tidyverse.org/reference/zap_labels.html) which removes *value* labels, and
- [zap_label()](https://haven.tidyverse.org/reference/zap_label.html) which gets rid of *variable* labels.

## Today's Topics

Today's slides discuss four things, specifically...

1. What happens if we fit a linear model to a count outcome? (This and items 2-3 also build on the medicare data from Class 15.)
2. How do I think about selecting non-linear terms in light of Spearman $\rho^2$? 
3. How do we fit a Poisson regression with the `rms` package, and do we then get everything we get with `ols()` and `lrm()`?
4. What are the six main Assumptions of Logistic Regression Models, and how do we check them effectively?

## One Last Thing

["Not statistically significant" is not the same as zero](https://statmodeling.stat.columbia.edu/2021/09/28/not-statistically-significant-is-not-the-same-as-zero/) from Andy Gelman's blog, 2021-02-28. The money quote for me is this:

> This illustrates one of the challenges of statistical communication: there are so many opportunities to garble the message. And even if you make no mistakes, people can still misinterpret what you’ve written, given the **norm of acting as if every study either makes a discovery or proves that something equals zero**.

- For more on a related example, you might be interested in [RCT on use of cloth vs surgical masks](https://statmodeling.stat.columbia.edu/2020/04/15/rct-on-use-of-cloth-vs-surgical-masks/) from 2020-04-15.
