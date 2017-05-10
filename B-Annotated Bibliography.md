### Theoretical

[Operationalizing](https://litlab.stanford.edu/LiteraryLabPamphlet6.pdf), Franco Moretti

Whether and how to use computational methods toward humanistic, interpretive problems is not immediately obvious. After all, many of our most closely held problems seem native to close reading. In this article, Moretti lays out a framework for re-thinking literary theoretical concepts in terms of measurment. He then uses this to explore several previous theorizations of literary "character," offering a different measurement for each -- and leveraging his findings against Hegel!


### Discriminating Words

[Fightin’ Words: Lexical Feature Selection and Evaluation for Identifying the Content of Political Conflict](http://languagelog.ldc.upenn.edu/myl/Monroe.pdf), Burt Monroe, Michael Colaresi, Kevin Quinn

Abstract: Entries in the burgeoning "text-as-data" movement are often accompanied by lists or visualizations of how word (or other lexical feature) usage differs across some pair or set of documents. These are intended either to establish some target semantic concept (like the content of partisan frames) to estimate word-specific measures that feed forward into another analysis (like locating parties in ideological space) or both. We discuss a variety of techniques for selecting words that capture partisan, or other, differences in political speech and for evaluating the relative importance of those words. We introduce and emphasize several new approaches based on Bayesian shrinkage and regularization. We illustrate the relative utility of these approaches with analyses of partisan, gender, and distributive speech in the U.S. Senate. 

[Comparing Corpuses by Word Use](http://sappingattention.blogspot.com/2011/10/comparing-corpuses-by-word-use.html), Benjamin M. Schmidt

When we want to determine whether a word is more distinctive of a one text versus another, there are two basic approaches: addition and multiplication. If a word appears in Text A twice and Text B ten times, do we care that it appears eight times more in Text B (ie measure by addition) or five times more frequently (ie measure by multiplication)? Schmidt visually explores the implications of each approach and then shows how Dunning's Log-Likelihood statistic marries these two approaches. See [response by Ted Underwood](http://tedunderwood.com/2011/11/09/identifying-the-terms-that-characterize-an-author-or-genre-why-dunnings-may-not-be-the-best-method/), experimenting with Mann-Whitney rank test as an alternative.

[Prizewinners Vs. Bestsellers](http://txtlab.org/?p=494), Eva Portelance

The publishing industry regularly draws a distinction among  books along familiar lines: the kind of book that wins praise (“literary fiction”) and the kind that sells (“commercial fiction”). Portelance asks whether there might be a difference in the content of these books – whether their authors have categorically “different intuitions on language” – and uses discriminating words to explore that possibility. Many of the intuitions in this blog post were folded into [this article](http://post45.research.yale.edu/2016/05/how-cultural-capital-works-prizewinning-novels-bestsellers-and-the-time-of-reading/).

[The Geographic Imagination of Civil-War Era American Fiction](http://alh.oxfordjournals.org/content/25/4/803.extract), Matthew Wilkens

The American Civil War is understood as a turning point in the country's history and cultural production, and literary histories of the period are often geographically inflected. The period before the war is often characterized by the American Rensaissance which took place primarily in New England and the period after by a flourishing of regionalism, reaching into the West and South. Wilkens tests these ideas by observing the frequencies of place names in American novels before and after the war. In turn, his finding challenge the prevailing wisdom and raise new questions about literary imagination and the geographic distribution of its readership. Methodologically, he tweaks the Dunning discriminating word method in order to find discriminating geography.

### Dictionary Methods & Sentiment Analysis

[A Novel Method for Detecting Plot](http://www.matthewjockers.net/2014/06/05/a-novel-method-for-detecting-plot/), Matt Jockers

Drawing inspiration from Kurt Vonnegut's theory of narrative, this is the first of several blog posts in which Jockers describes a principle that measuring emotional valence over the course of a novel can account for elements of plot. Later posts suggest the possibility that, based on this kind of accounting, there are just a handful of basic plot arcs. He has also released an R package – [syuzhet](https://cran.r-project.org/web/packages/syuzhet/index.html) – that automates this process.


### Supervised Classification

[Literary Pattern Recognition](https://lucian.uchicago.edu/blogs/literarynetworks/files/2015/12/LONG_SO_CI.pdf), Hoyt Long, Richard So

The Orientalist adoption of the haiku was an important marker of literary prestige in American Modernist poetry. By training a computer to recognize haiku vs non-haiku poetry, Long and So trace the genre's dissemination across the literary field over the course of a decade. In particular, they focus on instances when the computer "mistakes" non-haiku for haiku as a strategy for finding underlying patterns.

[How Quickly Do Literary Standards Change?](https://tedunderwood.com/2015/05/18/how-quickly-do-literary-standards-change/), Ted Underwood, Jordan Sellers

 In the study of literary history, there is an open question regarding the extent of the “great divide” between something like an elite versus a mainstream literature. Underwood and Sellers tried to answer one version of this question by seeing whether there were differences between books of poetry that were reviewed in prominent literary periodicals versus those that were not. In fact, this turned out to be the case, but even more compelling was a trend over the course of the nineteenth century, in which literature overall – both elite and mainstream –  tended to look more and more like the kinds of books that got reviews earlier in the century. 

### Topic Modeling

[Of Monsters, Men -- and Topic Modeling](http://opinionator.blogs.nytimes.com/2011/05/29/of-monsters-men-and-topic-modeling/), Robert K. Nelson

Robert K. Nelson's project [Mining the Dispatch](http://dsl.richmond.edu/dispatch/pages/intro) topic models articles from the <i>Richmond Daily Dispatch</i>, the paper of record of the Confederacy, over the course of the American Civil War. Following two topics that seem to rise and fall in tandem, Anti-Northern Diatribes and Poetry and Patriotism, Nelson identifies them as two sides of the same coin in the war effort. Taken together, they not only reveal how the Confederacy understood itself in relation to the war, but the simultaneous spikes and drops of these topics offer what he refers to as “a cardiogram of the Confederate nation.”

[Topic Modeling and Figurative Language](journalofdigitalhumanities.org/2-1/topic-modeling-and-figurative-language-by-lisa-m-rhody/), Lisa M. Rhody

The explicit objective of LDA is to identify words that cluster together in some meaningful way, yet it is unable to tell us what that meaning is. This poses a problem for literature in which techniques like irony and metaphor can distance a word from its dictionary meanings in unexpected ways. Rhody examines topics assigned to a particular poem, giving special attention to one with a deeply ambiguous relationship among its terms.

[The fictionality of topic modeling](http://bds.sagepub.com/content/spbds/2/2/2053951715610591.full.pdf), Rachel Sagner Buurma

Buurma has framed topic modeling as a tool that can productively defamiliarize a text and uses this to explore novelistic genre. Taking Anthony Trollope's six Barsetshire novels as her object of study, Buurma suggests that we should read the series not as a formal totality – as we might do for a novel with a single, omniscient narrator – but in terms of its partial and uneven nature. The prominence of particular topics across disparate chapters offer alternate traversals through the books and across the series.

[Topic Modeling Made Just Simple Enough](https://tedunderwood.com/2012/04/07/topic-modeling-made-just-simple-enough/), Ted Underwood

Abstract: "Right now, humanists often have to take topic modeling on faith. There are several good posts out there that introduce the principle of the thing (by Matt Jockers, for instance, and Scott Weingart). But it’s a long step up from those posts to the computer-science articles that explain “Latent Dirichlet Allocation” mathematically. My goal in this post is to provide a bridge between those two levels of difficulty."

### Stylistics

"The Poet Alone." <i>Becoming a Poet in Anglo-Saxon England</i>. Cambridge University Press: New York. 2014. Emily Thornbury.

Despite appearing in manuscript as a single poem, the Anglo-Saxon "Christ and Satan" is understood to have been written by different poets under different social circumstances. Thornbury develops what she calls an "ad hoc stylometry" in order to identify sections belonging to each poet. By using a novel measure of sound distribution across alliteration -- the formal structure of Anglo-Saxon poetry -- she identifies narrative elements that were written into the text at a later point in time. In turn, Thornbury interprets them for their commentary on the later poet's relationship to the existing poem and the circumstances of writing.

### Critique

[Where Is Cultural Criticism in the Digital Humanities?](http://dhdebates.gc.cuny.edu/debates/text/20), Alan Liu

Liu observes that, as of writing in 2011, digital humanistic inquiry had largely been "oblivious" to the cultural critique that characterizes much of mainstream humanities discourse. However, he does not believe that this is a necessary condition of the digital humanities and suggests strategies by which the field can become a "full partner of the humanities." These include its unique position to advocate for institutional support for the humanities from the public via online visibility.

[Designing for Difference](http://differences.dukejournals.org/content/25/1/177.abstract), Tara McPherson

McPherson takes seriously the charge that computational methods and critical theory may be incommensurable. In particular, she observes the practical difficulty of simultaneously building workflows in code -- the bread and butter of the digital humanities -- while activating the insights of code studies -- a subset of new media critique. McPherson sees a resolution to this impasse by building tools from the ground up that reflect feminist commitments, including ontological challenges to database hierarchy and democratizing spaces of reader interaction with texts.

### Sample Corpora

[Demonstration Corpora](http://dhresourcesforprojectbuilding.pbworks.com/w/page/69244469/Data%20Collections%20and%20Datasets#demo-corpora), Alan Liu

From the website: "Demo corpora are sample or toy collections of texts that are ready-to-go for demonstration purposes or hands-on tutorials--e.g., for teaching text analysis, topic modeling, etc.  Ideal collections for this purpose are public domain or open access, plain-text, relatively modest in number of files, organized neatly in a folder(s), and downloadable as a zip file. (Contributions welcome: if you have demo collections you have created, please email ayliu@english.ucsb.edu.)"
