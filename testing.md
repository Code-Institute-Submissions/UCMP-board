# **Boardclass Website - Testing details**

[Main README.md file](https://github.com/Verga1/UCMP-board/blob/master/README.md)

[View website in GitHub Pages](https://github.com/Verga1/UCMP-board)

## **Testing**

[W3C CSS validation](https://jigsaw.w3.org/css-validator/)
[W3C Markup Validation](https://validator.w3.org/)
- The developer used W3C CSS Validation Service and W3C Markup Validation Service to check the validity of the website code.

### **Client stories testing:**

Most common path through the website:

Home > About > Contact
The headers and footers contain a flow of links for each page. They also contain a call to action button which guides the user to the Contact page.
The About page is not necessarily part of the flow of the site for users, but it contains information about the business. The information is brief so as not to overload the user.


### **Testing client stories from UX section of README.md**

1. As a new visitor to the website, I want to easily navigate the site, so I can find what I need efficiently.
- All pages contain an easy to use navigation bar.
- The logo image always leads back to the home page.
- The call to action buttons leads the user to the contact page.

2. A potential client will want to see samples of the software available and descriptions of what it can do.
- Home page provides features of product software.
- About page provides further detail on the product including screenshots.

3. An interested client will want an easy to fill in contact form, so they can make contact with the company and request further information or a free demo.
- A clearly labelled contact page is easy to find in the website navigation on every page, with call to action buttons leading to that page.

4. An interested observer and/or potential client, will want to follow the company on social media, in order to keep up with their latest news or get further information.
- 3 social media icons can be found in the footer on every page of the website.


###**Manual (logical) testing of all elements and functionality on every page.**

**Home Page:**

1. Navigation bar:

- Go to the "Home" page from a desktop.
- Change the screen size from desktop to tablet and phone to verify that the navigation bar is responsive.
- When checking responsiveness of navbar, verify that there is no overflow causing ugly size changes to menu items.
- Click on the logo in the navigation bar and verify that it links to the home page.
- Click on each navigation menu item and verify that it links to the correct page.
- Hover over the "Free Demo" button and verify the hover colour change works as expected.
- Click on the "Free Demo" button and verify that it links to the contact page.
- Repeat verification of functionality and responsiveness on my mobile phone and tablet.

2. Hero image:

- Go to "Home" page from a desktop.
- Confirm image is 100% width of the screen.
- Reduce the width of the window to confirm the image in responsive.
- Reduce and expand width of window to confirm that the text on top of image responds correctly and does not obscure important features.

3. Features section:

- Reduce and expand width of window to confirm that the text in this section responds correctly and looks good on all device widths.

4. Footer:

- Hover over each social media icon and confirm colour and size transitions expected.
- Hover over the "Free Demo" button and verify the hover colour change works as expected.
- Click on the "Free Demo" button and verify that it links to the contact page.
-  Click on each menu item and verify that it links to the correct page.
- Reduce and expand width of window to verify that the footer is responsive and looks good on all device widths.
- Review all functionality and responsiveness on my mobile phone and tablet.

**About Page:**

1. Navigation bar:

- Repeat verification steps done for navbar on Home page.
- Confirm that navbar code is identical on all html pages.

2. Who are we - Values section:

- Reduce and expand width of window to confirm that the text in this section responds correctly and looks good on all device widths.

3. Footer:

- Repeat verification steps done for footer on Home page.
- Confirm that footer code is identical on all html pages.
- Review all functionality and responsiveness on mobile phone and tablet.

**Contact Page:**

1. Navigation bar:

- Navbar code is identical on all html pages. Testing already completed.

2. Contact form:

- Try to enter first name details.
- Try to enter last name details.
- Try to choose an option from the options menu.
- Try to type text in the message box.
- Click on the Submit button - verify it leads to the contact page.
- Reduce and expand width of window to verify that the form display behaves and centres the way expected, and that it looks good on all device widths.

3. Footer:

Footer code is identical on all html pages. Testing already completed.
Review all functionality and responsiveness on mobile phone and tablet.

##**Further testing:**
Verify pages in different browsers.
Requested friends and family to look at the site on their devices and report any issues they found. No further issues found.