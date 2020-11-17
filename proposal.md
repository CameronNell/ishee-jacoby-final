# Final project proposal

## Biotic Interactions as Range Limitations for Select Hawaiian Arthropods

Cameron Ishee, Joshua Jacoby

Cameron Ishee has been working with the UC Berkeley Evolutionary Genomics Lab (EvoLab) for two semesters now, including on the Dimensions Project. This project, conducted remotely, has featured an extensive literature review and data gathering on documented biotic interactions between Hawaiian arthropods, as well as between arthropods and plants. Our goal is to compile every known biotic interaction into a database that can be updated, manipulated, and used for a variety of applications. 

I've focused on the order Coleoptera, out of a combination of personal interest and recognition of the critical ecosystem services these detritivores provide. The plan is to explore this subset of the data, identify 3-6 species that have very many or particularly well-documented biotic interactions, and generate interaction webs and maps to depict possible ways in which these biotic interactions might limit the study species' ranges. I've done significant research into the methodology of assessing biotic limits on range, and based on this I would approach the question from the perspective of elevation and land cover type. Given that we understand a species' niche to include such-and-such elevation range and cover type, why do we *not* see them in certain areas? What about their documented range (realized vs fundamental niche) is not explained by elevation change and land cover type? Are there biotic interactions--the presence of a competitor, or the absence of a key food source--that might explain the realized range?


The whole scope of my project is as follows:

Step one: review the data to determine which select species may have enough data points to work with, and choose some to explore. 

Step two: determine rough fundamental niche for those species, based on existing research.

Step three: apply analysis of elevation and land cover (geoportal.hawaii.gov)

Step four: layer the interaction data 

Step five: analyze the gap between what is explained by elevation and land cover, and what the interaction data may show

Step six: using climate projections for the Islands, project how some key species' ranges may change in accordance with the expected warming of the next century

Step seven: provide analysis and conservation recommendations for future management based on these findings


I'm aware of the scope of this, and in the course of this class I'd consider myself lucky to get through step 3. I want to at least come out of this class project with a better analysis framework for my research, and a working knowledge of how to use maxent as a function. 


## Project Guidelines

### Project questions must illustrate all of the following tasks:

- Some form of data access / reading into R
- Data tidying preparation
- Initial data visualization
- Use of GitHub
- Reproducible execution with use of Travis
- RMarkdown writeup, with final submission as a nicely formatted PDF document that includes code and results.
- Overall clean and clear presentation of repository, code, and explanations.

### and at least three of the following skills (this list may be modified/extended):

- Use of at least 5 `dplyr` verbs / functions
- Writing / working with custom R functions
- Creating an R package for functions used in the analysis
- Interaction with an API
- Use of regular expressions
- Use of an external relational database
- Preparing processed data for archiving / publication
- Parsing extensible data formats (JSON, XML)
- Use of spatial vector data (`sf` package) and visualization of spatial data
- Creation of an R package
- Expansion of ggplot functions (to include more than default characteristics)
- Making layout and presentation into secondary output (e.g. .pdf, website) - should enhance presentaiton
- use lintr to clean code (checks adherence to a given style, syntax errors and possible semantic issues)

# Final Rubric 30 pts total

 - 5pts Proposal, turned in on time and with team member names, background, dataset, and 3 potential questions.

 - 10pts Polished github repository, including:
	 -  3pt updated readme with functional travis badge 
	 -  2pt passing travis build 
	 -  2pt clean and well formatted output document (html, pdf, or md with associated files). 
	 -  3pt enough supporting text that we can easily understand the project undertaken.
	 
 - 15 pts Project Substance: Objectives, Code, Visualization. Do you meet all of the required project objectives and at least 3 of the supplementary objectives.
	 - 15pts: exceptional
	 - 13pts: adequate and complete
	 - 11pts: adequate 2 questions, meeting 3 supplementary objectives
	 - 9pts: adequate 2 q, meeting 1-2 supplementary objectives
	 - 7pts: adequate 1 q, meeting 3 supplementary objectives
	 - 5pts: adequate 1q, meeting 1-2 supplementary objectives
