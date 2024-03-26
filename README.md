# Awesome Aussies

Awesome Aussies is a websites that targets an audience that is thinking about adding a new family member, and are looking for some general knowledge about this particular breed – to be able to decide if this is the dog for them! It´s purpose is not to encourage to buy the dog, but to provide some help in making that decision and is supposed to function as a place of knowledge. It doens’t target the user who alreday own this type of dog but acts as a support for the newbies. Hopefully it will provide the understanding of whether this is the dog for them – or absolutely not the dog for them. 

![printscreen responsive web page](assets/images_readme/responsivness.jpg)

## Features

### Existing Features


__The page header__

+ Every page on the site includes a header with a image of an Australian Shepherd, to quickly give the user a feeling of what the site is all about. The header also includes the name/title of the webpage and a text overlay that sums up the content, so that the visitor can quickly deside if it’s worth to continue scrolling.
The chosen header-images also set the color-scheme for the rest of the page, to keep the layout consistent and harmonizing throughout the different features on the webpage.

![printscreen header](assets/images_readme/header.jpg)


__Navigation Bar__

+ The navigation bar is featured on all three pages of the website and includes links to all the different pages. It helps the user find its way to the Home page/landing page, the About Page and a Contact page for further questions. 

+ The navigation bar is responsive and allows the user to jump between pages without having to use the ”back”-button. Furthermore the navigation bar has a drop down function for mobile devices so that it doesn’t take up to much space on smaller devices. On larger devices such as tablets and laptops it is responsive and changes font size according to screen size. 

+ I decided to simply name the navigation bar ”menu” in the drop down version on smaller devices, basically because of the fact that everybody is familiar with the term and the purpose of a menu.

+ The background color for the navigation bar is picked from the header image so that they harmonize with each other. 

+ The current page that the user is viewing is underlined in the navigation bar to further simplify navigation on the site for the user.

![printscreen navigation bar](assets/images_readme/navigation_bar.jpg)

![printscreen drop down menu](assets/images_readme/navigation_menu_mobile_device.jpg)


__Content of the home/landing page__

+ Below the header and navigation menu the user will find some additional general information about the page and it’s content – with the purpose of making it even clearer to the user that this is the page they were looking for. They will see the benefits of continuing reading and what they will gain when looking at the other content of the page. Hopefully this part will also make it crystal clear to the visitor that the page is for the user thinking about getting the breed, not for the user that already owns the dog.

+ The content on the landing page is also to validate the people behind the page so that the user will get a sense of that the creator knows what he/she is talking about. 

+ Below the text on the landing page is another image of an Australian Shepherd - mainly to have a visual element that breaks up the text and hopefully produces a good feeling within the user. 

![printscreen content on home page](assets/images_readme/content_home_page.jpg)


__Links to kennels__ 

+ Below the text and image on the home page are some links to different kennels, if the user is interested in learning more about the buying process itself and have come a little further in their descision making. 

+ There is also an embedded link to the Contact page if the user is interested in tips on more kennels.

+ All the external links open up in a new tab so that the user still have easy access to the original webpage.

+ The links have the same color and font as other elements on the page and lives in a responsive flexbox to adjust from row to column depending on device.

![printscreen links to kennels](assets/images_readme/kennels_links.jpg)


For the entire home page the index.html file implements the content, with additional styling found in the style.css file deployed through the assets-folder. 


__The Footer__

+ The footer section includes links to different social media platforms - relevant to the content of the website. They open in a new tab to allow for easy navigation so that the user can easily finds it’s way back to the webpage without having to use the ”back” tab.

+ If the site were to be deployed "for real" and managed for a long period of time – the footer with it’s social media icons would lead the user to different forums and member pages on Facebook, Instagram and so on with the concept of ”Awesome Aussies” in mind – a place for the user to connect with like-minded and a place to ask other owners all questions concerning their dogs. But for now the social media links directs the user to the offical sites.

