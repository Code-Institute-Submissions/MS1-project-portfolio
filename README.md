# MS1-PROJECT-PORTFOLIO


I chose to make a portfolio as my first project in this course as a basis in order to build my brand outwards when I apply for a job. My target group is primarily recruiters and future employers. 
I want to demonstrate my strengths' in programming as well as an idea of who I am as a person to facilitate my target group's quest for a future employee.

---

# Table of contents

* [Inspiration](#Inspiration)
* [UX](#UX)
* [Screenshots](#screenshots)
* [Features](#features)
* [Testing](#testing)
* [Technologies](#technologies)
* [Code](#code/sources)
* [Deployment](#deployment)
* [Contact](#Contact)

---

## Inspiration


I got a lot of inspiration from Apple's website as I wanted it very clean just like their website. I was also in other people's portfolios and checked a bit how they had done on their websites. but mostly it was to google around on pages I like and see how they did.


---

# UX

My UX goals was to create a website that displayed my programming strengths' and personality to my target group (recruiters and future employers). 

#  User stories

##  First Time Visitor Goals

* When I visit this site for the first time, I want to easily understand the main purpose of the site.
* When I visit this site for the first time, I want to be able to easily navigate throughout the site to find relevant content.
* When I visit this site for the first time, I want to get a professional impression of the person which the site is created by. 

## Returning Visitor Goals

* As a Returning Visitor, I want to find information about previous projects from the creator.
* As a Returning Visitor, I want to find the best way to get in contact with the creator with any questions I may have.
* As a Returning Visitor, I want to get a more in-depth presentation of the person creating the site.

##  Frequent User Goals

* As a Frequent User, I want to check to see if there are any new projects updated.
* As a Frequent User, I want to check to see if there are any new skills updated.

# Features

## Existing Features

* Feature 1 - A navigation bar for users so they can navigate throw the page nice and smooth.
* Feature 2 - A skills section for recruiters so they easy can get a picture of what i can.
* Feature 3 - Timeline and contact section that also show recruiters what i have done before and how to get in touch with me. 
* Feature 4 - A contactform for people to contact me.
* Feature 5 - Footer with social media links and a link to download my resume.

## Feature ideas to Implement

* I have an idea of makeing a nicer frontpage header with js
* The project section i wan't to do like a carusell thing so the pictures are much bigger and to add text on the pictures. This also whit js.
* Fix the submit button so the form works.
* The project section is for projects i do in the future, for now i its just examples.

---

# Screenshots

This is a picture before my first mentor call my code were broken and things weren't were its supposed to be. 

1. At first i had a grayscale on my background pic whitch looks nicer whitout.
2. Several parts was "broken" in terms of alignment, mostly on mobile and tablets.
3. I had alot of problems with the navigation bar, it broke on mobile and tablets. 
4. In the beginning i didn´t use boostrap so much and i became a problem further in the project.

![alternativetext](assets/images/screen3.png)

This are pictures when im almost finished. 

1. First i choosed to have the background picture cover the whole front page. Then i took away the grayscale becuse it looks more nice without it.
2. I fixed the broken parts mostly the navbar so it fits mobile and tablets. I used media Querys to solve most problems with the navbar and profilepicture. then i started to use bootstraps "row" and "col" to solve the alignment issues i had on the page. 


![alternativetext](assets/images/screen.png)


![alternativetext](assets/images/screen2.png)


---

# Testing

### My methods for testing my webpage consisted of:

* Using the inspector tool to test if the page was responsive on serveral different devices and browsers. 
* Having other people around me try to navigate the page and look for bugs that I didn't catch myself.
* Code validator.
* In the future I plan to implement automated tests.

### Testing User Stories from UX Section

##  First Time Visitor Goals

* When I visit this site for the first time, I want to easily understand the main purpose of the site.
    - When entering the site, there is a big headline with my name and profession, strongly indicating that this is a portfolio.
    - By clicking on the links in the navigation bar, or scrolling down, the user is lead to more sections which contains information about me and relevant information for a recruiter.
* When I visit this site for the first time, I want to be able to easily navigate throughout the site to find content.
    - At the top of the page there is a navigation bar, each link describes what the page contents of.
* When I visit this site for the first time, I want to get a professional presentation of the person which the site is created by.
    - I've done a lot of bug testing to make sure that the user is left with a site that is well-working.
    - I went for a clean look that doesn't contain irrelevant information or annoying colors and images.  

## Returning Visitor Goals

* As a Returning Visitor, I want to find information about previous projects from the creator.
    - There is distinct link in the navigation called "projects" that leads to the projects section.
    - I have several examples of previous projects in the project section, which leads to more information about each one.
* As a Returning Visitor, I want to find the best way to get in contact with the creator with any questions I may have.
    - In the top navigation there is a "contact" link that leads the user to a section with a form which they can use to get in touch via email.
* As a Returning Visitor, I want to get a more in-depth representation of the person creating the site.
    - In the "contact" section I have a small presentation text that aims to explain a little more about me as person and why I started my journey to become a full-stack developer.
    - I also have links in the footer, that leads to my facebook, github, linkedIn and CV.

##  Frequent User Goals

* As a Frequent User, I want to check to see if there are any new projects updated.
    - By simply clicking the "projects" link the navigation, the user can check the projects section and see if there are any new projects since the newest projects will be displayed first in line.
* As a Frequent User, I want to check to see if there are any new skills updated.
    - By clicking the "skills" link in the navigation, the user can check the skills section and see if there are any new skills by checking the progress bars or the logos for each programming skill.


### Here is some examples of bugs that I encounterd during testing:

* After trying to implement a responsive page, I didn't get the navigation bar to work correctly on smaller devices.
1. When viewing the page on mobile or a tablet, the navigation bar had been switched into a dropdown "hamburger" menu. But when clicking on the hamburger icon, the dropdown didn't drop down to show the menu options.
2. I solved this by adding an invisible checkbox that was layered above the hamburger icon. This way I could check for when the dropdown menu was clicked using the :checked selector in css. When the checkbox was checked I made the dropdown menu visible.

* During testing I also found an issue when viewing tablet devices. The problem was that I didn't get it correctly responsive for Ipad.
1. Using the inspector tool, I tested the page on a Ipad view. 
2. After looking for bugs in the Ipad view, I noticed that some of the different sections where meshed together.
3. Using media querys in the css, I made an exception for the existing margins when on a Ipad sized view.

---

# Technologies

1. Bootstrap 4.4.1:
* Bootstrap was used to assist with the responsiveness and styling of the website.
2. Hover.css:
* Hover.css was used on the Social Media icons in the footer to add the float transition while being hovered over.
3. Google Fonts:
* Google fonts were used to import the 'Titillium Web' font into the style.css file which is used on all pages throughout the project.
4. Font Awesome:
* Font Awesome was used on all pages throughout the website to add icons for aesthetic and UX purposes.
5. Git:
* Git was used for version control by utilizing the Gitpod terminal to commit to Git and Push to GitHub.
6. GitHub:
* GitHub is used to store the projects code after being pushed from Git.



---

# Code/Sources

## Content

Here i found how to put my text behind the background picture. I used "z-index" to solve this problem.

https://stackoverflow.com/questions/1093955/make-the-image-go-behind-the-text-and-keep-it-in-center-using-css

I used hexcolortool for all my colors in the page. 
I thought it was a very good and user-friendly tool for finding the right color.

https://www.hexcolortool.com/#351a42,0.87

I used stackoverflow a couple of times in my project, here i used it to find how i scroll to a specific element on my website.

https://stackoverflow.com/questions/24739126/scroll-to-a-specific-element-using-html

I thought this timeline fit perfectly on my website, so I used it. I changed the text to suit me and my experience. I also changed the color of it so that it would fit more in my page.

https://www.bootdey.com/snippets/view/bs4-my-experience-timeline

I used boostrap google map to get a map and shape for my page.

https://mdbootstrap.com/docs/jquery/javascript/google-maps/


Stackoverflow again where I needed help to get the media query right in different devices.

https://stackoverflow.com/questions/53701003/how-to-remove-the-hamburger-menu-icon-in-desktop-screen-but-only-needed-in-mobil

# Media


## Project "lava"

https://media.nationalgeographic.org/assets/photos/325/467/f4dab4c6-62a2-4c4f-acd0-5886ccca6f92.jpg

https://www.youtube.com/watch?v=EZjevnnkA20

## Project "Forrest"

https://images.unsplash.com/photo-1476362555312-ab9e108a0b7e?ixlib=rb-1.2.1&auto=format&fit=crop&w=1000&q=80

https://www.youtube.com/watch?v=uPIEn0M8su0

## Project "Ocean"

https://cdn.theatlantic.com/assets/media/img/photo/2020/01/winners-2019-ocean-art-underwater-p/u03_Kao/main_1500.jpg

https://www.youtube.com/watch?v=BDocp-VpCwY

## Backgrpund picture

https://cdn.pixabay.com/photo/2016/11/06/17/11/zermatt-1803481_960_720.jpg

## Icons for skills section

https://jquery-plugins.net/image/plugin/bootstrap-4-the-most-popular-html-css-and-js-library.jpg

https://g.foolcdn.com/art/companylogos/square/mdb.png

https://www.opengis.ch/wp-content/uploads/2020/04/django-python-logo-e1588009010920.png

https://cloudblogs.microsoft.com/uploads/prod/sites/32/2020/05/SQL.png

https://www.buildableweb.com/pub/photo/thumb/512px-HTML5-logo.svg_fitbox_700x700.png

https://upload.wikimedia.org/wikipedia/commons/thumb/9/99/Unofficial_JavaScript_logo_2.svg/480px-Unofficial_JavaScript_logo_2.svg.png

https://cdn.pixabay.com/photo/2017/08/05/11/16/logo-2582747_960_720.png

---

## Deployment

### GitHub Pages

The project was deployed to GitHub Pages using the following steps...

1. Log in to GitHub and locate the GitHub Repository
2. At the top of the Repository (not top of page), locate the "Settings" Button on the menu.
* Alternatively Click Here for a GIF demonstrating the process starting from Step 2.
3. Scroll down the Settings page until you locate the "GitHub Pages" Section.
4. Under "Source", click the dropdown called "None" and select "Master Branch".
5. The page will automatically refresh.
6. Scroll back down through the page to locate the now published site link in the "GitHub Pages" section.

### Forking the GitHub Repository

By forking the GitHub Repository we make a copy of the original repository on our GitHub account to view and/or make changes without affecting the original repository by using the following steps...

1. Log in to GitHub and locate the GitHub Repository
2. At the top of the Repository (not top of page) just above the "Settings" Button on the menu, locate the "Fork" Button.
3. You should now have a copy of the original repository in your GitHub account.

### Making a Local Clone

1. Log in to GitHub and locate the GitHub Repository
2. Under the repository name, click "Clone or download".
3. To clone the repository using HTTPS, under "Clone with HTTPS", copy the link.
4. Open Git Bash
5. Change the current working directory to the location where you want the cloned directory to be made.
6. Type git clone, and then paste the URL you copied in Step 3.

$ git clone https://github.com/YOUR-USERNAME/YOUR-REPOSITORY

### 7. Press Enter. Your local clone will be created.
$ git clone https://github.com/YOUR-USERNAME/YOUR-REPOSITORY

> Cloning into `CI-Clone`...

> remote: Counting objects: 10, done.

> remote: Compressing objects: 100% (8/8), done.

> remove: Total 10 (delta 1), reused 10 (delta 1)

> Unpacking objects: 100% (10/10), done.

Click Here to retrieve pictures for some of the buttons and more detailed explanations of the above process.

---

## Contact

E-mail: Linus.loof96@gmail.com






































