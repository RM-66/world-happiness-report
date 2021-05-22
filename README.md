# CSE412 Final Project Template (Idyll)

## Team Members

Cherry Pan, Hongying Wu, Ruimin Zhang, Robert Zheng

### Contribution Statements

Everyone contributes to this project.

## Project Proposal Abstract

We are hoping to find out what makes people happy and the happiness level among different groups of people as people pay more attention to their happiness and quality of life. Therefore, in our project, we use the [World Happiness Report](https://www.kaggle.com/PromptCloudHQ/world-happiness-report-2019) datasets to research the happiness level across countries and time. We use the _‘score’_ index to observe how different factors are linearly related to _‘score’_. In this proposal, we selectively choose data from 2019 as a reference to explore.

## Getting Started

**This template is a starting place for your project. Update the header information to include the relevant details for your project, and then feel free to mix and match the visualization and layout techniques introduced here for your own narrative.**

**Think about how the narrative structure draws readers into the story you are telling and how the visualizations interact with the text (and with each other). The narrative should help ensure that the page as a whole is greater than just the sum of it's parts. When designing your page, decide on particular layouts that enhance the reader's experience and understanding of the topic.**
**1. Features Analyzed:**
* GDP per capita - a measure of a country’s economic output that accounts for its number of people.
* Healthy Life Expectancy - Healthy life expectancies at birth based on the data extracted from the World Health Organisation (WHO) data repository
* Social support - Defined as having someone to count on in times of trouble (ranked from 0 to 1)
* Freedom to make life choices - Defined as the national average of responses to the Gall-WorldPoll question (“Are you satisfied or dissatisfied with your freedom to choose what you do with your life?”)
* Generosity - National average of responses to the question - “Have you donated money to a charity in the past month?”
* Perception of corruption - National average of responses to the questions (“Is corruption widespread throughout the government or not” and “Is corruption widespread within businesses or not” )

**2. Visualizations based on different factors**
* correlation heatmap:
![alt text](https://github.com/cse412-21sp/world-happiness-report/blob/main/static/images/correlation%20heatmap.png)
The correlation between six variables and happiness scores. We spot that GDPper capita, social support, and healthy life expectancy have stronger impacts over our scores than other variables. 

* five factors: 
![alt text](https://github.com/cse412-21sp/world-happiness-report/blob/main/static/images/A%20broad%20look%20of%20how%20score%20is%20related%20to%20these%20five%20factors%20.png)
A general look of the trend lines between score and different factors.

* score distribution: 
![alt text](https://github.com/cse412-21sp/world-happiness-report/blob/main/static/images/score%20distribution.png)
How happiness scores are distributed. 

* score vs GDP: 
![alt text](https://github.com/cse412-21sp/world-happiness-report/blob/main/static/images/score%20vs%20GDP.png)
This is the graph showing the relationship between Score and GDP. The slope is around 0.3. As we can see in the graph, most of the data points are around the trendline, meaning the variance is relatively small, and most of the country follow the trend that the the higher scores has a higher GDP per capita.

* score vs corruption: 
![alt text](https://github.com/cse412-21sp/world-happiness-report/blob/main/static/images/score%20vs%20corruption.jpg)
Weak correlation.

* score vs social support: 
![alt text](https://github.com/cse412-21sp/world-happiness-report/blob/main/static/images/score%20vs%20social%20support.png)
This graph shows the relationship between Score and social support. The slope is around 0.2. The variance is relatively small. This graph shows that the higher score is, the better the social support rate will be. Most of the data points are clustered around the score of 4 to 7.5, and the social support of 1.0 to 1.6, indicating the score in between 4-7.5 are likely to have the social support rate of 1.0-1.6

* score vs life expectancy: 
![alt text](https://github.com/cse412-21sp/world-happiness-report/blob/main/static/images/score%20vs%20life%20expectancy.jpg)
Strong correlation between score and life expectancy. In general, countries with higher scores have a higher life expectancy than countries with lower scores.

* score vs freedom to make choices:![alt text](https://github.com/cse412-21sp/world-happiness-report/blob/main/static/images/score%20vs%20freedom%20to%20make%20life%20choice.png)
Somewhat strong correlation between score and freedom with many outliers.

**3. Visualizations based on geographics**
* score map: 
![alt text](https://github.com/cse412-21sp/world-happiness-report/blob/main/static/images/score%20map.png)

* Top 10 rank countries map:
![alt text](https://github.com/cse412-21sp/world-happiness-report/blob/main/static/images/Top%2010%20countries.png)
A map of top 10 countries with highest score, we can find most toppest score countries are in Europe. 

* Map decribes countries included:
![alt text](https://github.com/cse412-21sp/world-happiness-report/blob/main/static/images/Map.jpg)
A plot that shows countries included in the dataset, missing countries:
Cuba, Guyana, Suriname, French Guiana, Greenland, Western Sahara, Guinea-Bissau, Angola, Sudan, Oman, North Korea, East Timor, Papua New Guinea, Solomon Islands, New Caledonia, Fiji


### Required Software

You must have Node.js installed. You can get it directly from https://nodejs.org/en/.

### Installation

- Clone and open your project repo on your own computer.
- Make sure you have `idyll` installed (`npm i -g idyll`).
- Run `npm install` to install project-specific dependencies.

npm is the node package manager. If you're curious how this works and what the project dependencies are, open up `package.json` to see where these are listed.

You can install custom dependencies by running `npm install <package-name> --save`. Note that any collaborators will also need to download the package locally by running `npm install` after pulling the changes.

### Developing a post locally

Run `idyll` from the command line. Your post will appear at [http://localhost:3000/](http://localhost:3000/). When the server is running, any local change that you make will be deteched and your webpage will auto-update with the new changes. Your local changes will not be visible to your team members until you push the changes to your repository. These changes will not be reflected in the final website unless you run the build script and push the updated docs folder (see below).

### Building a post for production

Run `idyll build`. The output will appear in the top-level `build` folder. To change the output location, change the `output` option in `package.json`.

### Deploying

Make sure your post has been built, then commit the `docs` folder to your project repository. It will be available at [cse412-21sp.github.io/your-repo-name/](). For example, you can view the sample embedded Tableau, vega-lite, and d3 charts at [https://cse412-21sp.github.io/Final-Project-Template](https://cse412-21sp.github.io/Final-Project-Template).

#### Acknowledgements

This template was adapted from the initial Scrollytelling template for Idyll. The code and visualization examples were adapted from the [final project template](https://github.com/cse412-21w/project-demo) created for a previous offering of CSE 412.
