# Methodology
In this section we describe the process of our literature review.
First we identified a few papers that we used to seed our review.
Secondly, we used those papers to compile a list of potentially relevant papers.
We then used a set of relevancy rules to determine if those papers were relevant or not.
Throughout this process we identified a few papers as *key papers* that were indispensible in our review.
After reviewing all papers we performed a *repertory grid analysis* to help us reason about our review as a whole.
The end result are important distinctions between game development and traditional software development.


## Step 1: Determining Seed Papers
Initially our search was to review literature around the frustrations of developers caused by development environments such as Eclipse, with the intention of comparing game development environments to traditional software development environments.
We used two papers we were very familiar with: one by Murphy-Hill et al. on differences between game development and traditional software development and a second by Ko et al. on the learning barriers encountered in development. 
We shifted our focus to be more general and to review literature around game development and how it differs from traditional software development.
As a result of this focus change, we replaced the seed paper on learning barriers with a magazine article by Blow. Blow's article gave us insight into what it meant to be a game developer.
We then compiled all references from these two papers into a list of potentially relevant papers.


## Step 2: Determining Relevant Papers
We took this list of potentially relevant papers and determine which were relevant based on a set of rules we developed.
If the paper met all of the below rules then we classified it as relevant and added it to our GitHub repository.

### Relevancy Rules
1. Does the paper discuss the development process?
2. Does the paper discuss game development?
3. Does the paper discuss some form of the challenges or stress encountered by developers?
4. Does the paper provide results of some form?


## Step 3: Extracting Dimensions
Our goal is to determine what each paper is about and then compare the papers to each other.
In order to do this we extracted a *dimension* from every paper.

### Reading Abstracts
After we compiled a list of relevant papers, we read through all of the abstracts, took some notes, and added them to our GitHub repository.
On some of them, we were able to extract a dimension from just the abstract, and if so, we noted that dimension in the repository.

### Reading in Depth
If we could not extract a dimension from just the abstract, or if the paper seemed especially useful, we marked it for in depth reading. 

#### Similar Dimensions
If we extracted a dimension we had already extracted from another paper, we attempted to find another useful dimension of the paper. If no other dimension could be extracted, we considered that paper to have no significant extra contribution that was relevant to our review and we marked the paper as a dead end. 


## Step 4: Defining Key Articles
In addition to the original two seed articles, we discovered two more articles to be immensely helpful in our review. We marked all four articles as key articles for future use.

The key articles were:

1. Cowboys, Ankle Sprains, and Keepers of Quality: How Is Video Game Development Different from Software Development?
2. Game Development: Harder Than You Think
3. The 'Console Ship is Sinking' and What this Means for Indies
4. International Game Developers Association. (2004). Quality of life white paper

### Reviewing References
We had reviewed all references of the first two key articles at the beginning of our review. When we encountered the third article we restarted from Step 1. We reviewed all references and added them to a list of potentially relevant papers. We then continued to Step 2 to determine which papers were relevant and then to Step 3 where we extracted dimensions.

The fourth article was a white paper that did not have a list of references and thus we did not cycle our process on this article.

At the end of this process we had a list of dimensions that differentiated the papers from each other.


## Determining Refining Process
### GitHub Issue Labels
We set up a flow of issue labels so we could easily identify what state each paper was in.

Our original process was:

1. Relevant Paper
2. Summarize
3. Adds Dimension
4. Dimesion added to grid

We started papers in step 0 and changed the labels as we made progress on each paper.  We decided that some papers were no longer useful at various stages of the process.  Whenever this happened, we marked that paper with our *Dead End* label and no longer considered it. Some papers might have been useful but for various reasons such as length or verbosity were hard to extract useful dimensions from.  We marked these papers with an *If time* label.  After processing all of our other papers we decided to change all papers with the 'If time' label to the 'Dead End' label since they would have taken a lot of time and not returned much value.

Partway through our review we realized we needed another label before all the others for papers that had been added to the repo but we weren't sure if they were relevant or not. So we added a Step 0: Determine if relevant.

Thus our full process was:

0. Determine if relevant
1. Relevant Paper
2. Summarize
3. Adds Dimension
4. Dimesion added to grid