+ Again the same color as in the navigation menu and other features on the page is used. 

![printscreen footer](assets/images_readme/footer.jpg)


__About the breed Page__

+ This page is probably the most valuable page to the user, since it contains all the useful information about the breed. 

+ The content of the about-page comes from other pages on the web (see content credits further down), since the function and purpose rather than the actual content of the text is in focus for this assignment. 

+ Evry paragraph has a picture below it so that the user can rest their eyes before jumping on the next section of text. The images are responsive in size to adjust according to screen size. 

+ This page gets it's text and image content from the about.html file, with additional styling form style.css. All images are found in the image folder. 

![printscreen of content on the about page](assets/images_readme/contet_about_page.jpg)


__Contact Page__

+ Since the site only holds some general information, the Contact Page is a chance for the user to ask other more specific questions about the breed that they didn’t find an answer to on the webpage. They will be asked to provide their full name and e-mail adress so that the people behind the webpage will know whom and where to send the reply. 

+ It also features a larger input-area for the questions – which is made up of additional rows to provide the user with the possibility to write more content than single line provides them with. 

+ The Contact-form is responsive to all devices and the text changes size according to device to provide a better user experience. 

+ All input-text is required for the user to put in to verify that they are actual human beings. 

+ This page gets its content from the contact.html file, and its looks and features from style.css. 


### Features left to Implement

+ For this website to be of actual use to a user that is about to purschase a new dog, a page filled with links to different types of kennels would be a good idea so that the user can navigate further once the current webpage has filled it’s purpose. But that would require a lot of research and collecting data from a lot of external sources. 

+ Another useful feature would have been to added more pages that separates the about the breed content in the navigation bar itself - for example if you're only interested in how you train this particular breed you could find your way to that content right away without having to scroll through other sections of text. 


## Testing

The page hase been tested on 

All the internal links work as they should, from all pages. The external links works as well and open in a new browser window as indented. 

The contact form 

## Validator testing

+ HTML

![printscreen html validating](assets/images_readme/w3c_validator.jpg)

+ CSS

![printscreen css validating](assets/images_readme/css-validator.jpg)

+ Accessibility using Lighthouse



## Unfixed bugs

From what I know there are no unfixed bugs, but the flex-box features were the biggest challenge for the project. Also finding the right margins and size of the content for different devices to make the user experience comfortable proved to be the biggest challenge in this particular project – mainly because the feature consists of only texts and images. Some more interactive features with videos and maybe a quiz-section would have added some more value to the user, but the main focus of the page is to show that the basic structure and features of HTML and CSS have been implemented.

## Deployment

The link to the live project-site can be found here: https://sofiawallq.github.io/awesome_aussies/

## Credits

### Content
+ The text for the different sections on the About the breed page were taken form Wikipedia (länk) and [The farmers dog](https://www.thefarmersdog.com/digest/australian-shepherd-care-guide/) since the project is about the form and function, and not so much about the actual content of the paragraphs. 
+ The drop down menu for mobile devices was created with some code from the Love Running code along-project, altered to fit this pages layout. 
+ The Favicon was created with the help of [favicon.io](https://favicon.io/logo-generator/)
+ All the social media icons in the footer were taken from [Font Awesome](https://fontawesome.com/)
+ To pick the color scheme for the page I used [Image Color Picker](https://imagecolorpicker.com/en) on the header image. 
+ The [Stack Overflow](https://stackoverflow.com/) forums has been my go-to whenever it got stuck with mainly CSS and needed to find my way out. 

### Media
+ All the pictures used in the project – the header image, the image used in the content on the landing page and the images in the About the breed-section were all taken from the Open Source page [Pexels](https://www.pexels.com/sv-se/). 
+ All of the images were run through [Tinypng](https://tinypng.com/) to make them “lighter” and adapted for display on the web – so that the page doesn’t take to long to load because of heavy image files. 
+ Some of the images used were cropped with the help of Photoshop Express. 
