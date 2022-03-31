# GripForce BJJ

GripForce BJJ is the website for a fictional Brazilian Jiu Jitsu club. The site is targeted at BJJ practitioners of all levels as well as people who are totally new to the sport.

![Mockup of GripForce the website](docs/feature-screenshots/gripforce-mockup.png)

## Existing Features

* Navigation bar
   * The Navigation Bar is intended to make the users experience smooth and as easy as possible.  
   * There are three links to all of the pages of the website and a logo. It is a uniform feature across all pages of the website.
   This allows the user to navigate through the website more efficiently.
   * The Nav bar is stuck to the top of the page which allows the user to quickly go to any page on the website without the need to scroll back to the top. 

 ![Screenshot of Navbar](docs/feature-screenshots/navbar.png)

 * Hero Image section
    * This section is intented to immediatley give the user visual confirmation that they have visited a BJJ website.
    * It displays the name of the club and the location

 ![Screenshot of Hero section](docs/feature-screenshots/hero-screenshot.png)

* Explanation of what BJJ is
   * This section allows users who may have no prior knowledge of Brazilian Jiu Jitsu get abetter understanding of what the sport is. 
   * It gives a bief introduction into both the history and the concept of the Martical Art.
   * Included is a picture of two men grappling. This gives the user a clear understanding of what BJJ might look like. 

 ![Screenshot of BJJ](docs/feature-screenshots/explanation-bjj.png)
 ![Screenshot of two men grappling](docs/feature-screenshots/grappling-screenshot.png)

 * Benefit Block Section
    * The purpose of the benefit section is to educate users on the positive aspects of doing BJJ.
    * There are 8 reasons included. They are styled in a block container which is aimed to grab the users attention. 
    * There is a scroll feature on the blocks to accomodate different screen sizes and quantity of text.

![Screenshot of the benefits of doing BJJ](docs/feature-screenshots/benefits-screenshot.png)

* Footer section
   * The footer section is consistent throughout the website. 
   * It contains 3 icons of social media platforms.
   * The icons also act as links and when clicked will bring you to the website in a new tab

![Screenshot of the footer](docs/feature-screenshots/footer-screenshot.png)

* Meet the coaches
  * Located on the Join us page, the Meet the coaches introduces the user to the fictional coaches of GripForce BJJ.
  * The section includes a brief bio of both coaches and their pictures. 

 ![Screenshot of the meet the coaches seciton including text and two pictures](docs/feature-screenshots/Meet-the-coaches.png)

* Timetable
   * This is a fictional timetable of the time and levels of training. 
   * Each category has a unique color to allow the user to quickly absorb the information.
   * The timetable ha a scroll feature to allow smaller screens to easily view all of the information. 

   ![Screenshot of the timetable for GripForce](docs/feature-screenshots/timetable.png)

* Contact section 
   * In this section the user can easily find all of the information about GripForce BJJ such as a phone number, address and email..
   * Also included is a form for any queries that the user would like to address.
   * The form has a name and email input and a textarea which are all required for the form to work. 

   ![Screenshot of the contact information and the form](docs/feature-screenshots/contact-section.png)

*  Feedback thank you page 
   * The final page is a feedback page which will open once the form is submitted.
   * It has a consistent nav and footer to maintain a seamless user experience. 


![Screenshot of the Feeback thankyou page](docs/feature-screenshots/Feeback-form.png)
 

## Testing
  I tested the website on verious web browsers and on several different devices including different sized mobile devices.
  All of the features work as intended on all devices. 

   * Lighthouse Desktop
      * The Desktop version came back with a very positive result in the lighthouse audit. All aspects of the Website were working efficiently. 

      ![Screenshot of lighthouse desktop test](docs/testing/lighthouse%20test.png)

   * Lighthouse Mobile
      * The mobile version for the test came back less efficient than the desktop. The accessibility measure came back with a high score however performance was much lower.

      ![Screenshot of lighthouse mobile test](docs/testing/lighthouse-test-mobile.png)

## Validator Testing

 * HTML
    * Code passed without errors. 

![Screenshot of HTML validator](docs/testing/html-validator.png)

 * CSS
    * Code passed without errors. 

    ![Screenshot of CSS validator](docs/testing/css-vlidator.png)

## Bug Fixes

  * HTML 
    * On the initial run through of the validator I got several errors stating that an extra closing tag was in my code. 
    I found the closing tag and removed it. 

    ![Screenshot of the stray tag](docs/testing/stray-tag.png)

  * CSS 
    * On the initial run of the validator I got several errors relating to a rgba value which was wrong. I found the rogue number and deleted it, which fixed the error. 

    ![Screenshot of css error](docs/testing/css-error.png)


## Unresolved Bugs

  * Lighthouse Mobile Performance
     * The performance issues relate to the size of the images which I used for the hero and the grappling sections. 
     * Early on in development I tried using the smaller files but did not like the look of the images on larger screens. 
     * Since the website works on mobile devices I decided to leave the images unchanged. 


## Deployment 
 After finishing the majority of the project I deployed the site on GitHub using the following steps:

  * GitHub Pages
     * Navigate to the repository on GitHub and click 'Settings'.
     * Then select 'Pages' on the side navigation.
     * From the source section drop-down menu, select the 'Main' Branch.
     * Click on the 'Save' button.
     * This is now a live website. 



The live link can be found here [GripForce BJJ](https://joequigley1.github.io/project-portfolio-1/)


 ## Credits

 [David Bowers](https://github.com/dnlbowers) - Webinar/channel lead
 [Martina Terlevic](https://www.linkedin.com/in/martinaterlevic/) - Mentor


 ## Content
   
   * The information on the home page as well as some of the benefits were taken from Wikipedia
   * The instrctions on how to code were taken from Code Institute. 
    * I tried to deviate away from the Love Running project example as much as possible. 
   * The icons in the footer were taken from Font Awesome
