# Shinrin-Yoku


This is a promotional website for a forest bathing meetup group , one of it's strategies is promote the importance of trees and nature. 

Forest bathing originated in Japan in the 1980s , where it's known as *Shinrin-Yoku*. It's the practice of walking in any natural environment and consciously connecting with what’s around you.

This site will hopefully create a community of people who appreciate trees and nature, and maybe wish to learn more about protecting them in their local city. 

---

## Table of contents


1. [**UX**](#ux)

2. [**Features**](#features)

3. [**Technologies Used**](#technologies-used)

4. [**Testing**](#testing)

5. [**Deployment**](#deployment)

6. [**Credits**](#credits)

---

## UX

### Scope

This is a fictional meetup group, so there is no limitations on the content . The site will be made to an MVP first, and if there is additional time, content/features will can be added.

**User stories**

1. As a visitor to the site, I want to read about forest bathing and it's benefits, so that I can decide if I wish to take part.
2. As a visitor to the site, I want to register my details , so I can be added to an email list to receive updates.
3. As a visitor to the site, I want to view nice pictures of nature.
4. As a visitor to the site, I want to read about locations of future forest bathing events.
5. As the site owner , I want to promote my service and have participants for meetups.
6. As the site owner , I want to promote the benefits of Trees and nature in our environment. 

### Structure

Site is put together using HTML, the Bootstrap framework and CSS.

Site is one page with minimum of three sections , suitable for visits from mobile phones. Navigation between sections can be done via the navbar or by call to action buttons .

### Skeleton

**Wireframe**

Below is the initial wireframe.

![initial wireframe](assets/wireframe/Wireframe_1.jpg)

Mobile use a first approach - one page site , navigation menu at the top. 

Section 1 - Home page - Navbar at top . Hero image below. With brief headline paragraph.

Section 2 - About page - Introduction paragraph followed by various panels of either Text or images promoting forest bathing , in a gallery format.

Section 3 - Contact page - Email subscribe form , contact information and links to various social media channels in footer section.

### Surface

**Colours**

As the site theme is connecting with nature , the colours too are connected to nature. Various shades of green or natural colours are used. Point of referance for the colours of the site are taken from the images using a colour palette tool. 

![Sample Colour palette](assets/readme-files/canva_swatch.png)

Root variables are used so colours can be updated quickly if revisions are needed. 

Colours used are:

- "Woodland" Green : Used for headings and text when on light background. This colour is used as background on footer and on the navigation buttons. 
- "Green Mist": Used on the background of the body.
- "Olivine" Green:
- "Nador" Green :  Used on the background of the mid section between hero image and about section.
- "Lemon Grass" colour: Used for hoover shadow on footer icons.
- White : used for text.
- Whitesmoke : used for the footer icons.


As colours are configured using rbga properties , these can be tweaked with opactity values to give more variety to the palette while keeping the uniformity. 

**Icons** used are from fontawesome.com .

**Images** used are one I took myself. 

**Fonts** :  Header (h1,h2 and h3) text elements use the font:  **"Shadows Into Light"**.

​				All other text uses the font:  **"Montserrat"**. 


![Sample of fonts selected](assets/readme-files/google-font-sample.png)

##### back to [contents](#table-of-contents)

---

## Features

The site is laid out on one page that has several sections .

### Existing Features

- It is responsive to screen size thanks to bootstrap.

- The navbar at the top collapses into a hamburger button on smaller screens.

- One of the image cards in the gallery is hidden on small screens to improve flow of the page.

- It has a subscription form ( this is for display purposes only , it's not working at the moment as it's out of scope for this phase of the project).

- Form validation on subscribe form , alert if name or email is empty. 

- In each section a call to action button will prompt / take the user to another section. 

- In the footer section , the icons will incorporate some sort of hover animation

- Improvements for visually impaired such as more descriptive tags and better contrasting colours (as per lighthouse report)
  

### Features Left to Implement ( or out of scope)

- The images of trees can be clicked on and the user will be brought to [another site](https://www.curio-eco.com/world/tagged-trees/2538832?lat=53.34427142201096&lng=-6.316257453758462&zml=18) that pinpoints the exact location of the tree. 

- Have the subscription form add the visitor to an email list.

- The navbar button will float on the top of the screen .

 ##### back to [contents](#table-of-contents)

---
## Technologies Used

- Languages : HTML , CSS and Bootstrap framework (Navbar uses Javascript).

- IDE: [Gitpod](https://www.gitpod.io/) (very similar to Visual Studio code but online).

- Version control: Git on [Gitpod](https://www.gitpod.io/) and [Github](https://github.com/).

- Wireframe: [Balsamiq](https://balsamiq.com/)

- Browser Developer tools : [Google Chrome](https://www.google.com/chrome) and [Firefox Developer Edition](https://www.mozilla.org/en-US/firefox/developer/) (really helped with fonts and images).

- KanBan planner : [Github projects](https://github.com/kenwals/shinrin-yoku/projects/1) . 

- Markdown editor: [Typora](https://typora.io/) was used when doing bulk updates to my README.md file, Gitpod editor was used for minor updates.

- Image editing: [Adobe online resize tool](https://www.adobe.com/ie/photoshop/online/resize-image.html) and [tinypng](https://tinypng.com/) compression tool.

- Fonts : [Google Fonts](https://fonts.google.com/)

- Icons : [Fontawesome](https://fontawesome.com/)

- Colours palette : [Canva](https://www.canva.com/colors/color-palette-generator/)

- Colour tool : [Google Material Design Color Tool](https://material.io/resources/color/#!/?view.left=0&view.right=1&secondary.color=9db769&primary.color=4e5c28&secondary.text.color=000000&primary.text.color=ffffff)

- Misc Planning: MS Excel was used for filename changes planning and making the names lowercase.

- Pomodoro timer : [Tomato Clock](https://chrome.google.com/webstore/detail/tomato-clock/enemipdanmallpjakiehedcgjmibjihj)

- Overflow rescue tool : [Unicorn Revealer](https://chrome.google.com/webstore/detail/unicorn-revealer/lmlkphhdlngaicolpmaakfmhplagoaln)

- HEX to RGB converter : [RapidTables](https://www.rapidtables.com/convert/color/hex-to-rgb.html)

- Colour contrast checking for Accessibility refinements : [WebAIM](https://webaim.org/resources/contrastchecker/)

##### back to [contents](#table-of-contents)  

---
## Testing

In this section, you need to convince the assessor that you have conducted enough testing to legitimately believe that the site works well. Essentially, in this part you will want to go over all of your user stories from the UX section and ensure that they all work as intended, with the project providing an easy and straightforward way for the users to achieve their goals.

Whenever it is feasible, prefer to automate your tests, and if you've done so, provide a brief explanation of your approach, link to the test file(s) and explain how to run them.

For any scenarios that have not been automated, test the user stories manually and provide as much detail as is relevant. A particularly useful form for describing your testing process is via scenarios, such as:

Test being used will be:

- [web.dev](https://web.dev/measure/) (lighthouse)

- http://ami.responsivedesign.is/

- Peer review on slack

- Devices on Developer tools in Chrome and Firefox DE



Devices manually tested browser for the following devices on:  

- Android Mobile phone (Screen width 360px) 
- Android Mobile phone (Screen width 412px)
- Android Tablet (Screen width 600px) sm
- Smart TV (Screen width 1920px) lg
- Windows laptop (Screen width 2560px) 



1. Contact form:
    1. Go to the "Contact Us" page
    2. Try to submit the empty form and verify that an error message about the required fields appears
    3. Try to submit the form with an invalid email address and verify that a relevant error message appears
    4. Try to submit the form with all inputs valid and verify that a success message appears.

In addition, you should mention in this section how your project looks and works on different browsers and screen sizes.

You should also mention in this section any interesting bugs or problems you discovered during your testing, even if you haven't addressed them yet.

### Bugs encountered on the way

1. Navbar was not expanding collapsing correctly. its turns out i choose the wrong emmet shortcut when starting the site. So the incorrect version of bootstrap and javascript was choosen. once i replaced both the navbar worked correctly.
3. Git commit issue , in the beginning i was using only git on the command line . Somehow not all my commits were appearing in Github when i pushed them . the problem maybe linked to me using gitpod in more then one browser (chrome and firefox) while i was trying to debug something else. I resolved this issue by git commiting with the Gitpod UI instead.
4. Page title was too long for mobile phone viewing , it was causing the hamburger button onto a new line. Fix was made by adding a media query to allow the h1 title font size reduced for smaller screens.
4. CSS comments , i made a mistake with the format used initially for commenting in the CSS file. I was using the javascript format (//)for commenting, this resulted in a problem with the colours not displaying correctly for a while in the infant version of the site.
5. text shadow typo mistake
6. images missing on github pages even though they worked in gitpod environment. 
7. unable to customize the ul for locations

### Known issues

1
2. When tested on my smart tv browser, the background colours don't show for hero text , mid section text and footer section. 
3.

### Project barriers and solutions

The navbar 

It was desirable to have the navbar menu float at the top of the screen , but i had difficulty getting the menu to collapse itself automatically with Bootstrap or CSS. I believe it's dependant on Javascript code, and Javascript is out of scope for this phase of the project. But I will review this again in future and hope to impove the UX for navigation.

### Version control

For Verions control i used the UI on gitpod for making commits. I used branches when i was working on new features , some branchs were scrapped didn't make it to the master.

### Functionality Testing

Devices manually tested browser for the following devices on:  

- Android Mobile phone (Screen width 360px) 
- Android Mobile phone (Screen width 412px)
- Android Tablet (Screen width 600px) sm
- Smart TV (Screen width 1920px) lg
- Windows laptop (Screen width 2560px) 

### CSS3 validator 

Initially I did get errors ,  x y z  .  a Problem with jigsaw is that it does not recognise root variables and rgba combinations. 

### HTML5 validator

Initially I did get errors ,  x y z  .  No errors to report now.

### Usability Testing

I shared the project on the peer review channel and also with firends. No Usability issues were raised with me.

### Compatibility Testing

| Screen size\Browser                          | Chrome | Firefox | Edge |
| -------------------------------------------- | ------ | ------- | ---- |
| Android Mobile phone (Screen width 360px) xs |        |         |      |
| Android Mobile phone (Screen width 412px) xs |        |         |      |
| Android Tablet (Screen width 600px) sm       |        |         |      |
| Smart TV (Screen width 1920px) lg            |        |         |      |
| Windows laptop (Screen width 2560px)         |   pass |  pass |  pass    |


### Performance Testing

### Testing User Stories

1. As a visitor to the site, I want to read about forest bathing and it's benefits, so that I can decide if I wish to take part.
2. As a visitor to the site, I want to register my details , so I can be added to an email list to receive updates.
3. As a visitor to the site, I want to view nice pictures of nature.
4. As a visitor to the site, I want to read about locations of future forest bathing events.
5. As the site owner , I want to promote my service and have participants for meetups.
6. As the site owner , I want to promote the benefits of Trees and nature in our environment. 

##### back to [contents](#table-of-contents)

---
## Deployment

For easy deployment you will need a Github user account and a Gitpod user account. If you wish to make changes to this repository , please follow the Github steps first. 

**Github**

Github is a code hosting platform for version control and collaboration. It's free to enroll for a user account and i would recommend you have one if you wish to deploy this repository and make changes.

When you have a Github account you can simple click on the Fork button on the top right corner. This is clone the Shinrin-Yuko repository for your Github account, then you can make any changes you like.

**Gitpod**

The site can deployed easily on a gitpod online workspace, you first register a free user account on http://gitpod.io/, then download the gitpod extension on your preferred internet browser. On signing up you will be expected to  have a Github user account.

Once you have the extension on your browser , a green gitpod button will appear beside this repository in github. for best results fork the repository in your personal account before you open it in 

Differences between the deployed version and the development version:
- none!

##### back to [contents](#table-of-contents)  

---
## Credits

### Content

- [Nature therapy ireland](https://www.instagram.com/naturetherapyireland) 
- [Shinrin Yuko Finland](https://www.shinrin-yoku.fi/home-en)
- [Forest Therapy Society, Japan](https://fo-society.jp/therapy/cn45/e_en.html)
- [Dublin City Council Tree strategy](https://www.dublincity.ie/sites/default/files/media/file-uploads/2018-08/Dublin_City_Tree_Strategy_2016-2020.pdf)

### Resources


- [Bootstrap components](https://getbootstrap.com/)
- [W3schools](https://www.w3schools.com/)
- [Code institute's Slack workspace channels](https://slack.com)
- [CSS tricks](https://css-tricks.com/) 
- [YouTube](https://www.youtube.com/)
- [Stack Exchange](https://stackexchange.com/)
- [Hover.css](https://ianlunn.github.io/Hover/#effects)
- [MDN Web Docs](https://developer.mozilla.org/en-US/)

### Media

- The photos used in this site were taken by me mostly in Dublin, Ireland.

### Acknowledgements

- [This newspaper article from The Irish Times](https://www.irishtimes.com/news/environment/busconnects-final-plans-for-16-dublin-bus-corridors-published-1.4400026 "Irish Times newspaper"). On the back this news article, I was inspired to make a site that could promote the importance of Trees and why they should be cherished and valued more then wider roads in our cities.

- The book ["The Hidden Life of Trees"](https://www.goodreads.com/book/show/28256439-the-hidden-life-of-trees) by Peter Wohlleben .

- Various people at [code institute](https://codeinstitute.net/)

- [Imbibe](https://imbibe.ie/) Coffee Roasters and [Barry's Tea](https://www.barrystea.ie/)

 ##### back to [contents](#table-of-contents)   
