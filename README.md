# Your Village

This first project was born from the idea that when I was preparing to have my first baby, there was either no information about certain topics (like combo feeding for example) or an overwhelming amount of information about others. 18 months on and I wish there was a one stop link tree, landing page or website with just a few useful resources, that I could easily scroll one handed on my phone in those first few days and weeks while my son slept on me, so that I had the information I so desperately needed at the time.

The project's name "Your Village" comes from the saying "It takes a village to raise a child". But, having a baby during the Pandemic, and with the more modern age we live in, there was no "village" for me at the time and there is no village for a lot of new parents.

I aim to keep the website clear and concise, easy to navigate on mobile devices first and foremost, and with relevant resources for new parents in Ireland. There will be a mock "Newsletter" or group sign-up form to meet the project criteria, as though this is part of a local initiative and you can meet with other parents in your area.

![Responsive screenshot](https://github.com/rahcancode/pp1-your-village/blob/main/media/sitepreview.png)
## Features 

The webpage is a static landing page with three main sections: 
- A welcome section with my inspiration for making the page
- A resources section with four external links to useful websites I used frequently in my early postpartum days
- A mock newsletter sign-up form

The color palette chosen was meant to be easy to read on mobile devices if a dark theme was not available. My experience of trying to read content on my phone, keeping my screen as dim as possible while using only one hand while my son slept, inspired a more neutral palette also. Some colors were changed slightly during the build of the webpage for accessability reasons.

![Color Palette](https://github.com/rahcancode/pp1-your-village/blob/main/media/PP1%2BPallette.png)

- __Navigation Bar__

  - Featured on the page is the full responsive navigation bar, which includes anchor links to the Logo, Home page, Resources and Newsletter sections.
  - This will allow the user to easily navigate from section to section across all devices without having to revert back to the previous page via the ‘back’ button. 

![Nav Bar](https://github.com/rahcancode/pp1-your-village/blob/main/media/nav-bar.png)

- __The landing page image__

  - The landing includes a photograph of some baby items, to indicate what the website is about. 
  - This section introduces the user to Your Village, and includes a blurb about my inspiration for creating the webpage.

![Landing Page](https://github.com/rahcancode/pp1-your-village/blob/main/media/landingpage.JPG)

- __Resources section__

  - This section will allow the user to access four resources as suggested by me and my husband, that were useful in my early postpartum days. 

![Resources](https://github.com/rahcancode/pp1-your-village/blob/main/media/resources.png)

- __Newsletter__

  - The mock Newsletter sign-up form is there as though there was a way to update the user about future updates to the website, share resources, or possibly announce local meet-up groups or classes.

![Newsletter](https://github.com/rahcancode/pp1-your-village/blob/main/media/newsletter.png)

- __The Footer__ 

  - The footer section includes links to the relevant social media sites. The links will open to a new tab to allow easy navigation for the user. 
  - The footer is valuable to the user as it encourages them to look for further information on the various social media sites available at this time.

![Footer](https://github.com/rahcancode/pp1-your-village/blob/main/media/footer.png)

### Features Left to Implement

- A forum style message board for people to connect and share information local to them in Ireland as new parents.
- A genuine newsletter that would send updates and announcements to new parents who sign up.

## Testing 

I posted my deployed site to our peer review Slack channel and asked other students to test it for usability and to see if there were any bugs.

One user noted that the footer nested under the newsletter form. When testing the website myself using dev tools, the background of the newsletter would "float" up through the other content on screen on screen sizes below 300px. Both issues were easily resolved by ensuring that the size of the footer and the newsletter container were not too small and were 400px or above.

I struggled with website performance on mobile when testing it using Lighthouse. Image sizes were too large and took too long to load. Converting the primary images to webp format improved site performance overall from 61 to the scores noted below for desktop and mobile respectively.

Lighthouse scored the website the following for desktop:

![Desktop score](https://github.com/rahcancode/pp1-your-village/blob/main/media/desktop.JPG)

Lighthouse score the website the following for mobile:

![Mobile score](https://github.com/rahcancode/pp1-your-village/blob/main/media/mobile.JPG)
### Validator Testing 

- HTML
  - One error was returned when passing through the official [W3C validator](https://validator.w3.org/nu/?doc=https%3A%2F%2Fcode-institute-org.github.io%2Flove-running-2.0%2Findex.html)
  - It related to the hero-outer not having a heading on line 36
  - This was resolved by changing from a <section> to a <div>
  - No other errors were found when passing through the validator after this change

- CSS
  - No errors were found when passing through the official [(Jigsaw) validator](https://jigsaw.w3.org/css-validator/validator?uri=https%3A%2F%2Fvalidator.w3.org%2Fnu%2F%3Fdoc%3Dhttps%253A%252F%252Fcode-institute-org.github.io%252Flove-running-2.0%252Findex.html&profile=css3svg&usermedium=all&warning=1&vextwarning=&lang=en#css)

### Unfixed Bugs

- When running the website through Lighthouse in Chrome, it populated this errors for performance on mobile: **Serve static assets with an efficient cache policy**
- Given the time frame the fix was beyond the scope of the project.
- The caching issue is also unlikely to be resolved while the website is being hosted on GitHub pages, as it requires access to parts of the backend I do not have at this time.

## Deployment

- The site was deployed to GitHub pages. The steps to deploy are as follows: 
  - In the GitHub repository, navigate to the Settings tab. 
  - In the left-hand menu, choose Pages.
  - Under Build and deployment, from the source section drop-down menu, select the Main Branch.
  - Click Save.
  - Once the main branch has been selected and you have clicked save, the page will be automatically refreshed with a detailed ribbon display to indicate the successful deployment. 

The live link can be found here - https://rahcancode.github.io/pp1-your-village/
## Credits 
### Content 

- The video run through's for the Love Running project was used as key reference points when first building the outline of the website
- Instructions on different HTML and CSS elements were referenced from [W3Schools](https://www.w3schools.com/)
- The icons in the resources headings and the footer were taken from [Font Awesome](https://fontawesome.com/)
### Media

- The images used on website are from [Burst](https://burst.shopify.com/)
- [Convertio](https://convertio.co/png-webp/) was used to convert the images from JPG and PNG to webp for faster loading times

## Acknowledgements

- My family: My son for being the inspiration for this website, but especially  my husband for running a tight ship for the final 48hrs before project submission
- Daisy & Bim for encouraging daily chats
- Grace for looking over my website in the 11th hour and offering help with this README (and for always offering help really)