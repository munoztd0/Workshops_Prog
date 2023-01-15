## Workshops

The main goal of these workshop series is to create the oppurtunity for Neuroscience/Pscyhology master students to improve their skills in data wrangling through active problem solving (with hints and guidelines) that are representative of ‘real world’ problems that one will probably encounter in cogntive/affective neuroscience research.

A non exaustive list of skills/methods we are going to focus on:

- Code reproducibility (dynamic programming)
- Code understandability (comments, style, Rmarkdown, Jupyter notebook)
- Version control and code availability (github)
- Automatisation (creating functions)
- Data wrangling
- Data vizualisation
- ANOVA
- Multilevel modeling
- Bayesian approach

<br><br>

<ins>*Advanced Data Visualization with R and Ggplot2.*</ins>

*What*: The grammar of graphics is a way of thinking about how graphs are constructed that allows data analysts to move beyond thinking about a small number of graph types (like bar graphs, line graphs, scatter plots, etc).

*Why*: The scientific literature is riddled with bad charts and graphs, leading to misunderstanding and worse... Avoiding design missteps can improve understanding of research. When it comes to practical usage, data visualization is as important as any other part of science could be, especially when it comes to practical use.

This practical will teach you the major components of the *Grammar of Graphics*:

- *Aesthetics*: Identify the dimensions you want to visualize, confirm the axes based on the data dimensions, positions of various data points in the plot.
- *Scale*: Do we need to scale the potential values, use a specific scale to represent multiple values or a range?
- *Geoms*: Should it be points, bars, lines and so on?
- *Statistics*: Do we need to show some statistical measures in the visualization like measures of central tendency, spread, confidence intervals?
- *Facets*: Do we need to create subplots based on specific data dimensions?

We will use different real world example to apply these concepts, adn learn which appropriate visualizations to represent your data.

- *Correlation*: scatterplot and bubble plot
- *Distribution*: histogram, density and boxplot.
- *Ranking*: barplot, lollipop and treemap.
- *Evolution*: line plot and area chart.


<br><br>


<ins>*Data wrangling with R*</ins>

*What*: Data wrangling is the process of converting and mapping raw data and getting it ready for analysis.

*Why*: With the world of data rapidly expanding, it is becoming increasingly essential to get the right data to be organized for analysis. Hence, it is important to make raw data usable for stastitical methos.

Learning Objectives:

- Select columns in a data frame with the dplyr function *select*.
- Select rows in a data frame according to filtering conditions with the dplyr function *filter*.
- Direct the output of one dplyr function to the input of another function with the *‘pipe’ operator %>%*.
- Add new columns to a data frame that are functions of existing columns with *mutate*.
- Understand the *split-apply-combine* concept for data analysis.
- Use *summarize*, *group_by*, and *count* to split a data frame into groups of observations, apply a summary statistics for each group, and then combine the results.
- *Joining* tables by a common variable.
- Learning how to pivot from wide to long data (and the other way around) with *pivot_longer* and *pivot_wider*.


<br><br>

<ins>*ANOVAs in R: A complete guide*</ins>

*What*: Analysis of Variance (ANOVA) is a family of statistical tests that are useful when comparing several sets of scores. A common application of ANOVA is to test if the means of three or more groups are equal. The basic idea behind ANOVA is a comparison of the variance between the groups and the variance within the groups.

*Why*: A key statistical test in research fields including biology, economics and psychology, is the analysis of variance (ANOVA). However thez are not taught in most Bachelor curriculum (and is not even taught in the Master of Neuroscience).

Learning Objectives:

- Linear regression reminder
- The different ANOVA tests (One-way, Two-way, Repeated Measures)
- Interactions between variables and covariates
- Finding the best-fit model
- Checking your assumptions
- Post-hoc test
- Plot results
- Report the results


<br><br>


<ins>*Multilevel Modeling in R*</ins>

*What*: The general aim of multilevel modeling is to simultaneously analyze data at a lower level (usually participants) and at a higher level (usually clusters of participants). In other words, multilevel modeling enables one to disentangle the effects of lower-level variables (e.g., individual effects) from the effects of higher-level variables (e.g., contextual effects) and examine how lower-level and higher-level variables interact with one another (interactions involving variables at different levels are called ‘cross-level interactions’).

*Why*: Traditional multiple regression techniques treat the units of analysis as independent observations. One consequence of failing to recognise hierarchical structures is that standard errors of regression coefficients *will be underestimated*, leading to an overstatement of statistical significance. Moreover, in a multilevel model the groups in the sample are treated as a random sample from a population of groups. Using a fixed effects model, inferences cannot be made beyond the groups in the sample.

