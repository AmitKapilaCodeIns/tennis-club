# Richings Tennis

The Richings Tennis club website's business goal is to increase membership. The site is an elegant solution to the need to showcase the club's services and it's friendly all-inclusive atmosphere.

The website illustrates the all-weather tennis courts, the coaching services, friendly club atmosphere, tennis leagues, social sessions, the bar.

Designed for anyone who wants to socialise, whether that person is into tennis or not. Tennis enthusiasts will be presented with essential information around coaching, leagues, social tennis and tournaments.

Users will be able to submit a convenient membership inquiry form and find out how to contact club staff. The site is responsive, adapting seamlessly to all screen sizes.

![Site images in all screens size responsive](./documentation/responsive.png)

---

## User Stories

As a First-Time Visitor:

-   I need easy navigation and a user-friendly design, including a responsive layout for my device, so I can find information quickly and efficiently without frustration.

As a Casual player:

-   I want to see high-quality images and engaging descriptions of the bar's ambience and tennis courts, so I can decide if it's the right place for me to relax and have fun.

As a tennis newbie:

-   I want to explore a selection of coaching options on the website, so I can decide which ones suit me or my child.

As a Prospective Customer:

-   I need to find essential information such as location, contact details, and opening hours clearly and concisely, so I can easily plan my visit or get in touch with the club.

As a potential customer

-   I want to be able to initiate a simple membership inquiry form, so I may be contacted by the membership team.

---

## Features

The website is comprised of 4 pages, two of which are accessible from the navigation menu (Home, Coaching, Membership). The last one is a button that opens a membership inquiry form.

-   All pages on the website have:
    -   Clear Navigation: Easily navigate through different sections of the website, including Home, Services, Events, Coaching and Contact, situated to the right.
    -   Responsive Design: Navigation bar adapts gracefully to various screen sizes, ensuring optimal usability whether you're browsing on a desktop, tablet, or mobile device situated in the burger-icon that expands when you click it.
    -   The header: At the top left in the header section, there is the website logo, that will take the user to the home page when clicked.
    -   The website logo and all pages use the main color theme; greens, blues and shades of white. The favicon adopts this theme. The primary colour choice of dark green and the secondary colour choice of light green reflect the colours a visitor might see. The navbar has light colours against a dark background contrasting each other well. The background is a light colour that contains the cards and other elements in a simple way.
    -   The primary font Prompt was chosen for it's harmonious and simple feel. The secondary Noto Serif elegantly makes large text stand out without looking ungainly.
    -   The icons used were chosen for their obvious meaning and purpose so that they can be understood by everyone.
        ![Image of the navbar and the logo Richings](./documentation/navbar.png)
    -   Dynamic Footer: the website boasts a dynamic footer section that provides essential links, such as social media profiles, contact information, and opening times, ensuring easy access to relevant content and enhancing user engagement.
        ![Image of the footer with all social medias contacs and copyright](./documentation/footer.png)

