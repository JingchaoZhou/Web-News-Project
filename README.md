# Web-News-Project
# Customized News Webpage
### Yueyi Yang  yueyiyan@usc.edu
### Jingchao Zhou jingchao@usc.edu

## Install
```
npm install 
npm install express
npm install cor
npm install mocha
npm install chai
```
## Description
Our purpose of creating a Customized News Website is filtering massive news from various categories and providing the information that users are really looking for. Recently, the coronavirus is spreading worldwidely. News about the coronavirus almost dominates every new web page. In this case, it is especially difficult for some certain people who read news online to find news that really interests them. For example, some users would like to read sports news other than the coronavirus or maybe some users are only concerned about the coronavirus news of their own countries. Therefore, we create our Customized News Webpage to help these people. Our project includes the following features.

# Homepage
Homepage is the initial web page in which some hottest news will be displayed. Users can go back to the homepage by clicking the home tab.

Every article will be classified into a tab (such as coronavirus, Sports, arts, etc) and viewers can go to these sections by clicking corresponding tabs on the homepage.
![image](https://github.com/JingchaoZhou/Web-News-Project/blob/master/Screen%20Shot%202020-04-29%20at%201.48.50%20AM.png)

# Detailed Article Page
All articles are clickable and open a detailed view of the article. Detailed contents of an article include title, image, date and description.
![image](https://github.com/JingchaoZhou/Web-News-Project/blob/master/Screen%20Shot%202020-04-29%20at%201.58.52%20AM.png)

# Favorite Tab
In the article page, users can add the article into their favorites. From the homepage of the website, the detailed article page and the search result page, the user can navigate to the favorite tab.
![image](https://github.com/JingchaoZhou/Web-News-Project/blob/master/Screen%20Shot%202020-04-29%20at%202.25.52%20PM.png)

# Keyword Search
Users can search their interested news by input keywords in the search box. After the user searches for a keyword, articles related to that keyword will be displayed on a new page.
Autosuggest will appear when some words are inputted
![image](https://github.com/JingchaoZhou/Web-News-Project/blob/master/Screen%20Shot%202020-04-28%20at%201.23.13%20PM.png)
![image](https://github.com/JingchaoZhou/Web-News-Project/blob/master/Screen%20Shot%202020-04-28%20at%201.26.18%20PM.png)

# Overview of implementation
## Frontend(port:4000)
1. Fetch data by api and display on the webpage.
2. Store favorite news information into windows.localStorage and display them under My Favorites section.

## Backend(port:5000)
![image](https://github.com/JingchaoZhou/Web-News-Project/blob/master/Screen%20Shot%202020-05-01%20at%201.44.01%20PM.png)

# Links
## link to video
https://www.youtube.com/watch?v=oOPrbqfKE9Y&t=122s

## link to slides
https://docs.google.com/presentation/d/1buSth_3eEQqd-O_IPFEVIwqk6lAWeQhkKtwGhdUrWmY/edit?usp=sharing

# Future Work
1. Allow users to login by their social accounts
2. Use database to store their favorite news under their own accounts
3. Add comments and share features


