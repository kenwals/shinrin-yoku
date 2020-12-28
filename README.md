# Shinrin-Yoku

![display of site seen from different devices](assets/readme-files/amiresponsivescreenshot.png)

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

Site is one page with three sections , suitable for visits from mobile phones. Navigation between sections can be done via the navbar or by call to action buttons .

### Skeleton

**Wireframe**

Below is the initial wireframe.

![initial wireframe](assets/wireframe/Wireframe_1.jpg)

Mobile use a first approach - one page site , navigation menu at the top. 

Section 1 - Home page - Navbar at top . Hero image below. With brief headline paragraph. under that a mid section with introduction paragraph.

Section 2 - About page -  Here is displayed various panels of either Text or images promoting forest bathing , in a gallery format.

Section 3 - Contact page - Email subscribe form , contact information and links to various social media channels in footer section.

### Surface

**Colours**

As the site theme is connecting with nature , the colours too are connected to nature. Various shades of green or natural colours are used. Point of referance for the colours of the site are taken from the images using a colour palette tool. 

![demonstration of colour sourcing to image](assets/readme-files/canva_swatch.png)

Root variables are used so colours can be updated quickly if revisions are needed. 

Colours used are:

- "Woodland" Green  #4e5c28 : Used for headings and text when on light background. This colour is used as background on footer. 
- "Green Mist"      #c9d3aa : Used on the background of the body and navbar.
- "Nador" Green     #4F5C54 :  Used on the background of the mid section between hero image and about section.
- "Lemon Grass"     #9da19a : Used for text shadow on the hero image text.
- White                     : used for text.
- Whitesmoke                : used for the footer icons.

![Site colour palette](assets/readme-files/colours-swatch.png)

As colours are configured using rbga properties , these can be tweaked with opactity values to give more variety to the palette while keeping the uniformity. 

**Icons** used are from fontawesome.com . these icons are visible on buttons , each card in the card gallery and in the social media icons in the footer.

