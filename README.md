![Site Logo](assets/images/flags-portugal-and-brazil-on-a-white-background.png)
## Table of Contents
* [Purpose](#Purpose)
* [Prototype](#Prototype)
* [Features](#Features)
    * [Existing](#Existing)
        * [Navigation Bar](#Navigation-Bar)
        * [The Hero Image](#The-Hero-Image)
        * [Main Section](#Main-Section)
        * [Footer](#Footer)
        * [Galleries](#Galleries)
        * [Form](#Form)
    * [Left to Implement](#Left-to-Implement)
* [Technologies](#Technologies)
* [User Experience Design (UX)](#User-Experience-Design)
    * [Business Goals](#Business-Goals)
    * [User Goals](#User-Goals)
        * [First Time Visitor](#First-Time-Visitor)
        * [Returning Visitor](#Returning-Visitor)
        * [Frequent User](#Frequent-User)
    * [Design](#Design)
        * [Color Scheme](#Color)
        * [Typography](#Typography)
        * [Wireframes](#Wireframes)
* [Limitations](#Limitations)
* [Testing](#Testing)
    * [Test Results](#Test-Results)
        * [Validators](#Validators)
        * [Lighthouse](#Lighthouse)
        * [Devices](#Devices)
    * [Testing Issues](#Testing-Issues)
* [Deployment](#Deployment)
    * [Project Creation](#Project-Creation)
    * [GitHub Pages](#Github-Pages)
    * [Locally](Locally)
    * [Commands](Commands)
* [Credits](#Credits)
    * [Content](#Content)
    * [Media](#Media)
    * [Acknowledgements](#Acknowledgements)
* [Comments](#Comments)

## Purpose
The idea behind this site is to bring some knowledge about the Portuguese and Brazilian gastronomies. There are a lot of sites with massive information regarding food from both countries but on this one, the focus is to centralize and put together some of the most common and representative products.
The portfolio of recipes will provide some information about each product and then, if the user wants to get additional information, should contact us by filling the form. 
This site was built with basic functionality and navigation but soon, more advanced features will be deployed such as online orders, request of recipes, requests for further information regarding specific locations (travelling, hotels) and feedback from users (blog). 

The live website can be found [here](https://baptistapaulo.github.io/pp1/).

[Table-of-Contents](#Table-of-Contents)

## Prototype
![Prototype](readme/prototype.png)

[Table-of-Contents](#Table-of-Contents)

## Features
### Existing
#### Navigation-Bar
![Logo-Menu-Bar](readme/header.PNG)
#### The-Hero-Image
![Hero-Image-Animation](readme/hero.PNG)
#### Main-Section
![main-section-part1](readme/index1.PNG)
![main-section-part2](readme/index2.PNG)
#### Footer
![Footer](readme/footer.PNG)
#### Galleries
![Gallery1-Brazil](readme/brazil1.PNG)
![Gallery2-Brazil](readme/brazil2.PNG)
![Gallery1-Portugal](readme/portugal1.PNG)
![Gallery2-Portugal](readme/portugal2.PNG)
#### Form
![Form](readme/form.PNG)
### Left-to-Implement
* Orders online for delivery of some selected products from the portfolio but this will require a secure link for payments and security compliance.
* A blog also may be created but only accessible to members, requiring therefore a registration and sign in.
* A database with multiple recipes may be deployed as a back-end engine to provide a feed of different products, so that every month for example, the front end can swift some of the recipes based on a voting scheme from members.

[Table-of-Contents](#Table-of-Contents)

## Technologies
* Languages
    * HTML5
    * CSS3
* Frameworks, Libraries and Programs
    * Google fonts
    * Font Awesome
    * GitHub (used to store repositories, files and images pushed from GitPod)
    * GitPod (IDE used to code the website)
    * Git (for version control, commits and push to GitHub)
    * Google Chrome Developer Tools (for checking compatibility, troubleshooting and editing code)
    * TinyPNG (for compression of your WEBP, JPEG and PNG files) [here](https://tinypng.com/).
    * Stackoverflow (for searching on some topics related to HTML/CSS)
    * W3schools (for HTML/CSS tutorials)

[Table-of-Contents](#Table-of-Contents)

## User-Experience-Design
The UX was deployed and tested for various screen sizes but still needs further testing across different platforms (hardware and software).
This is a section of the deployment still under development.

### Business-Goals
* Provide a central repository of gastronomy information.
* Allow users to have access to accurate product details at low fees.
* Promote a forum for discussions about gastronomy.
* Create and publish a ranking of the most voted products.
### User-Goals
#### First-Time-Visitor
* Easy navigation and search for information.
* Site should be visually appealing.
#### Returning-Visitor
* Leave some feedback.
* Contact for further information.
#### Frequent-User
* Check if any of the topics posted has been commented.
* Find new recipes.
* Order some products.
### Design
#### Color-Scheme
* Predominant colours across all site are green and yellow.
* Black and grey ocasionaly.
![Color](readme/color_scheme.PNG)
[Table-of-Contents](#Table-of-Contents)

#### Typography
**DynaPuff** (designed by Toshi Omagari, Jennifer Daniel) from Google fonts was used mostly for headers and logo title.
**Arial** (Helvetica, sans-serif) was used mostly for any other text in all sections, including the menu and form.
#### Wireframes
![wireframe-home](readme/wireframe-home.PNG)
![wireframe-brazil](readme/wireframe-brazil.PNG)
![wireframe-portugal](readme/wireframe-portugal.PNG)
![wireframe-contact](readme/wireframe-contact.png)

[Table-of-Contents](#Table-of-Contents)

## Limitations
This website has not a customized page to acknowledge the submit form so the Code Institute form dump page was used instead.

[Table-of-Contents](#Table-of-Contents)

## Testing
### Test-Results
#### Validators
* HTML - Official W3C validator [here](https://validator.w3.org/).
* CSS - Official (Jigsaw) validator [here](https://jigsaw.w3.org/css-validator/).
* Lighthouse – Developer Tools
* Chrome – Developer Tools
* Responsive Design [here](https://ui.dev/amiresponsive).
![responsive](readme/responsive-results.PNG)
#### Lighthouse
![lighthouse-index-results-performance](readme/lighthouse-index.PNG)
![lighthouse-brazil-results-performance](readme/lighthouse-brazil.PNG)
![lighthouse-portugal-results-performance](readme/lighthouse-portugal.PNG)
![lighthouse-contact-results-performance](readme/lighthouse-contact.PNG)

#### Devices
Tested functionality and responsiveness using the below devices and browsers.
* Mobiles
    * Samsung S9
    * Samsung Note
    * Samsung A51
* Laptops
    * HP EliteBook
    * Lenovo ThinkPad
* Browsers
    * Chrome
    * Firefox
    * Edge

### Testing-Issues
* Bugs identified that need to be fixed.
    * on Edge and Firefox browsers, the footer icons do not inherit the class social-media colour therefore not visible unless moving mouse over the icons but this is not affected in Chrome so further testing required in order to fix this.
    * on Edge and Firefox browsers, the form radius and checkbox buttons do not inherit the input custom options therefore they show default values but this is not affected in Chrome so further testing required in order to fix this.
    * on mobile devices and tablets, pages do not load properly (layout not resized) with impact on UXD but this can be fixed by different media screen sizes in the CSS and with further testing on different platforms.
    * HTML validator pointed to some errors (all related to same) but not all of them were fixed so further testing required to eliminate these errors.
* Further styling and optimization (different screen size) to improve UX requires additional time.

[Table-of-Contents](#Table-of-Contents)

## Deployment
### Project-Creation
This project website was created from scratch, with no forking from any other repositories but based on the initial structure of the Code Institute walkthrough.
Once the structure was in place, then added content and styling as the work was in progress. Some styling was gathered from **Stackoverflow** or **W3schools**.
#### Github-Pages
Repository
1. Navigate to the GitHub [Repository:](https://github.com/baptistapaulo/pp1)
1. Click the 'Settings' Tab.
1. Scroll Down to the Git Hub Pages Heading.
1. Select 'Master Branch' as the source.
1. Click the Save button.
1. Click on the link to go to the live deployed page.
### Locally
Clone
1. Navigate to the GitHub [Repository:](https://github.com/baptistapaulo/pp1)
1. Click the Code drop down menu.
1. Either Download the ZIP file, unpackage locally and open with IDE (This route ends here) OR Copy Git URL from the HTTPS dialogue box.
1. Open your developement editor of choice and open a terminal window in a directory of your choice.
1. Use the 'git clone' command in terminal followed by the copied git URL.
1. A clone of the project will be created locally on your machine.
### Fork
Most commonly, forks are used to either propose changes to someone else's project to which you do not have write access, or to use someone else's project as a starting point for your own idea. You can fork a repository to create a copy of the repository and make changes without affecting the upstream repository.
So a fork is a copy of a repository. Forking a repository allows you to freely experiment with changes without affecting the original project.
1. Navigate to the GitHub Repository you want to fork.
1. On the top right of the page under the header, click the fork button.
1. Create a new fork.
1. This will create a duplicate of the full project in your GitHub Repository.
### Commands
* `CTRL + S` was used to save the page.
* `CTRL + Z` was used to undo a change.
* `python3 -m http.server` was used to view and test site before pushing live.
* `git add` was used to add pages to the stage area.
* `git commit -m "fix: message here"` was used to comit them them to github and provide a relevant message to the changes that had been made.
* `git push` was used to push the changes upto Github for public viewing.

[Table-of-Contents](#Table-of-Contents)

## Credits
### Content
* Text for the main section was created by myself.
* Additional information gathered from official sites (for both countries).
* ReadMe structure from **Daisy McGirr** GitHub repositories.
* Code ideas were gathered from **Kera Cudmore** GitHub repositories [here](https://github.com/kera-cudmore/Bully-Book-Club).
* Recipes were taken from the below site:
[Brazilian Chocolate Truffles](https://www.bbcgoodfood.com/recipes/brazilian-chocolate-truffles-brigadeiro)
[Brazilian Feijoada](https://www.bbcgoodfood.com/recipes/black-bean-meat-stew-feijoada)
[Brazilian Pastel](https://www.bbcgoodfood.com/recipes/pastel-de-palmito)
[Brazilian Coconut Quindim](https://www.bbcgoodfood.com/recipes/coconut-quindim)
[Brazilian Cheese Bread](https://www.bbcgoodfood.com/recipes/brazilian-cheese-bread-pao-de-queijo)
[Brazilian Chicken Croquettes](https://www.bbcgoodfood.com/recipes/coxinhas)
[Portuguese Lagareiro Cod](https://portugalgourmand.com/en/recipes/lagareiro-fresh-cod/)
[Portuguese Grilled Sardines](https://portugueserecipes.ca/recipe/78/1/Portuguese-Grilled-Sardines)
[Portuguese Pork Stew](https://portugueserecipes.ca/recipe/653/30/Portuguese-Pork-Stew-Recipe)
[Portuguese Egg Yolk Sweets](https://www.easyportugueserecipes.com/portuguese-egg-yolk-sweets-ovos-moles-de-aveiro/)
[Portuguese Pig Stew](https://www.easyportugueserecipes.com/leitao-a-bairrada-suckling-pig/)
[Portuguese Custard Tarts](https://www.bbcgoodfood.com/user/411558/recipe/portugese-custard-tarts)

### Media
* The photos used in this website were taken from some resources such as the below.
    * Pexels.com - used for images
    * Unsplash.com - used for images
    * Google.com - used for images

### Acknowledgements
* Huge thank you to my mentor **Ronan McClelland** for his guidance throughout my project.
* Special thanks to Student Care support (**Aoife**) for assisting me on a delicate health issue.

[Table-of-Contents](#Table-of-Contents)

## Comments
The Git Pages may contain two different deployments due to a change on the repository name where
`github-pages at 307921d` refers to a previous version of this website (**baptistapaulo.github.io/baptistapaulo-pp1.github.io/**) and
`github-pages at bd31b90` refers to the current version (**baptistapaulo.github.io/pp1/**).

[Table-of-Contents](#Table-of-Contents)