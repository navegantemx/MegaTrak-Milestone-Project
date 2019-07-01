MegaTrak - Automated Fuel Tracking System 

Stream One Project: User-Centric Frontend Development - Code Institute

This is my fuel management system website for the transportation industry. 
The website shows diferent technologies of fuel tracking systems for gas and alternative fluids. 
There is information about diferent ways to collect fueling transactions data and software support. 
The contact form allows potential customers to submit their fuel tracking needs information to get a quick quote or estimate.

Demo
A live demo can be found here. ????

Desktop Demo ????

UX
My goal in the design was to provide potential customers all the necesary information to make a desicion based on their fuel tracking
and administrative software needs. I made as easy as possible the access of the information on the site.

In the "contact" section, I wanted to provide an easy way to sumbmit critical information required to get a quick system's cost estimate.

I also included a link to our "Customer's Service Support Site" ??? and "Download Site"???

Technologies
HTML
CSS
Bootstrap (4.1)

Features
This site uses the "Navbar" feature in Bootstrap with an extra JavaScript function added to create a 'smooth scrolling' effect. 
The navbar also sticks regardless of screen scrolling.
A "Carousel with Indicators" feature was also used from Bootstrap components.


Features Left to Implement
I would like to add in the future, information about the administrative software functions with sample screens.

Testing
The "News" section is intended to provide fleet managers with information on the latest fuel management industry technologies. 
In the "Support" section, they can find information on MegaTrak's main service support technicians as well as accesing social media profiles via clicking on the Font Awesome icons.

If you try to submit the contact form with an invalid email address, there will be an error noting the invalid email address. 
Furthermore, the 'required' attribute is added to all form input fields, so if those fields are not filled in, the form will not submit. 
If all field are valid, the page will reload. If potential customers are interested in contacting me, they will have to fill out all fields in order for the form to go through.

By clicking on the links in the navbar, the "Smooth Scroll" effect will work regardless of whether or not you're viewing the sections in the same order they are listed in the dropdown navbar.
It allows to animate scrolling to anchor links.

This site was tested across multiple browsers (Chrome, Safari, Internet Explorer, FireFox) and on multiple mobile devices (iPhone 4, 5, 7: Chrome and Safari, iPad, Samsung Galaxy) to ensure compatibility and responsiveness. 

During the testing phase, I realized that background-attachment: fixed was not compatible with iOS browsers. 
On Chrome and Safari in iOS, the background photos appeared zoomed-in and blurry. 
To fix this, the background-attachment: scroll property value was added in a media query. ??????

Deployment
This site is hosted using GitHub pages, deployed directly from the master branch. 
The deployed site will update automatically upon new commits to the master branch. 
In order for the site to deploy correctly on GitHub pages, the landing page must be named index.html.

To run locally, you can clone this repository directly into the editor of your choice by pasting git clone https://github.com/navegantemx/MegaTrak-Milestone-Project.git into your terminal. 
To cut ties with this GitHub repository, type git remote rm origin into the terminal.

Credits
Web Site design by YouTube channel "Easy Tutorials

Content
All content on website site sections was written by me and Kay Turner CEO of MegaTronics Int. Corp.

Media
All photos and logos were taken from my company www.megatrak.com 

Acknowledgements

The smooth delay animate scrolling JavaScript function was found through this tutorial here??? https://github.com/cferdinandi/smooth-scroll

The "Navbar" feature was found in Bootstrap 4.1 here???? https://getbootstrap.com/docs/4.1/components/navbar

The "Carousel" feature was found in Bootstrap 4.1 here???? https://getbootstrap.com/docs/4.1/components/carousel

This is for educational use.
