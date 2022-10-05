# Title

**Authors**: Drew Holcombe, Raul, Torres, Edward Juarez

## Overview

Microsoft is a well-established technology corporation most known for creating computers and software. Unlike their competitors in the technology industry (Apple, Amazon, etc.), Microsoft de=oes not currently produce original video content. If they were to compete in this medium, what factors would best contribute to their success? We sought out answers using database files from Box Office Mojo, IMDB, TheMovieDB, and The Numbers, which pointed towards certain times of year, genres, and persons associated with reliable financial success.

## Business Problem

If Microsoft were to break into the film industry, what strategy would give them the best chance of success? What types of films are currently doing the best at the box office, and how can we translate this information into actionable items? How can we minimize the risk of potential films becoming box office bombs?

## Data

Describe the data being used for this project.

***
Questions to consider:
* Where did the data come from, and how do they relate to the data analysis questions?
* What do the data represent? Who is in the sample and what variables are included?
* What is the target variable?
* What are the properties of the variables you intend to use?
***

## Methods

To analyze the genres of films, we utilized the genres as listed in the database by IMDB with the production budget and worldwide gross provided by The Numbers. We then determined the median profit, return on investment, and so on from each genre to determine which has the largest potential to earn money. We used the median to avoid over-emphasizing outliers, i.e. massively successful films that don't accurately reflect the overall potential of their genre.

To analyze the potential of actors, writers, and directors, we utilized the persons listed in the database by IMDB with the production budget and worldwide gross provided by The Numbers. We split the movies into those with above-average profits from those with below-average profits. We then looked for persons who contributed to more above-average earning films than below-average earning films; this is intended to identify reliable artists, rather than artists who contributed to one or two massive successes.

To analyze time of year of release, we utilized the date of release and financial information from the database provided by The Numbers. 
Describe the process for analyzing or modeling the data. For Phase 1, this will be descriptive analysis.

***
Questions to consider:
* How did you prepare, analyze or model the data?
* Why is this approach appropriate given the data and the business problem?
***

## Results

Present your key results. For Phase 1, this will be findings from your descriptive analysis.

***
Questions to consider:
* How do you interpret the results?
* How confident are you that your results would generalize beyond the data you have?
***

Here is an example of how to embed images from your sub-folder:

### Visual 1
![graph1](./images/viz1.png)

## Conclusions

Provide your conclusions about the work you've done, including any limitations or next steps.

***
Questions to consider:
* What would you recommend the business do as a result of this work?
* What are some reasons why your analysis might not fully solve the business problem?
* What else could you do in the future to improve this project?
***

## For More Information

Please review our full analysis in [our Jupyter Notebook](./dsc-phase1-project-template.ipynb) or our [presentation](./DS_Project_Presentation.pdf).

For any additional questions, please contact **name & email, name & email**

## Repository Structure

Describe the structure of your repository and its contents, for example:

```
├── README.md                           <- The top-level README for reviewers of this project
├── dsc-phase1-project-template.ipynb   <- Narrative documentation of analysis in Jupyter notebook
├── DS_Project_Presentation.pdf         <- PDF version of project presentation
├── data                                <- Both sourced externally and generated from code
└── images                              <- Both sourced externally and generated from code
```
