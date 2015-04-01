Title
===

# Goals
Game development shares some of the same things as traditional software engineering but also differs in several ways [4]. For example, Murphy-Hill et al. [4] showed that tension "between creative desires and technical constraints" is much more prevalent in games development than traditional software. 

We wanted to find out what other frustrations game developers experience. Additionally, we wanted to find out if and how game developer frustrations differ from the frustrations of traditional software developers. We also wanted to see how these frustrations stunt productivity. Our final goal was to see what is being done to mitigate these frustrations.

In order to accomplish these goals, we conducted a literature review. After performing our literature review, we present our findings in this paper. Our findings are presented in the form of a repertory grid analysis as demonstrated by Menzies et al. [5]. Such an analysis allows us to concisely convey the differences we found between game developers and software developers.


# Background

## Motivation
Both authors have an interest in these fields and wanted to gain a better understanding of the this area. There are some papers (notably [4]) which provide differences between game developers and traditional software developers, but that work lacks research on the qualitative lifestyle of each. Both authors wanted to understand where future effort could be best applied for games research and desired to contribute this to the research community.

## Literature Review
Before starting our review, we reviewed literature on how to set up a literature review. One such resource by Hall et al. [1] was very valuable to us in this regard.  Hall had defined research questions *before* starting the review which allowed them to be very structured in their review. Hall showed us how to start with a large number of papers and cut that number down to a reasonable number to review.

## Repertory Grid Analysis
Before starting our review, we were encouraged to conduct a repertory grid analysis to communicate our results. Thus we reviewed literature on how to conduct such an analysis. Menzies et al. [5] have published work that includes a repertory grid analysis and was very helpful in our review. Menzies used the repertory grid to distinguish certain characteristics, or dimension, about an idea. A new row of dimensions is only added if it helps distinguish differences of that idea. Each row is identified by a dimension and has a description for each end of the spectrum. One end of the spectrum is low and the other end is high. Each paper should be rated for each dimension on the spectrum from low to high. Additionally, each row is weighted such that more important differences can be appropriately factored into the analysis. The final grid allows conclusions to be made about the differences between the reviewed papers.

# Methodology
In this section we describe the process of our literature review. First we identified a few papers that we used to seed our review. Secondly, we used those papers to compile a list of potentially relevant papers. We then used a set of relevancy rules to determine if those papers were relevant or not. Throughout this process we identified a few papers as *key papers* that were indispensible in our review. After reviewing all papers we performed a *repertory grid analysis* to help us reason about our review as a whole.
The end result are important distinctions between game development and traditional software development.


## Step 1: Determining Seed Papers
Initially our search was to review literature around the frustrations of developers caused by development environments such as Eclipse, with the intention of comparing game development environments to traditional software development environments. We used two papers we were very familiar with: one by Murphy-Hill et al. on differences between game development and traditional software development and a second by Ko et al. on the learning barriers encountered in development. We shifted our focus to be more general and to review literature around game development and how it differs from traditional software development. As a result of this focus change, we replaced the seed paper on learning barriers with a magazine article by Blow. Blow's article gave us insight into what it meant to be a game developer. We then compiled all references from these two papers into a list of potentially relevant papers.


## Step 2: Determining Relevant Papers
We took this list of potentially relevant papers and determine which were relevant based on a set of rules we developed. If the paper met all of the below rules then we classified it as relevant and added it to our GitHub repository.

### Relevancy Rules
1. Does the paper discuss the development process?
2. Does the paper discuss game development?
3. Does the paper discuss some form of the challenges or stress encountered by developers?
4. Does the paper provide results of some form?


## Step 3: Extracting Dimensions
Our goal is to determine what each paper is about and then compare the papers to each other. In order to do this we extracted a *dimension* from every paper.

### Reading Abstracts
After we compiled a list of relevant papers, we read through all of the abstracts, took some notes, and added them to our GitHub repository. On some of them, we were able to extract a dimension from just the abstract, and if so, we noted that dimension in the repository.

### Reading in Depth
If we could not extract a dimension from just the abstract, or if the paper seemed especially useful, we marked it for in depth reading. 

