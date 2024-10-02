# The Elite Equine Academy

## Introduction:

The Elite Equine Academy website is a site aimed at showjumping riders looking for a trainer/trainers to increase their skills to be able to progress with their riding and the training of their horses on the showjumping circuit.

Users of this website will be able to find out about the different types of training that is available at the academy, our facilities, they will be able to see images of our past and present students in action and they will be able to contact us to make general enquiries or enquire about any of our  courses.

[You can view the live project here.](https://lorrainedaly.github.io/elite-equine-academy/) 

The website is designed to be responsive and accessable on a wide range of devices, making it easy to navigate for all users.


![Picture of my website on different devices](/docs/images/amiresponsive.png)

# Planning Stages

## Target Audiences

* Users interested in progressing their showjumping career.
* Users starting out on their showjumping career.
* Users that want to build on their skills in producing showjumping horses.
* Users who have seen or heard about our academy and would like to find out more.
* Users who are looking for a different approach to their coaching.

## Site Aims

* To inform the user of the services that we offer.
* To provide the user with an insight into our unique and personalised coaching.
* To provide the user with a clear view of the different level of riders that we accomodate for in our academy.
* To offer the user a simple way to contact us without having to leave our site to contact by phone or email.

# Features

## Header:

* The header is fixed at the top of the page on all devices. It includes the navigation bar and is responsive for all devices.

* The title is clear and easy to read on all devices.

 On mobile devices.

![Header on a mobile device](/docs/images/header-mobile-devices.png)

On tablets and larger devices.

![Header on tablets and larger device](/docs/images/header-tablets.png)

## Navigation Bar
 ### On mobile devices: 
* The navigation bar has has a drop down menu below the logo on all pages.
* When the hamburger menu is clicked the menu is displayed below the header.
* There will be an underline on the page section that you are currently on when the dropdown menu is selected.

![Nav bar on a mobile device](/docs/images/nav-bar-mobile.png)

### On tablets and larger devices devices: 

* The nav bar is displayed under the logo on all pages.
* The current page will be high lighted on the nav bar by an underline.
* The width of the nav bar is responsive.
* A white line will appear as you hover over a particular page link.

![Nav bar on a tablets and larger devices](/docs/images/nav-bar-tablets&larger.png)

## Home Page:

* The home page includes an image that clearly show the website a related to showjumping.
* Introductory text about our academy is placed under the image.

![Home page image and text](/docs/images/home-page-mobile.png)

* There are two links included in this text that will direct users to the gallery page and the contact us page to make the site easily navigated. These highlight as the mouse is hovered over them.

![Home page image and text](/docs/images/home-page-links.png)

* All aspects of the home page are fully responsive on all device sizes.

* The home page is finished off with an inspirational quote to inspire our users.

![Home page images and text](/docs/images/quote.png) 

## About Us:

* Users will find our more information on who we are, what we offer, our facilities and our our mission.
* The page is divided into sections clearly marked by different background colors and font colors making it easy to read and acess the information that you as a user are after.
  * On Mobile

  ![About page screenshot](/docs/images/about-us-mobile.png) 
  * On Tablets and larger

![About page screenshot](/docs/images/about-us-tablet.png) 


## Gallery Page 

* The gallery is there to show users previous and present students at different levels out competing.
* This will allow users to see that all levels of riders are accomodated for at the academy, removing any nervousness for less accomplished or younger  riders.
* The gallery is fully responsive on all divices.
  *  On Mobile Devices:

  ![Gallery page on mobile devices](/docs/images/gallery-mobile.png)
  * On tablets:

  ![Gallery page on tablets](/docs/images/gallery-tablet.png))

  * On laptops and larger devices:

  ![Gallery page on laptops and larger devices](/docs/images/gallery-laptops.png)


## Contact Us:

* This page allows the user to contact us directly from our site.
The user will be able to select the relevant query from the drop down menu and add any comment or question that they have.

 ![Contact us page](/docs/images/contact-us-page-laptop.png)

* An error will highlight if a user does not fill in all required sections.
* When submitted a thank you page will open up advising the user that we will be in touch shortly.

![Thank you page](/docs/images/thank-you-page.png)

## Footer 

* The footer is pushed to the bottom of the site on all pages.
* It contains the same color styling as the header.
* It contains four social media links that open up in a new tab.
  * On Mobiles:

  ![Footer image on mobile devices](/docs/images/footer-mobile.png)

  * On Tablets and larger devices:

  ![Footer image on tablets and larger devices](/docs/images/footer-tablets.png)


