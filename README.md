# Zalama Care Services

Zalama care service is a site aim at providing information about social care services offered at Zalama care. The site offers visitors seeking care for themselves or their loved ones.

Target audience: adults with limited mobility or living with disability, elderly, individuals/families seeking care support for their loved ones and individuals who have just had a surgery and require support temporarily.

The site is helps individuals and families understand available care options for themselves or their loved ones. This site will ensure that the quality of life for our clients remain positive and their dignity is respected.

## Features 


### Existing Features
1) Logo icon and Navigation Bar - pages: Home, About, Services and Contact
  <figure>
    <img src="docs/site-screenshots/navbar-view-large-screen.png" width="80%" height="50%">
    <figcaption><strong><em>Navbar: Home page</em></strong></figcaption>
  </figure>

- **Logo** - when clicked, it allows users to return to home from any part of the website

- **Navbar | Home** - returns user to home pages

- **Navbar | About** - Allows user to navigate to the about page to learn more about the company's history, mission, vision statements and the team

- **Navbar | Services** - Allows users to navigate to the services section within the home page to get information about the types of care services we offer at Zalama care.

- **Navbar | Contact** - This navigates users to the contact page where they can complete a form to get in touch with the business or inquiry about a service


2) Expand/collapse button in services section
- 'Read more' to expand 
- 'Show less' to collapse
- Corresponding services icon are clickable with the same  functionality as the 'Read more'/'Show less' buttons 
4) 'Contact us', 'Enquire now' and 'Let's talk today' buttons
- On click, they redirect the user to the contact page where there is a contact form
5) Contact information in the footer
- phone number with a clickable icon to initiate a call (also available in about and success page)
- email address with a clickable icon for sending an email (opens and email app or prompts user to email - also available in about page)
- office address with clickable icon which opens a google maps link in new tab. This helps users to easily and conveniently locate the business 
6) Disability accessibility icon - informs users that the business premises support and are accessible to individuals with mobility needs
7) Video in footer
- shows an elder man being comforted overlaid with a contact us button
8) Business hours section in the footer
- Shows the office opening and closing times during weekdays, weekend and bank holidays
9) After hours notice in the footer
- informs users how to contact the business outside working hours
10) Link to Images and video credits modal in the footer
- when clicked, it open a modal listing sources of images, video and icon used in the project
11) Social media links
- when clicked, each link will open in a new tab and direct user to the home page of the relevant social media 
11) Contact form in contact page
- Comprises name, email, phone number, inquiry type (radio select) and message (text-area)
- all fields are required before form submission
12) success page
- appears when user submits a valid form and it confirms submission was successful and has a return to homepage link to redirect user back to home page
13) Responsive design
- Website layout and outlook remains consistent on different screen sizes which improves user experience 


### Features Left to Implement
This subsection covers other feature that would add good value to the site but are reserved for future releases of the project site.
1) Testimonials image carousel
- This would display past and existing client's stories/testimonial about their experiences with Zalama care's level of service. This is to build trust and confidence in the brand/service for the business.
2) Sign-up form for newsletter 
- A form to allow users to subscribe for business news, updates and any events from the business 
3) Careers's page
- For recruitment purposes, this page will provide information about working at zalama care, how to apply and what vacancies are available. The page will feature an application form for interested job-seekers.

## Project planning
in this section, we provide all tasks related to project planning. 

User stories and business goals are defined in this section

### Key business goals

Primary goal: Increase sales of care service packages.

Other goals:
- Share information about social care options we offer
- Increase engagement from visitors through enquiries and social media
- Improve online presence with high quality and accessible website
- attrack potential employees through careers's page

### User stories

1) Accessible and User-Friendly Navigation (Must-have)

Story: 
As a visitor (general), I want a user-friendly website with a clear and intuitive navigation so I can find specific information about care services.

Acceptance Criteria:
The website layout and navigation are intuitive making it easier for visitors to find important information on the site
The website is fully responsive and accessible on various devices with different screen sizes
All website content can be accessed by assistive technologies like screen-readers 

Tasks:
Implement HTML/CSS code to ensure responsiveness on different screen sizes
Use the appropriate aria attributes to ensure compatability with assistive technologies (e.g. screen readers)
Implement a user-friendly and intuitive layout with clear navigation for the website for ease of access to important information

2) Information on types of services offered (must-have)

Story: 
As a potential service user (or family/friend of), I need detailed descriptions of types of services offered so I can decide on a suitable service for me (or loved one).

Acceptance Criteria:
There is a dedicated page with detailed information and description of different types of services offered
There is a section in the home page with brief/summary information about different types of services offered and with links to the services page

Task:
implement HTML to provide descriptions of services in the services page and in a section of the home page 
Structure and style the content to include quality images
Include a clear CTA button/link in under each service type in the services page 
ensure responsivity across different screen sizes

3) Contact and address information (must-have)

Story:
As a family member seeking care support for my loved one, I need to find contact details so I can call or visit the office and enquire about some of the services.

Acceptance Criteria:
Essential contact information is present in a clear and well-structured manner (phone, email, address and operating times) 

Task:
Implement HTML section for the contact information (phone, email and address) and business hours
Structure and style the content to ensure responsivity on screen sizes

4) Enquiry form (must have)

Story:
As potential service user, I want to enquire about my specific needs for care and ask to be contacted.

Acceptance Criteria:
A page dedicated for enquiries with a user-friendly form to submit, the form confirms on submission
Add floating CTA buttons so visitors can click to be re-directed to the contact us page 
All form fields are validated where required and form is responsive 

