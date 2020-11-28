# ![logo](https://github.com/pinco227/dublin-hills/blob/main/assets/images/logo-small.png) Dublin Hills

This is the presentation website for a new Housing Development that offers a good lifestyle support for families. The main goal is to get the interested user to book a viewing. Dublin Hills is an educational project made to serve as a Milestone Project for the **Software Developer Diploma** programme of **Code Institute**.

## Table of Contents
  - [Demo](#demo)
  - [UX](#ux)
    - [Business Goals](#business-goals)
    - [User Goals](#users-goals)
    - [User Scenarios](#user-scenarios)
    - [Structure](#structure)
    - [Skeleton](#skeleton)
      - [Wireframes](#initial-wireframes)
      - [Improvements](#improvements)
    - [Design Choices](#design-choices)
  - [Features](#features)
  - [Technologies used](#technologies-used)
  - [Testing](#testing)
      - [Encountered Issues](#encountered-issues)
      - [Testing User Stories](#testing-user-stories)
      - [Testing Functionality](#testing-functionality)
      - [Testing Compatibility](#testing-compatibility)
      - [Testing Performance](#testing-performance)
      - [Testing Accessibility](#testing-accessibility)
      - [Code Validation](#code-validation)
      - [Further Testing](#further-testing)
  - [Deployment](#deployment)
  - [Credits](#credits)
  - [Aknowledgements](#aknowledgements)

## Demo

### [Live website](https://pinco227.github.io/dublin-hills/)

[![Responsive Mockup](https://github.com/pinco227/dublin-hills/blob/main/docs/responsive-mockup.png)](http://ami.responsivedesign.is/?url=https://pinco227.github.io/dublin-hills)

## UX

- ### Business Goals
  - The main goal of any business is to sell the product. In this case the product is the 3 presented houses built throughout the estate.
  - Target and reach users that are members of a family with children.
  - Have a list of interested people by making viewing appointments.
  - Promote and present the 3 house models and their features/specifications.
  - Promote and present the estate's and area's features and specifications.
- ### Users Goals
  - Have a good lifestyle by living in a safe and quiet place along with their families.
  - Have access to essential services and amenities such as cleaning, childcare, schools, transportation, shopping and businesses.
  - Have options and details about the houses.
  - Have details and specifications about the place and location.
  - View the desired house and place in person.
- ### User Scenarios
  - #### As a user I need:
    - to easily understand the purpose of the page.
    - to easily navigate throughout the content.
    - to first be able to see the information on my mobile and then share it with peers on a bigger screen.
    - to find detailed information about the desired product.
    - to find information about who the business is and where to find them, this will give me trust.
    - to be able to contact the business and its contributors.
  - #### As a parent I need:
    - to find information about the safety.
    - to find information about child services within and around the estate/area.
    - to find information about leisure and activities within and around the estate.
    - to find information about why should I choose to live here.
  - #### As a worker I need:
    - to find information about transportation.
    - to find information about career opportunities around the area.
- ### Structure
  The website is designed to be consistent, intuitive and learnable.
  - Interaction design
    - For predictability, the interface interacts with user actions as the user expetcs. The scroll/swipe actions respond with the normal behaviour and buttons acts instantly on press.
    - For consistency, the interface offers a subtle visual feedback to the user (on hover, focus and press of buttons and fields) which is similar throughout the application and helps the user to quickly learn the functionality.
  - Information architecture
    - The content is organised and prioritised by importance from top to bottom and left to right.
    - For consistency, the information is presented in the rule of 3 on large screens and individual on small screens.
    - The information is structured mostly in nested lists and hub and spoke design for bigger screens.
- ### Skeleton
  - ### Initial wireframes
    - Landing Page:
      - [mobile](https://github.com/pinco227/dublin-hills/blob/main/docs/wireframes/index-mobile.png)
      - [tablet](https://github.com/pinco227/dublin-hills/blob/main/docs/wireframes/index-tablet.png)
      - [desktop](https://github.com/pinco227/dublin-hills/blob/main/docs/wireframes/index-desktop.png)
    - House Details Page:
      - [mobile](https://github.com/pinco227/dublin-hills/blob/main/docs/wireframes/house-mobile.png)
      - [tablet](https://github.com/pinco227/dublin-hills/blob/main/docs/wireframes/house-tablet.png)
      - [desktop](https://github.com/pinco227/dublin-hills/blob/main/docs/wireframes/house-desktop.png)
    - CTA Modal Form:
      - [mobile](https://github.com/pinco227/dublin-hills/blob/main/docs/wireframes/form-mobile.png)
      - [tablet](https://github.com/pinco227/dublin-hills/blob/main/docs/wireframes/form-tablet.png)
      - [desktop](https://github.com/pinco227/dublin-hills/blob/main/docs/wireframes/form-desktop.png)
  - ### Improvements
    - #### **Landing Page**:
      - #### Features section:
        - A main brochure pdf download button right under the section title.
      - #### Site layout section:
        - A short description about the location and a map before the site plan subsection.
        - Travel times subsection after the site plan.
        - General technical specifications subsection.
        
    - #### **House Details Page**:
      - #### Presentation section:
        - Book a viewing modal toggle button.
        - A house brochure pdf download button.
      - #### Other homes section:
        - A new section representing the other two house on each house page instead of the go back button.
- ### Design Choices
  - #### Colours
    ![Colour Palette](https://github.com/pinco227/dublin-hills/blob/main/docs/colour-palette.png)
    - The colour palette consists of warm and welcoming colours inspired by the "Eye Comfort" reading mode in most of the screen devices.  
    ![Colour Psychology Wheel](https://github.com/pinco227/dublin-hills/blob/main/docs/colour-wheel.jpg)  
    - According to [The Psychology of Color](https://www.toptal.com/designers/ux/color-in-ux), the chosen colours represent desire, cheerfulness, stimulation and comfort.
    - The 60-30-10 Rule was also taken into consideration when building the project. The light shades which are used mostly for background are considered neutral and makes up to 60% of the palette. The dark shades are complementary and makes up to 30% while the accent colours completes the remaining 10% of the design.
  - #### Typography
    There are two fonts used throughout the project, both with a ```serif``` fallback. These font-faces inspire classiness and elegance:
    - [EB Garamond](https://fonts.google.com/specimen/EB+Garamond?query=eb+garamond) is used as a general font.
    - [Merienda](https://fonts.google.com/specimen/Merienda?query=Merienda) is used for brand text, footer headings and all h1 and h2 headings in the project.
  - #### Media
    - The main call to action section is using an attractive video as background which inspires to family, happiness and joy and it has a photo background as a fallback for devices that are not compatible with autoplay videos and for the cases when the video is not loaded for any reason. The fallback image is a stop-frame of the video.
    - The rest of the images used throughout the project are in relation with they're containing section.
    - All images are sized and compressed for the best UX flow.
  - #### Iconography
    - Icons are used throughout the project to help user understand more efficiently the meaning of the content. They are a very good asset to improve UX.

## Features
Website's features are presented in an importance order.
- ### Navigation bar
    Allows users to navigate through the page. As the website is mainly a single landing page, the navigation will be visible all the time.
- ### Full width Call To Action (CTA)
    Allows users to understand the page purpose in the first look. Attracts users by giving on-point bite-size information. Allow business to acommplish the main goal by providing users with the viewing posibility. This is only showed on 80% of the screen height, the remaining 20% are left visible on purpose to let users know there is more content and to invite them to scroll through it. On the bottom of the CTA is an animated arrow inspired by the social networks stories which invites users to scroll down/swip up. This arrow is also clickabe and will scroll down when clicked, bringing user to the **Features** section.
- ### Book a Viewing Modal Form
    Allows interested users to book a viewing by having them fill the provided form.
- ### Housing Estate's features section
    Allow users to learn the main features of the presented product. These are ordered by importance. This also allows users to download the full pdf brochure by clicking the download button under the title.
- ### A list of the 3 house models
    Allows users to find the 3 house types and they're main photos, few imporant features and a button for more details. This button brings the user to the house's own details page.
- ### Details page for each house
    Allows interested users to find additional information for each of the 3 presented houses by visiting they're unique page. This pages have the following features ordered by importance:
  - #### Presentation
    This section present the house main photo, the most important features and 2 large buttons:
    - Book a viewing
    - Download House Brochure
  - #### A gallery of house plans
  - #### Full technical specification list
  - #### A gallery of photos
  - #### A list of the other 2 houses for quick access.
- ### Site section
    Allows users to find more details about the housing estate by presenting these subsections:
    - Site Map with a brief location description.
    - Site layout with legend.
    - Travel times.
    - General technical specifications.
- ### A photo gallery
    Allows users to visually understand more about the presented product. 
- ### Contact section
    Gives users information about the contact details of the site's developer, estate agent and solicitor. Provides a contact form for any queries.
- ### Footer
    Reminds users to book a viewing if interested by clicking the modal toggle button. Allows users to find more information on social networks by clicking the social icons.
- ### Accessibility
    Images are provided with descriptive text. The website is optimised for screen readers and allows users with impaired vision to zoom at any point.
- ### Features left to implement
    - 360 house viewing.
    - close modal and lightGallery with browser/device back button.

## Technologies used
- Workspace
  * [Ubuntu20.04](https://ubuntu.com/) as Operating System
  * [Visual Studio Code](https://code.visualstudio.com/) as Integrated Development Environment
- Languages
  * [HTML5](https://en.wikipedia.org/wiki/HTML5)
  * [CSS3](https://en.wikipedia.org/wiki/CSS)
- Frameworks & Libraries
  * [Bootstrap4](https://getbootstrap.com/) was used for its great responsivness and styling classes.
  * [Font Awesome](https://fontawesome.com/) icons were used for aesthetic and [UX](#ux) improvements.
  * [Google Fonts](https://fonts.google.com/) was use as the main font resource.
  * [Google Maps API](https://console.cloud.google.com/google/maps-apis/) for displaying the map on the site section. The Maps JavaScript API was used for this project following this [documentation](https://developers.google.com/maps/documentation/javascript/adding-a-google-map#maps_add_map-javascript).
  * [lightGallery](http://sachinchoolur.github.io/lightGallery/) plugin was used for photo galleries.
- Version Control
  * [Git](https://git-scm.com/) as Version Control System.
  * [Github](https://www.github.com) for repository hosting.
  * [Commitizen](https://github.com/commitizen/cz-cli) for commit linting.
- Wireframes
  * [Balsamiq](https://balsamiq.com/) for creating [wireframes](#wireframes).
- Media
  * [Inkscape](https://inkscape.org/) for creating the logo.
  * [Photopea](https://www.photopea.com/) online photo editor tool for creating the BER rating labels and for editing the site plan and the site entrance sign.
  * [Canva](https://www.canva.com/tools/logo-maker-q1/) for creating the 3 contact card logos.
  * [Adobe Photoshop Express](https://photoshop.adobe.com/resize) for quick resizing images for improving performance.
- Other
  * [Colormind.io](http://colormind.io/bootstrap/) as a tool for color palette testing.
  * [BrowserLing](https://www.browserling.com/) for cross-browser testing.
  * [Chrome Lighthouse](https://developers.google.com/web/tools/lighthouse) for performance, accessibility and best-practices audit.
  * [a11y](https://color.a11y.com/) for accessibility colour contrast testing.
  * [CSS Autoprefixe](https://autoprefixer.github.io/) for adding css vendor prefixes.
  * [W3C Markup](https://validator.w3.org/) for markup code validation.
  * [W3C CSS](https://jigsaw.w3.org/css-validator/validator#css) for css code validation.
  * [W3C Spell Checker](https://www.w3.org/2002/01/spellchecker) for checking the spelling.
  * [Unicorn Revealer](https://chrome.google.com/webstore/detail/unicorn-revealer/lmlkphhdlngaicolpmaakfmhplagoaln?hl=en-GB) chrome extension for overflow testing.

## Testing
- ### Encountered Issues
    Issues found during the building process:
  - video background on callout section would not autoplay on mobile, especially on android devices.
      - **FIXED** by adding these attributes to ```autoplay loop muted``` acording to **[this article](https://developers.google.com/web/updates/2016/07/autoplay)** of **Sam Dutton** and **[this repo](https://github.com/googlechrome/samples/tree/gh-pages/muted-autoplay)** of **Google Chrome**.
      - for iOS10 devices I have used the ```playsinline``` video attribute.
      - This feature is still not supported by all browsers/devices. For this I have provided a fallback which consists of a static background image as follows: ```background: url('../images/hero-img.jpg') no-repeat;```
  - video background on callout section would not position on center of the screen.
    - **FIXED** by adding the following css code to the ```.cta-video``` selector: 
        ```
        top: 50%;
        left: 50%;
        transform: translate(-50%, -50%);
        ```
        according to **[this article](http://thenewcode.com/777/Create-Fullscreen-HTML5-Page-Background-Video)** by **Dudley Storey**.
  - navbar would cover the title when navigating through the landing page using the nav links.
    - **FIXED** by adding the following css code that offsets the target:
        ```
        :target:before {
            content: "";
            display: block;
            height: 2.2rem;
            margin: -2.2rem 0 0;
        }
        :target {
            display: block;
            position: relative;
            top: -2.2rem; 
            visibility: hidden;
        }
        ```
        and the following code before the section's title
        ```
        <span id="features" class="invisible"></span>
        ```
        this will get targeted by the ```#features``` nav link as described in **[this article](https://spigotdesign.com/smooth-scroll-offset-anchor-links-with-css/)**.
  - collapsible menu would not collapse when clicking on link to navigate through landing page's sections. This requires user to tap 3 times to get to the desired section:
    1. click on "hamburger" button to expand the menu.
    2. click on desired link.
    3. click again on "hamburger" button to toggle the menu that covers the top of the section.
    - **FIXED** by adding this code to the ```.nav-item``` list element: ``` data-toggle="collapse" data-target="#menu"```. It was added to the list element and not to the anchor, otherwise it would disable the anchor funcionality.
- ### Testing user stories
  - #### As a user I need:
    - to easily understand the purpose of the page.
    > As the user lands on the website, the first thing it shows up is a big heading which briefly describe the websites purpose. 
    - to easily navigate throughout the content.
    > The navigation bar is fixed to top which means it is visible and accessible at all times on any device.
    - to first be able to see the information on my mobile and then share it with peers on a bigger screen.
    > The project is build in a mobile-first manner which means that every piece of information is design to be easily displayed on mobile first and expanded on a bigger screen whitout changing the functionality.
    - to find detailed information about the desired product.
    > All the information is structured in an importance order. For further details there are pages implemented for each of the main focus content, the houses. The website presents an option of downloading a pdf brochure for each of the house and for the site itself. The download button are big and visible, placed in focus areas.
    - to find information about who the business is and where to find them, this will give me trust.
    > There is a section dedicated for this purpose. The contact section gives information about all the contributors of the business and it is easily accessible from the navigation menu or by scrolling down the bottom of the landing page. Information about the developer is presented on the footer of the website on every available page.
    - to be able to contact the business and its contributors.
    > - If the contact purpose is to arrange a viewing, there is a call to action button on top of the landing page, on the footer of every page and on the top of each house page. This will toggle a modal form for booking a viewing. At this stage the business goal has been fulfilled.
    > - The contact section offers a contact form as well. This form can be used to contact the developer directly by email.
  - #### As a parent I need:
    - to find information about the safety.
    - to find information about child services within and around the estate/area.
    - to find information about leisure and activities within and around the estate.
    > Every piece of this required information is listed and described in the features section of the landing page, immediately under the main call to action section.
    - to find information about why should I choose to live here.
    > The first section offers brief details about the most important features of the estate. The house types section shows a photo for each house and the best features of each house. On each house page are presented in detail every feature and visually represented the most appealing details as a gallery of photos. Further details can be found navigating through the website. All the content is designed to be appealing and inviting.
  - #### As a worker I need:
    - to find information about transportation.
    > On the site section, one of the subsections is the **travel times**. There are listed few of the main destinations and the required time to travel to each.
    - to find information about career opportunities around the area.
    > One of the features is the **Location** which offers a great career opportunity, businesses and industries being at a short travel distance from the living area.
- ### Testing functionality
    > ### Checking for broken links
    > #### Landing Page
    > Starting from top to bottom, left to right, click on every button, link, toggle to check for expected action.
    > - top navigation fully functional including the brand title and logo.
    > - Hero: CTA button toggles the modal form. The **X** button and clicking outsite the modal container closes the modal.
    > - Modal form: submit button is submiting the form.
    > - Features: Download brochure button opens the pdf in a new tab.
    > - House types: every **view details** button opens the right house page in the same tab.
    > - Gallery: click on every photo opens the lightGallery showing the correct photo.
    > - LightGallery: click on arrows/swipe left-right/mouse drag/mouse scroll navigates through photos. The **X** button and clicking anywhere outside the photo closes the lightGallery.
    > - Contact: submit button of the contact form submits the form.
    > - Footer: CTA button opens the modal form. Social media buttons open each the expected link on a new tab.
    > #### Montpelier, Three Rock, Lugmore pages
    > Starting from top to bottom, left to right, click on every button, link, toggle to check for expected action.
    > - top navigation fully functional including the brand title and logo. Every link goes to expected section of the landing page in the same tab.
    > - Presentation: CTA button opens the modal form. The **X** button and clicking outsite the modal container closes the modal. Download brochure button opens the pdf in a new tab.
    > - Modal form: submit button is submiting the form.
    > - Plans, Gallery: click on every photo opens the lightGallery showing the correct photo.
    > - LightGallery: click on arrows/swipe left-right/mouse drag/mouse scroll navigates through photos. The **X** button and clicking anywhere outside the photo closes the lightGallery for both the plans and the gallery section.
    > - Other Homes: every **view details** button opens the right house page in the same tab.
    > - Footer: CTA button opens the modal form. Social media buttons open each the expected link on a new tab.

    > ### Testing browser back/forward action
    > Navigation: browser back and forward and mobile back tap acts as expected throughout. Although, when modal or lightGallery are opened, the back click/tap targets the url and it doesn't toggle/close the modal. In order to function like this, it requires further Javascript coding. This is left to be implemented.

    > ### Testing form validation
    > - CTA modal form: the form was tested for validation by trying to submit first with no field filled and then by filling the fields one by one. Result as expected, all fields asked for input. The email field asks for email format with ```@``` and the date and time fields cannot be filled differently.
    > - Contact form: the form was tested for validation by following the same process as above. Result as expected, the required fields asked for input (first name, last name, email, subject, message). The email field asks for email format with ```@```.

- ### Testing Compatibility
    > ### Responsiveness
    > Using DevTools and different device sizes such as mobile and tablet, the website was tested for any posible screen size combination and orientation. No issues found. Site is size compatible.

    > ### OS test
    > #### Desktop
    > The website was tested on Ubuntu 20.04, Windows 7 and Windows 10 systems. Result as expected, desktop system-cross compatible.
    > #### Mobile
    > The website was tested on Android 6, Android 9, Android 10 and iOS 14 systems. Result as expected, mobile system-cross compatible.

    > ### Devices test
    > The website was tested on ASUS 17" notebook, ACER 17" notebook, Huawei P30 PRO, Huawei P20 PRO, Huawei P10, iPhone 11, Lenovo Yoga Tab. The result was consistent, website is platform-cross compatible.

    > ### Browser test
    > The website was tested on Google Chrome, Firefox, Safari, Edge, Internet Explorer. Browsers versions were all up to date. Further testing was done using [BrowserLing](https://www.browserling.com/) and the website was tested for android 7 native browser. Results were consistent. Conclusion: the website is browser-cross compatible.
  
- ### Testing Performance
  > ### Landing page
  > ![LightHouse Landing Page Results](https://github.com/pinco227/dublin-hills/blob/main/docs/landing-lighthouse.png)  
  > Performance has been tested using chrome lighthouse tool. The results are slightly different every time due to device performance and value estimation. The performance test results are satisfying as the landing page is heavy loaded with content, especially images and the hero video. See further details below...
  > ![LightHouse Landing Page Performance](https://github.com/pinco227/dublin-hills/blob/main/docs/landing-perf.png)

  > ### House details page
  > ![LightHouse Landing Page Results](https://github.com/pinco227/dublin-hills/blob/main/docs/house-lighthouse.png)  
  > On these pages the performance test values are higher then the landing page as these pages are not so heavy on content (less images and no video). See further details below...  
  > ![LightHouse House Page Performance](https://github.com/pinco227/dublin-hills/blob/main/docs/house-lighthouse-perf.png)

- ### Testing Accessibility
  > The accessibility was tested throughout the site using chrome lighthouse and [a11y contast cecker](https://color.a11y.com/Contrast/). The result are satisfying in both cases. When contrast was checked wit a11y tool, there were 3 issues displayed on the landing page. The first two issues are for the hero headings, as they are on an absolute position container overlayed on top of the video, the contrast checker tool cannot evaluate correctly. The third issue is with the Developer card from the contact section of the landing page and this has been a design choice and can be ignored. No contrast issues found on the house details page.
- ### Code Validation
  > ### HTML
  > Html was tested and validated with [W3C Validator](https://validator.w3.org/). The results are satisfying on all pages. Two warnings are present in all pages about the use of headings throughout the page. These are no reason to worry and can be ignored as the headings are in place starting from top with ```h1``` and with every section with ```h2```.

  > ### CSS
  > CSS was validated with [W3C CSS](https://jigsaw.w3.org/css-validator/) by direct input. The results came with no error and only warnings about the vendor prefixes, which can be ignored.

- ### Further Testing
  > ### Overflow
  > Every page was tested for overflow by using the [Unicorn Revealer](https://chrome.google.com/webstore/detail/unicorn-revealer/lmlkphhdlngaicolpmaakfmhplagoaln?hl=en-GB) chrome extension to highlight the elements margins.

  > ### Spelling
  > Spelling throughout the website was checked using [W3C Spell Checker](https://www.w3.org/2002/01/spellchecker). The results are satisfying. The only spelling errors are actually technical names and UK-US english differences such as ```centre - center```.

## Deployment
- ### GitHub Pages
  The project was deployed to GitHub Pages using the following steps:
  1. Log in to GitHub and locate the [Dublin Hills Repository](https://github.com/pinco227/dublin-hills).
  2. At the top of the Repository, locate and click the "Settings" Button on the menu.
  3. Scroll down the Settings page until you locate the "GitHub Pages" Section.
  4. Under "Source", click the dropdown called "**None**" and select "**main**" branch.
  5. The page will automatically refresh.
  6. Scroll back down through the page to locate the now published [site link](https://pinco227.github.io/dublin-hills/) in the "GitHub Pages" section.
- ### Forking the GitHub Repository
  By forking the GitHub Repository we make a copy of the original repository on our GitHub account to view and/or make changes without affecting the original repository by using the following steps:
  1. Log in to GitHub and locate the [Dublin Hills Repository](https://github.com/pinco227/dublin-hills).
  2. At the top right of the Repository just above the "Settings" Button on the menu, locate and click the "**Fork**" Button.
  3. You should now have a copy of the original repository in your GitHub account.
- ### Making a Local Clone
  1. Log in to GitHub and locate the [Dublin Hills Repository](https://github.com/pinco227/dublin-hills).
  2. At the top of the Repository just above the list of files, locate and click the "**Code**" dropdown.
  3. To clone the repository using HTTPS, under "**Clone**", make sure "**HTTPS**" is selected and copy the link.
  4. Open Git Bash.
  5. Change the current working directory to the location where you want the cloned directory to be made.
  6. Type ```git clone```, and then paste the URL you copied in Step 3.
    ```
    $ git clone https://github.com/pinco227/dublin-hills.git
    ```
  7. Press Enter. Your local clone will be created.
    ```
    $ git clone https://github.com/pinco227/dublin-hills.git
    Cloning into 'dublin-hills'...
    remote: Enumerating objects: 408, done.
    remote: Counting objects: 100% (408/408), done.
    remote: Compressing objects: 100% (258/258), done.
    remote: Total 408 (delta 156), reused 368 (delta 116), pack-reused 0
    Receiving objects: 100% (408/408), 24.92 MiB | 15.71 MiB/s, done.
    Resolving deltas: 100% (156/156), done.
    ```
  Click [Here](https://docs.github.com/en/free-pro-team@latest/github/creating-cloning-and-archiving-repositories/cloning-a-repository#cloning-a-repository-to-github-desktop) to retrieve pictures for some of the buttons and more detailed explanations of the above process.
  

## Credits
- ### Content
  - [HSQ.ie](http://www.hsq.ie/) as a general content inspiration.
  - [Abbotfield.ie](http://www.abbottfield.ie/) for site and house specifications, for description on site section, for house plans and for lugmore house photos.
  - [OldtownWalk.ie](https://www.oldtownwalk.ie/) for three rock and montpelier houses photos and site entrance photo.
  - [MeadowBankSwords.ie](http://meadowbankswords.ie/) for site plan.
- ### Media
  - [ConvertIco](https://convertico.com/) for converting logo from .png to .ico .
- ### Code
  - [CSS TRICKS](https://css-tricks.com/) as a general resource.
  - [Stack Overflow](https://stackoverflow.com/) as a general resource.
  - [w3schools](https://www.w3schools.com/) as a general resource.
  - [Sam Dutton (Google dev)](https://developers.google.com/web/updates/2016/07/autoplay) for video attributes that makes autoplay available on android devices: ```autoplay loop muted```.
  - [Dudley Storey](http://thenewcode.com/777/Create-Fullscreen-HTML5-Page-Background-Video) for video positioning [issue](#encountered-issues).
  - [Spigot Design](https://spigotdesign.com/smooth-scroll-offset-anchor-links-with-css/) for anchor offsetting [issue](#encountered-issues).

## Aknowledgements
  - **My Mentor**: Nishant Kumar for continuous helpful feedback.
  - **Tutor** support at Code Institute for their support.
  - **Slack** Code Institute community for feedback.
  - **Peer student**: [Alexandru Valentin Grapa](https://github.com/alexandruvalentin) for helpful feedback along the coding progress and for help with iPhone device testing.