# Shinrin-Yoku

This is a promotional website for a forest bathing meetup group , one of it's strategies is promote the importance of trees and nature. 

Forest bathing originated in Japan in the 1980s , where it's known as *shinrin-yoku*. It's the practice of walking in any natural environment and consciously connecting with what’s around you

This site will hopefully create a community of people who appreciate trees and nature , and maybe wish to learn more about protecting them in their local city. 

***
## UX

### Scope

This is a fictional meetup group , so this is no limitations on the content . The site will be made to an MVP first , and if there is additional time, content/features will can be added.

#### User stories

- As a visitor to the site, I want to read about forest bathing and it benefits, so that i can decide if i wish to take part.
- As a visitor to the site, I want to register my details , so i can be added to an email list to receive updates.
- As a visitor to the site, I want to view nice pictures of nature.
- As a visitor to the site, I want to read about locations of future forest bathing events.
- As site owner , i want to promote my service and have participants for meetups.
- As site owner , i want to promote the benefits of Trees and nature in our environment. 

### Structure

Site will be put together using HTML, Bootstrap framework and CSS.

Site will be one page with minimum of three sections , suitable for visits from mobile phones.

### Skeleton

#### wireframe.

![initial wireframe](assets/wireframe/Wireframe_1.jpg)

Mobile first approach - one page site , navigation menu at the top. 

Section 1 - Home page - Navbar at top . Hero image below. With brief headline paragraph.

Section 2 - About page - Introduction paragraph followed by various panels of either Text or images promoting forest bathing , in a gallery format.

Section 3 - Contact page - Email subscribe form , contact information and links to various social media channels in footer section.

### Surface

**Colours** : various shades of green or natural colours, colours of site will blend with image colours by using a colour picker.

- --green-bg-light: 135, 170, 75; /* light green background colour

- --green-hg-dark: 80, 100, 45; /* Dark Green colour */*
- *--green-mossy: 125, 188, 143; /* mossy green colour */
- hero text color: white;

- mid section background colour :

- mid section text colour: white;

- Footer background colour:

- Footer icons colour:whitesmoke;


**Icons** used are from fontawesome.com .

**Images** used are one i took myself. 

**Fonts** (sourced from google fonts) used are:  

- Header text elements use the font: **"Shadows Into Light"**, cursive;

- All other text uses the font: **"Montserrat"**, sans-serif;

  


## Features

The site will have be layed out on one page that has several sections .


### Existing Features
- It has a subscription form ( this is for display purposes only , it's not working at the moment as it's out of scope for this phase of the project).

- It is responsive to screen size, the navbar at the top collapses into a hamburger button on smaller screens, one of the image cards in the gallery is hidden on small screens to improve flow of the page.

  

For some/all of your features, you may choose to reference the specific project files that implement them, although this is entirely optional.

In addition, you may also use this section to discuss plans for additional features to be implemented in the future:

### Features Left to Implement
- In the footer section , the icons will incorporate some sort of hover animation
- the images of trees can be clicked on and the user will be brought to another site that pinpoints the exact location of the tree. 
***
## Technologies Used

In this section, you should mention all of the languages, frameworks, libraries, and any other tools that you have used to construct this project. For each, provide its name, a link to its official site and a short sentence of why it was used.

- Languages : HTML , CSS and Bootstrap framework.

- IDE: Gitpod (very similar to Visual Studio code but online).
- Version control: Git and Github
- Browser Developer tools : Firefox Developer Edition and Google Chrome

- KanBan : Github projects . https://github.com/kenwals/shinrin-yoku/projects/1
- Markdown editor: Typora was used when i needed to do large volume of updates, Gitpod editor was used for minor updates.
- Image editing: https://www.adobe.com/ie/photoshop/online/resize-image.html
- Fonts : Google fonts
- Icons : Fontawesome

***
## Testing

In this section, you need to convince the assessor that you have conducted enough testing to legitimately believe that the site works well. Essentially, in this part you will want to go over all of your user stories from the UX section and ensure that they all work as intended, with the project providing an easy and straightforward way for the users to achieve their goals.

Whenever it is feasible, prefer to automate your tests, and if you've done so, provide a brief explanation of your approach, link to the test file(s) and explain how to run them.

For any scenarios that have not been automated, test the user stories manually and provide as much detail as is relevant. A particularly useful form for describing your testing process is via scenarios, such as:

1. Contact form:
    1. Go to the "Contact Us" page
    2. Try to submit the empty form and verify that an error message about the required fields appears
    3. Try to submit the form with an invalid email address and verify that a relevant error message appears
    4. Try to submit the form with all inputs valid and verify that a success message appears.

In addition, you should mention in this section how your project looks and works on different browsers and screen sizes.

You should also mention in this section any interesting bugs or problems you discovered during your testing, even if you haven't addressed them yet.

### Bugs encountered on the way

1. navbar was not expanding collapsing correctly. its turns out i choose the wrong emmet shortcut when starting the site. So the incorrect version of boostrap and javascript was choosen. once i replaced both the navbar worked correctly.
3. Git commit issue , in the beginning i was using only git on the command line . Somehow not all my commits were appearing in Github when i pushed them . the problem maybe linked to me using gitpod in more then one browser (chrome and firefox) while i was trying to debug something else. I resolved this issue by git commiting with the Gitpod UI instead.
4. Page title was too long for mobile phone viewing , it was causing the hamburger button onto a new line. Fix was made by adding a media query to allow the h1 title font size reduced for smaller screens.
5. CSS comments , i made a mistake with the format used initially for commenting in the CSS file. I was using the javascript format (//)for commenting, this resulted in a problem with the colours not displaying correctly for a while in the infant version of the site.


If this section grows too long, you may want to split it off into a separate file and link to it from here.
***
## Deployment

This section should describe the process you went through to deploy the project to a hosting platform (e.g. GitHub Pages or Heroku).

The site was built using an online IDE called gitpod . http://gitpod.io/

The site can deployed easily on gitpod , you first register a free account on http://gitpod.io/, then download the gitpod extension on your preferred internet browser. 
Once you have the extenstion on your browser , a green gitpod button will appear beside this repository in github.

In particular, you should provide all details of the differences between the deployed version and the development version, if any, including:
- Different values for environment variables (Heroku Config Vars)?
- Different configuration files?
- Separate git branch?

In addition, if it is not obvious, you should also describe how to run your code locally.

***
## Credits

### Content

- [Nature therapy ireland](https://www.instagram.com/naturetherapyireland) 
- [Shinrin Yuko Finland]( https://www.shinrin-yoku.fi/home-en)
- [Forest Therapy Society, Japan](https://fo-society.jp/therapy/cn45/e_en.html)
- [Dublin City Council Tree strategy](https://www.dublincity.ie/sites/default/files/media/file-uploads/2018-08/Dublin_City_Tree_Strategy_2016-2020.pdf)
- Bootstrap components
- W3schools
- css tricks 
- youtube videos 

### Media
- The photos used in this site were taken by me mostly around Dublin, Ireland.

### Acknowledgements

- I received inspiration for this project from X

- [This newspaper article from The Irish Times](https://www.irishtimes.com/news/environment/busconnects-final-plans-for-16-dublin-bus-corridors-published-1.4400026 "Irish Times newspaper"). On the back this news article, i decided to make a site that could promote the importance of Trees and why they should be cherished and valued more then wider roads in our cities.

- The book "The Hidden Life of Trees" by Peter Wohlleben 

- Various people at code institute

- Imbibe Coffee Roasters 

  