# Testing
## Google Lighthouse
I ran all the pages in lighthouse on both mobile and computer setting to view the sites performance, accessibility, best practices and SEO. Please see the results below.
* Home:
  * On Mobile:

![Lighthouse report on Mobile for home page](/docs/images/home-mobile-report.png)

  * On Laptops

  ![Lighthouse report on Mobile for home page](/docs/images/home-computer-report.png)

  
* About us:
  * On Mobile
  
![Lighthouse report on Mobile for about us page](/docs/images/about-us-mobile-report.png)

  * On Laptops:

  ![Lighthouse report on Mobile for about us page](/docs/images/about-us-computer-report.png)

  
* Gallery:
  * On Mobile:
  
![Lighthouse report on Mobile for gallery page](/docs/images/gallery-mobile-report.png)

  * On Laptops:

  ![Lighthouse report on Mobile for gallery page](/docs/images/gallery-computer-report.png)

  
* Contact Us:
  * On Mobile
  
![Lighthouse report on Mobile for home page](/docs/images/contact-us-mobile-report.png)

  * On Laptops

  ![Lighthouse report on Mobile for home page](/docs/images/contact-us-computer-report.png)


## Bugs

As I was building this website I encountered a number of bugs and with fixing one bug it caused a new bug that needed fixing. Unfortunately due to this being my first project I mistakenly did not make a note, or take screenshots, of all of the bugs that I encountered while developing this website and this is a step that I will ensure I do for all of my future projects and website for going forwards.

* On the nav bar the underline was not showing up under the correct page I was viewing. On review I had not removed the active class from the home page. I resolved this by placing the active class on the correct link on nav bar.  

* On tablets and larger devices there was extra blank space on the right of my pages in the main sections. By inspecting the page I found that it was coming from the footer. On closer inspection I noted that I had used text-transform in css to make the logos in the footer larger and this was making my footer wider causing the extra space in the main sections on my website. By removing this is removed the extra space and used font-size to make the icons larger.

* When testing my form I encountered an error. On review I noted that I had mistakenly put post in the action instead of to a destination(e.g. a thank y ou page). To remedy this I put the code institute home page in the action and later linked up a thank you page when I had it created.

* When I deployed my project I noted that the main image was not showing up on the deployed site. On inspecting my site, I noted that I had used the incorrect file path to link up the image. Once corrected the image loaded perfectly.

* On testing my site I noted that the pages were taking a very long time to load, especially the gallery page. On review I noted that the images I used were incredibly large. I compressed and resized all the images and after my websites performance was improved. This was further proved when I ran lighthouse again.

* On final testing I noted that the thank you page styling was no longer coming through. On review I had changed the id for the error page and on the css styling but I had not updated the id on the thank you page. Once this was completed, the styling was back.

## Validator Testing
* HTML
  * I ran the code from my deployed project through the W3C validator and I ammended the few errors that I found. E.g. missing end tags, opening h3 with a closing h4.
    * Home:

    ![HTML validator report for home page](/docs/images/home-page-html-checker.png)

    * About us:
    
    ![HTML validator report for about us page](/docs/images/about-page-html-checker.png)

      * Gallery:

    ![HTML validator report for gallery page](/docs/images/gallery-page-html-checker.png)

    * Contact us:
    
    ![HTML validator report for contact us page](/docs/images/contact-page-html-checker.png)


* CSS
  * I ran my style sheet through the CSS validator and amended the few small errors.

  ![CSS validator report](/docs/images/css-checker.png)


##  Unfixed Bugs
* No unfixed bugs.

# Deployment 
* The site was deployed early to GitHub pages. The steps I took to deploy my project are as follows:
  * Push my project on GitPod.
  * Go to the GitHub repository and navigate to the Settings tab.
  * From the source section drop-down menu, select Master Branch.
  * You can select and view the deployed site from the right hand side of the page.

[Please click here to view the live project.](https://lorrainedaly.github.io/elite-equine-academy/) 
  
  # Credits

* As this is my first project alot of my code has been inspired by the Love Running website that we created as part of our course. I have tried to make my website as different as possible but there are similarities in the Nav bar, the footer and some of my layout.
* The favicons were taken from [Font Awesome](https://fontawesome.com/) 
* the images were taken from [Pexels](https://www.pexels.com/) 
* Some of the inspiration for the content for my website were taken from the following sites [Elite Equine Ireland](http://equineeliteireland.com/), [Austrailian Equine Behavious Center](https://www.aebc.com.au/) and [Elite Equestrian Academy](https://www.eliteequestrianacademy.com/).
