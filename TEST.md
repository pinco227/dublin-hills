# Testing

## Table of Contents
- [Encountered Issues](#encountered-issues)
- [Testing User Stories](#testing-user-stories)
- [Testing Functionality](#testing-functionality)
- [Testing Compatibility](#testing-compatibility)
- [Testing Performance](#testing-performance)
- [Testing Accessibility](#testing-accessibility)
- [Code Validation](#code-validation)
- [Further Testing](#further-testing)
## Encountered Issues
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
  - when validated the code through [W3C Validator](https://validator.w3.org/), **2 issues** were found on each page.
    - **FIXED** by taking the ```h1``` out of its container and moved as a direct child of the ```<article>```. For the landing page, the ```h1``` is part of the CTA so for fixing this issue, the ```<section>``` element has been removed from CTA so that the ```h1``` is a child of the ```<article>```. For house pages, moving up the ```h1``` has left the first section with no header. This has been fixed by adding a ```h2``` header to the presentation section. See details below...  
    ![W3C Validator Results](https://github.com/pinco227/dublin-hills/blob/main/docs/w3c-issues.png)  
## Testing user stories
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
## Testing functionality
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

## Testing Compatibility
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
  
## Testing Performance
  > ### Landing page
  > ![LightHouse Landing Page Results](https://github.com/pinco227/dublin-hills/blob/main/docs/landing-lighthouse.png)  
  > Performance has been tested using chrome lighthouse tool. The results are slightly different every time due to device performance and value estimation. The performance test results are satisfying as the landing page is heavy loaded with content, especially images and the hero video. See further details below...
  > ![LightHouse Landing Page Performance](https://github.com/pinco227/dublin-hills/blob/main/docs/landing-perf.png)

  > ### House details page
  > ![LightHouse Landing Page Results](https://github.com/pinco227/dublin-hills/blob/main/docs/house-lighthouse.png)  
  > On these pages the performance test values are higher then the landing page as these pages are not so heavy on content (less images and no video). See further details below...  
  > ![LightHouse House Page Performance](https://github.com/pinco227/dublin-hills/blob/main/docs/house-lighthouse-perf.png)

## Testing Accessibility
  > The accessibility was tested throughout the site using chrome lighthouse and [a11y contast cecker](https://color.a11y.com/Contrast/). The result are satisfying in both cases. When contrast was checked wit a11y tool, there were 3 issues displayed on the landing page. The first two issues are for the hero headings, as they are on an absolute position container overlayed on top of the video, the contrast checker tool cannot evaluate correctly. The third issue is with the Developer card from the contact section of the landing page and this has been a design choice and can be ignored. No contrast issues found on the house details page.
## Code Validation
  > ### HTML
  > Html was tested and validated with [W3C Validator](https://validator.w3.org/). **No errors or issues**. The results are satisfying on all pages. 

  > ### CSS
  > CSS was validated with [W3C CSS](https://jigsaw.w3.org/css-validator/) by direct input. The results came with no error and only warnings about the vendor prefixes, which can be ignored.

## Further Testing
  > ### Overflow
  > Every page was tested for overflow by using the [Unicorn Revealer](https://chrome.google.com/webstore/detail/unicorn-revealer/lmlkphhdlngaicolpmaakfmhplagoaln?hl=en-GB) chrome extension to highlight the elements margins.

  > ### Spelling
  > Spelling throughout the website was checked using [W3C Spell Checker](https://www.w3.org/2002/01/spellchecker). The results are satisfying. The only spelling errors are actually technical names and UK-US english differences such as ```centre - center```.

