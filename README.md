# ![logo](https://github.com/pinco227/dublin-hills/blob/main/assets/images/logo-small.png) Dublin Hills

[Live website](https://pinco227.github.io/dublin-hills/)

This is the presentation website for a new Housing Development that offers a good lifestyle support for families. The main goal is to get the interested user to book a viewing.

## Table of Contents
  - [UX](#ux)
    - [Business Goals](#business-goals)
    - [User Goals](#users-goals)
    - [User Scenarios](#user-scenarios)
    - [Structure](#structure)
    - [Wireframes](#wireframes)
    - [Design Choices](#design-choices)
  - [Features](#features)
  - [Technologies used](#technologies-used)
  - [Testing](#testing)
  - [Deployment](#deployment)
  - [Credits](#credits)
  - [Aknowledgements](#aknowledgements)

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
- ### Wireframes
  - Landing Page:
    - [mobile](https://github.com/pinco227/dublin-hills/blob/main/assets/docs/wireframes/index-mobile.png)
    - [tablet](https://github.com/pinco227/dublin-hills/blob/main/assets/docs/wireframes/index-tablet.png)
    - [desktop](https://github.com/pinco227/dublin-hills/blob/main/assets/docs/wireframes/index-desktop.png)
  - House Details Page:
    - [mobile](https://github.com/pinco227/dublin-hills/blob/main/assets/docs/wireframes/house-mobile.png)
    - [tablet](https://github.com/pinco227/dublin-hills/blob/main/assets/docs/wireframes/house-tablet.png)
    - [desktop](https://github.com/pinco227/dublin-hills/blob/main/assets/docs/wireframes/house-desktop.png)
  - CTA Modal Form:
    - [mobile](https://github.com/pinco227/dublin-hills/blob/main/assets/docs/wireframes/form-mobile.png)
    - [tablet](https://github.com/pinco227/dublin-hills/blob/main/assets/docs/wireframes/form-tablet.png)
    - [desktop](https://github.com/pinco227/dublin-hills/blob/main/assets/docs/wireframes/form-desktop.png)
- ### Design Choices
  - Colours
  - Typography
  - Images
  - Icons

## Features
Website's features are presented in an importance order.
- ### Navigation bar
    Allows users to navigate through the page. As the website is mainly a single landing page, the navigation will be visible all the time.
- ### Full width Call To Action (CTA)
    Allows users to understand the page purpose in the first look. Attracts users by giving on-point bite-size information. Allow business to acommplish the main goal by providing users with the viewing posibility.
- ### Book a Viewing Modal Form
    Allows interested users to book a viewing by having them fill the provided form.
- ### Housing Estate's features section
    Presents users the site's main offered amenities ordered by importance.
- ### A list of the 3 house models
    A brief presentation of the 3 houses with main photo, few imporant features and a button for more details.
- ### Details page for each house
    Interested users can find additional information for each of the 3 presented houses. This pages have the following features ordered by importance:
  - #### Main photo and attractive description
  - #### A gallery of house plans
  - #### Full technical specification list
  - #### A gallery of photos
  - #### A button to go back to the "Homes" section of the landing page
- ### Estate's layout and bird's eye view
    A photo representing the layout of the site and a "see from above" photo of the finished product.
- ### A photo gallery
    A gallery of photos representing the houses, amenitites and the POI (points of interest) in and around the site. 
- ### Contact section
    Gives users information about the contact details of the site's developer, estate agent and solicitor. Provides a contact form for any queries.
- ### Footer
    A footer section containing the business name and logo, another smaller callout button and social links.
- ### Accessibility
    Images are provided with descriptive text.

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
  * [lightGallery](http://sachinchoolur.github.io/lightGallery/) plugin was used for photo galleries.
- Version Control
  * [Git](https://git-scm.com/) as Version Control System
  * [Github](https://www.github.com) for repository hosting
  * [Commitizen](https://github.com/commitizen/cz-cli) for commit linting
- Wireframes
  * [Balsamiq](https://balsamiq.com/) for creating [wireframes](#wireframes)
- Media
  * [Inkscape](https://inkscape.org/) for creating the logo
- Other
  * [Colormind.io](http://colormind.io/bootstrap/) as a tool for color palette testing

## Testing
- ### Encountered Issues
  - video background on callout section would not autoplay on mobile, especially on android devices.
      - fixed by adding these attributes to ```autoplay loop muted``` acording to **[this article](https://developers.google.com/web/updates/2016/07/autoplay)** of **Sam Dutton** and **[this repo](https://github.com/googlechrome/samples/tree/gh-pages/muted-autoplay)** of **Google Chrome**.
      - for iOS10 devices I have used the ```playsinline``` video attribute.
      - This feature is still not supported by all browsers/devices. For this I have provided a fallback which consists of a static background image as follows: ```background: url('../images/hero-img.jpg') no-repeat;```
  - video background on callout section would not position on center of the screen.
    - fixed by adding the following css code to the ```.cta-video``` selector: 
        ```
        top: 50%;
        left: 50%;
        transform: translate(-50%, -50%);
        ```
        according to **[this article](http://thenewcode.com/777/Create-Fullscreen-HTML5-Page-Background-Video)** by **Dudley Storey**.
  - navbar would cover the title when navigating through the landing page using the nav links.
    - fixed by adding the following css code that offsets the target:
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

## Deployment
_[to be completed]_

## Credits
- ### Content
  - [HSQ.ie](http://www.hsq.ie/) as a general content inspiration.
  - [Abbotfield.ie](http://www.abbottfield.ie/) for site specification content.
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
_[to be completed]_