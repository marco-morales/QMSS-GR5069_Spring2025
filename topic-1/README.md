## TOPIC 1 - Data Science as a Function

#### In preparation for this week:
* read/listen/watch as much as you can from the annotated materials below that provide some necessary context for the lecture on this topic

---

### What is Data Science?

Data Science remains a very nebulous concept with a very fluid definition, perhaps for the best. While there is no agreed upon definition, it is nonetheless important to understand the thinking in the field.

A great starting point are the first two chapters of Spector, Norvig, Wiggins & Wing's (2023) book - [__Data Science in Context__](https://datascienceincontext.com/manuscript/)  - where they distill our best contemporary understanding of what Data Science is.

You also don't want to miss this deeply thought piece by David Donoho (2017) - [__50 Years of Data Science__](https://www.tandfonline.com/doi/full/10.1080/10618600.2017.1384734) - discussing data science (and statistics) and arguing - correctly - that there is more Statistics in Data Science than Data Scientists are prepared to admit. Underlying his argument is **critical thinking about data** as a core requirement for Data Scientists. An incredibly relevant piece for Social Scientists to read as they head into the world of Data Science. <!--(Almost 20 years earlier, Jeff Wu (1997) had argued in his Carver Lecture - [**Statistics = Data Science?**](http://www2.isye.gatech.edu/~jeffwu/presentations/datascience.pdf) - that Data Science would be a more appropriate name for Statistics given the empirical tasks that statisticians perform. You might enjoy this (2016) interview with him - [**A conversation with Jeff Wu**](https://projecteuclid.org/download/pdfview_1/euclid.ss/1484816590).)-->  