#### Similar Dimensions
If we extracted a dimension we had already extracted from another paper, we attempted to find another useful dimension of the paper. If no other dimension could be extracted, we considered that paper to have no significant extra contribution that was relevant to our review and we marked the paper as a dead end. 


## Step 4: Defining Key Articles
In addition to the original two seed articles, we discovered two more articles to be immensely helpful in our review. We marked all four articles as key articles for future use.

The key articles were:

1. Cowboys, Ankle Sprains, and Keepers of Quality: How Is Video Game Development Different from Software Development? [4]
2. Game Development: Harder Than You Think [7]
3. The 'Console Ship is Sinking' and What this Means for Indies [8]
4. International Game Developers Association. (2004). Quality of life white paper [9]

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
After combining from the previous round we actually found that two of our papers had the exact same ratings on the grid. This means that they didn't contain any unique dimensions captured in our grid and so we removed one paper from the grid. This paper was Product Development in Japanese TV Game Software [6]. We again tried to capture the more general ideas behind the dimensions now that we had fewer to look at and were able to reduce down to the following list:

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


#Results

In this section we will discuss the results from our systematic literature review. 
This project presented us with a repertory grid that compares the dimensions defined from the review.

##Dimension Defined
 - can be filled in from Dimension Defined .md file

##Weighted Dimensions

While defining the initial list of dimensions, the weights of the dimensions in the Repertory Grid were all divided equally across the dimensions in the grid. 
As the final grid was generated and similar dimensions were combined, the authors worked together to determine which dimensions were ranked higher than others.
During this process we valued <i>importance</i> over <i>frequency</i>.
Frequency refers to the amount of times an article discussed a dimension and importance refers to how much depth the article discussed a particular topic.

<img src="https://github.com/FrustratedGameDev/Papers/blob/master/Grid/cluster_v3.png">

For the final repertory grid, we decided to rank them as follows:  Requirement Volatility(25) , Quality of Life(21), Creativity(16), Developer Motivation(11), Testing(9), Team Composition(9), and Autonomy from Funding(9). 
When determining the weights, the goal was to make sure that the sum of all dimensions was 100. 
In addition,  we had to determine the importance of each dimension as it compared others. 
To do this we first identified the most discussed dimensions which were found to be Requirement Volatility, Quality of Life, Creativity, and Developer Motivation as interesting factors in the literature from the game Development community. 
After carefully determining  the comparision of the high valued groups we moved onto Testing, Team Composition, and Autonomy from Funding. 
In comparison to each other, this small subset were all determined to be on the same tier. There was not distinctive information provided on these categories to give one a heavier weight than the other.

<img src="https://github.com/FrustratedGameDev/Papers/blob/master/Grid/WeightAdjuster.png">

The tool 'Prioritze Concerns' feature of the Repertory Grid tool supported our adjustment of the weights. 
This feature of the tool ensured that the value of the weights always summed to 100 and reflected the difference between dimensions as discussed between colloborators.

<img src="https://github.com/FrustratedGameDev/Papers/blob/master/Grid/weightedCluster.png">


##Dimensions Defined

### Requirement Volatility

   Requirement volatility describes how often the requirements of a project change. This dimension was inspired by agile and waterfall comparison of iterative development. The process of which products are developed vary across the companies. In some circumstances the process if fully up to the team, for others it comes from upper management.
   
   During the design phase their are elements of the product that are considered a higher value. 
   In games, a valued part of the product is how engaging and 'fun' the product is for the user; more than it does in traditional software development. 
   Due to the fact that fun can vary upon many variables and is difficult to predict, the requirements and expectations of the product will vary as well.

### Quality of Life

   This dimension outlines the general lifestyle of developers. The pressures of crunch while on the job, maintaining a stable job, and the desire to remain at the company all can be encompassed into the quality of life in this career.

#### Crunch
   
   Crunch defines the time period before a shipping of a project where the developers are expected to work long hours. 
   The length of the crunch varies across product. Extended crunches often lead to "Death Marches" where developers are too tired to produce quality code.