Task:
Implement an enquiry form in the contact us page 
Ensure all essential fields in the form are validated before submission
create a confirmation page to acknowledge submission

5) Company mission, vision, values and team (should have)
Story:
As a family member/potential service user, I want to learn and understand the company's values and team expertise so I can feel confident about my expectations of care for my loved one 

Acceptance Criteria:
An about page clearly presents the company's vision and mission statements in an easy to read manner
organisation staff are displayed with their name, email and one-liner about why they're in social care 
core values are briefly described in the 'why choose us' section of the home page with a link to 'about' page
CTA to guide visitors to explore more about our service (links to services section) or contact us (links to contact us)

Task:
Implement about-us page with the company's mission & vision statements presented in a friendly and informative format
Add 'Our team' section in the about page, include an image, name, role, email and one line of positive comment about work
present core values in the 'why chose us' section using icons and brief description of those values
Include a small text with links/buttons to invite the visitors to explore 'services' sections or CTA for contact us

5) Onboarding steps (should-have)

User story:
As a prospective service user/family member, I want to see a brief outline of the different stages to go through in order to receive care services, so i can make an informed decision about requesting the service for myself/family member.

Acceptance criteria:
A section that gives an outline of the 4 stages of new service user onboarding from initial enquiry
Each step/stage is clearly presented in an easy to read format
CTA is included to guide the client towards the inquiry form

Task:
Add HTML and content for onboarding section
Style and format the section with the use of appropriate icons/images
Include a clear CTA for visitors to send an inquiry via the contact-us page 

6) Testimonials  with positive stories (could have)

Story:
As a potential service user, I want to read testimonies from from current/past service users so I can be assured and confident about the quality of service offered.

Acceptance Criteria:
A dedicated testimonial section features stories from current clients, shows name of client, type of service, year and one liner of feedback
Visually appealing high-quality images have been used and visitors can navigate through multiple testimonies with ease.

Task:
Create an auto sliding carousel of bootstrap cards with essential text (name, service type, year service received, comment) and quality images
Style the section to ensure it is responsive 

7) Newsletter Sign-Up form (Could have)

Story:
As a family member of service user, I want to sign-up for newsletter so I can stay informed about tips and guides we can employ to support our loved one 

Acceptance Criteria:
Newsletter sign-up form is available at the bottom of all pages
Visitors get confirmation about their subsciption after submiting the form

Tasks:
Create a sign-up form for the newsletter, include fields (full name and email)
Imeplement confirmation message once submission has been completed.

8) Careers page for recruitment (could-have)

Story:
As a job seeker, I want to find information about career/employment opportunities so I can submit an application online to be considered for future opportunities 

Acceptance Criteria:
A careers page has been created with a responsive application form
The page has content relevant for job seekers explaining benefits, job requirements and overview about working for the company
Confirmation is sent when the user (job seeker) submits an application form

Task:
create a careers page with an overview of benefits, general job requirements
Add an application form with fields (name, contact, email, address, experience, submit CV)
There should be confirmation to acknowledge submission of application form

### Wireframes
<figure>
  <img src="docs/wireframes/wireframe-home.png" width="50%" height="50%">
  <figcaption><strong><em>Wireframe: Home page</em></strong></figcaption>
</figure>
<figure>
  <img src="docs/wireframes/wireframe-about.png" width="50%" height="50%">
  <figcaption><strong><em>Wireframe: About page</em></strong></figcaption>
</figure>
<figure>
  <img src="docs/wireframes/wireframe-contact.png" width="50%" height="50%">
  <figcaption><strong><em>Wireframe: Contact Us page</em></strong></figcaption>
</figure>
<figure>
  <img src="docs/wireframes/wireframe-careers.png" width="50%" height="50%">
  <figcaption><strong><em>Wireframe: Careers page</em></strong></figcaption>
</figure>

### Color Pallet
We used the color pallet generator from
(https://coolors.co/)


## Testing 



## Deployment

This section should describe the process you went through to deploy the project to a hosting platform (e.g. GitHub) 

- The site was deployed to GitHub pages. The steps to deploy are as follows: 
  - In the GitHub repository, navigate to the Settings tab 
  - From the source section drop-down menu, select the Master Branch
  - Once the master branch has been selected, the page will be automatically refreshed with a detailed ribbon display to indicate the successful deployment. 

The live link can be found here - https://tumelo-maja.github.io/zalama-care/index.html


## Credits 
Youtube tutorial on how to create a 'Read More' button with only CSS - (https://www.youtube.com/watch?v=b6_u8IVVLdo)

Services content:
Home care and ADLs (https://www.ncbi.nlm.nih.gov/books/NBK470404/)

Create click to call button - (https://www.youtube.com/watch?v=hk5v-dO57n4) 

Add video and overlay with texts/other elements (https://www.youtube.com/watch?v=ytnOT-gg5Lw)

Accessibility Icon via Font Awesome (https://accessibleicon.org/)

Codepen for coloring png icons using hex color code (https://codepen.io/sosuke/pen/Pjoqqp)

Learn CSS ::before and ::after in 4 minutes - used for nav hover/ footer underline (https://www.youtube.com/watch?v=dIUOWdwwZBw)

JavaScript to collapse Bootstrap mobile navbar when navigating to in-page links

Spell checker extension for grammar fixes in the readme (https://marketplace.visualstudio.com/items?itemName=streetsidesoftware.code-spell-checker)
