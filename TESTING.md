# Testing
## Code Validation
The Dublin Minds website has be throughly tested. All the code has been run through the [W3C html Validator](https://validator.w3.org/) and the [W3C CSS Validator](https://jigsaw.w3.org/css-validator/). Minor errors were found on the home and inspiration pages. After a fix and retest, no errors were returned for both. 

The HTML validator results for each page are below:

* Home page

![W3C Validator test result](assets/readme-images/w3HTML-Index-test.PNG)

* Techniques page

![W3C Validator test result](assets/readme-images/)

* Bookings page

![W3C Validator test result](assets/readme-images/w3HTML-book-test.PNG)

* Contact Us page

![W3C Validator test result](assets/readme-images/w3HTML-contact-test.PNG)

* Form Response page

![W3C Validator test result](assets/readme-images/w3HTML-response-test.PNG)

The CSS validator results are below:

![CSS Validator test result](assets/readme-images/w3CSS-test.PNG)

## Responsiveness Test

* The responsive design tests were carried out manually with [Google Chrome DevTools](https://developer.chrome.com/docs/devtools/) and [Responsive Design Checker](https://www.responsivedesignchecker.com/).

|        | Moto G4 | Galaxy S5 | iPhone 5 | iPad | iPad Pro | Display <1200px | Display >1200px |
|--------|---------|-----------|----------|------|----------|-----------------|-----------------|
| Render | pass    | pass      | pass     | pass | pass     | pass            | pass            |
| Images | pass    | pass      | pass     | pass | pass     | pass            | pass            |
| Links  | pass    | pass      | pass     | pass | pass     | pass            | pass            |

Note: On wide display types the contents of the site is restricted in width to 2000px. This helps the UX by not spreading the content too wide on extra wide screens.

## Browser Compatibility

Dublin Minds website was tested on the following browsers with no visible issues for the user. 
Google Chrome, Microsoft Edge, Safari and Mozilla Firefox. Appearance, functionality and responsiveness were consistent throughout for a range of device sizes and browsers.

## Known Bugs
* ### Resolved

    * Bugs related to fonts became known when the icons code snippet copied from Font Awesome were not showing the icons on the rendered webpage.

    * Global
    ![Font Awesome script](assets/readme-images/footer-font-test.PNG)
    This was fixed by adding the required Font Awesome script during development.

    * An assumed oversight became known with a horizontal line showing on the index page, but which did not show up during an investigation using [Google Chrome DevTools](https://developer.chrome.com/docs/devtools/), this was fixed by removing hr syntax from css file.

    ![Horizontal Rule bug](assets/readme-images/hr-test.PNG)