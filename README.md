# Milestone 2 Project - Data Dashboard
This site (https://laurgeo.github.io/data-dashboard/) is for those interested in data about wine. This dataset was obtained from Kaggle(https://www.kaggle.com/zynicide/wine-reviews). It contains information about different wines, their origination, province, year. 

It also has interesting data such as reviews. Reviews contain user names and twitter handles. It is a dynamic dashboard, so users can get accurate up to date information in the click of a button.

## UX
I chose to download the csv file of all the data, and importing that using dc. 
As this is a dashboard, i chose to use the template of a 'single page application'. 

This is because the point of the dashboard is so that a user can take one look at the screen and absorb the data that is there. I put 6 graphs on the screen, as this is a good number for a human to absorb information with.

Although this is a single page application, these types of applications are sometimes thought of to be boring. I wanted to add a twist to the regular dashboard. I added some styling that is not normally seen on these types of applicaitons.

Using a dashboard, the best option is to minimise the amount of clicks a user needs to make.

When the user visits the page they are greeted with the site logo in a very aesthetically pleasing way.
It encourages them to scroll, as it has an element of curiosity. This is because the site name is 'Wine not?', which is a question, so indulging the users curiosity. 

The screen is completely black, so the first instinct would be to scroll.

The user is then greeted with an introduction to what the site is, so they can understand. Here is a very basic overview of the data available.

The first graph is a simple graph of different wines by the country. This is easily absorbed by the user and easily understood. The following graphs are slightly more complex.

The final spread of data, is a list of the reviews, with the reviewer names and twitter handles.

The user is then shown the site footer, where they can contact the site owners.

At the top of the charts, there is a counter there for all filters selected, where you can reset by clicking on the button. This is to make it easier to reset to the starting data.

I chose to use: overflow: hidden on each of the charts so that if the dashboard was displayed on a smaller screen  that the user could just scroll across to view the graph info. This was a workaround to making the dc charts fully responsive.

I chose not to use a legend with the bar charts, as they are self explanitory and do not require it. It would also make the design look much too bulky.

Wireframes are located in the wireframes folder.

### Navigation
To allow users to go to any graph they want, I chose to make the navbar sticky. This means that the user can click on each chart from wherever they are on the page. 
On mobile, the menu nicely turns into a hamburger menu. This is so that mobile users find it easy to jump to each graph. This is still sticky from mobile, as it is important that the user always has navigation options.

### Colors
I chose to go with a red color scheme for the charts. This is to tie it in to the 'wine' data set
The red contrasts with the white background, and the greyed out charts. I used font awesome icons in red to make them pop.

## User Stories
1. As a wine enthusiast, I want to browse a site with data about wine
2. As a lover of Sauvignon Blanc, I want to see reviews of this wine
3. As someone who likes looking at data about Italy, I want to see how many reviews were written about wine in Italy
4. As a person who has discovered a discrepancy in the data, i want to contact hte company via social media
5. As a Pino Grigiot fan I want to see written reviews of this wine

## Features
1. Navbar - From wherever the user is on the page, they can visit each different section of the page. This is sticky so that it is always present wherever the user scrolls.

2. Footer - This is a basic footer that contains links to social media. In case someone needs to make contact with the site owner.
3. Charts - For users to view data
    i. BarChart - for categorical data that is easily read. The bars are big enough for users to click.
    ii. PieChart - This is for when ther eis a bit more data than the bar chart
    iii. Grid - I used the grid to effectively display the reviews along with the title of the wine, and the reviewers name and twitter handle

4. Header - Contains the name of the site. This uses an artistic approach, trying to grab the users attention


## Technologies Used
- VSCode
- HTML
- CSS
- Bootstrap
- Javascript
- d3.js
- crossfilter
- purgecss
- jigsaw
- w3validator

## Testing
1. Browsers this site has been tested in: Internet Explorer, Microsoft Edge, Mozilla Firefox and Google Chrome. 
2. Devices this site has been tested on: Android, iOS.

3. In order to check that the site behaves as expected on different screen sizes, i used the Chrome Developer Tools changing the size of screen. I also tested on the different devices available in the developer Tools to ensure that they all look as i intended them to.

   **After analyzing making d3 charts responsive, it proved too difficult to complete for this project, but is something that should be done in future.
4. I also used the error window in chrome developer tools ensuring that i there are no issues.
5. Hovering over each element to make sure the tooltips work
6.  I used https://validator.w3.org/ to validate my code thorughout to check that the html is valid
7.  I used jshint.com to run my code through
8.  I used purgecss to see unnecesary css and remove

## Deployment
This site was deployed on github pages. The link is here: https://laurgeo.github.io/data-dashboard/. 

 In order to do this, I had to go to the Settings tab, and click deploy.
1. Go to the repository
2. Click Settings
3. Under GitHub Pages, and Source, go to master

For running this code locally:
1. Go to the repository main page
2. Select Clone with HTTPS
3. Copy link
4. Open git bash in desired directory
5. type git clone and the URL from step 2
6. Press Enter

## Credits
I got the styling and idea for the logo in the header from: https://codepen.io/FrankieDoodie/pen/dgVGad
Credits to w3 schools, tutorialspoint.

## Content
Content is belonging to the data set obtained from Kaggle.

## Media

## Acknowledgements
Inspiration came from codeinstitute data dashboard exercises and azure dashboard, and bootstrap custom dashboard theme. 
