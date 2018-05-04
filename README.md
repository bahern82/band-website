# The Monkees- offical band website

## Websites Target Audience 

The target audience of this website is fans and potential fans of a rock n roll group called "The Monkees".

## The Purpose of this Website

The purpose of this website is to showcase the bands music and publicise their availability to perform at events such as weddings and Christmas parties.
This website is responsive and a mobile-first appraoch has been used.
This is a solely a **front end project**.

## Technologies used

This website has been created using HTML,CSS and Bootstrap. Fontawesome icons and Google Fonts have also been used.

## Functionality/Design

### Layout

The layout contains 3 container divs - 2 of which are fluid, the third is a central fixed sized container which contains the main page content. The two fluid sidebar containers are hidden on all media sizes except extra large(1200pxs or more). When visible they display a red background and a Monkees logo at roughly half page intervals.
The mobile layout is a single column. On medium sized devices(min-width: 768px) the layout varies. On the Index page the first row has three columns, the second and third rows have two columns and the fourth row has a single column. The variation on the index page keeps the viewer visually interested.

The Media, About and Contact-Us pages use a two thirds, one third approach to rows.This consistency is used to display information of the same type e.g. album information, track information, band member information in a uniform manner.

Flexbox has been used to align items horizontally and vertically where required on all pages.

### The Header
Fontawesome icons were used to display visually appealing social media links
A Bootstrap navbar was used for the navigation menu. It's appearance was changed to make the page less generic. When hovered over a transition is used to change the links color to black in a visually appealing fashion.
When the page loads the Monkeys Logo fades in over the main band picture, an animation targeting opacity was used to generate this effect.
A Bootstrap alert and pill were used to highlight the bands availability for parties

### Index page

The page sections are clearly identified through the use of background colors and images. In the "Preview Latest album" section a text shadow effect was used to make the text more visible over the background image.The brightness of the image was reduced using image editing software.
Audio controls allow the viewer to listen to some audio tracks from the bands latest album.

### Media page

The page sections are clearly identified through the use of a background image in the middle section of the page.
In the "New album - The Very Best Of The Monkeys" section to make the text more visible the font weight was adjusted and a text shadow outline effect was used.
Audio controls allow the viewer to listen to some audio tracks from the bands latest album. A mobile friendly sized video is provided, the user can make the video full screen if desired.

### Gigs page
An exciting live concert background is used to wet the viewers appetite to attend a live concert. BootStrap was used to create the table, a striped style was applied and the hover row color was manually changed to a light yellow to make it more distinctive.

### Band History

The image corners were rounded to look more warm and less blunt.A 60s color scheme background was added to the band members section to emphasise the bands origins and playfulness.

### Contact Us 

A form has been provided to allow viewers to contact the band in regards to booking parties and concerts.
The form uses labels to aid visually impaired users. All form elements have been igven the required attribute which means the form can not be submitted in an incomplete state. 

## Testing

An Agile approach has been taken to developing this web application. Each sprint has been geared towards developing and testing a new part of functionality or design.
Whenever a new feature was added it was tested comprehensively in Google Chrome development tools. It was tested in terms of appearance and functionality on mobiles,tablets and laptop devices. As an extra precaution all links,functionality and layouts have been checked post development in Google Chrome.
No issues in Google Chrome browser.

All webpages have been validated using https://validator.w3.org


### Cross browser compatibility testing

Browser prefixes were used for translations and animations to aid cross browser compatibility.

#### Firefox
Web developer reponsive design mode was used for testing on the Firefox browser.All the standard devices were tested in portrait and landscape mode using the viewport rotate feature.

The following issues were detected:


| Device             | Issue                                                         | Level of issue | Action            |
| :----------------: |:-------------------------------------------------------------:| :--------------------------:|
| Apple Ipad Air     | In portrait mode - navbar hover  transition works sparingly   | Non-critical ignore         |    
| Apple Ipad Mini 2  | In portrait mode - navbar hover  transition works sparingly   | Non-critical ignore         |

The above issues may be due to emulation, they do not affect use and are not a major blight visually.
Decision ignore.

#### Microsoft Edge , Internet Explorer 10,11

Edge's developer tool's emulation feature was used for testing.

The following issues were detected:

| Device             | Issue                                                         | Level of issue | Action            |
| :----------------: |:-------------------------------------------------------------:| :--------------------------:|
| Various            | In resolutions - 800x480 and 1024x788 - navbar hover transition doesn't work    | Non-critical ignore         |

The above issues may be due to emulation, they do not affect use and do not affect visuals.Hover effect is missing but website still looks good.
These resolutions are not the default resolutions for the tested devices and it is unlikely they will be used.
Decision ignore.

#### Opera

Opera uses the same Blink layout engine as Google Chrome, nevertheless I have tested the website using Opera's Dragonfly Developer tools.
Testing was carried out using all the device presets available. No issues were detected.

#### Safari

The website was not tested in Safari due to the lack of access to an Apple device.