We also created labels for 'Grid' and 'Writing' but did not define specific processes for them as we felt they generated more overhead then they provided value for the short time we needed them.

### Adding Dimension to Grid
At this point, each paper was listed in the repository complete with notes and the dimensions extracted from it. We considered a paper's dimensions and the dimensions that were already on the grid. If that dimension was not already on the grid then we added it to the grid. If the dimension was already present then skipped it and moved on to the next one.

To add the dimension to the grid we had to rate each paper on that dimension.
For instance, one dimension was 'developer motivation'. We would take each paper and rate it on a score of 1-5 to correspond to a spectrum along that dimension. So rating that paper with a 1 meant that that paper talked about low developer motivation and rating another paper with a 5 meant that it talked about high developer motivation.

Ideally, a 3 would indicate that the paper did talk about that dimension but did not take a side on it. However, the tool we used to create the grid did not support marking certain ratings as not applicable and thus a 3 could either mean the paper was neutral on that dimension or it could mean that this dimesion does not apply to this paper.

### Merging Dimensions on the Grid
We started off with a lot of dimensions after reviewing all papers. Once all dimensions had been added to the grid we realized that some had the same meaning but different names.  We also realized that some dimensions simply weren't as relevant as we originally thought and thus we merged them with other dimensions or eliminated them. After the merge we realized that there were other dimensions that could be encapsulated in an abstracted idea.  For instance, 'job stability', 'job turnover', and 'crunch' were all merged into the more general 'quality of life'.

#### Dimensions - Round 1
Here are our list of original dimensions:

* agile process vs waterfall process
* process vs no process
* entertainment vs solves problem
* developer interaction with other developers
* creative vs constructive
* unit tests vs system tests
* creativity vs features
* user challenge
* user emotion
* user fun
* multi-disciplined teams vs single-discipled teams
* user engagement
* documentation
* team composition
* organizational hierarchy
* indie developer studios vs AAA studios
* user impact
* testing
* crunch
* social interaction
* company size
* case study vs empirical data
* indies vs publisher
* funding
* medium games vs large games
* job stability
* job turnover
* work ownership

#### Dimensions - Round 2
After merging, we resulted in the following list of dimensions:

* requirement volatility
* user interactions
* testing
* Developer motivation
* creative vs constructive
* team composition
* funding
* crunch
* job stability
* turnover
* work ownership
* size

#### Dimensions - Round 3
After combining from the previous round we actually found that two of our papers had the exact same ratings on the grid. This means that they didn't contain any unique dimensions captured in our grid and so we removed one paper from the grid. This paper was Product Development in Japanese TV Game Software [cite]. We again tried to capture the more general ideas behind the dimensions now that we had fewer to look at and were able to reduce down to the following list:

* autonomy from funding
* developer motivation
* requirement volatility
* team composition
* testing
* creative vs constructive
* quality of life

### Ranking Dimensions
The next step was to see if any dimensions were more important than other dimensions.  At the general level we started by pulling out the most important dimension. Then we chose the next important and the third most important. Left with four dimensions, we were unable to determine if one was more important than the others so we instead reversed and chose the one that was least important. We continued choosing the least important dimension until we had an ordered list of dimensions by their importance.

## Repertory Grid Tool
We used a website called 'Repertory Grid Tool' (http://repertorygridtool.com/) to create our grid and run analysis on it. We considered creating the grid in Microsoft Excel but realized that the website did all of the analysis for us and so we put all of our work into the website. 

However, the website was limiting in some aspects. As already mentioned, the website did not allow us to mark specific intersections of a dimension and paper as not applicable. Additionally, the website only displayed about 15 characters in each cell of the grid, which is insufficient for both long paper titles and long dimension names.  Limitations aside, the website saved us a lot of time in generating the analysis of the grid.

We used the website to automatically compute cluster analysis to determine similarity amongst the dimensions as well as similarity of the papers. As mentioned previously, this analysis helped us to determine if a paper added unique value to our review. It also showed us which papers were most similar to each other (in clusters). This would be useful to someone new to the field of game development as they could simplly read one paper from each cluster and get a broad understanding of the field without doing an extensive literature review.