#### Job Stability
   
   Job stability is something that is very important in today's society. As developers are humans and have families and lifestyles to support, it becomes more evident that job stability is valued. Across different industries, developers can expect a varied time period to be employed. Some industried have an expected risk associated with them, which often attracts employees.
   
#### Turnover
      
   Developers can easily get fed up with the work envrionments. This can cause them to leave their companies at high rates after staying at the company for a short amount of time resulting in high turnover. Low turnover can be defined as high retention rates for the company. 

### Creativity 
   
   Creativity refers to the encouragement of developers to start from scratch with a project versus building on top of a current codebase. This spectrum from creativity to constructivism varies upon audience addressed in the project.

### Developer Motivation

   With every profession there are certain aspects that draw interest. These interests for developers can be motovated by the actual product and the opportunity to interact with that product and it's users.

#### User Interactions

   The interactions of the users of the product can change the approach of how the product is approached. If the developers know that the users would use the product as a learning tool the developers are inclined to feel more connected to the product. In oppositon, if the developers feel as though the product is for mere entertainment of the user they can be less inclined to contribute their efforts to the product. Making the developers aware of the challenges, emotions, levels of fun, and engagement that the user will come incontact with can produce a more motivated developer. These motivated developers create amazing products that they can be proud of.

#### Work Ownership
      
   As a developer, it feels good to be acknowledged for the hardwork, responsibility, and accountability that is put into a product. This can be characterized as high work ownership. When a developer is not acknowledged for their contributions or made responsibile for their portion of a project  this can be characterized as low work ownership.
   
### Testing
 
   During the process of the literature review it was found that there are circumstances where products have little to no documented testing strategy. Testing a product (both unit testing and system testing) is apart of the process of developing products to ensure that the user receives the best experience and continue to use the product. This dimension identifies whether there is a tesing framework in place.
 
### Team composition

   There are many aspects of a team that are covered in this dimension: (1) the variation of interactions between the team- having many interactions to none at all, (2) the viscosity - how often the developers switch teams, and (3) the number of projects a team may handle. These apects of a team have been defined on a spectrum of being dynamic to static. Fluid team movements is an example of an organizational hierarchy where all employees(management and developers) are able to flexible in their work and the company fully supports their movement as long as its productive.

