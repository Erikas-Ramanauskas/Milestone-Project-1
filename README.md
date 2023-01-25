<h1 align="center">Brick By brick Website</h1>

[View the live project here.](https://erikas-ramanauskas.github.io/Milestone-Project-1/)

This is a website for "Brick by brick" bricklyer company. It is created to be responsible on all range of devices informing any visitor of hat the companies services and goals are as well as helping to find new clients

<h2 align="center"><img src=""></h2>

## User Experience (UX)

### Main idea

Brick By Brick is a website for team of bricklayers who specialises in brickwork based around London. The purpose of website is to inform of the services team provides as well as capture potential leads quickly.

Goal of each section is to answer main qestions:

- Team expirenece
- Team vision
- Past projects
- What they are able to offer.
- How to find them and contact them

- ### User stories

  - #### First Time Visitor Goals

    1. Understand clearly hat the site is representing and able to offer.
    2. Quickly find out what the team can offer.
    3. Have multiple clear ways to contact the team.
    4. Accses clear vissable review section

  - #### Returning Visitor Goals

    1. I want to find out were are their based and visit their showroom
    2. Have easy and clear acsess to get more information about their past projects
    3. I want to find social media links

  - #### Frequent User Goals

    - Fequent users would be a contractors who works with developemtns on daily basis and they would be recomending the company to regular clients. Main purpose is to have clear Contact section

  1.  Easy acsess to teams perofile and what they did in the past.
  2.  Clear contact details and the form to fill in.
  3.  Check up with Brick by Brick owners and have their projects added to a galery.

- ### Design

  - #### Colour Scheme

    - 5 main colours used were created using [Adobe Color](https://color.adobe.com/create/color-wheel) website.

    I used several brick pictures and played diferent shades to get few darker colours that landed me on the fallowing list:

    ```CSS
    :root {
    --primary-color: rgb(242, 211, 172);
    --secondary-color: rgb(166, 119, 78);
    --third-color: rgba(89, 64, 54, 0.5);
    --shade-color: rgb(191, 146, 120);
    --shadow-color: rgb(38, 30, 27);
    }
    ```

    I used variables to allow me in a future to change colours or add dark mode or other themes to the website. The text is made of white colour mostly with added dark shadow were the texts is directly on the picture for better visability.

- #### Typography

  - I used mix of Roboto, Saira and Archivo fonts

Roboto is a main font i used for for larger pieces of text. for main section as well as about us section

Saira was used for contact details in a navigation bar

Archivo was kept for Navigation links, Contact details and Headers.

- #### Imagery

- Head image is chosen to be a clear indication for what is the company about. It is full screen on every device and only covered by navigation bar and Hero-outer that are also semi transperant. It is also made to be responsive and hide a parts of picture depending on a screen size yet keaping the main part of the picture (Hand with a brick) centered

- All other Immagery is chosen real projects done by the company.

* ### Wireframes

  - Home Page Wireframe - [View]()

  - Mobile Wireframe - [View]()

  - Contact Us Page Wireframe - [View]()

## Features

The website is combined of 4 pages: Home, About us, Galery and Contact us pages.

### Header / Footer

- All of pages contain same header and footer with navigation links. Apart Home one having extended header. I chose a picture that would not only clearly would represent exacly what the company/website is about but also would have clear brick contrast behind a navigation bar as a client browses to other pages. Additionaly the colours of the picture allowed me to blen it in with bacgroudn and other chosen colours.

- Header contains of svg logo that draws it self once the page is open, the title of the the company, navigation bar for all 4 pages and main contact lins: Phone and Email.This was implemented to to have easy accses for the user to all the important links and quick accses to contacting the team for consultation.

- Footer contains animation responsive 4 social media links for a visitor to visit if they wish to check social media of Brick by Brick.

### Home page

- Home page header picture is extended 100% screen size height and containing additional hero outer with quick catchy summary of what the company does with clear call to action button to fill in the form by the visitor.

- The main section consist of 4 parts. Three parts briefly explaining what is a company about, what services do they offer and the last one is customer review carousel for visitors to view recomendations. I have alternated a background colours for each part to make them stand out from each other.

### About us page

- About us page consist of 2 parts. One is an explanation about general Brick by Brick team and the second is individual member profiles. Each profile is made in to a card with picture at the top and text below.

### Galery page

- Galery is consisting of responsive picture layout of Companies works.
  It is designed with intent that with smaller screen sizes less of pictures are added per row and more pictures when screen sizes gets bigger.

- Additionaly user can scrol their mouse on each picture to have animation reveling the general lociation and the project done for that particular picture.For phones and tables this is done with a click on the picture

### Contact page

- contact page is designed for people who ould like to get a quotation or directly contact the company them selves.
- With first section at the row having main ways to contact or visit including email, phone, and adress. For people who ould like to copy/paste the contact detail i left those unclickable, however the titles (Phone, Email, Lociation) are made with links and hover animation to allow both functionalities in a same section.

- Additional form is added as a second section for those who might have missed in a home page with same functionality just in a different colours and hover effects.

- Lastly the google maps is added for people who would be looking to visit showroom

---

## Technologies Used

### Languages Used

- [HTML5](https://en.wikipedia.org/wiki/HTML5)
- [CSS3](https://en.wikipedia.org/wiki/Cascading_Style_Sheets)

### Frameworks, Libraries & Programs Used

1. ## [Bootstrap 5.3:](https://getbootstrap.com/docs/5.3/getting-started/introduction/)

- Used Botstrap to add resposivnes to a werbsite and making sure it looks good on all screen sizes.

2. [Google Fonts:](https://fonts.google.com/)

- Used to add custom fonts to the website.

3. [Font Awesome:](https://fontawesome.com/)

- Used to add custom icons to enhance user expirenece and navigation

5. [Visual Studio Code](https://code.visualstudio.com/)

- For mijority of programing and version control

6. [Git](https://git-scm.com/)

- Git was used for version control by utilizing the Gitpod terminal to commit to Git and Push to GitHub.

7. [GitHub:](https://github.com/)

- Used to store and publish the project to web

8. [Figma:](https://www.figma.com/)
   - Figma was used to create the [wireframes](https://github.com/) during the design process.

## Testing

The W3C Markup Validator and W3C CSS Validator Services were used to validate every page of the project to ensure there were no syntax errors in the project.

- [W3C Markup Validator](https://validator.w3.org/) - [Results](https://github.com/)
- [W3C CSS Validator](https://jigsaw.w3.org/css-validator/) - [Results](https://github.com/)

Additionaly tested the website on chrome lighthouse to ensure that 4 categories: Performance, Accessibility, Best practices and SEO are to highest Standarts.

Test were done for all 4 pages using mobile set up:

<h2 align="center"><img src=""></h2>

- [Chrome Lighthouse](https://developer.chrome.com/docs/lighthouse/overview/)- [Results](https://github.com/)

### Further Testing

- The Website was tested on Google Chrome, Internet Explorer, Microsoft Edge and Safari browsers.
- The website was viewed on a variety of devices such as Desktop, Laptop, iPhone7, iPhone 8 & iPhoneX.
- A large amount of testing was done to ensure that all pages were linking correctly.
- Friends and family members were asked to review the site and documentation to point out any bugs and/or user experience issues.

### Known Bugs

- Once opened on smaller devices the hamburger Menu opens automaticaly

## Deployment

### GitHub Pages

The project was deployed to GitHub Pages using the following steps...

1. Log in to GitHub and locate the [GitHub Repository](https://github.com/Erikas-Ramanauskas/Milestone-Project-1)
2. At the top of the Repository (not top of page), locate the "Settings" Button on the menu.
   - Alternatively Click [Here](https://raw.githubusercontent.com/) for a GIF demonstrating the process starting from Step 2.
3. Scroll down the Settings page until you locate the "GitHub Pages" Section.
4. Under "Source", click the dropdown called "None" and select "Master Branch".
5. The page will automatically refresh.
6. Scroll back down through the page to locate the now published site [link](https://erikas-ramanauskas.github.io/Milestone-Project-1/) in the "GitHub Pages" section.

### Forking the GitHub Repository

By forking the GitHub Repository we make a copy of the original repository on our GitHub account to view and/or make changes without affecting the original repository by using the following steps...

1. Log in to GitHub and locate the [GitHub Repository](https://github.com/Erikas-Ramanauskas/Milestone-Project-1)
2. At the top of the Repository (not top of page) just above the "Settings" Button on the menu, locate the "Fork" Button.
3. You should now have a copy of the original repository in your GitHub account.

### Making a Local Clone

1. Log in to GitHub and locate the [GitHub Repository](https://github.com/Erikas-Ramanauskas/Milestone-Project-1)
2. Under the repository name, click "Clone or download".
3. To clone the repository using HTTPS, under "Clone with HTTPS", copy the link.
4. Open Git Bash
5. Change the current working directory to the location where you want the cloned directory to be made.
6. Type `git clone`, and then paste the URL you copied in Step 3.

```
$ git clone https://github.com/YOUR-USERNAME/YOUR-REPOSITORY
```

7. Press Enter. Your local clone will be created.

```
$ git clone https://github.com/YOUR-USERNAME/YOUR-REPOSITORY
> Cloning into `CI-Clone`...
> remote: Counting objects: 10, done.
> remote: Compressing objects: 100% (8/8), done.
> remove: Total 10 (delta 1), reused 10 (delta 1)
> Unpacking objects: 100% (10/10), done.
```

Click [Here](https://help.github.com/en/github/creating-cloning-and-archiving-repositories/cloning-a-repository#cloning-a-repository-to-github-desktop) to retrieve pictures for some of the buttons and more detailed explanations of the above process.

## Credits

### Prior to the course

- Prior to the course i was self learning HTML, CSS and Javascript from multiple sources thus i had some basic knoweladge and references to different websites or sources for a different ideas of the project that i will mention below.

### Code

- The full-screen hero image code came from this [Adobe Stock](https://stock.adobe.com/uk/images/id/117356918?clickref=1011lwvzCN3L&mv=affiliate&mv2=pz&as_camptype=&as_channel=affiliate&as_source=partnerize&as_campaign=wbm)

- [Bootstrap4](https://getbootstrap.com/docs/5.3/getting-started/introduction/): Bootstrap Library used throughout the project mainly to make site responsive using the Bootstrap Grid System.

- With bootstrap a lot of help came from [Web Dev Simplified](https://www.youtube.com/watch?v=Jyvffr3aCp0&t=870s) chanel and this particular video. I also have to give credit to multiple ideas and HTML and CSS code details or ideas that came from this chanel spread out though multiple videos.

- Another youtube content creator [Kevin Powell](https://www.youtube.com/@KevinPowell) helped me with a lot of concepts when it came to using CSS, specificaly "var()" for a colour cheme, "rem" for measurments, "calc()" and many more.

- Multiple references to the code and adjustmens during research on improvements or bug fixes were found on [W3 Schools](https://www.w3schools.com/) as well as [MDN website](https://developer.mozilla.org/en-US/)

- SVG logo drawing was made learning from [Jakob Jenkov](https://www.youtube.com/watch?v=k6TWzfLGAKo&t=243s) and the animation pathing was done by learnign [this tutorial](https://www.cassie.codes/posts/creating-my-logo-animation/)

- Galery card hover effect ide insipered by [This video](https://www.youtube.com/watch?v=E2TW4ZxXrsI&t=683s). and vith combination of [MDN Transition](https://developer.mozilla.org/en-US/docs/Web/CSS/transition) i worked out what i anted to do with my card design.

- Google maps was a simple copy paste code from [Google maps](https://www.google.com/maps) website by searching for address then having option to press buton "Share", which led to "Embed a map" were the code is found and coudl be copy pasted

- Hamburger button effect was made using [This video](https://www.youtube.com/watch?v=vJ85fm4m7lw).

- Navigation link hover effect idea come from [This video](https://www.youtube.com/watch?v=aswRKAjjWuE)

### Content

- All content was written by the developer.

### Media

- All Images apart from hero immage were created by developers friend with full authority rights given to developer.

### Acknowledgements

- My Mentor for continuous helpful feedback.

- Tutor support at Code Institute for their support.

- Multiple friends for giving me a feedback
