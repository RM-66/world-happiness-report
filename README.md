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
1. Features Analyzed: 
* GDP per capita - a measure of a country’s economic output that accounts for its number of people.
* Healthy Life Expectancy - Healthy life expectancies at birth based on the data extracted from the World Health Organisation (WHO) data repository
* Social support - Defined as having someone to count on in times of trouble (ranked from 0 to 1)
* Freedom to make life choices - Defined as the national average of responses to the Gall-WorldPoll question (“Are you satisfied or dissatisfied with your freedom to choose what you do with your life?”)
* Generosity - National average of responses to the question - “Have you donated money to a charity in the past month?”
* Perception of corruption - National average of responses to the questions (“Is corruption widespread throughout the government or not” and “Is corruption widespread within businesses or not” )

2. Visualizations based on different factors
* 
4. Visualizations based on geographics


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
