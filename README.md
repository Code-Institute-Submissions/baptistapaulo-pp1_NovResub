![Site Logo](assets/images/flags-portugal-and-brazil-on-a-white-background.png)
## Table of Contents
* [Purpose](#Purpose)
* [Prototype](#Prototype)
* [Features](#Features)
    * [Existing](#Existing)
        * [Navigation Bar](#Navigation-Bar)
        * [The Header Image](#The-Header-Image)
        * [Main Section](#Main-Section)
        * [Footer](#Footer)
        * [Galleries](#Galleries)
        * [Form](#Form)
    * [Left to Implement](#Left-to-Implement)
* [Technologies](#Technologies)
* [User Experience Design (UX)](#User-Experience-Design)
    * [Structure](#Structure)
    * [Business Goals](#Business-Goals)
    * [User Goals](#User-Goals)
        * [First Time Visitor](#First-Time-Visitor)
        * [Returning Visitor](#Returning-Visitor)
        * [Frequent User](#Frequent-User)
    * [Design](#Design)
        * [Colour Scheme](#Colour-Scheme)
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
The idea behind this site was to bring some knowledge about the Portuguese and Brazilian gastronomy. There are a lot of sites with massive information regarding culture and food from both countries but on this one, the focus is to centralize and put together some of the most common and representative products.
The portfolio of recipes will provide some basic information about each product and then, if the user wants to get additional information, should contact us by filling the form. 
This site was built with basic functionality and navigation but soon, more advanced features will be deployed such as online orders, request of recipes, requests for further information regarding specific locations (travelling, hotels) and feedback from users (blog). 

The live website can be found [here](https://baptistapaulo.github.io/pp1/).

[Table-of-Contents](#Table-of-Contents)

## Prototype
![Prototype](assets/readme/prototype.png)

[Table-of-Contents](#Table-of-Contents)

## Features
### Existing
#### Navigation-Bar
![Logo-Menu-Bar](assets/readme/header-menu-and-logo.PNG)
#### The-Header-Image
![Header-Image-Animation](assets/readme/header-image-animation.PNG)
#### Main-Section
![main-section-part1](assets/readme/main-section-part1.png)
![main-section-part2](assets/readme/main-section-part2.png)
#### Footer
![Footer](assets/readme/footer.PNG)
#### Galleries
![Gallery-Brazil](assets/readme/gallery-brazil.PNG)
![Gallery-Portugal](assets/readme/gallery-portugal.PNG)
#### Form
![Form](assets/readme/form.PNG)
### Left-to-Implement
* Orders online for delivery of some selected products from the portfolio but this will require a secure link for payments and security compliance.
* A blog also may be created but only accessible to members, requiring therefore a registration and sign in.
* A database with multiple recipes may be deployed as a back-end engine to provide a feed of different products, so that every month for example, the front end can swift some of the recipes based on a voting scheme from members.
* Gallery images with the recipe attached underneath and/or text over the photo on mouse click (hover effect).
* Video and/or music clips to ilustrate some of the cultural aspects of both countries.

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
The UX was deployed and tested only for screen sizes greater than 1600px but needs further deployment for smaller screen sizes (480px & 1000px).
This is a section of the deployment still under development.

### Structure
![Structure](assets/readme/structure.png)
[Table-of-Contents](#Table-of-Contents)

### Business-Goals
* Provide a central repository of gastronomy and cultural information.
* Allow users to have access to accurate product details at low fees.
* Promote a forum for discussions about culture and gastronomy.
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
#### Colour-Scheme
* Predominant colours across all site are lightgrey and grey.
* Black and white ocasionaly.
* Custom rgb(184,184,184) for headers.
#### Typography
**DynaPuff** (designed by Toshi Omagari, Jennifer Daniel) from Google fonts was used mostly for headers and logo title.
**Arial** (Helvetica, sans-serif) was used mostly for any other text in all sections, including the menu and form.
#### Wireframes
![wireframe-home](assets/readme/wireframe-home.PNG)
![wireframe-brazil](assets/readme/wireframe-brazil.PNG)
![wireframe-portugal](assets/readme/wireframe-portugal.PNG)
![wireframe-contact](assets/readme/wireframe-contact.png)

[Table-of-Contents](#Table-of-Contents)

## Limitations
This website has not a customized page to acknowledge the submit form so the Code Institute form dump page was used instead.
Currently, the website is only optimized for screen sizes greater than 1600px.

Views of all pages on a screen size greater than 1600px.
![home-1600px-part1](assets/readme/home-1600px-part1.PNG)
![home-1600px-part2](assets/readme/home-1600px-part2.PNG)
![brazil-1600px](assets/readme/brazil-1600px.PNG)
![portugal-1600px](assets/readme/portugal-1600px.PNG)
![contact-1600px](assets/readme/contact-1600px.PNG)

[Table-of-Contents](#Table-of-Contents)

## Testing
### Test-Results
#### Validators
* HTML - Official W3C validator [here](https://validator.w3.org/).
* CSS - Official (Jigsaw) validator [here](https://jigsaw.w3.org/css-validator/).
* Lighthouse – Developer Tools
* Chrome – Developer Tools
* Am I Responsive [here](https://ui.dev/amiresponsive).
![responsive](assets/readme/responsive-results.PNG)
#### Lighthouse
![lighthouse-index-results-performance](assets/readme/lighthouse-index-results-performance.PNG)
![lighthouse-brazil-results-performance](assets/readme/lighthouse-brazil-results-performance.PNG)
![lighthouse-portugal-results-performance](assets/readme/lighthouse-portugal-results-performance.PNG)
![lighthouse-contact-results-performance](assets/readme/lighthouse-contact-results-performance.PNG)

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
    * both HTML and CSS validators pointed to some errors (and warnings) but not all of them were fixed so further testing required to eliminate these errors.
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
* Code ideas were gathered from **Chris Williams**, **Daisy McGirr** and **Kera Cudmore** GitHub repositories.

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