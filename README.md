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
  * [ConvertIco](https://convertico.com/) for converting logo from .png to .ico .
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
  ### [Click Here for Full Testing Process](https://github.com/pinco227/dublin-hills/blob/main/TEST.md)
  ### Overview
  - #### Issues
    | Issue                                                                                                   | Fixed              |
    | ------------------------------------------------------------------------------------------------------- | ------------------ |
    | [Video autoplay mobile](https://github.com/pinco227/dublin-hills/blob/main/TEST.md#encountered-issues)  | :heavy_check_mark: |
    | [Video position](https://github.com/pinco227/dublin-hills/blob/main/TEST.md#encountered-issues)         | :heavy_check_mark: |
    | [Page navigating offset](https://github.com/pinco227/dublin-hills/blob/main/TEST.md#encountered-issues) | :heavy_check_mark: |
    | [Collapsing menu](https://github.com/pinco227/dublin-hills/blob/main/TEST.md#encountered-issues)        | :heavy_check_mark: |
    | [Semantic heading](https://github.com/pinco227/dublin-hills/blob/main/TEST.md#encountered-issues)       | :heavy_check_mark: |
  - #### Tests
    | Test                                                                                                                          | Result             |
    | ----------------------------------------------------------------------------------------------------------------------------- | ------------------ |
    | ***[User Stories](https://github.com/pinco227/dublin-hills/blob/main/TEST.md#testing-user-stories)***                         | :heavy_check_mark: |
    | ***[Functionality](https://github.com/pinco227/dublin-hills/blob/main/TEST.md#testing-functionality):*** broken links         | :heavy_check_mark: |
    | ***[Functionality](https://github.com/pinco227/dublin-hills/blob/main/TEST.md#testing-functionality):*** browser back/forward | :white_check_mark: |
    | ***[Functionality](https://github.com/pinco227/dublin-hills/blob/main/TEST.md#testing-functionality):*** form validation      | :heavy_check_mark: |
    | ***[Compatibility](https://github.com/pinco227/dublin-hills/blob/main/TEST.md#testing-compatibility):*** Responsiveness       | :heavy_check_mark: |
    | ***[Compatibility](https://github.com/pinco227/dublin-hills/blob/main/TEST.md#testing-compatibility):*** System-cross         | :heavy_check_mark: |
    | ***[Compatibility](https://github.com/pinco227/dublin-hills/blob/main/TEST.md#testing-compatibility):*** Platform-cross       | :heavy_check_mark: |
    | ***[Compatibility](https://github.com/pinco227/dublin-hills/blob/main/TEST.md#testing-compatibility):*** Browser-cross        | :heavy_check_mark: |
    | ***[Performance](https://github.com/pinco227/dublin-hills/blob/main/TEST.md#testing-performance)***                           | :heavy_check_mark: |
    | ***[Accessibility](https://github.com/pinco227/dublin-hills/blob/main/TEST.md#testing-accessibility)***                       | :heavy_check_mark: |
    | ***[HTML Validation](https://github.com/pinco227/dublin-hills/blob/main/TEST.md#code-validation)***                           | :heavy_check_mark: |
    | ***[CSS Validation](https://github.com/pinco227/dublin-hills/blob/main/TEST.md#code-validation)***                            | :heavy_check_mark: |
    | ***[Overflow](https://github.com/pinco227/dublin-hills/blob/main/TEST.md#further-testing)***                                  | :heavy_check_mark: |
    | ***[Spelling](https://github.com/pinco227/dublin-hills/blob/main/TEST.md#further-testing)***                                  | :heavy_check_mark: |

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
  - [Abbotfield.ie](http://www.abbottfield.ie/) for site and house specifications and for description on site section.
- ### Media
  - [Gustavo Fring](https://www.pexels.com/@gustavo-fring?utm_content=attributionCopyText&amp;utm_medium=referral&amp;utm_source=pexels) for landing page's hero [video](https://www.pexels.com/photo/a-mother-and-daughter-bonding-time-in-a-park-4265250/?utm_content=attributionCopyText&amp;utm_medium=referral&amp;utm_source=pexels).
  - [MeadowBankSwords.ie](http://meadowbankswords.ie/) for site plan.
  - [OldtownWalk.ie](https://www.oldtownwalk.ie/) for three rock and montpelier houses photos and site entrance photo.
  - [Abbotfield.ie](http://www.abbottfield.ie/) for house plans and for lugmore house photos.
- ### Code
  - [CSS TRICKS](https://css-tricks.com/) as a general resource.
  - [Stack Overflow](https://stackoverflow.com/) as a general resource.
  - [w3schools](https://www.w3schools.com/) as a general resource.
  - [Sam Dutton (Google dev)](https://developers.google.com/web/updates/2016/07/autoplay) for video attributes that makes autoplay available on android devices: ```autoplay loop muted```.
  - [Dudley Storey](http://thenewcode.com/777/Create-Fullscreen-HTML5-Page-Background-Video) for video positioning [issue](#encountered-issues).
  - [Spigot Design](https://spigotdesign.com/smooth-scroll-offset-anchor-links-with-css/) for anchor offsetting [issue](#encountered-issues).
  - [StackOverflow user: Stickers](https://stackoverflow.com/users/483779/stickers) for up and down arrow animation [SOLUTION](https://stackoverflow.com/questions/35990445/how-to-move-a-div-up-and-down-infinitely-in-css3) used in landing page hero.

## Aknowledgements
  - **My Mentor**: Nishant Kumar for continuous helpful feedback.
  - **Tutor** support at Code Institute for their support.
  - **Slack** Code Institute community for feedback.
  - **Peer student**: [Alexandru Valentin Grapa](https://github.com/alexandruvalentin) for helpful feedback along the coding progress and for help with iPhone device testing.