*   The home page

    -   The website features an engaging homepage designed to increase awareness of tennis club, provide essential information and encourage event participation. With stunning visuals, concise messaging, and intuitive navigation.
        ![Image of the landing-page - welcome and carousel](./documentation/landing-page.png)

        -   The services section highlights the diverse range of things available to members. It's role is to introduce visitors to Riching's engaging offerings, be they the all-weather tennis courts, the coaching services, friendly club atmosphere, tennis leagues, social sessions and the bar. The aim is to show the club will fulfill the needs of casual players looking for all year-round tennis in a fun and relaxed atmosphere or enthusiasts looking to play competitive team tennis and join leagues. Parents looking to encourage their kid’s tennis skills will also find the club satisfies that need. Furthermore, the layout of the services section has been optimized for responsiveness using CSS Grid. This ensures that the services are displayed in varying numbers of columns, depending on the screen size, providing an optimal viewing experience across different devices.
            ![Image of the services section part of Riching's website](./documentation/services-section.png)
        -   The events section details specific events held weekly. It allows visitors to decide on what events they are interested in and whether the timings suit them.
            ![Image of the events section part of Riching's website](./documentation/events-section.png)

*   The Coaching page

    -   Discover the LTA approved coaching options available to a broad demographic. Each type of coaching service has a helpful description and to what type of person it is tailored to. The experienced coaches are here to offer encouragement and support. Coaching session information includes the Date, Time and the Age group it is catered to. Furthermore, the layout of the coaching page section has been optimized for responsiveness using CSS Grid. This ensures that the options are displayed in varying numbers of columns, depending on the screen size, providing an optimal viewing experience across different devices.
        ![Image of the Coaching Cards](./documentation/coaching.png)

*   The Membership form page

    -   Each page on the site contains a button that allows the visitor to submit a membership inquiry form that satisfies the need to increase membership. A simple and intuitive form allows to make that first step in becoming a member. It allows the client to make contact with the club and the trained club staff to discuss membership in a personal manner.
        ![Image of the membership page](./documentation/membership-form.png)

*   The form success page
    -   Once a visitor submits a membership inquiry form they want assurance that the form was submitted. They are redirected to a simple page thanking them for their interest. messageand intuitive form allows to make that first step in becoming a member. It allows the client to make contact with the club and the trained club staff to discuss membership in a personal manner.
        ![Image of the thank you page](./documentation/thank-you.png)

### Features left to implement

-   I would like to add a static section on the website for customer testimonials and populate this section with a selection of pre-written testimonials.
-   I would like to integrate a newsletter sign-up form into the website footer.

---

## Testing

-   Accessibility
    -   I used Lighthouse within the Chrome Developer Tools to allow me to test the performance, accessibility, best practices and SEO of the website. I confirmed that the colors and fonts are easy to read and that the site is accessible.
    -   **INDEX PAGE**
        ![Lighthouse Index page screenshot ](./documentation/index-lighthouse.png)
    -   **COACHING PAGE**  
        ![Lighthouse Services page screenshot ](./documentation/coaching-lighthouse.png)
    -   **Membership PAGE**  
        ![Lighthouse Member page screenshot ](./documentation/membership-lighthouse.png)
    -   **Membership PAGE**  
        ![Lighthouse Member page screenshot ](./documentation/thankyou-lighthouse.png)
-   The website was tested on Chrome, Mozilla, Edge and Safari browsers with no problems found.
-   Links: Tested and confirmed that each link refer to each page, worked as expected,and redirecting the user between the pages
-   Tested all links, to social media sites leading to external pages opened correctly in a seperate browser tab.
-   I tested and confirmed that the Membership form works, all fields are required, the email field only accepts email, and the submit button works perfectly in the end to submit the form, with a message back from the thank you page.
    ![Screenshot of data from the form submit ](./documentation/member-form.png)
-   HTML

    -   [HTML Validator](https://validator.w3.org/#validate_by_upload) was run each page of the project. A syntax error was found in the footer of all 4 pages.
        ![Screenshot Html pages error ](./documentation/html-validator-error.png)
        The error was fixed. At the final stage no errors or warnings were found.
        ![Screenshot Html pages validator ](./documentation/html-validator.png)
        ![Screenshot success Html page validator ](./documentation/successhtmlvalid.png)
        ![Screenshot success Html page validator ](./documentation/membershiphtmlvalid.png)
        ![Screenshot success Html page validator ](./documentation/coachinghtmlvalid.png)

-   CSS
    -   [Vendor prefixes](https://autoprefixer.github.io/) Used Autoprefixer to parse the CSS and add vendor prefixes.
    -   [CSS Validator](https://validator.w3.org/#validate_by_upload) some syntax errors were identified.
        ![Screenshot CSS page validator ](./documentation/css-validator.png)

---

## Bugs

-   Initially, when clicking on the navbar links to the sections in the page the h2 header was covered by the navbar.
    ![Screenshot Navigation to section Bug ](./documentation/navclick-to-section.png)
-   By adding padding to the top of the section class the navbar was not covering the h2 header.

-   On smaller screens, the navbar did not close when clicking on links to sections on the same page.
    ![Screenshot Navigation to section Bug ](./documentation/navbar-not-closing.png)
-   Fixed by adding javaScript to ensure the navbar closes when clicking internal links

```
    <script>
        document
            .querySelectorAll(".navbar-collapse .nav-link")
            .forEach((link) => {
                link.addEventListener("click", function (e) {
                    let section = document.querySelector(e.target.getAttribute("href"));
                    if (section) {
                        e.preventDefault(); // Prevent default anchor click behavior
                        let navbarHeight = document.querySelector(".navbar-toggler").offsetHeight;
                        window.scroll({
                            top: section.offsetTop - navbarHeight, // Adjust for navbar height
                            behavior: "smooth",
                        });
                        document
                            .querySelector(".navbar-collapse")
                            .classList.remove("show"); // Collapse navbar
                    }
                });
            });
    </script>
```

-   Relative measures were also applied to image sizes, divs, and sections across all pages, as suggested and explained by the tutor to enhance responsiveness.

---

### Unfixed Bugs

All bugs identified were fixed

## Deployment

### Version Control

-   The site was created using VS Code as IDE and pushed to Github to the remote repository 'tennis-club'.
-   Git commands were employed extensively during development to push the code to the remote repository. The sequence of Git commands utilized includes:
    -   **git add .**: This command adds the files to the staging area, preparing them for commitment.
    -   **git commit -m "commit message"**: It commits the changes to the local repository queue, marking them as ready for the final step.
    -   **git push**: This command is executed to push all committed code to the remote repository on Github.
    ### Deployment to Github pages
    The site was deployed to GitHub pages. The steps taken to deploy are as follows:
    1. Log in to [Github](https://github.com/);
    2. Navigate to [AmitKapilaCodeIns/tennis-club](https://github.com/AmitKapilaCodeIns/tennis-club) in the list of repositories;
    3. In the GitHub repository, navigate to the Settings tab;
    4. In Settings scroll down to GitHub pages which opens in a new page;
    5. From the source section drop-down menu, select the Master Branch;
    6. Once the master branch has been selected, the page is automatically refreshed and a display indicates the successful deployment and the link to the address.
       The live live link can be acess here: [Richings Tennis](https://amitkapilacodeins.github.io/tennis-club/index.html)
    ### Cloning Repository Code locally
    -   To clone the repository code locally, follow these steps:
    1. Navigate to the Github repository you wish to clone;
    2. Click on the "Code" button located above all the project files;
    3. Select "HTTPS" and copy the repository link;
    4. Open the IDE of your choice and paste the copied git URL into the IDE terminal;
    5. Press Enter to execute the command;
    6. The project will now be created as a local clone in your IDE.

---

## Wireframes

-   These wireframes were created using Balsamiq during the Scope Plane part of the design and planning process for this project. The site was developed with the Desktop layout method first. The wireframes were therefore drawn with that thought in mind and adapted along of the project, and created with [Balsamiq](https://balsamiq.cloud/) . First picture: Home page, Second picture: Coaching page, Third picture: Member page, Fourth picture: Thank you page.
    ![Screenshot Home page Wiframe ](./wireframes/home-wiframe.png)
    ![Screenshot Coaching page Wiframe ](./wireframes/coaching-wiframe.png)
    ![Screenshot Member page Wiframe](./wireframes/member-wiframe.png)
    ![Screenshot Thankyou page Wiframe](./wireframes/thankyou-wiframe.png)
    ***

---

## Credits

-   I would like to extend a special thanks to my tutor [Spencer Barriball](https://www.linkedin.com/in/spencerbarriball/), whose guidance and support have been invaluable throughout this journey.
    ### Content
-   The icons in the footer and in the headings were taken from:[Font Awesome](https://fontawesome.com/).
-   The Logo and Favicon was created by Ylivdesign from:[flaticon.com](https://www.flaticon.com/free-icons/tenniscamp).
-   I took inspiration from the Love Running project to create the header, hero-image section and footer. Other parts were inspired by [w3schools](https://www.w3schools.com/)
-   [Google fonts](https://fonts.google.com/) were used to import the fonts into the style.css file which is used on all pages throughout the project.
    [WebAIM](https://webaim.org/resources/contrastchecker/) were used to contrast the color palettes, into the style.css file which is used on all pages throughout the project.
-   Part of the English content in this website was generated with the assistance of [AI-ChatGPT](https://chat.openai.com/), an AI language model developed by OpenAI.

    ### Media

-   All the images in eache page of the site: Home, Services and Member was taken from: [Pexels](https://www.pexels.com/).
-   The video in the home page as taken as well from [Pexels](https://www.pexels.com/).
-   For a better performance of the website, the images was resizes and changed the format to WEBP using the [Birme](https://www.birme.net/) website.
