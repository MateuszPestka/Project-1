# **Vegan Drop Meals**
Vegan drop meals is a meal delivery service that currently covers areas in Dublin,Galway and Cork. Vegan Drop Meals aims to provide an easy way for people to transition to a plant based diet and to give people the right amount of calories and nutrients to sustain all their activities. This site will target people who want to turn to a plant-based, vegan or vegetarian diet.

 It will also target people who already are on one of these diets but struggle to find time to cook or get the right nutrients into their body which is extremely common in any of these diets. As meat is a HBV protein it provides you with all the protien you need Vegan Drop Meals will provide you with the right amount of different LBV proteins as those are present in vegetables.

 ![Display of website on different screen sizes](assets/images/device-view.PNG)

 ## Features Of Page:

 - **Navigaton Bar**

   - The navigation bar is exactly the same on all three of the Vegan Drop Meals website allowing users to easily navigate back to the home page or anywhere in the website.
   - The logo and the navigation menu are all the same across the website with resposive elements showing them what specific page they are on.

![Navigation bar](assets/images/nav-bar.PNG)

- **Landing Page**

  - The landing page is a slideshow of images that allows the viewer to see the different meals that Vegan Drop Meals offers.
  - The slideshow will allow viewers to quickly identify the website is a meal delivery service.
  - The animation of a slideshow will grab the users attention as they aren't bored of a single image placed in the landing page.
  - This features five different images to allow the user to see a different image each time.

![First landing page image](assets/images/landing-page1.PNG)

![Second landing page image](assets/images/landing-page2.PNG)

- **About Section**

  - The about section aims to provide a quick description of the service that vegan drop meals provides and how to contact the deiticians and get started on the plan.
  - The section also aims to give an iinsight into the service and the ingredients used.
  - The about section features a link inside the contact our dieticians section that will allow users to wuickly navigate the website without having to go to the top of the page.

![About section](assets/images/about-img.PNG)

- **Packages Section**

  - The packages section gives the user a simple breakdown of the four packages that are provided by Vegan Drop Meals. It allows them to easily compare the packages and choose the best one that suits them.
  - The packages section has a hover element that makes the package they hover over stand out compared to the other packages but this is only present in devices over 1150px wide, as smaller devices are usually touch screen and it would not be viable.
  - Each package and background image of the package is a clickable link which also expands when hovered. This will allow the user to easily choose a package and be transfered to the contact us page.

![Package section not hovered over](assets/images/package-readme.PNG)

![Package when hovered over](assets/images/package-hover.PNG)

- **The Footer**

  - The footer has an extremely minimalistic design which incorporates to the flow of the website by not changing colors and matching the color scheme.
  - There is four icons that link to different social media platforms being Instagram, Facebook, Twitter and Youtube.
  - The inspirational message is designed to be discrete yet promote the move to a vegan or plant based diet.

![Image of footer](assets/images/footer-img.PNG)

- **The FAQ Page**
  
  - The FAQ section is a retractable accordion style section that allows users to only see the answers for questions that they want answered.
  - The accordion style design will reducce frustration for the user when they just want an answer to one question.
  - This section aims to inform the user about the different options and answer any questions that they may need an answer for before deciding to contact us.

![FAQ Questions when not expanded](assets/images/faq-not-expanded.PNG)

![FAQ Questions when partially expanded](assets/images/faq-part-expanded.PNG)

- **Contact Us Page**

  - The contact us page is designed to be simple and easy to use like the rest of the website. The user has to fill out a form that requires basic information for them to be    contacted.
  - The inclusion of a preferred way of contact is to promote easy access for people generally anxious of phone calls. This will allow the user to have a positive experience   with Vegan Drop Meals and a none stressful way to contact the dieticians.
  - The phone number has a set limit of characters to prevent any false numbers being input to the field.

![Contact us form](assets/images/contactus-form.PNG)

- **Features left to implement**

  - **Back To Top Button**

    - A back to top button would improve UX allowing a quick and easy return to the navigation bar to browse the different sections of the website.
    - It would also reduce frustration as scrolling tends to be tedious and can cause a user not to return to the website.

  - **Why Vegan Page**
  
    - A Why Vegan page would further encourage users to change their diet. This page would be dedicated to studies done and health benefits of a plant based diet.
    - This would allow users to gather information on a vegan or plant based diet in one source without having to travel to other websites or look for the information themselves. This would make the website more beneficial to the user and promote the service itself.