Learning Objectives:

- Learn the 3 key principles of two-level linear modeling (two levels mean two types of residuals, predictors, and level-1 effect parameters).
- Follow a ready-to-use three-step procedure for conducting two-level linear modeling using R.
- Interpret the results and check the assumptions.
- Addressing multilevel modeling issues pertaining to statistical power, effect sizes, complex design, and nonlinear regression.
- Differences between repeated measure ANOVAs and MLM.


<br><br>


<ins>*Bayesian in R*</ins>

*What*: The frequentist approach assigns probabilities to data, not to hypotheses, whereas the Bayesian approach assigns probabilities to hypotheses. Furthermore, Bayesian models incorporate prior knowledge into the analysis, updating hypotheses probabilities as more data become available.

Interpretation of the frequentist 95% confidence interval: we can be 95% confident that the true (unknown) estimate would lie within the lower and upper limits of the interval, *based on hypothesized repeats of the experiment*. Many researchers oversimplify the interpretation of the frequentist 95% confidence interval by dichotomizing it in statistically significant or non-statistically significant.

Interpretation of the Bayesian 95% confidence interval (which is known as *credible interval*): there is a 95% probability that the true (unknown) estimate would lie within the interval, *given the evidence provided by the observed data*.

*Why*: Bayesian statistics has been neglected over the years. However, it provides a more intuitive interpretation of results. The outcome of a Bayesian model is *a posterior distribution*. This describes the joint uncertainty in all the parameters you are trying to estimate. This can be used to *describe uncertainty* in a prediction for some new input data. By comparison, alternative (frequentist) methods typically describes uncertainty in predictions using confidence intervals, which are widely used but easy to misinterpret.

Learning Objectives:

- Whats is a probability
- Bayesian analysis VS Null Hypothesis Significance Testing
- What is a prior, a posterior, a credible interval
- What a sampling distribution is good for
- Bayesian model comparison: Baye's Factor
- Bayesian Approaches to Testing a Point (“Null”) Hypothesis
- Full on Bayesian analysis in R with {brms}


<br><br>


## R Lunches

The idea behind this lunches is to make available all the ressources we have gathered/created over the years make other people’s life easier.

Another purpose is to create a network of people interested in Data Science and a place for them to find information about it, so really feel free to ask for new stuff and comment on what is not working for you.

Moreover, if you are interested in the project don’t hesitate to participate !

Tuesday (12pm-13pm), 28 February 2023, UniMail TBD [Zoom link (soon)](https://we-data-ch.github.io/workshops/XXX)
<ins>*Using vim with R*</ins> - Fabrice Hategekimana (University of Geneva)

Tuesday (12pm-13pm), 7 March 2023, UniMail M3220 [Zoom link (soon)](https://we-data-ch.github.io/workshops/XXX)
<ins>*Beautiful, easy-to-use, highly interactive data visualization with R: Leveraging Apache ECharts*</ins> - Jean Philippe Coene (Opifex)

Tuesday (12pm-13pm), 4 April 2023, UniMail M3220 [Zoom link (soon)](https://we-data-ch.github.io/workshops/XXX)
<ins>*Learn to host your RMarkdown reports and Shiny application for free on the web with R and GitHub or AWS*</ins> - David Munoz Tord (We Data)

Tuesday (12pm-13pm), 4 May 2023, Zoom [Zoom link (soon)](https://we-data-ch.github.io/workshops/XXX)
<ins>*Unravelling the port of Lists in R: The creations of the CORESIDENCE Database*</ins> - Juan Galeano
(Barcelona Center for Demographic Studies)

Tuesday (12pm-13pm), 4 May 2023, UniMail M4050 [Zoom link (soon)](https://we-data-ch.github.io/workshops/XXX)
<ins>*{[hayalbaz](https://github.com/rundel/hayalbaz)}: Scrapping dynamic web page without dependencies in R*</ins> - Vestin Hategekimana (University of Geneva)


<br><br>

## Other ressources that I put available

Useful tutorials for data science in R, Pyhton and MATLAB: [here](https://munoztd0.github.io/Hitchhikers_guide_to_the_brain/links)

Other miscellaneous tutorials and slides about stats (bayesian and frequentist), machine learning (AI, Reinforcement learning, computational modeling), MRI (technicalities and analysis), onlines studies (pros and cons about different recruitment platforms and online experiment builders), Linux/server stuff, more data science/visualization stuff can be found [here](https://github.com/munoztd0/Hitchhikers_guide_to_the_brain/tree/gh-pages/tutos).
