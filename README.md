# 2018-03-16 talk "Rethinking Statistical Significance"

Thomas E. Love, Ph.D., Email: `Thomas dot Love at case dot edu`

- Professor of Medicine, Population & Quantitative Health Sciences, Case Western Reserve University
- Director of Biostatistics and Evaluation, [Center for Health Care Research and Policy](http://chrp.org/)
- Chief Data Scientist, [Better Health Partnership](http://betterhealthpartnership.org/)
- `@ThomasELove` and `THOMASELOVE` on Github

# The Slides from Today's Talk

The slides are available [in PDF](https://github.com/THOMASELOVE/rethink/blob/master/Love_2018-03-16.pdf) and were built using [R Markdown](https://raw.githubusercontent.com/THOMASELOVE/rethink/master/Love_2018-03-16.Rmd).

## What I Used to Teach Gladly, and am Trying to Quit Doing

- Null hypothesis significance testing is here to stay.
    - Learn how to present your p value so it looks like what everyone else does
    - Think about "statistically detectable" rather than "statistically significant"
    - Don't accept a null hypothesis, just retain it.
- Use point and interval estimates
    - Try to get your statements about confidence intervals right (right = just like I said it)
- Use Bayesian approaches when they seem appropriate
    - But look elsewhere for people to teach/do that stuff
- Use simulation to help you understand non-standard designs
    - But, again, look elsewhere for examples
- Power is basically a hurdle to overcome in a grant application
    - Retrospective power calculations are a waste of time and effort
    
## What I Think I Think Now

- Null hypothesis significance testing is much harder than I thought.
    - The null hypothesis is almost never a real thing.
    - Rather than rejiggering the cutoff, I would mostly abandon the *p* value as a summary
    - Replication is far more useful than I thought it was.
- Some hills aren't worth dying on.
    - Think about uncertainty intervals more than confidence or credible intervals
    - Retrospective calculations about Type S (sign) and Type M (magnitude) errors can help me illustrate ideas.
- Which method to use is far less important than finding better data
    - The biggest mistake I make regularly is throwing away useful data
    - I'm not the only one with this problem.
- The best thing I do most days is communicate more clearly.
    - When stuck in a design, I think about how to get better data.
    - When stuck in an analysis, I try to turn a table into a graph.
- I have A LOT to learn.

# Sources of Material in the Talk

- [The ASA's Statement on p-Values: Context, Process, and Purpose](https://amstat.tandfonline.com/doi/full/10.1080/00031305.2016.1154108?scroll=top&needAccess=true#.Wqqvlej4-Uk). ASA = American Statistical Association
    - Full Citation: Ronald L. Wasserstein & Nicole A. Lazar (2016) The ASA's Statement on p-Values: Context, Process, and Purpose, *The American Statistician*, 70:2, 129-133, DOI: 10.1080/00031305.2016.1154108
    - The paper begins with a presentation of George Cobb's argument about why *p* values deserve re-evaluation.
    - The many supplemental materials can be found at [this link](https://www.tandfonline.com/doi/suppl/10.1080/00031305.2016.1154108?scroll=top). 
- Benjamin D et al. (2017) [Redefine Statistical Significance](https://psyarxiv.com/mky9j/)
    - [It will be much harder to call findings "significant" if this team gets its way](http://www.sciencemag.org/news/2017/07/it-will-be-much-harder-call-new-findings-significant-if-team-gets-its-way) in *Science* by Kelly Servick
    - Lakens D et al. [Justify Your Alpha: A Response to "Redefine Statistical Significance"](https://psyarxiv.com/9s3y6)
    - McShane Bradley B., Gal, David et al. [Abandon Statistical Significance](http://www.stat.columbia.edu/~gelman/research/unpublished/abandon.pdf)
- "[The Value of a *p*-valueless Paper](https://www.nature.com/ajg/journal/v99/n9/pdf/ajg2004321a.pdf?origin=ppub&foxtrotcallback=true)" by Jason T. Connor, *Amer J Gastroenterology* 2004, 99(9): 1638-1640.
- Andrew Gelman (2013) [Too good to be true](http://www.slate.com/articles/health_and_science/science/2013/07/statistics_and_psychology_multiple_comparisons_give_spurious_results.html) *Slate* July 24. Subtitle: Statistics may say that women wear red when they’re fertile... but you can't always trust statistics.
- Andrew Gelman and John Carlin [Beyond Power Calculations: Assessing Type S (Sign) and Type M (Magnitude) Errors](http://www.stat.columbia.edu/~gelman/research/published/retropower_final.pdf) *Psychological Science* 2014, 9(6): 641-651.
- Andrew Gelman and Eric Loken (2013) [The garden of forking paths](http://www.stat.columbia.edu/~gelman/research/unpublished/p_hacking.pdf): Why multiple comparisons can be a problem, even when there is no "fishing expedition" or "p-hacking" and the research hypothesis was posited ahead of time.
- Andrew Gelman and David Weakliem [Of Beauty, Sex and Power](http://www.stat.columbia.edu/~gelman/research/published/power5r.pdf) *American Scientist* 97, 310-316.
- "[Why Most Published Research Findings Are False](http://journals.plos.org/plosmedicine/article?id=10.1371/journal.pmed.0020124)" by John P. A. Ioannidis, *PLOS Medicine* August 2005: https://doi.org/10.1371/journal.pmed.0020124
- Kass RE et al. (2016) [Ten Simple Rules for Effective Statistical Practice](http://journals.plos.org/ploscompbiol/article?id=10.1371/journal.pcbi.1004961)
- [Understanding the Role of P Values and Hypothesis Tests in Clinical Research](https://jamanetwork.com/journals/jamacardiology/fullarticle/2566171) by Daniel B. Mark, Kerry L. Lee and Frank E. Harrell Jr. (December 2016) *JAMA Cardiology* 1(9):1048-1054. doi:10.1001/jamacardio.2016.3312
- Simmons JP et al. (2011) [False-Positive Psychology: Undisclosed Flexibility in Data Collection and Analysis Allows Presenting Anything as Significant](http://journals.sagepub.com/doi/abs/10.1177/0956797611417632) *Psychological Science* 22(11): 1359-1366. 
- [Do Not Over (*P*) Value Your Research Article](https://jamanetwork.com/journals/jamacardiology/fullarticle/2566166) by Laine E. Thomas, Michael J. Pencina (December 2016) editorial in *JAMA Cardiology*  1(9): 1055. doi:10.1001/jamacardio.2016.3827

### From FiveThirtyEight.com

- ["Not Even Scientists Can Easily Explain p Values" article and video](http://fivethirtyeight.com/features/not-even-scientists-can-easily-explain-p-values/) by Christie Aschwanden
- ["Statisticians Found One Thing They Can Agree On: It’s Time To Stop Misusing P-Values"](http://fivethirtyeight.com/features/statisticians-found-one-thing-they-can-agree-on-its-time-to-stop-misusing-p-values/) discussion of the American Statistical Association's 2016 Statement on P values, by Christie Aschwanden.
- [Science isn't broken](https://fivethirtyeight.com/features/science-isnt-broken) by Christie Aschwanden, with p-hacking graphic by Ritchie King
- [Finally, A Formula for Decoding Health News](https://fivethirtyeight.com/features/a-formula-for-decoding-health-news/) by Jeff Leek

### Nature.com

- [Psychology journal bans P values](http://www.nature.com/news/psychology-journal-bans-p-values-1.17001) on the banning of null hypothesis significance testing by *Basic and Applied Psychology*, by Chris Woolston, 2015-03-09.
- [Scientific method: Statistical errors](https://www.nature.com/news/scientific-method-statistical-errors-1.14700) column on *p* values by Regina Nuzzo, 2014-02-12. "the P value, which is neither as reliable nor as objective as most scientists assume"

### NOVA

- [Rethinking Science's Magic Number](http://www.pbs.org/wgbh/nova/next/body/rethinking-sciences-magic-number/) from Tiffany Dill at NOVA Next. 2018-02-28.
- NOVA Season 45 Episode 6 [Prediction by the Numbers](http://www.pbs.org/video/prediction-by-the-numbers-hg2znc/) 2018-02-28.

### Andrew Gelman's blog "Statistical Modeling, Causal Inference, and Social Science"

- "[Instead of 'confidence interval,' let’s say 'uncertainty interval'](http://andrewgelman.com/2010/12/21/lets_say_uncert/)" 2010-12-21
- "[Researcher Degrees of Freedom](http://andrewgelman.com/2012/11/01/researcher-degrees-of-freedom/)" 2012-11-01
- "[How can statisticians help psychologists do their research better?](http://andrewgelman.com/2013/05/17/how-can-statisticians-help-psychologists-do-their-research-better/)" 2013-05-17
- "[The Fallacy of Placing Confidence in Confidence Intervals](http://andrewgelman.com/2014/12/11/fallacy-placing-confidence-confidence-intervals/)" 2014-12-11
- "[The feather, the bathroom scale, and the kangaroo](http://andrewgelman.com/2015/04/21/feather-bathroom-scale-kangaroo/)" 2015-04-21
- "[Statistics is like basketball or knitting](http://andrewgelman.com/2016/03/11/statistics-is-like-basketball-or-knitting/)" 2016-03-11.
- "[More on my paper with John Carlin on Type M and Type S errors](http://andrewgelman.com/2016/11/13/more-on-my-paper-with-john-carlin-on-type-m-and-type-s-errors/)" 2016-10-13.
- "[Marginally Significant Effects as Evidence for Hypotheses: Changing Attitudes Over Four Decades](http://andrewgelman.com/2016/10/15/marginally-significant-effects-as-evidence-for-hypotheses-changing-attitudes-over-four-decades/)" 2016-10-15.
- "[How not to analyze noisy data: A case study](http://andrewgelman.com/2016/10/25/how-not-to-analyze-noisy-data-a-case-study/)" 2016-10-25.
- "[Abandon statistical significance](http://andrewgelman.com/2017/09/26/abandon-statistical-significance/)" 2017-09-26
- "[My favorite definition of statistical significance](http://andrewgelman.com/2017/10/28/favorite-definition-statistical-significance/)" 2017-10-28.
 
### From Jeff Leek, and Simply Statistics

- [A few things that would reduce stress around reproducibility/replicability in science](https://simplystatistics.org/2017/11/21/rr-sress/) by Jeff Leek at Simply Statistics, 2017-11-21.
- Jeff Leek's books on LeanPub:
    - [How To Be a Modern Scientist](https://leanpub.com/modernscientist)
    - [The Elements of Data Analytic Style](https://leanpub.com/datastyle)
- Jeff Leek's [tidypvals package in R, on GitHub](https://github.com/jtleek/tidypvals)
- [Sad *p* value bear meme](https://simplystatistics.org/2013/08/26/statistics-meme-sad-p-value-bear/) discussion from Jeff Leek at Simply Statistics

### On Reproducible Research
- Karl Broman has all kinds of great stuff, including the "I'm really sorry you did all the work" slide in [this talk](https://www.biostat.wisc.edu/~kbroman/presentations/repro_research_UMass2016.pdf) 
 - Karl Broman's [Initial Steps Towards Reproducible Research](http://kbroman.org/steps2rr/) page
 - Harrell FE Scott T (2012) [Reproducible Research Tutorial](http://biostat.mc.vanderbilt.edu/wiki/pub/Main/ReproducibleResearchTutorial/HarrellScottTutorial-useR2012.pdf)
 - Donoho DL (2010) [An invitation to reproducible computational research](https://academic.oup.com/biostatistics/article/11/3/385/257703)

### Cartoons

- XKCD cartoons include:
    - [ISO 8601 (Public Service Announcement)](https://xkcd.com/1179/)
    - [Significant (Green Jelly Beans)](https://xkcd.com/882/)

### Tweets

- Jenny Bryan [Why is this the hill that statisticians choose to die on?](https://twitter.com/JennyBryan/status/946433827076939776)
- Jenny Bryan [Decision making under uncertainty struggles](https://twitter.com/JennyBryan/status/94644114851556)
- J. P. de Ruiter [Specific null, arbitrary alternative...](https://twitter.com/JPdeRuiter/status/963481008417988609)
- Michael Donohoe [Comprehensive map of all countries in the world that use the MMDDYYYY format](https://twitter.com/donohoe/status/597876118688026624)
- Joran Elias [A confidence interval is ...](https://twitter.com/joranelias/status/973662113657843712)
- Frank Harrell [It's important to get this right](https://twitter.com/f2harrell/status/946437578391216129)
- John Holbein [Nothing screams GRADUATE STUDENT ...](https://twitter.com/JohnHolbein1/status/967815244574703616)
- Jeff Leek [2.5 million p values](https://twitter.com/jtleek/status/890180014733492225)
- Thomas Leeper [An interval drawn such that ...](https://twitter.com/thosjleeper/status/973664676897837057)
- Michael Lopez [analyzes some of those p values](https://twitter.com/StatsbyLopez/status/890230164042469376)
- Chelsea Pelleriti [What's your 280 character definition of a confidence interval?](https://twitter.com/ChelseaParlett/status/973657698536366080)
- Randy Sweis [p value of 0.06 trending...](https://twitter.com/RandySweisMD/status/951828002807132160)
- Sean J. Taylor, Facebook Core Statistics Team
    - [If OLS doesn't work, get better data](https://twitter.com/seanjtaylor/status/967940381831716864) 
    - [Often a better ROI for improving data](https://twitter.com/seanjtaylor/status/968145837976051712) 
    - [Training on methods vs. finding/making/designing better data](https://twitter.com/seanjtaylor/status/968147593845813250)