## **Testing** 

### **Website Functionality Testing**

- **Links Testing**:
  - I tested all my links in my website and realised that my packages weren't linked to my contact us page.
  - **Fix**: I replace the current placeholder # with the right href to link to contact us page.

  - All other links are functional and links to external sites in the footer open in a new tab.

- **Form Testing**
  - During the testing of my form I realised my Phone number input only allowed for ten characters and required at least 13 with dashes inbetween each 3 number.
  - **Fix**: I removed the dashes inbetween the allowed pattern of numbers and increased my max-length to 14 to allow for prefixes like +353.

  - My Enquire button did not have a hover attribute and when hovered over did not look clickable.
  - **Fix**: I added a hover attribute in my CSS file making the button change color and improving UX making it easier to recognise as a button.

- **FAQ Testing**

  - The accordion style FAQ section works with no issues. The transition works without a problem allowing for a smooth satisfying UX.

- **Background Image Slideshow**

  - The background image slideshow works smoothly and without any problems that could cause a harmful UX. It adjust to screen size and works on different sized devices.

- **Package Hover**

  - My package hover works generally smoothly with only one slight bug when switching too fast from the right packages to the one on the left. The package on the right seems to clip the package on the left for a second before the package on the left pops up over it. 
  - **Fix**: I could not identify what is causing this in the code as all packages have the same hover attribute from class '.package:hover'. This is only a small bug and does not harm UX in any extreme measure as it only blocks a small side of the left package and for a second.

### **Lighthouse Testing**

My lighthouse testings highly positive with my desktop reaching 100 on all aspects.

**Lighthouse Desktop Test**

My desktop lighthouse test was extremely positive with all my results reaching 100.

![Desktop lighthouse test](assets/images/desktop-lighthouse.PNG)

**Lighthouse Mobile Test**

My Mobile score was slightly less and I could not identify the reason why it wasn't going up.

![Mobile lighthouse test](assets/images/mobile-lighthouse.PNG)

### **Validator Testing**

- **HTML**

  - No errors or warnings reported when passing through [W3C validator](https://validator.w3.org/nu/?doc=https%3A%2F%2Fmateuszpestka.github.io%2FProject-1%2F) 

- **CSS**

  - No errors or warnings when passing through [(Jigsaw) validator](https://jigsaw.w3.org/css-validator/validator?uri=https%3A%2F%2Fmateuszpestka.github.io%2FProject-1%2F&profile=css3svg&usermedium=all&warning=1&vextwarning=&lang=en)

### **Unfixed Bugs**

- **Package Hover**

  - I have discovered a minor bug in my package hover. When moving the cursor from the right package to the left there is a slight visual bug that causes the right package to cut off a small bit of the package on the left. This causes the background image on the left to suddenly pop out after that second. I could not find any fix to this as the CSS for the hover package is the same for all 4 packages and it only happens when transitioning from the right to the left. This bug does not occur when transitioning from the left to the right.

- **Flavicon**

  - My Flavicon does not appear on my fully deployed website. When I use 'python3 http.server' the flavicon appears with no issues but when my website is fully deployed it does not appear.

## **Deployment**

- I deployed the site to GitHub Pages. These are the steps I took to deploy it:

  - In my GitHub repository, I navigated to the settings menu.
  - I went down to the GitHub Pages section and clicked the link.
  - In the source I selected the branch to Main Branch.
  - Once selected I clicked save and the page refreshes deploying the page giving me a detailed display ribbon to indicate the finishing of deployment.

## **Credits**

### **Content**

- **Background Slideshow**

  - I learnt how to make a background slideshow of this tutorial from [Youtube](https://www.youtube.com/watch?v=P0Ot9qE5was)

- **Accordion FAQ**

  - I learnt how to make an accordion style FAQ were taken of this website: [Supfort](https://supfort.com/pure-css-accordion-without-javascript)

  - The transition for the accordion style FAQ were taken from [Supfort](https://supfort.com/css-accordion-animation)

  - I have made slight changes of the codes above to suit my website but the I learnt the code and have used substantial parts of the code above for my website.

### **Media**

- **Images**

  - All my images were taken of [Pexels](https://www.pexels.com/)