# Blue Waves Diving

[Blue Waves Diving](https://kerem-haeger.github.io/blue-waves-diving/index.html) is a site that advertises the services of a Scuba Diving Center named Blue Waves Diving. The site will be targeted to first time visitors as well as returning customers who seek more information or to get in touch. It will be useful to get divers and non-divers alike excited about the diving and dive spots Blue Waves Diving offers with the ultimate goal to generate more business for the dive center.

Utilising an about section including easy to locate pricing for beginners and experienced divers, as well as a gallery page to get visitors in the mood for the experience, the goal is to attract clients and make them want to get in touch and dive with the dive center.

![Responsive Mockup](https://github.com/Kerem-Haeger/blue-waves-diving/blob/main/documentation/responsive-design.png)

__Intended Targets__

- New visitors:
  - New vistors should get excited about what the center offers.
  - If they are new to scuba diving, they should feel comfortable starting this journey with the center and also be able to see the pricing.
  - New visitors can easily see reviews and testimonials left by previous customers.
  - If they are divers they should be able to see what the center offers in terms of pricing and diving via the gallery.
  - New visitors should be able to get in touch with the center easily and give all necessary information in the contact form.

- Returning visitors:
  - Returning visitors can check the gallery for new pictures.
  - They can easily get in touch with the center to organise a future dive as well as remind themselves of what is offered and how much it costs.

## Features 

### Existing Features

- __General__

  - The site is built to mimic colour and light changes under water, meaning from brighter sections, we go lower, to darker, more coloured sections.

- __Navigation Bar__

  - Featured across the site and all pages. The navigation bar is kept simple as to facilitate easy navigation across the site.
  - As most of the site is in one page, the navigation bar stays on top in order to make navigating the different sections easier.

![Nav Bar](https://github.com/Kerem-Haeger/blue-waves-diving/blob/main/documentation/nav-bar-large.png)

  - On small screens, the navigation bar collapses into a Hamburger Menu to not take up as much space on the screen. 

![Nav Bar Small](https://github.com/Kerem-Haeger/blue-waves-diving/blob/main/documentation/nav-bar-small.png)

  - In addition, a "Back to top" Button helps users return to the nav bar on small screens, as the navigation does not stay in the field of view.
  - As the "Back to top" button is only visible on small screens, such as phone screens, it does not have a hover function. The design and placement indicates its function and should be recognised by users.

![Back to top button](https://github.com/Kerem-Haeger/blue-waves-diving/blob/main/documentation/scroll-up-button.png)

- __The home section__

  - This section is the hero section and is meant to catch the users eye with a stunning graphic, depicting a possible encounter while diving.
  - A catchy headline and sub-headline should get the user into the right mindset to want to explore more
  - The hero section takes up 90% of the screen on all devices, in order to show the user what comes next and encourage scrolling down.

![Hero Section](https://github.com/Kerem-Haeger/blue-waves-diving/blob/main/documentation/hero-section.png)

- __About Us Section__

  - The About Us section consists of three parts and is essential to the webiste.
  - First of all it introduces the center and its morals, such as an environmentally friendly approach to diving, providing certified instructors by PADI, which should put the users mind at ease when considering booking with the center.
  - The second important part of the About Us section is "What we offer". Here the user can see the different options they have as well as the prices at a glance.
  - The About Us section is very responsive and collapses on small screens in order to maximise readability.
  - Thirdly, the user can see what previous customers have to say about the center, thus verifying the claims made on the website.

![About Us](https://github.com/Kerem-Haeger/blue-waves-diving/blob/main/documentation/about-us-section.png)

![Pricing](https://github.com/Kerem-Haeger/blue-waves-diving/blob/main/documentation/pricing-about-us-section.png)

![Testimonials](https://github.com/Kerem-Haeger/blue-waves-diving/blob/main/documentation/testimonials.png)

- __Gallery section and page__

  - This section on the main (index.html) page is for new and returning users to peruse images of the dives, dive spots, and possible sightings underwater.
  - As scuba diving is an incredibly visual form of entertainment, having a gallery is important to generate interest.
  - The actual gallery is on a seperate page, which makes loading the page easier, especially on mobile devices. Further, when editing the gallery, the dive center can have their information on the main page untouched, while adding or changing up to date pictures. 
  - The Gallery section on the home page includes a tooltip, so users understand that the image is clickable.

![Gallery section](https://github.com/Kerem-Haeger/blue-waves-diving/blob/main/documentation/gallery-section-with-tooltip.png)

![Gallery page](https://github.com/Kerem-Haeger/blue-waves-diving/blob/main/documentation/gallery-page.png)

- __The Contact section__

  - This section allows the user to contact the dive center. It appears at the bottom, to ensure the user has had enough impressions to want to get in touch. In order to process the contact requests suitably, the user can chose their experience, which helps the dive center to quickly pass the request on to the suitable person/s.
  - Only first name and e-mail are required, as this is all that is needed in a more relaxed environment. The experience dropdown menu is on "None" by default and should be selected by the user, albeit this is not a requirement.

![Contact Us](https://github.com/Kerem-Haeger/blue-waves-diving/blob/main/documentation/contact-section.png)

- __The Footer__ 

  - The footer was taken from the "Love Running" project, as it fulfills the purpose and does not require much deviation. It is the only code borrowed and as such clearly marked in the HTML.
  - I have removed the link to Twitter/X as I do not want to support the people behind it.

![Footer](https://github.com/Kerem-Haeger/blue-waves-diving/blob/main/documentation/footer.png)

### Features Left to Implement

- The Testimonials section could be improved by having an array of many reviews, of which the website randomly displays some for each loading.
Further, the user should be able to cycle through the reviews via buttons on each side.
As this is not a real business, there is no reference to where the reviews come from, however, this could be implemented, and the reviews could be made clickable to direct the user to Google Reviews or similar.
- Information about dive spots could be included with an interactive map.
- Returning users could be able to leave a review directly on the webiste.
- A more interactive Gallery section/page would enhance the experience, such as a slideshow, or cards which can be navigated by the user.
- The contact form currently does not do anything, except lead the user to a 'Success'page, confirming receipt of their information. In order for the form to be useful, it should send the information to the dive center, which can be implemented, once the course continues (please also see Unfixed Bugs)

## Testing 

- __Responsiveness__

  - Extensive testing was done regarding responsiveness of the website. This is due to approach of "mobile first" development, and thus styles had to be changed using media queries, which required constant tests with different screen sizes.
  - Testing of different screensizes was done via the devtools in browsers, as well as on the actual devices (iPhone, iPad, Laptop) and the site reacts as intended on all.
  - Media queries were limited, as the design of the webiste works well on screens of 768px or above and would not need to be changed much on any screen above that.
  However, a limit to the size of some sections has been applied, in order to not overwhelm the user with solid colours.

- __Functionality__

  - The functionality of all links has been rigorously tested on all pages and work smoothly, thanks to smooth transitions.
  - All images have been resized in order to maintain a good quality, but speed up loading times.
  - The site has been tested with Lighthouse and passes well above 90 in each category.

![Lighthouse Index](https://github.com/Kerem-Haeger/blue-waves-diving/blob/main/documentation/lighthouse-index.png)

![Lighthouse Gallery](https://github.com/Kerem-Haeger/blue-waves-diving/blob/main/documentation/lighthouse-gallery.png)

  - The site has been tested on different browsers (Chrome, Firefox, Opera) and performs as expected on all.
  - Most testing during coding was done on Chrome.


### Validator Testing 

- HTML
  - No errors were returned when passing through the official [W3C validator](https://validator.w3.org/nu/?doc=https%3A%2F%2Fkerem-haeger.github.io%2Fblue-waves-diving%2Findex.html)
  - This was repeated with gallery.html an success.html and no errors were found

![W3C Validator Index](https://github.com/Kerem-Haeger/blue-waves-diving/blob/main/documentation/html-validator-index.png)

![W3C Validator Gallery](https://github.com/Kerem-Haeger/blue-waves-diving/blob/main/documentation/html-validator-gallery.png)

![W3C Validator Success](https://github.com/Kerem-Haeger/blue-waves-diving/blob/main/documentation/html-validator-index.png)

- CSS
  - No errors were found when passing through the official [(Jigsaw) validator](https://jigsaw.w3.org/css-validator/validator?uri=https%3A%2F%2Fkerem-haeger.github.io%2Fblue-waves-diving%2Findex.html&profile=css3svg&usermedium=all&warning=1&vextwarning=&lang=en)

![W3C Validator](https://github.com/Kerem-Haeger/blue-waves-diving/blob/main/documentation/css-validation.png)

## Technologies Used

- [HTML](https://developer.mozilla.org/en-US/docs/Web/HTML) was used as the foundation of the site.
- [CSS](https://developer.mozilla.org/en-US/docs/Web/css) - was used to add the styles and layout of the site.
- [CSS Flexbox](https://developer.mozilla.org/en-US/docs/Learn/CSS/CSS_layout/Flexbox) - was used to arrange items on the pages.
- [CSS Grid](https://developer.mozilla.org/en-US/docs/Web/CSS/grid) - was used to make "gallery" and "contact" pages responsive.
- [VSCode](https://code.visualstudio.com/) was used as the main tool to write and edit code.
- [GitHub](https://github.com/) was used to host the code of the website.

### Fixed Bugs

- The 'Scroll Up' Button was barely visible on some images, so I needed to add a white background to it.
- The Gallery section on the main page was not UX friendly enough, so I added an enlarging effect, as well as a box-shadow, a text over it, and a tooltip, to make it obious that it is clickable.
- The about us section caused some issues, as the second image should be the third item when the screen is larger, so I used 'order' when styling the flexbox.
- The social network links weren't obviously clickable, so I added a box-shadow when hovered.

### Unfixed Bugs

- Contact section
  - Currently, the contact form will only refer the user to a 'Success' page, stating that the center will get back to them ASAP.
  - This method uses 'GET', which is not ideal as it leaves confidential information in the URL.
  - This bug can not be fixed at the moment, as I we have not covered databases or similar in the course.
  - Please also see Features Left to Implement

## Deployment

- The site was deployed to GitHub pages. The steps to deploy are as follows: 
  - In the GitHub repository, navigate to the Settings tab 
  - From the source section drop-down menu, select the Master Branch
  - Once the master branch has been selected, the page will be automatically refreshed with a detailed ribbon display to indicate the successful deployment. 

The live link can be found here - https://kerem-haeger.github.io/blue-waves-diving/index.html

### Local Deployment

In order to make a local copy of this project, you can clone it.
In your IDE Terminal, type the following command to clone my repository:

- `git clone https://github.com/kerem-haeger/blue-waves-diving.git`

- Alternatively, if you use Gitpod, you can [click here](https://gitpod.io/#https://github.com/kerem-haeger/blue-waves-diving.git), which will start the Gitpod workspace for you.

### Note

- I am aware that the commit messages were inconsistent in the beginning and have hopefully improved over time. A big thank you to my [tutor](https://github.com/IuliiaKonovalova), who pointed me in the right direction regarding when to commit and how to use commit messages.

## Credits  

### Content 

- The text for the About section was written by myself, as I am a scuba diving instructor and used to work for a diving center.
- The icons in the footer, the hamburger menu, the "Back to top" button, were taken from [Font Awesome](https://fontawesome.com/)
- As mentioned above, the footer html was taken and adjusted from the "Love Running" project, which can be found here - https://github.com/Code-Institute-Solutions/love-running-v3/blob/main/3.7-creating-the-footer/index.html
- For some code, [W3Schools](https://www.w3schools.com/), as well as [MDN Web Docs](https://developer.mozilla.org/en-US/) were used as a reminder.
- As a reminder for flexbox, this [YouTube Video](https://www.youtube.com/watch?v=fYq5PXgSsbE&t=1s) was helpful.

### Media

- The photos used throughout this website are from [Pexels](https://www.pexels.com)
- The images in the About Us section were generated with Google's image creation AI [Image-FX](https://labs.google/fx/tools/image-fx) 
- The Favicon "Wave" was taken from [Flaticon](https://www.flaticon.com/free-icons/favicon)