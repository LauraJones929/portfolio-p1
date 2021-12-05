# Portfolio Project 1 - HTML / CSS
## **Jess Hynes Music - Live Site**
[View Live Site](https://laurajones929.github.io./portfolio-p1/)

## **Business Objectives**

For this project I have designed and created a genuine, static website for a professional, local singer. The website will be used to promote what she has to offer, as well as inform her potential clients/customers of the range of packages and entertainment that she provides.

The application is designed to be accessible to all users and responsive to all screen sizes, so that the targeted audience can easily navigate through the site and achieve what they set out to do.

The project's main purpose and focus is to ensure that I successfully complete my first milestone on the Code Institute course. I have used HTML and CSS only as I wanted to build on these skills first, before expanding my knowledge on Bootstrap or any other frameworks.

![Homepage Mockup](assets/imgs/mockups/homepage.png)

## Client's Requests

Since the pandemic restrictions have been lifted, Jess has a heavy number of enquiries coming in and an even larger number of people wanting to book her in. As Jess has always taking bookings and enquiries on her mobile phone, she is now struggling to keep track of her schedule and needs a platform that is more accessible and appropriate for managing her business.

In order to create an informative and effective platform, these are the key features that the client has requested:
- an 'About Me' section - this gives a detailed insight into who Jess Hynes is and what skills she possesses.
- media (images and videos) - these are displayed throughout the website. Embedded YouTube videos as well as background images to add the desired aesthetic. *Images/videos are credited and sourced throughout.*
- a list of packages - this informs potential clients/customers of Jess' packages that she has to offer.
- a contact form - to allow potential clients/customers to get in touch with any enquiries that they may have. *As this project is HTML/CSS focused, the form is static until I have aquired further skills in order to be able to script in the necessary attributes and coding to send form input to a specific destination.*
- social media links available at all times throughout site - this allows users to access Jess' social platforms if desired.

## **User Experience (UX)**
### User Stories
- **First Time Visitor Goals**
  - As a first time visitor, I want to be able to quickly navigate through the site and see what style and aesthetic Jess brings as I'm interested in booking her for my wedding.
  - As a first time visitor, I want to be able to locate Jess' social media links.
  - As a business owner, I want to allow any potential clients to navigate through my site easily without getting lost or feeling overwhelmed as this could put people off and they may look elsewhere.

- **Returning Visitor Goals**
  - As a returning visitor, I want to find contact information to enquire about prices and availability.
  - As a first time visitor, I want to find a link to be able to listen to Jess on Spotify or YouTube.
  - As a business owner, I want to provide social media links that are easy to spot and access.

- **Frequent Visitor Goals**
  - As a frequent visitor, I want to see if there are any new packages available for cooperate events.
  - As a business owner, I want to update any new videos or package offers onto my website.
  - As a business owner, I want to be able to receive any queries or messages from potential customers via email.

### Design
- **Colour Scheme**

Colour contrast checks were made throughout the process of building the project to save going back and re-doing colours that did not work together.
  
  - The main colour scheme is neutral and light, in order to highlight any darker text. As photographic images are used throughout the site, neutral colours will not take away any attention from the images that are put in place for promotional and decorative purposes.
  - For backgrounds (body/header/footer) I have chosen to use white and off-white, a very subtle difference which is easy on the eyes for users. When looking back at any strategy planning regarding this project, the users are looking to potentially book the client to perform at an event, whether it is a wedding, a festival or a store opening, however most of her bookings do come from weddings, therefore I thought it was more appropriate to use softer colours, as opposed to bright and bold or too contrasting.
  - For any element background, including paragraphs, contact form and the contact icon, I have used a faint, low-key green that ties in nicely with the white tones. Green is known for its ability to induce calming and relaxing emotions which I think suits the style of music that the client has to offer, as well as creating a positive emotional response for users.
  - The text throughout the site is a very dark grey as I thought black would be too contrasting and take away the soft, subtleness that I was aiming for.
  
- **Typography**

  - Fonts are imported into the CSS file via Google Fonts.
  - To keep the website looking clean and neutral, a selection of 3 fonts is used throughout the website, 2 of which have a very similar look and feel.
  - For the main heading which is the artists name, I have chosen to use the font family of 'Parisienne', with a fallback font of 'Cursive', in the event of the preferred font failing to import. This font will hopefully create a positive user experience when first entering the site as it exudes a professional yet warm mood.
  - For sub-headings which includes the navigation menu, along with sub-titles across the page/s, I have chosen to use the font family of 'Raleway' as it stands clean and clear, making a statement but not enough to draw attention away from more important features on the page. In the event of this font failing, I have set the fallback font to 'Sans-serif'.
  - For general text I have chosen the font family of 'Inter'. Again this is a clean and clear font that is easy to read, and maintains the neutral tone flowing throughout the site. Fallback font set to 'Sans-serif'.
  
  Text is responsive throughout the site and is easily readable across all screen sizes. 308px is the lowest breakpoint where the nav menu will appear outside of the header.

- **Imagery**

  - Photographic imagery is used throughout the site. Background imaging is used across the page to give the user a well rounded look and feel of the clients' aesthetic and style. Images are used to capture the essense of the artist and the height of the entertainment that she brings. After consideration, 2 background images will be used so as to not overload the page with distractions, this will also encourage the user to access the clients' social media via the link icons.
  Each image is provided by the client and is taken from her social media accounts. These images are credited and sourced appropriately in the credit section of the README file and in comments above the relevant code.

  The header will be fixed to the top of the page when scrolling so the user can navigate between sections without having to scroll back to the top. The footer is also fixed so that the user is aware of social media links, the client has requested that social media links be available at all times.

  Videos that the client has recorded in her home studio have been embedded via iframe elements, sourced by YouTube. The videos respond to screen sizes so that they fill the screen width on smaller devices, and maintain an evenly spaced row on larger devices.

### Wireframes
Below are 3 links to show the initial drafts for each screen size. They show how I expect the responsivity between devices to go and how the structure of each page will look.

The project is designed with a desktop first approach. I felt this was more appropriate as the majority of the clients' bookings are made by businesses or store owners, who are more likely to be working from a desktop. The client has also specified that she will be accessing and managing the website from her own laptop.

- [Desktop Wireframe](desktop-wf.md)
- [Tablet Wireframe](tablet-wf.md)
- [Mobile Wireframe](mobile-wf.md)

After initiating the project, I decided that I would no longer have separate pages on the website but instead I will have different sections that are clearly spaced and marked on one page. The user is able to navigate between sections via a fixed navigation menu. As there is not a great deal of text or content within each section, only what is needed, I thought this would be the best approach as separate pages would look too spacey or empty.

Some other changes that I made compared to the wireframe are as follows:
- The text on each page does not overlay the background image. The background images now have their own section as I felt the overlaying would look too busy, and would not match the desired effect of subtlety.
- The textbox in the contact form is now under the name and email address input area, rather than to the right side of them.
- I have embedded 3 iframe videos instead of 5, as I felt 3 looked more pleasing to the eye when in a row.
- The event services are in a list on a single line (2 lines on smaller screen sizes) rather than in separate paragraphs.

![Various Mockups](assets/imgs/mockups/various.png)

## Features
### Existing Features
- Logo - located in the top-left of the header, the logo acts as a link to the landing page. As the header is fixed and visible at all times, the user can use either the logo or the nav menu to go back to the home section (top of the page)

![Logo](assets/imgs/features/logo.png)


- Navigation bar - Sticks to the right side of the header which is fixed to the top of the page at all times. As this is a one page website, this will make it easier for users rather than having to scroll between in section.
Hover effect creates a bottom border with a green colour to match the green colour that is often used throughout the page.

![Navbar](assets/imgs/features/navbar.png)

- Landing Page - On first entering the site, users will be drawn to hero image of the singer. This image uses warm colours and has a 'friendly' feel to it that invites the users in. From here they can easily navigate the site via the navigation menu or by scrolling.
- Images - Large background images (photographs) will draw the users' attention as they are brightly coloured and bold against the subtleness of the webpage. The images bring a "fun-ness" to the site, creating a positive emotional response.
- Text - Paragraphs throughout the site provides the user with some basic information about Jess, including her achievements and what she has to offer.
- Contact icon - An envelope icon is centered half way down the page, below the events services section, so that users can click this icon and be directly taken to the contact form.
- Videos - YouTube videos that Jess has recorded in her home studio are embedded via iframes, so the user can see what sounds and styles Jess brings to the table.
- Contact form - A static contact form is in place, currently sourced by HTML and CSS only. After aquiring the skills to enable to me to make this an active form, users will be able to contact Jess via email with any enquiries that they may have.

![Contact form and Footer](assets/imgs/features/footer.png)

- Footer - The footer is fixed so that social media links are visible and accessible at all times. Links are opened in a new tab. Currently the links will only take you to the social platforms home page, eventually I would like to link these up with the clients' social media accounts.

### Features yet to implement
- The logo is currently made using HTML text and CSS styling. I would like to aquire the skills to design and create a logo so that it could be embedded as an image.
- I would like to add some sort of interactive system, such as calendly, to select a wedding package or event service so users can set a date with Jess in accordance to her calendar.
- The videos as they are now clash quite a bit as they have different images when static. I would like to create an overlay that sits on top of the video, before being interacted with, so that they are of a consistent and common theme and colour, such as a background colour with the title of the song being sang in the video.
- The contact form currently sends any messages submitted to the CI form dump, this is because this project is purely based on HTML and CSS. I would like to set the form up so that the client can receive emails from users.
- Verification or feedback for the user after a message has been submitted on the form.

## Technologies Used
### Languages
- HTML - Used to build the main structure of the webpage.
- CSS - Used to style the content of the webpage.

### Libraries
- Hover.css - Used in the nav menu, submit button and all icons when hovered over (nav menu - bottom border, icons and button - change of colour)
- Google Fonts - Imbedded in the CSS, Google fonts are used in the header and body of the project.
- Font Awesome - Icons used for social media links as well as a link directly to the contact form.
- Balsamiq - Used to create wireframes for the project.
- Chrome Dev Tools - Heavily used to fix any spacing issues as well as testing responsivity.
- Github - To store repositories and codes after being pushed on Gitpod.
- Git - Used for version control and tracking changes made to files.
- Gitpod - Used for the workspace for this project.
- Multi Device Mockup Generator (techsini) - To create an image of what the project will look like on various devices. TechSini.com
- WebAIM Contrast Checker - To test colours throughout the site for whether or not they will produce good user experience.
- W3C Markup Validator - To check for any HTML or CSS errors. There were some errors such as open tags or incorrect CSS values. These were all corrected and the project was fortunately left with 0 errors.

## Testing

Most testing was carried out via Google Chrome browser and the Chrome Dev Tools for responsivity and colour contrast checking, throughout the process of building the project. I also tested the site on an iPhone 12 for responsivity, this included Google Chrome which showed no errors, and on Safari which did show some issues regarding the background images that would often stick when scrolling. Additional testing was carried out which I will include below.