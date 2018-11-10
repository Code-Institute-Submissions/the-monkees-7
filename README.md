# The Monkees Band Website

This website will provide a user friendly and responsive platform for the band to showcase to their fans their latest music and 
videos.

In addition, the website has the functionality to allow potential customers to book the band for an event, using
the booking form, where they can also look through other customers' recent reviews.

## User Experience

This website has been designed with the mobile user in mind, providing clearly layed out pages, which allows the user
to navigate easily to each page, depending on their interest and / or reason their for visiting the website.

The list of user stories below details each aspect of the user experiences of the website:

- As a new listener to The Monkees music, I wanted to continue the experience as easily as possible, which I was able to through the Home page with its great range of tracks.
- As a fan of The Monkees I wanted to view pictures and videos of them, I found pages with both of these on the website.
- If I or anyone wanted to book The Monkees for an event, one could log on and to listen to some of their tracks and read the reviews before completing the booking form.

The main source used to design the website was by completing manually drawn diagrams which are 
included in this project [project1_wireframes.pdf](https://github.com/eldowling/the-monkees-project1/blob/master/assets/documents/project1_wireframes.pdf)

## Features

The website consists of six pages which were designed to divide each feature into clearly defined sections. 
This is important not only for clarity, but also for mobile users who may only wish to view one of the features available.

1. The Home page is designed to provide an introduction to the band and showcase some of their latest music singles.

2. Following from this the Band Information and Pictures page provides more detailed information about the band and biographies for each of its members. 
A picture gallery of the band was included as part of this section.

3. The Albums page was created with a CSS Grid layout for easily formatted and responsive display of albums and their track listings. This page format can be easily added to with the release of new albums.

4. The Videos page provides a simple and uncomplicated section for users to enjoy music videos / performances and interviews from early releases right through to more current performances.

5. The Event Bookings page allows potential customers to submit a booking enquiry, which prompts them to input detailed information related to the required booking.
It makes use of radio options to allow them to select an event type, and a list to provide options of locations for the event / proformance, as well as a date picker to allow simple selection of the required event date.

6. On the Event Bookings page the user can also read reviews from previous customers, where a star rating is also displayed for 3 headings: "Live Performance", "Audience Interaction", "Value"

7. The Merchandise page allows fans to browse through various items to buy, such as Albums, Singles, Clothing and Accessories. 
    The website displays the items through the use of a reusable grid, that additional items can easily be added to. 
    It is planned to have a link on each item image which would add the item to the user's basket, this has not yet been implemented.
 
### Existing Features
- Latest Music - this section allows the user to scroll through a selected list of singles on the Home page and play any of these through the use of an audio bar.
- Band Pictures Border Image - A border image was used to customise and define each picture in the album.
- Albums CSS Grid Layout - Each new album can be easily added to the Albums page through the use of a simple CSS Grid layout. Grid areas are formatted to suit the layout of device used to view the page.
- Videos CSS Grid - This page also makes use of the CSS Grid Layout, and allows for more videos to be added using the simple structure.
- 'Other' Event Type Modal Box - The form on the Event Bookings page provides a text input box to enter another event type. If the 'Other' radio option is selected by the user, then a modal box will display a message prompting the user to complete the text box.
- Star Ratings - The reviews section on the Event Bookings page provides a simple and eye-catching layout for potential customers looking to get feedback from others who have already booked or attended a previous event.
- Merchandise CSS Grid - A simple grid modal was used to display the collection of merchandise available to buy. This allows for easy inclusion of additional items.


### Features Left to Implement
- Merchandise - This page can updated to include a wider range of products, some more categories can also be added conveniently through the reuse of predefined sub-headings and shopping grid layout. It can be further enhanced by adding a link to allow the user to add the item to their basket by simply clicking on the item image.

## Technologies Used

The following frameworks and technologies were used in order to create the style and functionality required for this website. A brief description of how they have been implemented in the project is detailed below:

- [HTML5](https://en.wikipedia.org/wiki/HTML5)
    - **HTML5** is the markup language used to structure and present the content of the website. It provided the features to allow for the use of audio and video clips throughout the website.
- [CSS3](https://en.wikipedia.org/wiki/Cascading_Style_Sheets)
    - A **CSS Stylesheet** was used in the project to define the style of the page, such as colours, fonts and layout. It also contains additional settings used by the other elements of the page such as Grids and Flexboxes.
- [Bootstrap](https://getbootstrap.com/docs/3.3/)
    - The project uses **Bootstrap** to provide a responsive grid through the use of predefined column structures. It is also used for a panel layout on the Home page.
- [FontAwesome](https://fontawesome.com/)
    - **Font Awesome** was used to allow for easily customisable icons and highlight particular areas such as the menu bar and some headings.
- [JavaScript](https://www.javascript.com)
    - **JavaScript** was used to create the modal functionality on the Event Bookings page.


## Testing

Extensive testing was completed throughout the development of each page. While working on each page it was initially designed for mobile
layout first. Once this was completed, a media query for other layouts was then added and any modification for the device type needed was included.

Testing was carried out using the Chrome browser initially, and changing between the various screen size options. A Samsung Galaxy S7 also used to check the mobile layout on each design update.
Following from this some additional testing was completed in both Firefox and Internet Explorer browsers.

Specific testing was carried out in the following areas:

1.  Audio Bars:
    1.  Open the "Home" page and view the "Latest Music" sidebar
    2.  Location of audio bar was originally set as relative
    3.  This was subsequently changed after the CSS Grid was implemented for this section and it provide an improved structure inwhich the audio bar could be more easily placed.
2.  Booking Form:
    1.  Open the "Event Bookings" page
    2.  Try to submit the form without the "Name" input box completed, an error message should be displayed requesting that the field is completed.
    3.  Try to submit the form without the "Phone No." input box completed, an error message should be displayed requesting that the field is completed.
    4.  Try to submit the form without the "Email Address" input box completed, an error message should be displayed requesting that the field is completed, and also that it is in the correct email address format.
    5.  Select the Event Type radio option for 'Other', ensure that a Modal box is displayed which will prompt the user to enter text in the text box below which states that they should state the event type required if not listed.
3. Embedded Videos:
    1. Open the "Videos" page
    2. Try to play the embedded video file at the top of the grid.
    3. Try to play each of the embedded YouTube videos further down on the page.


## Deployment
The completed website is deployed on the web-based hosting and version control service 'GitHub'.

Throughout the project on completion of each section, the project was commited to the GitHub repository, this was in order to maintain correct version control.

There are no differences between the deployed and development versions, the project did however start off with a different layout / design concept,
but this was quickly changed as it was unsuitable to the layout requirments.

## Credits

### Content

- Biography  
    - [Biography.com article on The Monkees](https://www.biography.com/people/groups/the-monkees)
    - [Wikipedia article on The Monkees](https://en.wikipedia.org/wiki/The_Monkees)
    - Wikipedia articles on band members [Davy Jones](https://en.wikipedia.org/wiki/Davy_Jones_(musician)), [Mickey Dolenz](https://en.wikipedia.org/wiki/Micky_Dolenz), [Michael Nesmith](https://en.wikipedia.org/wiki/Michael_Nesmith) and [Peter Tork](https://en.wikipedia.org/wiki/Peter_Tork)
    - Billboard.com article [The Monkees' 10 Biggest Hot 100 Hits](https://www.billboard.com/articles/news/502980/the-monkees-10-biggest-hot-100-hits)
- List of Songs
    - Wikipedia article [List of songs recorded by the Monkees](https://en.wikipedia.org/wiki/List_of_songs_recorded_by_the_Monkees)
- List of Albums and Album Information
    - Wikipedia article [The Monkees discography](https://en.wikipedia.org/wiki/The_Monkees_discography)
    - Wikipedia article [The Monkees (album)](https://en.wikipedia.org/wiki/The_Monkees_(album))
    - Wikipedia article [More of the Monkees](https://en.wikipedia.org/wiki/More_of_the_Monkees)
- CSS Flexbox
    - [A Complete Guide to Flexbox](https://css-tricks.com/snippets/css/a-guide-to-flexbox/) by Chris Coyuier
    - W3 Schools article and examples on [CSS Flexbox](https://www.w3schools.com/css/css3_flexbox.asp)
    - [Flexbox Form Examples](https://www.quackit.com/css/flexbox/examples/flexbox_form_examples.cfm) on Quackit.com
- CSS Grid
    - W3 Schools article and examples on [CSS Grid](https://www.w3schools.com/css/css_grid_item.asp)
    - [A Complete Guide to Grid](https://css-tricks.com/snippets/css/complete-guide-grid/) by Chris House
- Border Image
    - YouTube Video Tutorial [CSS3 border-image Property Custom Graphics Slice Tutorial](https://www.youtube.com/watch?v=lpf-5mG9CGg) by Adam Khoury
- Modal Box
    - W3 Schools article and examples on [CSS Modals](https://www.w3schools.com/howto/howto_css_modals.asp)  
- Embedded Videos & Embedded YouTube Videos
    - W3 Schools [HTML5 Video](https://www.w3schools.com/html/html5_video.asp)
    - W3 Schools [HTML YouTube Videos](https://www.w3schools.com/html/html_youtube.asp)
    - W3 Schools [Responsive Web Design - Videos](https://www.w3schools.com/css/css_rwd_videos.asp)


### Media
The photos and singles / albums covers were obtained from the following sources:
- [Daydream Believer Cover](https://www.discogs.com/The-Monkees-Daydream-Believer/release/3267520)
- [Picture Frame Border](https://clipart.info/images/minicovers/1520539443black-border-png-transparent-background.png)
- [Band Playing Image](https://img.rasset.ie/000bc3a2-800.jpg)
- [More of the Monkees Album Cover](https://en.wikipedia.org/wiki/More_of_the_Monkees)
- [Last Train to Clarksville Single Cover](https://streamd.hitparade.ch/cdimages/the_monkees-last_train_to_clarksville_s_3.jpg)
- [The Monkees Album Cover](https://en.wikipedia.org/wiki/The_Monkees_(album))
- [The Monkees Band Picture 2](https://images-na.ssl-images-amazon.com/images/I/C1YdDyfno6S._SL1000_.png)
- [The Monkees Band Picture 3](https://flashbak.com/wp-content/uploads/2017/09/The-Monkees-Pop-Group-1967.jpg)
- [The Monkees Band Picture 4](https://www.telegraph.co.uk/content/dam/music/2016/05/25/99058693-The-Monkees-CULTURE_trans_NvBQzQNjv4Bqeo_i_u9APj8RuoebjoAHt0k9u7HhRJvuo-ZLenGRumA.jpg?imwidth=450)
- [The Monkees Band Recent Picture](https://www.culturesonar.com/wp-content/uploads/2016/06/The-Monkees-600x400.jpg)
- [Band T-Shirt](https://thumbs3.ebaystatic.com/d/l225/m/mReg5O-2J_7mKwZYO_RL05A.jpg)
- [Long sleeved T-Shirt](https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcSbiHWMnUWT383Mn6Gs7wf_WMJNNdExP92-aqaQi_CW70xYCJHpzw)
- [Blue Hat](https://thumbs.worthpoint.com/zoom/images1/1/0518/13/monkees-original-mike-nesmith-knit_1_568d05d6c2326bd4690e1f84ac446b4e.jpg)
- [Red Band Button](https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcRYKYV1YjA3CaOGoxnFU2abx8v_YPVbaKFNGHHgMSmKYtqSR-mxrQ)
- [Tamborine](https://www.rhino.com/sites/rhino.com/files/styles/square/public/monkees-tamborine.jpg?itok=q_2LFgfQ)
- [Red Logo Keyring](https://img.secure.cdn2.wmgecom.com/media/catalog/product/cache/1124/image/800x/9df78eab33525d08d6e5fb8d27136e95/k/e/keychain2_1.jpg)

### Acknowledgements

-   I would like to thank my Mentor Rick Gallegos, and also my family for their input, advice and support throughout the project.