For a much more applied perspective that complements Donoho's, listen to Hillary Mason's (2018) interview - [__Data Science, Past, Present and Future__](https://soundcloud.com/dataframed/1-data-science-past-present-and-future) - in the [DataFramed podcast](https://soundcloud.com/dataframed), where she provides a very insightful walkthrough of processes, realities, challenges and areas of opportunity for Data Science circa late 2017. The world has changed much since, but her points are still incredibly relevant.

A much more useful way to understand Data Science - which reflects our contemporary practice of the disicipline - is to focus on its outputs: **Data Products** - which are digital solutions that address a need or a problem in a business. To get a better understanding of this perspective, read Marco Morales' (2024) Substack post -  [__What is Data Science?__](https://datascienceshop.substack.com/p/what-is-data-science) - where he lays out this more pragmatic approach that may be foundational for any aspiring Data Scientist. 

### What is a Data Scientist and what does a Data Scientist do?

It's hard to separate Data Science, the discipline, from the people that perform it. A lot more has been written about Data Scientists and the work they do, seeking to provide more practical grounding to define Data Science.

Leveraging his role as host of the [DataFramed podcast](https://soundcloud.com/dataframed), Hugo Bowne-Anderson (2018) compiled a very nice summary article - [__What Data Scientists Really Do, According to 35 Data Scientists__](https://hbr.org/2018/08/what-data-scientists-really-do-according-to-35-data-scientists) - where he organizes the common topics that emerged from conversations with his 30+ guests, giving us a sense of what Data Scientists do circa 2018. A longer - and funnier - [talk version](https://www.youtube.com/watch?v=vSFWw6n0CZs&feature=youtu.be) of this article is also available.

Perhaps the most famous definition from this perspective comes from the title of an article by Thomas Davenport & DJ Patil's (2012) - [__Data Scientist: The Sexiest Job of the 21st Century__](https://hbr.org/2012/10/data-scientist-the-sexiest-job-of-the-21st-century) - where they uncover the then-nascent profession populated by individuals they describe as "a hybrid of data hacker, analyst, communicator, and trusted adviser". You don't want to miss their 2022 rejoinder - [__Is Data Scientist Still the Sexiest Job of the 21st Century?__](https://hbr.org/2022/07/is-data-scientist-still-the-sexiest-job-of-the-21st-century) - where they update their perspective of Data Science and detail the professionalization of the field that we see today.

Yet, the urge to understand what Data Scientists do as means to define Data Science started much earlier with a post by Drew Conway (2010) - [__The Data Science Venn Diagram__](http://drewconway.com/zia/2013/3/26/the-data-science-venn-diagram) - where he defines the profession as the intersection of its three core elements: (i) hacking skills, (ii) math & statistics knowledge, and (iii) substantive expertise. Many iterations of this idea have followed, as you can see in David Taylor's (2016) compilation - [__Battle of the Data Science Venn Diagrams__](https://www.kdnuggets.com/2016/10/battle-data-science-venn-diagrams.html).

Around the same time as Conway, a non-Venn-diagrammed view of what Data Scientists do was written in a very early post by Hillary Mason and Chris Wiggins (2010) - [__A taxonomy of Data Science__](http://www.dataists.com/2010/09/a-taxonomy-of-data-science/) - describing, possibly for the first time in writing, the tasks that in their view should define Data Science at the beginning of the 2010s.

A more recent view that brings it all together in a very coherent way is Cassie Kozyrkov's (2018) article - [__What on earth is data science?__](https://hackernoon.com/what-on-earth-is-data-science-eb1237d8cb37) - where she defines Data Science as the confluence of three subfields: __data mining/analytics__ (for _inspiration_), __statistics__ (to make decisions based on _limited information_), and __machine learning__ (to _automate tasks_).  

### How is a Data Scientist different from a Data or ML Engineer?

If you have read, seen and listened to the references above, it will be clear that a good number of activities described as belonging to the realm of Data Science can be hard to distinguish from those performed in Data or ML Engineering. But there is - and there should be - a clear difference between these activities, although that difference is not always as clear in practice.

Jesse Anderson's (2018) post - [__Data engineers vs. data scientists__](https://www.oreilly.com/radar/data-engineers-vs-data-scientists/) - makes a very crisp argument about the difference between data scientists and data engineering underscoring the limited skills overlap between both roles. His broader point: failing to recognize these differences might allocate people in the wrong roles.

As you can see, there are many different roles that come together to build Data Products in Data Science, and it can get confusing. If what you need is clarity on these (and other roles), you will enjoy Marco Morales' (2024) Substack post - [__WHO are the people that make Data Science possible?__](https://datascienceshop.substack.com/p/the-people-that-make-data-science-possible) - that provides a very accessible definition of the different skills, tasks, and outputs needed to create Data Products in Data Science,


### Critical Thinking in Data Science

In addition to understanding the technical discussions above, you should also know that __one of the most important skills that a Data Scientist must have is critical thinking__, in particular about data and its appropriateness to answer the question at hand. Put more colloquially, the ability to realize that _not all problems are nails to the Data Scientist's favorite hammer._

Debbie Berebichez's (2019) interview - [__Critical Thinking in Data Science__](https://soundcloud.com/dataframed/critical-thinking-in-data-science) - in the [DataFramed podcast](https://soundcloud.com/dataframed) gives a very intuitive and personal perspective on what critical thinking should mean for a Data Scientist. But critical thinking in Data Science must start with the "data". Read Cassie Kozyrkov's (2020) blog post - [__Understanding data__](https://towardsdatascience.com/what-is-data-8f94ae3a56b4) - where she makes a very compelling case for how data fits in Data Science and why we should avoid thinking about data with a capital "D".

A complementary argument for the need of critical thinking in Data Science can be found in Cassie Kozyrkov's (2019) article - [__The First Thing Great Decision Makers Do__](https://hbr.org/2019/06/the-first-thing-great-decision-makers-do) - where she discusses the importance of thoroughly understanding the context of a problem to be able to think critically about how best to solve it, even before you start thinking of the Data Science tools to apply.

If you are going to read just one piece about critical thinking in Data Science, read the transcript of Hanna Wallach's (2014) NIPS talk - [__Big Data, Machine Learning, and the Social Sciences: Fairness, Accountability, and Transparency__](https://hannawallach.medium.com/big-data-machine-learning-and-the-social-sciences-927a8e20460d). She does a fantastic job of explaining why we need critical thinking about data: most of the massive data out there used in Data Science is _granular_ data about the _behavior of individuals_. She then proceeds to draw the obvious conclusion that motivates this course: we need __MORE__ Social Scientists in Data Science. Her logic is indisputable: 

> Few computer scientists or engineers would consider developing models or tools for analyzing astronomy data without involving astronomers. So, why, then, are so many methods for analyzing social data developed without the involvement social scientists?