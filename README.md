# The Monkees Band Website

This website was provides a *well layed out* and responsive platform for the band to showcase their latest music and videos to their fans.

In addition, the website has the functionality to allow potential customers to book the band for an event, using
the booking form, where they can also look through other customers' recent reviews.

## User Experience

This website has been designed with the mobile user in mind, providing clearly layed out pages, which allows the user
to navigate easily to each page, depending on their intrest or reason for visiting the website.



## Features

The website consists of six pages which were designed to divide the each feature into clearly defined sections. 
This is import not only for clarity, but also for mobile users who may only wish to view one of the features available.

The Home page is to provide an introduction to the band and showcase some of their latest music singles.

Following from this the Band Info and Pics page provides more detailed information about the band and biographies for each of its members. 
A picture gallery of the band was included as part of this section.

The Albums page was created with a CSS Grid layout for easily formatted and responsive display of albums and their track listings. This page format can be easily added to with the release of new albums.

The Videos page provides a simple (uncomplicated) area for users to enjoy music videos / performances and interviews from early releases right through to more current performances.

The Event Bookings page allows potential customers to submit a booking enquiry, which prompts them to input detailed information related to the required booking.
It makes use of radio options to allow them to select an event type, a list to provide options of locations for the event / proformance, as well as a date picker to allow simple selection of the required event date.

On the Event Bookings page the user can also read reviews from previous customers, where a star rating is also displayed for 3 headings: "Live Performance", "Audience Interaction", "Value"

There is an option to include a page to display Merchandise available for fans to buy, this has not yet been implemented.
 
### Existing Features
- Latest Music - allows the user to scroll through a selected list of singles on the Home page and play any of these through the use of an audio bar.
- Band Pictures Border Image - A border image was used to customise and define each picture in the album.
- Albums CSS Grid Layout - Each new album can be easily added to the Albums page through the use of a simple CSS Grid layout. Grid areas are formatted to suit the layout of device used to view the page.
- Videos CSS Grid - This page also makes use of the CSS Grid Layout, and allows for more videos to be added using the simple structure.
- 'Other' Event Type Modal Box - The form on the Event Bookings page provides a text input box to enter another event type. If the 'Other' radio option is selected by the user, then a modal box will display a message prompting the user to complete the text box.
- Star Ratings - The reviews section on the Event Bookings page provides a simple and eye-catching layout for potential customers looking to get feedback from others who have already booked or attended a previous event.


### Features Left to Implement
- Merchandise - This page can easily be implemented using the Flexbox areas set up in the style sheet and creation of another CSS Grid and Grid Areas to provide a responsive design. 

## Technologies Used

In this section, you should mention all of the languages, frameworks, libraries, and 
any other tools that you have used to construct this project. For each, provide its name, a link to its official site and a short sentence of why it was used.

- [Bootstrap](https://getbootstrap.com/docs/3.3/)
    - The project uses **Bootstrap** to provide a responsive grid through the use of predefined column structures. It is also used for a panel layout on the Home page.
- [FontAwesome](https://fontawesome.com/)
    - **Font Awesome** was used to allow for easily customisable icons and highlight particular areas such as the menu bar and some headings.
-[JavaScript](https://www.javascript.com)
    -**JavaScript** was used to create the modal functionality on the Event Bookings page.


## Testing

Extensive testing was completed throughout the development of each page, while working on each page it was initially designed for mobile
layout first. Once this was completed, a media query for other layouts was then added and any modification for the device type needed was included.

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


## Credits

### Content


### Media


### Acknowledgements


