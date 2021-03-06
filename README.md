
# Rome

![](assets/images/responsive-design/responsive-design.png)

This is a "Rome" lading page for Italian capital visitors. On this site, users can find useful information about famous places in Rome. 
There is short text content besides famous places images. Also on the site is a map with recommended places for Rome visitors. 
They are famous places, hotels, restaurants, bars. In the map are markers with the real coordinates of the place, that will showplace that is visitor has to see. 
This interactive website was created for a non-existing travel guide.

The website you can view here - [Rome](https://andrius-siup.github.io/visit-rome/) .

# UX
 

## User Stories

* As a user type, I want to perform an action, so that I can achieve a goal.
* As a user of the website, I would like to that website will be responsive, that I can use it from any device.
* As a user of the website, I would like to see a user-friendly website with normal color contrasts, handy navigation bar.
* As a user of the website, I would like to contact the website admin, for my personal questions.
* As a user of the website, I would like to see the map of the city.
* As a user of the website, I would like to see the markers in the map for recommended places to visit, to plan my journey.
* As a user of the website, I would like to see in the marker of the map, useful information about places with links to their own sites.
* As a user of the website, I would like to see recommended hotels for city visitors, where I can stay.
* As a user of the website, I would like to see recommended restaurants for city visitors, where I can visit to taste Italian kitchen.
* As a user of the website, I would like to see recommended bars for city visitors, where I can spend little entertainment time. 
* As a user of the website, I would like to see the website's social media links, to see the comments, or find some more information from the others visitors to the city.

## Wireframes

Home Page

![Home](assets/images/wireframes/wireframe-home-page.png)

Famous places

![Famous Places](assets/images/wireframes/wireframe-famous-places.png)

Map

![Map](assets/images/wireframes/wireframe-map.png)

Contact Us Form 

![Contact Us](assets/images/wireframes/wireframe-contact-us-form.png)

All Page

![All Page](assets/images/wireframes/wireframe-all-page.png)


## Mockups

![](assets/images/responsive-design/responsive-design-1.png)
![](assets/images/responsive-design/responsive-design-midle-1.png)
![](assets/images/responsive-design/map-responsive-1.png)


# Features

* Navigation bar 

    * There is hamburger button on the mobile view.
    * Fixed 
    * Links
    * Logo - brings you on the home page.

 * Home-page

    * There is image castle in the night
    * Short paragraph why you have to visit Rome 
 

 * Famouse Places

     *  There is used bootsrap for grid layout
     * On mobile view change grid layout
     * Buttons used slide toggle - the user can open and close paragraphs

* Map
 
    * Buttons in the future will show markers position on the map
    * When clicking on the markers it shows info window about place, with link to this website.
 
 * Contact Us form

    * EmailJS I used 
    * Check all field before submitting
    * Functional contact us form, sends to my email, when user submited.

 ## Features Left to implemented
 

 # Technologie Used

 * [HTML5](https://en.wikipedia.org/wiki/HTML5) - provides the content and structure for website.
 * [CSS](https://en.wikipedia.org/wiki/CSS) - provides the styling.
 * [jQuery](https://jquery.com/) - was used for website interactives.
 * [JavaScript](https://en.wikipedia.org/wiki/JavaScript) - was used to create Google map on the site.
 * [Gitpod](https://www.gitpod.io/) - used for write the all code, commited, pushed to the GitHub.
 * [GitHub](https://github.com/) - used for hosting this code and deployment.
 * [Grammarly](https://app.grammarly.com/) - was used for check typo.


### Design

* [Bootstrap](https://getbootstrap.com/) - framework was used to create the layout for all of the page. Also used it for grid system, 
navbar, trainer cards, sign up / sign in and contact us forms.
* [Fontawesom](https://fontawesome.com/) - used for style the social media links and used in timetable.
* [Google Fonts](https://fonts.google.com/) - used Ubuntu fonts.

### Testing

* [Markup Validation Service](https://validator.w3.org/) - used for tested html code.
* [CSS validation service](https://jigsaw.w3.org/css-validator/) - used for tested css code.
* [Responsive Design](http://ami.responsivedesign.is/#) - checked website responsive.
* [Chrome DevTools](https://developers.google.com/web/tools/chrome-devtools/) - used for testing and found new ideas, it's like in sandbox.

 # Testing

 ## Testing User Stories

 The user looking for some information about Rome famous places, visiting this website clicking on the navigation link, finds famous places, by clicking the read more button,
 can read short text content about the place.

 The user looking for information on the map in this website, by clicking on the map link or scrolling
 down, find the map. Then interesting on the map markers, see that a lot of markers and they close each together.

 Users click on the markers to get useful information, can make route plans for daily activities. 
 
 Users that are interested in the trip and want to contact the site admin for a plan to trip, click on
 the navigation link Contact Us. Form is opened. Then the user has to fill in all fields before submitting the form
 because the form has the required attribute.

 When the user sends the request for some questions, the admin gets an email from him with the name
 and email link to send him a reply. They have a conversation.

 There were few warnings on the CSS validator, but was easily to fix: in the < section > was written < h1 > and 
another warning was that < section > was without h2-h6. All the project time I am regularly used the below validators to avoid errors.
There were typo errors that were fixed. Also left some warnings in the HTML validator, but will be fixed in the future.

[HTML Validator](https://validator.w3.org/)   
![](assets/images/validator/html-validator.png) 


[CSS Validator](https://jigsaw.w3.org/css-validator/)

![](assets/images/validator/css-validator.png) 


[jshint](https://jshint.com/)

![](assets/images/validator/map-jshint.png) 


[jshint](https://jshint.com/)

![](assets/images/validator/send-mail.png) 

[Lighthouse](https://developers.google.com/web/tools/lighthouse) - was used to improve the quality of the website.

![](assets/images/validator/lighthouse.png)

There is Best Practices place in Lighthouse that will be fixed in the future.

 # Deployment

 The websited is hosted on my Github page.

### Deployment steps:
1. Navigate to my **GitHub** repository - [https://github.com/andrius-siup/visit-rome.git](https://github.com/andrius-siup/visit-rome.git) . 
1. Go to the **Settings** tab of the top page.
1. Scroll down to the **GitHub Pages** section.
1. Make sure the source is **master branch**, saved it.
1. After selecting **master branch** the page will refresh.
1. Scroll down, back to the **GitHub Pages** section and you will see a link that saying **"Your site is published"** with the link.
1. Now you can **click the link** and go to the published website.

### Cloning Steps:
1. Navigate to my repository - [https://github.com/andrius-siup/visit-rome.git](https://github.com/andrius-siup/visit-rome.git) .
1. Click the **Code** button.
1. To clone with **HTTPS** copy the URL in the box [https://github.com/andrius-siup/visit-rome.git](https://github.com/andrius-siup/visit-rome.git) .
1. Open your IDE.
1. Changed the directory to the location you want to clone to be made.
1. Type **git clone** then paste the copied URL.
1. Press enter and clone will be created.   

### Download
1. Navigate to my repository - [https://github.com/andrius-siup/visit-rome.git](https://github.com/andrius-siup/visit-rome.git) .
1. Click the **Code** button.
1. Click the **Download Zip**, it will be downloaded zip folder.
1. Extract where you want to keep all files.

## Author

The website was created by Andrius Siupinys.

 # Credits

 ## Content
 * All text content was be taken from Google and edited for website purposes.

 ## Media
 * The photo used on the home page in this site were obtained from [Unsplash](https://unsplash.com/photos/vnv6nKdtqLc) website.
 * The photo used for the visit to St. Peter's Basilica in this site was obtained from [shutterstock](https://www.shutterstock.com/image-photo/st-peters-basilica-evening-via-della-1218983827) website.
 * The photo used for the visit to Coloseum in this site was obtained from [shutterstock](https://www.shutterstock.com/image-photo/sunrise-view-colosseum-rome-italy-architecture-789412159) website.
 * The photo used for the visit to Trevi Fountain in this site was obtained from [Unsplash](https://unsplash.com/photos/pbBeTkp97ic) website.
 
 

 ## Acknowledgements
 * I received inspiration for the google map section from youtube channel [Traversy Media](https://www.youtube.com/watch?v=Zxf1mnP5zcw&t=4s). Also used Google API documentation.
 *  For the mailJS on the Contact Us form I used CI video tutorial and also mailJS documentation.
 * Brian Macharia - mentor support, huge help through the project. Thank you 
 * Also want to thank you for CI tutor suport.




