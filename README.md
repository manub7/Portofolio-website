# Emanuel Blaga  Portfolio

Stream One Project: User-Centric Frontend Development - Code Institute

This is my portfolio website to present to prospective employers. The portfolio highlights two projects that cover a range of technologies, as well as including a bit about myself, my coding skills, and a contact form.

## Wireframe 
Balsamiq was used to create the wireframes for this website. You can view it [here](/assets/images/Portofolio-wireframe.pdf) 


## Desktop Demo

UX
My goal in the design was to make it as easy as possible to access information on the site while striving for a minimalist design. The greyscale color scheme was chosen to create a sleek and modern feel.

For employers, I wanted to provide them with a brief overview of myself and my capabilities via a user friendly design. This way, they would be able to get a glimpse of who I am, my background, work I've done, and my skills, with the option to contact me if they choose. In the 'Work' section, I wanted them to be able to quickly access work that I've done, providing a short summary of the project and main technologies with a link to each GitHub Repository and live demo. A link to my LinkedIn profile, my GitHub, and a downloadable PDF version of my CV were also provided for their ease of access.

## Technologies
HTML
CSS
Bootstrap (3.3.7)
Features
This site uses the scrollSpy feature in Bootstrap with an extra JavaScript function added to create a 'smooth scrolling' effect. The navbar also stays collapsed regardless of the screen size to promote a minimalist design.

## Features Left to Implement
In the future, I would like to add further projects that I've worked on to create a more comprehensive 'work' section. I would like to also add more animations. 

## Testing
The employer and recruiter user story achieved the intended outcome of providing them with a showcase of myself and my work. In the about me section, they can read a bit about my background, and if they're viewing on a desktop, the background of this section is a photo to fill up the space . They are able to see my showcased projects via the project cards in the "Work" section. They can view both the live version and the GitHub repository by clicking on the Font Awesome icons. They are also able to view my social media profiles via clicking on the icons in the footer. They are also able to download my CV by either clicking on CV in the navbar dropdown, or by clicking on the document icon in the footer.

If you try to submit the contact form with an invalid email address, there will be an error noting the invalid email address. Furthermore, the 'required' attribute is added to the 'name,' 'email,' and 'message' fields, so if those fields are not filled in, the form will not submit. If all field are valid, the page will reload. If an employer or recruiter is interested in contacting me, they will have to fill out all fields in order for the form to go through.

All links will open in a new tab using 'target="_blank"' and the CV will download to your default folder for downloads on click using the 'download' attribute. All links have been manually tested to ensure that they are pointing to the correct destination.

By clicking on the links in the navbar, the scrollSpy effect will work regardless of whether or not you're viewing the sections in the same order they are listed in the dropdown navbar.

This site was tested across multiple browsers (Chrome, Safari, Internet Explorer) and on  mobile devices (iPhone 11Max) to ensure compatibility and responsiveness. During the testing phase, I realized that background-attachment: fixed was not compatible with iOS browsers. On Chrome and Safari in iOS, the background photos appeared zoomed-in and blurry. To fix this, the background-attachment: scroll property value was added in a media query. I also realised that filters for the background image was not working with Edge and IE and therfore I opted to have the photo transformed black and white with a photo editor. 

Issues unresolved relate to IE browser for grey filters that do not work also on IE browser the background images are shaking upon scrolling (still looking for a fix) and still in IE and Edge the Wanderlust webiste project does not display correctly. 


## Deployment
This site is hosted using GitHub pages, deployed directly from the master branch. The deployed site will update automatically upon new commits to the master branch. In order for the site to deploy correctly on GitHub pages, the landing page must be named index.html.

To run locally, you can clone this repository directly into the editor of your choice by pasting git clone https://manub7.github.io/Portofolio-website/ into your terminal. To cut ties with this GitHub repository, type git remote rm origin into the terminal.

## Credits
Content
All content in the "About Me and "Work" sections in this portfolio site were written by me.

### Media
All photos were taken from Pexels, a stock image library. A greyscale filter was applied to each one prior to upwitload to preserve the greyscale theme.

### Acknowledgements
The scrollSpy delay JavaScript function was found through this tutorial [here](https://www.abeautifulsite.net/smoothly-scroll-to-an-element-without-a-jquery-plugin-2)

All skill overaly filters displaying on hover were well modified to fit my purose and  was found [here](https://stackoverflow.com/questions/14263594/how-to-show-text-on-image-when-hovering)

Colapsable hamburger menu with animation was found [here](https://mdbootstrap.com/docs/jquery/navigation/hamburger-menu/)

Website layout and design inspiration was found here: https://www.haleyschafer.com/







