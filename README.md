# Code Refactoring

## Description 
A marketing agency wants to improve their website so that it follows accesibility standards and it is optimized for search engines. 

A link to the deployed application:
https://kristixxg.github.io/site-refactor/.


## Table of Contents

* [Corrections](#corrections)
* [Installation](#installation)
* [Usage](#usage)
* [Credits](#credits)
* [License](#license)

## Corrections
1. Original: Website used HTML code like ```<div class="header">``` or ```<div class="footer">```
 Correction: Replaced ```<div>``` with semantic element like ```<header>``` or ```<footer>```.
- Explaination: There are semantic elements that can be used to define parts of a web page. 

2. Original: ```<li>Search Engine Optimization</li>```   
 Correction: ``` <li><a href="#search-engine-optimization">Search Engine Optimization</a></li> ```
 - Explaination: An anchor tag and a href were added so the listed item is linked with the same exact id. 

 3. Original: ```.benefits {background-color: #2589bd;}```   
 Correction: ```.benefits {background-color: #0072bb;} ```
 - Explaination: Unless it's intentional, having consistent color scheme would make a website look more professional. 

 4. Correction: Added universal font-family onto the css style sheet.
 - Explaination: Unless it's intentional, having consistent font would make a website look more professional. 

 5. Original: ```<img src="./assets/images/search-engine-optimization.jpg" class="float-left"/>```   
 Correction: ``` <img src="./assets/images/search-engine-optimization.jpg" class="float-left" alt="Notebook Image"/> ```
 - Explaination: alt="" attribute was added to all images which make the website more accessible. Above codeblock is one of the examples. 

 6. Original: ``` <h2>Made with ❤️️ by Horiseon</h2>```   
 Correction: ``` <h4>Made with ❤️️ by Horiseon</h4>```
 - Explaination: Heading attributes should in sequential order. 

 7. Original: Line 7 on the index.html: ```<title>Website</title>```  
 Correction:  ```<title>Horiseon Social Solution Services</title>```
-   Explaination: One of good reasons to have a proper title for the website is that people who have multiple tabs open can easily identify which tab is which website. 


## Installation

No other installation required. 


## Usage 

![screenshot of web](./assets/images/Screen%20Shot%202022-03-30%20at%202.53.23%20PM.png)


## Credits

*UCB Bootcamp March 2022 Cohort*


## License

Not applicable


---

---

© 2022 xxx Confidential and Proprietary. All Rights Reserved.