**Images** used are ones I took myself. The original high quality images are located [here](https://photos.google.com/share/AF1QipNpAlgEAwPS5Pjltq_81afFH2kgaHUYhmgoE-poGQhNGkx4mknGbwwCHOTYylgYRw?key=bEFOWWloNGJ6REdpbEZDRzVjd3BROWREaEprTXF3).

**Fonts** : 

![Sample of fonts selected](assets/readme-files/google-font-sample.png)

**"Shadows Into Light"** was used for Header (h1,h2 and h3) text elements

**"Montserrat"**​ was used for all other text. 

On slow connections , another font might be swapped in and visible while the site is loading.

##### back to [contents](#table-of-contents)

---

## Features

The site is laid out on one page that has several sections .

### Existing Features

- It is responsive to screen size thanks to bootstrap.

- The navbar at the top collapses into a hamburger button on smaller screens.

- One of the image cards in the gallery is hidden on small screens to improve flow of the page.

- Form validation on subscribe form , alert if name or email is empty. 

- In the first two sections a call to action button prompts the user to another section. 

- In the footer section , the icons will incorporate a hover animation

- Contrasting colours are used to ensure site supports visually impaired visitors.

- The navbar button will float at the top of the screen .

- Some images of trees can be clicked on and the user will be brought to [another site](https://www.curio-eco.com/world/tagged-trees/2538832?lat=53.34427142201096&lng=-6.316257453758462&zml=18) that pinpoints the exact location of the tree.
  
### Features Left to Implement

- Have the subscription form add the visitor to an email list. 

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

- HEX to RGB converter : [RapidTables](https://www.rapidtables.com/convert/color/hex-to-rgb.html) and [](https://www.webfx.com/web-design/hex-to-rgb/)

- Colour contrast checking for Accessibility refinements : [WebAIM](https://webaim.org/resources/contrastchecker/)

- Favicon creater : [favicon.io](https://favicon.io/favicon-generator/)

##### back to [contents](#table-of-contents)  

---
## Testing

I tested the site as i went along , either manual testing myself or automated testing using online tools such a Lighthouse . I focused on getting the site working on a small mobile phone screen first (iPhone 5 simulation on the Chrome Developer tools), and then subsequently all other screen sizes.

Utilities used for testing were:

- lighthouse audit tool in Chrome devtools

- http://ami.responsivedesign.is/

- Peer review on slack

- Simulated Devices on Developer tools in Chrome

- Friends and family .

Devices manually tested browser for the following devices on:  

- Android Mobile phone  (Screen width 360px) 
- Android Mobile phone  (Screen width 412px)
- Android Tablet        (Screen width 600px) sm
- Smart TV              (Screen width 1920px) lg
- Windows laptop        (Screen width 2560px) 

### Bugs encountered on the way

1. Navbar was not expanding collapsing correctly. its turns out i choose the wrong emmet shortcut when starting the site. So the incorrect version of bootstrap and javascript was choosen. Once i replaced both the navbar worked correctly.
3. Git commit issue , in the beginning i was using only git on the command line . Somehow not all my commits were appearing in Github when i pushed them . The problem maybe linked to me using gitpod in more then one browser (chrome and firefox) while i was trying to debug something else. I resolved this issue by git commiting with the Gitpod UI instead.
4. Page title was too long for mobile phone viewing , it was causing the hamburger button onto a new line. Fix was made by adding a media query to allow the h1 title font size reduced for smaller screens.
4. CSS comments , i made a mistake with the format used initially for commenting in the CSS file. I was using the javascript format (//)for commenting, this resulted in a problem with the colours not displaying correctly for a while in the infant version of the site.
5. Images missing on github pages even though they worked in gitpod environment. fix for this was to input a "." in the begining of image file address. 
6. Unable to customize the ul for locations.

### Known issues

1. On medium and larger screens the navbar items flicker after they have been selected.
2. When tested on my smart tv browser, the background colours don't show for hero text , mid section text and footer section. 

### Project barriers and solutions

#### The navbar 

It was desirable to have the navbar menu float at the top of the screen , but i had difficulty getting the menu to collapse itself automatically with Bootstrap or CSS. But I seen [this solution](https://stackoverflow.com/questions/36405991/bootstrap-toggle-menu-on-one-page-site-does-not-uncollapse-when-clicked/36406437#36406437) mentioned on Slack so , I included this trick in the navbar links. 

### Version control

For version control i used the UI on gitpod for making commits. I used branches when i was working on new features , some branchs were scrapped didn't make it to the master.

### Functionality Testing

Navbar : all the links work, this section is reponsive to screen size, menu collapses after item is selected.

Hero image and text: clearly visible/readable , call to action button takes user to the about section.

About section: The card gallery is a template taken from the bootstrap framework library . it's reponsive to screen size off the shelf. No isues found. 

email link: This behaves as expected, the link should trigger the users browser to open a new window for composing an email , the To field and the subject field should be prepopulated.

Subscription form : The form displays validation messages if fields are blank when the subscribe button is pressed. 

Footer section : All icons animate when the mouse is hovering over them, each icon links to a new page.

Devices manually tested browser for the following devices on:  

- Android Mobile phone  (Screen width 360px) 
- Android Mobile phone  (Screen width 412px)
- Android Tablet        (Screen width 600px) sm
- Smart TV              (Screen width 1920px) lg
- Windows laptop        (Screen width 2560px)  

### CSS3 validator 

Initially I did get errors ,  x y z  .  a Problem with jigsaw is that it does not recognise root variables and rgba combinations. [source](https://stackoverflow.com/questions/57661659/w3c-css-validation-parse-error-on-variables)

### HTML5 validator

Initially I did typos and invalid synthax , all issues resolved .  No errors to report now.

### Usability Testing

I shared the project on the peer review channel and also with frends/family. No major usability issues were raised.

Lighthouse Accessibility validation gave me interesting insights on issues that would impact visually imparied visitors to the site, as a result i made efforts to improve access for this audience. 

### Compatibility Testing

| Screen size\Browser                          | Chrome | Firefox | Edge |
| -------------------------------------------- | ------ | ------- | ---- |
| Android Mobile phone (Screen width 360px) xs |        |         |      |
| Android Mobile phone (Screen width 412px) xs |        |         |      |
| Android Tablet (Screen width 600px) sm       |        |         |      |
| Smart TV (Screen width 1920px) lg            |        |         |      |
| Windows laptop (Screen width 2560px)         |   pass |  pass |  pass    |


### Performance Testing


Lighthouse Performance report highlighted issues for me in regard to images  xyz , so i xyz

### Testing User Stories

1. As a visitor to the site, I want to read about forest bathing and it's benefits, so that I can decide if I wish to take part.

*There is bit size pieces of information spread around the home page section and the about page section.*

2. As a visitor to the site, I want to register my details , so I can be added to an email list to receive updates.

*This can be achieved on the contact page section.*

3. As a visitor to the site, I want to view nice pictures of nature.

*Various pictures are used on each section of the site.*

4. As a visitor to the site, I want to read about locations of future forest bathing events.

*A list of locations is available on the secord card in the about page section.*

5. As the site owner , I want to promote my service and have participants for meetups.

*The site is structured to load up fast to avoid bounce from visitors , it also prompts the user to sign up their contact details if they wish the hear more.*

6. As the site owner , I want to promote the benefits of Trees and nature in our environment. 

*Various facts about trees and nature are displayed in the about page section.* 

##### back to [contents](#table-of-contents)

---
## Deployment

For easy deployment on github pages you will need a Github user account and a possibly a Gitpod user account. If you wish to make changes to this repository , please follow the Github steps first. 

**Github**

Github is a code hosting platform for version control and collaboration. It's free to enroll for a user account and i would recommend you have one if you wish to deploy this repository and make changes.

When you have a Github account you can simple click on the Fork button on the top right corner. This is clone the Shinrin-Yuko repository for your Github account, then you can make any changes you like.

**Gitpod**

The site can edited easily on a gitpod online workspace, you first register a free user account on http://gitpod.io/, then download the gitpod extension on your preferred internet browser. On signing up you will be expected to  have a Github user account.

Once you have the extension on your browser , a green gitpod button will appear beside this repository in github. for best results fork the repository in your personal account before you open it in Gitpod.

**Github Pages**

Once you have the completed site in your own repository, you can deploy to Github pages by the following steps.

1. On Github, go to the completed sites repository.
2. Click on settings, on the settings page scroll down the the Github Pages section. .
3. Under Github pages Select the appropriate branch or folder the index.html is in. 
4. Click on save . A message should then appear advising the URL of your deployed site.

**Cloning**

If you prefer working on the repository locally, you can clone the repository to your desktop by the following steps.

1. Go to [the Shinrin-Yuko github page](https://github.com/kenwals/shinrin-yoku) .
2. above the list of files , click on the code button.
3. - To clone the repository using HTTPS, under "Clone with HTTPS", click the paste icon. 
   - To clone the repository using an SSH key, click Use SSH, then click the paste icon . 
   - To clone a repository using GitHub CLI, click Use GitHub CLI, then click the paste icon.
4. Open Git Bash.
5. Change the current working directory to the location where you want the cloned directory.
5. Type 'git clone' , then paste the URL you copied earlier above. 
6. Press Enter to create your local clone.



##### back to [contents](#table-of-contents)  

---
## Credits

### Content

- [Nature therapy ireland](https://www.instagram.com/naturetherapyireland) 
- [Shinrin Yuko Finland](https://www.shinrin-yoku.fi/home-en)
- [Forest Therapy Society,Japan](https://fo-society.jp/therapy/cn45/e_en.html)
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

- The photos used in this site were taken by me mostly in Dublin, Ireland. [Album available here](https://photos.google.com/share/AF1QipNpAlgEAwPS5Pjltq_81afFH2kgaHUYhmgoE-poGQhNGkx4mknGbwwCHOTYylgYRw?key=bEFOWWloNGJ6REdpbEZDRzVjd3BROWREaEprTXF3).

### Acknowledgements

- [This newspaper article from The Irish Times](https://www.irishtimes.com/news/environment/busconnects-final-plans-for-16-dublin-bus-corridors-published-1.4400026 "Irish Times newspaper"). On the back this news article, I was inspired to make a site that could promote the importance of Trees and why they should be cherished and valued more then wider roads in our cities.

- The book ["The Hidden Life of Trees"](https://www.goodreads.com/book/show/28256439-the-hidden-life-of-trees) by Peter Wohlleben .

- Various people at [code institute](https://codeinstitute.net/).

- [Imbibe](https://imbibe.ie/) Coffee Roasters and [Barry's Tea](https://www.barrystea.ie/).

 ##### back to [contents](#table-of-contents)   
