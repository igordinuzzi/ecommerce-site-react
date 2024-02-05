# Fietsen, ecommerce in React

## Table of Contents
1. [Introduction](#oishi-izayaka)
2. [What's in Store](#whats-in-store)
3. [Features](#features)
4. [Existing Features and Features to Implement](#existing-features-and-features-to-implement)
5. [Technologies](#technologies)
6. [User Stories](#user-stories)
7. [User Flow](#user-flow)
   - [Task Flow for Booking a Table](#task-flow-for-booking-a-table)
8. [Wireframes](#wireframes)
9. [Code Snippets](#code-snippets)
10. [Testing](#testing)
11. [Deployment](#deployment)
12. [Credits](#credits)


This React-based platform emerges as a distinctive Dutch bike second-hand ecommerce site, skillfully merging product exploration, in-depth insights, and streamlined shopping within a 
richly functional and aesthetically pleasing digital environment. It leads users with a dynamic navigation bar and an inviting Hero section through a 
carefully selected assortment of Dutch bicycles and related accessories. The incorporation of an intuitive Product Search and detailed Product Pages simplifies 
the journey toward discovering and acquiring pre-loved cycling gems. Enhanced by a comprehensive FAQ section, an engaging About page, and a direct Contact form, 
the platform offers a narrative and a bridge to its community. The Sell Bike Form specifically invites users to become active contributors to this cycling marketplace. 
Further enriched by a Generic Banner for announcements and a strategically placed Footer for navigation, the site prioritizes transparency and user trust through its Cookie Consent feature. 
This platform isn't just an ecommerce site; it's a vibrant community hub dedicated to Dutch cycling culture, where every interaction signifies a pedal stroke towards a more connected cycling community.

 ![Mockup](doc/mockup.png)

## What's in Store:

- Inventory: Dive into our extensive collection of pre-loved Dutch bikes and cycling accessories. From classic city bikes to rugged touring models, our inventory caters to every cyclist's needs. Discover high-quality, second-hand gems and find the perfect ride to match your lifestyle and preferences.

- Heritage: Every bike tells a story. Explore the rich history behind our Dutch bike second-hand ecommerce platform, our dedication to sustainability, and the cycling culture that drives us forward. Delve into the stories of previous owners, the craftsmanship of Dutch bicycles, and the values that underpin our community-focused mission.

- Purchase & Sell: Begin your next cycling chapter with us. Whether you're looking to purchase a piece of Dutch cycling heritage or sell your own bike, our platform makes the process straightforward and secure. Use our online system to find your next bicycle or to give your old bike a new home, fostering a cycle of continuous passion and care within the cycling community.

Step onto our digital platform for an unparalleled journey into the world of Dutch cycling. We're excited to connect you with the bikes, stories, and community that make Dutch cycling not just a mode of transportation, but a way of life. Welcome to our cycling community, where every transaction is a pedal stroke towards a more sustainable and connected world.

Live webpage [here](https://igordinuzzi.github.io/oishizakaya/)

## Features

- Navigation:
Adaptive navigation with comprehensive links ensures seamless browsing on every device. Essential to crafting an intuitive online environment, this React component facilitates smooth exploration through the site's diverse sections, thereby enhancing user engagement and satisfaction. Through meticulously structured navigation, implemented via React Router and Bootstrap for responsive behavior, users can effortlessly locate desired information, products, or services. This not only amplifies usability but also strengthens user retention by offering an accessible and navigable interface. The NavBar component, enriched with dynamic cart animations and straightforward access to cart management, embodies a pivotal touchpoint in the user journey, reinforcing the seamless blend of functionality and aesthetic appeal. Incorporating icons from FontAwesome for visual cues and utilizing a collapsible design, it ensures that navigation remains fluid and user-focused across all viewing platforms.
 ![Navigation](doc/features/nav-desktop.jpg)
 ![Navigation mobile](doc/features/nav-mobile.jpg)
  
- Footer: 
Anchoring the site, the footer integrates social media connectivity, app store accessibility, and intuitive navigation. It prominently displays icons for Facebook, Twitter, and Instagram, seamlessly connecting users to the platform's vibrant social community for updates and engagement. The footer also houses a concise navigation menu, guiding visitors through key site pages such as Home, Products, Sell Your Bike, About, FAQs, and Contact, thereby enhancing the user experience. Essential for those interested in deeper engagement, an email link fosters direct communication. Additionally, it features a visually appealing section with links to download the platform's application from Google Play and the Apple App Store, inviting users to access the site's offerings on-the-go. This React component, styled with custom CSS and leveraging FontAwesome icons for visual appeal, not only solidifies the site's brand presence but also underscores its commitment to accessibility, community engagement, and user convenience.
  ![Footer](doc/features/footer-desktop.jpg)
  ![Footer mobile](doc/features/footer-mobile.jpg)

- Favicon for easy recognition.
The favicon is important in a webpage as it provides a recognizable visual identity in browser tabs, 
enhancing brand visibility and user recognition, and it helps users quickly locate and return to the site.
  ![Favicon](doc/features/favicon.png)
  
- Landing page 
The interface of this React application is architecturally designed to streamline user navigation, featuring a fluid layout that intuitively guides users through its comprehensive functionalities. Upon entering, users are welcomed by a Hero component that sets the tone for their journey, further complemented by a NavBar for easy access to various sections including Products, About, FAQs, and more. The core of the application revolves around the ProductList, where users can browse through an array of second-hand Dutch bikes and accessories, enriched by a ProductSearch component to refine their exploration. Detailed views provided by the ProductDetail component enhance user engagement by offering in-depth information about each item, including the option to add products to a virtual cart.

Interactivity is heightened through real-time feedback mechanisms, such as notifications for added or removed cart items, and a Cart page that summarizes the user's potential purchases. The SellBikeForm introduces an interactive platform for users to contribute to the cycling community by listing their own bikes for sale. Additionally, the application encompasses informative sections like About, FAQ, and Contact, offering insights into the platform's mission and operations. A GenericBanner serves to highlight special announcements or deals, further engaging the audience.

The application's layout ensures that essential features are within easy reach, facilitated by smooth scrolling functions and responsive design principles, ensuring compatibility across all devices. The Footer component anchors the experience with social media links, app store downloads, and a concise navigation menu, encapsulating the essence of the platform's brand and community ethos. Through thoughtful integration of components like CookieConsent, the application emphasizes user privacy and compliance, rounding off a holistic user experience designed to cater to the needs of Dutch bike enthusiasts and casual browsers alike.
    ![Welcome Page](doc/features/index-desktop.jpg)
    ![Welcome Page](doc/features/index-mobile.jpg)


  

## Existing Features and Features to Implement

**Existing features:**
- JavaScript functionality for the navigation burger menu.
- JavaScript functionality for bouncing calls to actions.
- JQuery functionality for changing the greeting in the hero image based on the user's timezone. 
- JavaScript functionality for menu tabs.
- JavaScript functionality for the milestone timeline.

## Technologies

The Oishi website utilizes the following technologies:

- Figma for design.
- FontAwesome for icons.
- CSS for styling.
- HTML for content.
- JavaScript
- JQuery
- Visual Studio Code for development.
- GitHub for version control.
- ChatGPT for content creation.

## User Stories

1. **As a food enthusiast,** I want to explore a Japanese Izakaya menu online so I can decide what to try before visiting.

2. **As a potential customer,** I need an easy way to book a table at Oishi Izakaya, ensuring I have a reserved spot.

3. **As a tourist in Tokyo,** I am looking for a local dining experience and want to find a Japanese tavern with an authentic atmosphere.

4. **As a regular customer,** I want to keep up with any new additions to the menu or special offers at Oishi Izakaya.

5. **As a social media user,** I want to follow Oishi Izakaya on platforms like Facebook, Twitter, and Instagram to stay connected.

## User Flow

1. **Landing on the Website**
   - User is greeted with a vibrant homepage showcasing Oishi Izakaya’s ambiance.
   - Sees the navigation menu with options like Home, Menu, Book a table, About Oishi, and Contact us.

2. **Exploring the Menu**
   - Clicks on 'Menu' to explore the variety of dishes and drinks offered.
   - Browses through different categories and items.

3. **Making a Reservation**
   - Navigates to 'Book a table' to make a reservation.
   - Fills in details like date, time, and number of guests.
   - Confirms the booking and receives a confirmation.

4. **Learning About the Izakaya**
   - Visits 'About Oishi' to learn about the Izakaya’s history, values, and unique selling points.

5. **Contacting the Izakaya**
   - Chooses 'Contact us' for inquiries or feedback.
   - Uses the provided form or contact details to reach out.

6. **Following on Social Media**
   - Scrolls to the footer to find social media icons.
   - Follows Oishi Izakaya on selected platforms for updates and community engagement.

### Task Flow for Booking a Table

1. **Accessing the Reservation Section**
   - User clicks on 'Book a table' from the navigation menu.

2. **Filling in Reservation Details**
   - Enters the required information: date, time, and number of guests.
   - Optionally provides additional preferences or requests.

3. **Submitting the Reservation**
   - Reviews the entered details.
   - Clicks on a button to confirm the booking.

4. **Receiving Confirmation**
   - Receives a notification or email confirming the reservation with the details.

### Additional Notes

- The website is designed to provide an immersive experience that reflects the ambiance and offerings of Oishi Izakaya.
- Emphasis is placed on easy navigation and accessibility to cater to a diverse user base.
- Social media integration and online reservation functionality enhance user engagement and convenience.

## Wireframes

```css
:root {
  --main-font: 'Karla', sans-serif;
  --secondary-font: 'Bitter', serif;
  --primary-color: #76141C;
  --secondary-color: #764214;
  --background-color: #E0E0E0;
  --text-color: #282c45;
  --link-color: #350004;
  --link-hover-color: #F8CACD;
  --hover-color: #141E76;
}
```

 ![Book mobile](doc/wire/01.jpg)
 ![Book mobile](doc/wire/02.jpg)
 ![Book mobile](doc/wire/03.jpg)
 ![Book mobile](doc/wire/04.jpg)
 ![Book mobile](doc/wire/05.jpg)
 ![Book mobile](doc/wire/palette.jpg)

## Learning Outcomes

From a student's perspective, the Oishi Izakaya project offered a valuable opportunity for learning and development, particularly in the following areas:

- Web Design and Development: Gaining practical experience in designing and developing a responsive and user-friendly website.
- Creative Problem Solving: Overcoming design and development challenges to create a website that effectively conveys the essence of a Japanese izakaya.
- Technical Skills Enhancement: Improving skills in HTML, CSS, JavaScript, and jQuery.
- User Experience Design: Understanding the importance of creating a seamless and engaging user experience.
- Project Management: Learning to manage a web development project from concept to deployment.
- Cultural Exploration: Gaining insights into Japanese culture and cuisine, and translating that understanding into the design and content of the website. 

## Code snippets
 ![Book mobile](doc/code/01.jpg)
 ![Book mobile](doc/code/02.jpg)
 
## Testing

The website has been thoroughly tested on various devices and browsers:

- Mobile (iPhone 14)
- Smaller laptop MacBook Air
- iMac

**Responsiveness:**

All pages were tested to ensure responsiveness on screen sizes from 320px and upwards as defined in WCAG 2.1 
Reflow criteria for responsive design on Chrome, Edge, Firefox, Safari and Opera browsers.

Steps to test:

- Open the browser and navigate to Oishi Izakaya
- Open the developer tools (right-click and inspect)
- Set to responsive and decrease width to 320px
- Set the zoom to 50%
- Click and drag the responsive window to the maximum width

Expected:

The website is responsive on all screen sizes and no images are pixelated or stretched. 
No horizontal scroll is present. No elements overlap.

Actual:

The website behaved as expected.

The website was also opened on the following devices and no responsive issues were seen:

- iPhone 14
- iPhone SE
- Samsung Galaxy Android S20 Android 11
- MacBook Air
- iMac 27''
- iMac 24''


**Accessibility:**

[Wave Accessibility](https://wave.webaim.org/) tool was used throughout the development 
and for final testing of the deployed website to check for any aid accessibility testing.

Testing was focused to ensure the following criteria were met:

- All forms have associated labels or aria-labels so that this is read out on a screen reader to users who tab to form inputs
- Color contrasts meet a minimum ratio as specified in WCAG 2.1 Contrast Guidelines
- Heading levels are not missed or skipped to ensure the importance of content is relayed correctly to the end user
- All content is contained within landmarks to ensure ease of use for assistive technology, allowing the user to navigate by page regions
- All not textual content had alternative text or titles so descriptions were read out to screen readers
- HTML page lang attribute has been set
- Aria properties have been implemented correctly
- WCAG 2.1 Coding best practices being followed

Manual tests were also performed to ensure the website was as accessible as possible and an accessibility issue was identified.

I've discovered several errors on the webpage, specifically related to headers and the iframe. 
I fixed these issues to enhance accessibility and ensure that all users can easily navigate 
and interact with the content, promoting a more inclusive and user-friendly experience.

**Browser Compatibility Checked:**

- Safari
- Firefox
- Google Chrome

**Functional Testing**

Navigation Links:

Testing was performed to ensure all navigation links on the respective pages, navigated 
to the correct pages as per design. This was done by clicking on the navigation links on each page.

| Navigation Link | Page to Load          |
| --------------- | ----------------------|
| Home            | index.html            |
| Menu            | menu.html             |
| Book a table    | reservation.html      |
| About           | about.html            |
| Contact         | contact.html          |
| 404             | 404.html              |

Links on all pages navigated to the correct pages as expected.

| Test Case                 | Description                                                       | Expected Result                                                                  |
|---------------------------|-------------------------------------------------------------------|----------------------------------------------------------------------------------|
| 1. Homepage               | Verify that the homepage loads successfully.                      | Page loads without errors.                                                       |
| 2. Navigation             | Test the navigation menu to ensure all links are functional.      | All links navigate to the correct pages.                                         |
| 3. Menu Items             | Check if menu items can be viewed and selected.                   | Menu items are visible and selectable.                                           |
| 4. Images                 | Confirm that images load properly and are not broken.             | All images are displayed without errors.                                         |
| 5. Contact Form           | Test the contact form for usability and submission.               | Form fields can be filled and submitted without errors.                          |
| 6. Mobile Responsiveness  | Test the webpage on different screen sizes.                       | Content adjusts and remains readable on various screen sizes.                    |
| 7. Browser Compatibility  | Verify that the webpage works on multiple browsers.               | Webpage functions correctly on popular browsers (Chrome, Firefox, Safari, etc.). |
| 8. Social Links           | Check if social media links are functional.                       | Social media links open in new tabs and navigate to the correct profiles.        |
| 9. Loading Speed          | Measure the loading speed of the webpage.                         | Page loads within an acceptable time frame.                                      |
| 10. Error Handling        | Test for proper error messages when encountering issues.          | Appropriate error messages are displayed when errors occur.                      |

**Usability testing**

Conducting web usability testing for Oishi Izakaya was essential 
to ensure that our webpage provides a seamless and user-friendly experience across 
both mobile and desktop platforms. By gathering insights from real users, we aimed 
to identify any potential issues, enhance the overall usability, and validate the functionalities 
of our website. Maria, Carlos, and Sofia, all in the same age group, were among 
the individuals who participated in the testing process. Their valuable feedback and interactions 
with the webpage allowed us to make necessary improvements, ensuring that Oishi Izakaya's 
online presence meets the needs and expectations of our diverse user base. The three participants 
got the mission without any problem quickly, underscoring the effectiveness of our 
user-centred design approach. We are committed to delivering an exceptional online experience for our visitors, 
and web usability testing played a pivotal role in achieving this goal.

_Scenario One - Mobile Responsiveness and Booking_

Steps to test:

1. Open the Izakaya webpage on a mobile device.
2. Verify that the webpage is responsive and all content is displayed correctly.
3. Click on the "Book a Table" link in the navigation.
4. On the "Book a Table" page, fill in the required information, including selecting a date and time for the reservation.
5. Submit the booking request using the input forms.

Outcome: The webpage worked properly on a mobile device, with a responsive design. The user effectively 
achieved the mission of booking a table by successfully providing the required information, 
including the date and time, through the input forms.

_Scenario Two - Desktop Menu Navigation_

Steps to test:

1. Access the Izakaya webpage on a desktop computer.
2. From the landing page, locate the navigation menu.
3. Click on the "Menu" option.
4. On the "Menu" page, find and click on the "Dessert" tab.
5. Verify that the "Dessert" menu is displayed, and you can view the dessert options.

Outcome: The webpage worked properly on a desktop computer. The user effectively achieved 
the mission by easily navigating to the "Dessert" section of the menu, where dessert options were displayed as expected.

_Scenario Three - Contact and Directions:_

Steps to test:

1. Visit the Izakaya webpage.
2. Navigate to the "Contact" page.
3. Click on the map or a relevant link to access the embedded Google Map.
4. Use the map to get directions to the Izakaya's location using Google Maps.

Outcome: The webpage worked properly, allowing the user to access and interact with the embedded Google Map. 
The user effectively achieved the mission of obtaining directions to the Izakaya's location through Google Maps.

_Scenario Four - About Me Page and Milestone Tabs_

Steps to test:

1. Enter the Izakaya webpage.
2. Navigate to the "About Me" page.
3. Scroll down the page to find the section with opening and closing milestones.
4. Click on the tabs or buttons associated with the milestones to view their content and details.
5. Ensure that the milestones' information is presented accurately.

Outcome: The webpage worked properly, providing the user with a smooth scrolling experience. 
The user effectively achieved the mission of exploring the "About Me" page and accessing the opening 
and closing milestones by clicking on the relevant tabs. The milestones' information was accurately presented.

**Lighthouse Report:**

- Landing Page
  ![Landing Page Lighthouse](doc/lighthouse/index.jpg)


- Menu page
  ![Thank you Lighthouse](doc/lighthouse/menu.jpg)

- Book a table page
  ![Thank you Lighthouse](doc/lighthouse/book.jpg)

- About page
  ![Thank you Lighthouse](doc/lighthouse/about.jpg)

- Contact page
  ![Thank you Lighthouse](doc/lighthouse/contact.jpg)

- 404 page
  ![Thank you Lighthouse](doc/lighthouse/404.jpg)    


**W3C Validator results:**


- Landing Page
  ![Landing Page Lighthouse](doc/checker/index.jpg)


- Menu page
  ![Thank you Lighthouse](doc/checker/menu.jpg)

- Book a table page
  ![Thank you Lighthouse](doc/checker/book.jpg)

- About page
  ![Thank you Lighthouse](doc/checker/about.jpg)

- Contact page
  ![Thank you Lighthouse](doc/checker/contact.jpg)

- 404 page
  ![Thank you Lighthouse](doc/checker/404.jpg)

**Javascript Validation results:**

- Button
  ![JS Button](doc/js/button.jpg)

- Fast click
  ![JS fast click](doc/js/fastclick.jpg)

 - Greetings
  ![JS greetings](doc/js/greetings.jpg)

  - Menu tabs
  ![JS tab](doc/js/menu-tabs.jpg)

  - Milestones
  ![JS milestones](doc/js/milestone.jpg)

  - Navigation
  ![JS navigation](doc/js/navigation.jpg)

  - Responsive Navigation
  ![JS resp navigation](doc/js/responsive-navigaiton.jpg)

  - Scrolling
  ![JS scrolling](doc/js/scrolling.jpg)  

## Deployment:

**Version Control:**

The site was created using the Visual Studio code editor and pushed to Github to the remote repository ‘Oishizakaya’.
The following git commands were used throughout development to push code to the remote repo:
git add <file> - This command was used to add the file(s) to the staging area before they are committed.
git commit -m “commit message” - This command was used to commit changes to the local repository queue ready for the final step.
git push - This command was used to push all committed code to the remote repository on GitHub.

**Deployment to Github Pages:**

The site was deployed to GitHub pages. The steps to deploy are as follows:
In the GitHub repository, navigate to the Settings tab
From the menu on left select 'Pages'
From the source section drop-down menu, select the Branch: main
Click 'Save'
A live link will be displayed in a green banner when published successfully.
The live link can be found [here](https://igordinuzzi.github.io/oishizakaya/)


## Credits

- Design and Development: Igor Dinuzzi
- Content Creation: ChatGPT
- Iconography: FontAwesome
- Images: Sourced from Unsplash