### Autonomy for Funding

   The traditional funding source for projects has been funding from venture captilalists and other investors who are intersted in receiving some return from the product such as being a valued stakeholder of the company. Recently, crowdfunding has been trending as a way to receive donated money with no strings attached, eventhough it may not complete all the finacial needs of the company. 
   You can consider this spectrum as how much  responsibility and accountability a company has over its own product. An example of this is Oracle as major mogul and Teklec being thesmall company: (1) Oracle buying all of Teklec and running teklec as Oracle v.s. (2) Oracle and Teklec running simultaneously and both Oracle and Tekelec are one in the same and share equal amounts of power v.s. (3) Teklec running individually receives funding from Oracle, yet Oracle still does not run any part of the company.
   [//]: # (   The spectrum of this dimension starts from (1)receiving all traditional funding from a company (where the investors own the company) to (2)receiving partial many money from a traditional source(where there is an equal balance of income and power in the company) to (3)having no connections to other companies and being completely self sustaining.)



# Discussion

The dimensions as defined in our results have found to be encouraged differently across the development community.
For example, Requirement Volatility amongst general software developers in comparison to games developers. 
Since fun and engagement, can be very hard to define[cite] for varied environments it affects the development process greatly in games. 
When creating a game this is something that can change at any stage in creating the game and the stress relies on games developers to ensure that it exists.
Fun and engagement is a high priority for the games industry as it is what encourages the revenue from product users.
In general software developement, requirements can be flexible in the agile process[cite:creator of agile] and can be modified with iterative rollouts of a product. The iterative development process in games varies as planned crunches are approached.

Another example of how a dimension can vary across the development community is creativity.
The creativity versus constructivism spectrum compares the value of fostering the natural ability to create art versus the ability to build upon what has already been done.
This spectrum defines part of the process to building an amazing product.
In this literature review, the games industry placed a higher price tag on the art of game making.
This art is valued in general software development but on a completly different scale. The reason for this could be the multitude of art directed industries that are similar to games, such as movie production, and  music video production.
Most games have a narrative; a story that is told often without explicitly stating it. 
In general software development this art is not valued on the same tier as other industries with a narrative. 
The constructivism of code reuse as a starting point is the approach in general software development where efficiency is a charactersistic of art. 

This repertory grid analysis provides many implications for further research in games development.
Through completing this analysis it has been a found that there needs to be a call for more research into the lifestyle of games developers. 
A key paper from our literature reivew[cite:Murphy, Cowboys] has been recognized by the community as a step in the right direction but there is more to be done. 
There is more to the development of games than the design process. 
A detailed review of the design process would present how the design process in games affects the developers. 
Just as previous researchers have refined what and how the social aspects of being a developer modifies the process[cite:programmer interrupted, exploring frustration, some SO study], we expect this paper to encourage the same for the games industry.
As an industry that is so similar and highly valued, the games industry will benefit highly from a deeper analysis of the games lifestyle.# Future Work

In defining these dimensions during the repertory grid analysis we were able to define the many ways that software development compares to games development.
This literature review provides a qualitative comparision and implies that there are multiple ways that development can be approached to achieve a product.
Implications from this work also include that there should be similar analysis to compare the amount of research approached in other software fields.

#Conclusion

In this paper we discussed the benefits of repertory grid analysis and the great information that can be depcited from them. 
From previous systematic literature reviews we were able to see that by navigating through the literature a research area can be identified as valuable. 
In our study we identified papers that identified the frustrations of a games developer. 
Through this review of the literature we were able to define and finalize 6 distinct dimensions: Requirement Volatility, Developer Motivation, Creativity, Team Composition, Autonomy for Funding, and Quality of Life. 
These dimensions that we have defined have outlined implications that can affect both games developers and software developers.
One of these implications lead to expanding this Repertory Grid Analysis to the comparison of software developers and games developers.
We expect that this qualitative analysis of the literature will continue to be a valued approach to defining differences across an environment.

# References
 
[1]: Tracy Hall, Sarah Beecham, David Bowes, David Gray, and Steve Counsell. 2012. A Systematic Literature Review on Fault Prediction Performance in Software Engineering. IEEE Trans. Softw. Eng. 38, 6 (November 2012), 1276-1304.

[2]: Barbara Kitchenham, O. Pearl Brereton, David Budgen, Mark Turner, John Bailey, and Stephen Linkman. 2009. Systematic literature reviews in software engineering - A systematic literature review. Inf. Softw. Technol. 51, 1 (January 2009), 7-15.

[3]: Budgen, D., Burn, A. J., Brereton, O. P., Kitchenham, B. A. and Pretorius, R. (2011), Empirical evidence about the UML: a systematic literature review. Softw: Pract. Exper., 41: 363–392. doi: 10.1002/spe.1009

[4]: Emerson Murphy-Hill, Thomas Zimmermann, Nachiappan Nagappan. Cowboys, Ankle Sprains, and Keepers of Quality: How Is Video Game Development Different from Software Development?. In Proceedings of the 36th International Conference on Software Engineering (ICSE 2014), Hyderabad, India, June 2014.

[5]: Menzies, Tim and Pearce, Adrian and Heinze, Clinton and Goss, Simon. What is an agent and why should I care? Appears in Formal Approaches to Agent-Based Systems, 2003, 1-14

[6]: YASUNORI BABA and F. TED TSCHANG, PRODUCT DEVELOPMENT IN JAPANESE TV GAME SOFTWARE: THE CASE OF AN INNOVATIVE GAME. Int. J. Innov. Mgt. 05, 487 (2001). DOI: 10.1142/S1363919601000464

[7]:  J. Blow, "Game Development: Harder Than You Think," IEEE Software, pp. 28-37, February 2004

[8]: WHITSON, J.. The 'Console Ship is Sinking' and What this Means for Indies. Loading..., North America, 7, dec. 2012. Available at: http://journals.sfu.ca/loading/index.php/loading/article/view/125. Date accessed: 01 Apr. 2015.

[9]: International Game Developers Association. Quality of Life in the Game Industry: Challenges and Best Practices. Published online April 20, 2004.