"# pirate-resort" 
#
# Pirate-resort
#



##*Table of content*
[User expectation](#user-expectation)

##**1. Project Goal**

###**User goals**
- Finding a place distant from all civilization and pollution (calm and filled with tranquillity)
- Trying out the food not by any standards or specific recipes
- Taste something different
- Different environment
- Different theme
- More casual, but still high-quality service

###**Site owner goal**
- Provide a unique experience
- Attract specific types of people (passengers on a long voyage, adventures and people who appreciate finer things)
- Attract people who want to experience peace, calm, good food and rest from a long voyage
- Promote business but in a way that remains high quality and less grow
- Provide basic but unique food choices found nowhere else
- Provide basic information on how the restaurant came to be and why it was established
- Share some pictures for a user to get a glimpse of the experience that awaits the user


###**User Exp**
####**Targeted group**
- People who are travellers on a specific route
- People who appreciate good, unique food, atmosphere and environment
- Adventures 
- People who like peace and calm, sun and waves, palm beaches and do not mind the sand
- Anyone who wants to escape busy street (or law)
- People who like less formal, more casual and relaxed atmospheres, while still receiving perfect service

###**User expectation**
- Simple directions (it is the only island 100 miles away)
- Limited food choices but with excellent quality and unique ingredients
- Warm and nice weather, palm trees, chill atmosphere, relaxed mood, delicious food
- Affordable prices
- Trying something that cannot be found normally

##**User Stories**

###**1st time users**
- I want to know the location
- I want to know the availability of the food menu
- I want to know the prices
- I want discounts
- I want to taste food that is nowhere to be found 
- I want to have breakfast, lunch or dinner in a place that barely has any civilization

###**Returning users**
- I want to continue getting discounts
- I want to try other dishes
- I want to experience what I had 1st time around
- I want contact details so I can reserve a spot

###**Owner of the restaurant**
- I want more subscribers so I can share updates regularly and increase potential clients as a targeted group is smaller than usual
- I want clients to have our contact to have them visit again
- I want potential customers to have all info in an effortless and straightforward way
- I want the user to find their way around easily and quickly
- I want to show a few pictures for potential customers so they can get an idea of what they can expect
- I want them to have access to our menu so they know the selection and understand what kind of food can be offered 



##**2. Design of the webpage**
####**Design decisions**
Given that the restaurant is in the middle of the Atlantic Ocean on a small island covered with palm trees, the idea was to include lots of teal, blue, aquamarine, and green. Some red and gold were used so that we have contrast and increased visibility for the vision-impaired customers.

The idea is to create a tropical/ocean vibe, with bright colours to match the style of the restaurant itself (relaxed, semi-vacation, a bit adventurous, unique, casual)

##Color
*Full list - most frequently used colours*
rgb(127, 255, 212)
rgb(30, 124, 183)
rgb(182, 243, 13)

*Fonts:*
rgb(255, 6, 6) - for title
rgb(240, 255, 240) - for text over images to increase visibility
rgb(182, 243, 13) - for some 
rgb(255, 215, 0) - for headers to improve contrast

*Shadows:*
rgb(0, 0, 0) - when we wanted full dark shadows
rgb(14, 53, 4) - when we used slightly dark shadow but not full dark
rgb(165, 227, 6) - for footer to contrast background better

*Order:*
rgb(255, 165, 0)

*Link:*
rgb(255, 192, 203) - this needed to be used to be similar for text over the picture, but not the same to distinguish between regular text and link

*Background (mostly added in case pictures do not load so there is a contrast with the context that is displayed over it):*
rgb(17, 129, 129)
rgb(0, 255, 255)
rgb(255, 192, 203)
rgb(41, 49, 41)
rgb(0, 128, 128)

##**Fonts:**
An attempt was to create more "Adventure/Pirate/Caribbean/Ocean atmosphere from the late 18th century, so specific fonts were used like "Rouge Script", "Tangerine", "Dancing Floor", and "Lavishly Yours". I still decided to add more "common" fonts like "lato", "Oswald" as a fallback font to distinguish from whatever browser might use

Due to the "way too stylish" appearance of fonts like "Lavishly Yours" and "Tangerine", they had to be removed from Menu Items (menu tabs) as visibility was not the best even when put as bold and with very distinguished colours used as background and font.

"Dancing Script" and "Sour Gummy" were doing the job properly as suitable replacements where the style was kept with better visibility and readability.

"Lavishly Yours" was used for the title due to the large font size and the standalone names of each tab so readability was not compromised.



##Structure
To match the casual style, the decision to go with a straightforward and simple approach. 
I decided to go with 5 (five) separate pages divided into
![Small devices](https://github.com/user-attachments/assets/154e9b46-1fcd-432e-9274-fbdeb9f1cdb5)
![large device](https://github.com/user-attachments/assets/ef0c6da9-fc33-4ee2-bb7d-eb95c7e9bab2)



1. Landing page that is also basic "about" & "intro" page
2. Food menu (second from the top left position)
3. Contact (third after the food menu, as it is most important after checking the availability of items on the menu)
4. Loyalty and Reward centre (as I believe this would be the next step in attracting the customers - discounts/vouchers)
5. Gallery where user can see pictures of the location and food prepared

Order is placed in a way that each item will *always* be positioned at its place (Main page on 1st, Food on 2nd, Contact on 3rd, Loyalty on 4th and  Gallery on 5th place)

Each section has a separate webpage, but the user can always return to the main page or any other 5 pages available from the top (all 5 pages have a consistent look/appearance).

2 additional webpages for "Coupons" and "Subscription" have the same UI as other pages but they are accessed only from the "Reward Centre" (Loyalty) page. From these 2 pages, the user can navigate to any of the 5 pages.

![Order 1 nav bar](https://github.com/user-attachments/assets/4aa2c581-4a57-45b4-875d-b4d5c53e6ab2)
![Order 2 nav bar](https://github.com/user-attachments/assets/f2dd8622-d55a-44a2-9a0d-c24023486615)
![Order 3 nav bar](https://github.com/user-attachments/assets/cb030125-dbf5-4b90-b24e-949a87087501)
![Order 4 nav bar](https://github.com/user-attachments/assets/de655eef-0fe4-4bc2-838a-89eeaf499875)
![Order 5 nav bar](https://github.com/user-attachments/assets/688540c6-9713-4375-b1e3-7c44f4918ddf)



Making it complex with lots of dropdown menus (despite consuming less space) seems like a setback and an additional click was needed for the user.

The decision was made to go with tab views on smaller devices (same as on the larger ones)
To avoid truncations decision was made to replace full title names (using characters) with symbols and emojis on smaller devices. Emojis are fully related to the topic of the tab. Piece of paper and dish for Food Menu. Anchor and Pirate flag symbol for the Main Page of Pirate Resort. Royal crown and gift wrapped for royalty reward centre. Film and Camera icons for the Gallery page. 

On larger devices, I set that the full name is displayed (icons are removed as they would be redundant in this case)  

Small devices nav bar
![Nav bar - small](https://github.com/user-attachments/assets/066505e6-3541-4b7e-9ffe-90ae530c6c9d)

Large devices nav bar
![Nav bar - big](https://github.com/user-attachments/assets/4ab8951f-e764-4ced-8049-cf3e002b2dce)


# Tab names
![Tab names](https://github.com/user-attachments/assets/c8b365a6-d764-40bb-94b8-1e67ac1acb79)
All tabs have names and symbols


#Home page / Main Page and header
1. Landing page
![Landing page menu](https://github.com/user-attachments/assets/01f82f9e-537b-4073-828b-303705231470)

2. Food menu 
![Food_Menu](https://github.com/user-attachments/assets/385a1ba0-020b-4d95-9a71-1d93f4a21021)

3. Contact 
![Contact menu](https://github.com/user-attachments/assets/af3cddff-4711-42bc-a3d0-160362d85301)

4. Loyalty and Reward centre
![Loyalty page](https://github.com/user-attachments/assets/1baf2652-0ec3-4e3c-814c-0f4b571cda9e)

5. Gallery
![Gallery Menu](https://github.com/user-attachments/assets/7153e1fb-af3c-4754-83f1-4c6b359fe94f)

6. About us 
![About menu](https://github.com/user-attachments/assets/fb6ca2de-79b7-4317-8efb-29102c72ea72)


# Footer
![Footer](https://github.com/user-attachments/assets/e91709ae-b2ec-43d5-a216-c24818e5fce4)


Shadows were added for stylistic reasons
More than the usual number of icons placed to make sure it will wrap nicely
![Footer](https://github.com/user-attachments/assets/3e4e8b08-02b0-4ad2-a291-30f5063f8c4e)


# Background images
For the nav bar, I did something similar where I wanted to represent more sky
![header_background_image](https://github.com/user-attachments/assets/f8511518-8410-410c-915f-ca455d9be1b7)

For the Gallery page, I set both colour and background image in case images do not load, background colour can give contrast to the context making it stand out.
![water_background_for_gallery](https://github.com/user-attachments/assets/f6958bcd-c712-4f22-8a5d-692f44e3516d)

The footer was something related to water (so opposite of the nav bar and sky)
![wave-footer-background](https://github.com/user-attachments/assets/f7aca0f0-b079-406f-9ae0-01f567c09768)


#Technology and tools used
##Languages
- HTML
- CSS

##Tools
- Git
- GitHub
- Gitpod
- TextEdit
- BBEdit
- Word
- Paint
- Google Fonts
- Font Awesome
- Favicon
- Diff Checker
- Google Fonts Pairing
- Grammarly
- Pen and paper (as some things need to be placed quickly before ideas go away)


## Additional help
- Training materials
- YouTube
- *I intentionally didn't want to reach out to tutors as I wanted to make this work on my own, using knowledge and materials I have*


# Feature
## Navigation bar

Contains 5 (five) pages, while the selected page goes "on top" and "landing page" takes up the position of "landing page" so that the order remains the same all the time 
0. Landing page
*Starting page* gives a basic intro and serves as a hub for all other pages. Focus is more on visual effects than on text to attract potential customers using graphics.
The text is short and divided into small sections to give the user a pause and time to sink into a sense of relaxation, calm and beauty
![Landing page menu](https://github.com/user-attachments/assets/01f82f9e-537b-4073-828b-303705231470)

1. Food menu
*First page* user will pay attention to the page after the initial opening of the website. It is a place where only food choices are displayed and nothing else to distract user from it. Names are unique, short and without description about ingredients, preparation, alergens or similar. Clear and simple but enough to spark the imagination. 
![Food_Menu](https://github.com/user-attachments/assets/385a1ba0-020b-4d95-9a71-1d93f4a21021)

3. Contact
*2nd page in line* is the one user will most likely check next after checking the food menu. Location, how to get there, where can user find us, how to contact us. Simple UI, with little but all-important information without any other elements that are not directly related to how to reach out to us
![Contact menu](https://github.com/user-attachments/assets/af3cddff-4711-42bc-a3d0-160362d85301)

5. Loyalty and Reward centre
*middle page* and also the 3rd form the left and 3rd that user will most likely select contains basic things to get sign up, fill the questioner and even request discount vauchers. Again, it is simple and easy to use, with not too much or too little interaction.
![Loyalty page](https://github.com/user-attachments/assets/1baf2652-0ec3-4e3c-814c-0f4b571cda9e)

7. Gallery
*2nd before last* contains only pictures of our place and the food we prepare. No text, nothing to distract visitor at all. Small gaps left between pictures for stylistic purposes. A picture tells 1000 words, so this page is all about visual interpretation.
![Gallery Menu](https://github.com/user-attachments/assets/7153e1fb-af3c-4754-83f1-4c6b359fe94f)

9. About us
*Last in the list* and most likely the last one that will be selected, but still needed to get the visitors of the website and potentially customers familiar with who are we, how we get there, why, when and under what circumstances. It is a story, but the text is not taking away users' time. It just tells it in a few lines
![About menu](https://github.com/user-attachments/assets/fb6ca2de-79b7-4317-8efb-29102c72ea72)


The difference is between small and large devices to accommodate spacing and avoid truncations and overlapping

**Large devices**
![large device](https://github.com/user-attachments/assets/20f5939f-6021-4fdf-af6c-0b971e76570a)

**Small devices**
![Small devices](https://github.com/user-attachments/assets/35b4d664-42fc-4e3b-a297-2327007957d1)


# Validation
## HTML
![html-about us - 0 errors](https://github.com/user-attachments/assets/9577cf20-d4f9-4d22-861b-bf1a37d06630)
![html-contact - 0 errors](https://github.com/user-attachments/assets/6827b350-97f1-48e4-98db-793bce474fd8)
![html-food menu - 0 errors](https://github.com/user-attachments/assets/d98fa83d-0459-4b46-9742-afe82448c15e)
![html-landing page - 0 errors](https://github.com/user-attachments/assets/9db73e27-8390-4d5d-8f85-e276493131c6)
![html-gallery - 0 errors](https://github.com/user-attachments/assets/610efefa-0afa-4124-853f-79ca25dc8569)


## CSS
![No errors found](https://github.com/user-attachments/assets/ca3d96b2-f17f-4cef-81e7-456c316dc150)


## Accessibility
Accessibility is at a high of 98%
![Accessibility](https://github.com/user-attachments/assets/2009077f-bebb-4996-bad5-592f598e15dc)

Other values worth mentioning are 96% of Best practices
Performance is at 88& due to using background images and background colours, if images fail to load.
Additionally, having lots of media queries that I sorted into 5-6 categories for height and 3-4 for width to have better responsivnes contribute to this (on top of 7-year-old computer and opened over 30 tabs in Chrome)
![Performance](https://github.com/user-attachments/assets/c10fa2c3-b2aa-44c1-81ff-543028a740e6)


## Responsivnes
On top of using pages for responsive, I checked over 20 virtual devices and responsive behaviour just to be sure various device size are fitted
![Responsivnes](https://github.com/user-attachments/assets/f3a15439-4353-4c23-a08b-3c85de47220d)

*Device list are:*
- *Smaller devices*
iPhone XR, iPhone SE, iPhone 12, iPhone 14 Pro, Galaxy S9, Galaxy S8, Galaxy S5, Salaxy S20, Galaxy A51/71, Pixel 7

- *Medimu devices (tablets)*
iPad, iPad Pro, iPad Air, iPad Mini, Surface Pro 7, Surface Duo,

- *Medimu size devices (laptops)*
Nest Hub, Nest Hub Max

- *Large siye*
Dekptop computers


## Devices used
- Huawei P smart
- Samsung A15
- iPad 15
- iPad Pro
- iPhone 16
- MacBook Pro
- MacBook Air
- Nitro 5, Ryzan 7


## Browsers used
### Chrome
### Safari


## Links
*Font and icons related*
- https://www.fontpair.co/all
- typ.io/lists
- https://fontjoy.com/
- https://fonts.google.com/selection/embed
- https://fontawesome.com/kits
- https://icons8.com/icons

*Validation related*
- https://validator.w3.org/
- https://jigsaw.w3.org/css-validator/
- https://developer.chrome.com/docs/lighthouse/overview/
- https://wave.webaim.org/
- https://ui.dev/amiresponsive?url=https://

*Training and tips & tricks*
- https://code-institute-students.github.io/flexbox-interactive-demo/
- https://css-tricks.com/snippets/css/a-guide-to-flexbox/
- https://docs.github.com/en/get-started/start-your-journey/hello-world
- https://flexboxfroggy.com/#hr

*Various*
- https://www.diffchecker.com/
- YouTube
- https://github.com/


# Deployment
*https://agnogh.github.io/pirate-resort/*


## Bugs
There were several bugs along the way, but most were fixed before deployment when applying validators or responsive design
The ones that were fixed after were:
- Few typos
- The sign-in process has mandatory fields and optional fields
- Sign-in process gets user alert messages for name and email
- Adding "number" type in number field (it was "email" before)
- Duplicate items in the food menu (2 times "sea beast burgers")
- Addon to Read me
- Various minor enhancements
- Changing from style=number (where there are increase and decrease numberical value) to style=tel (where we can add letters on top of numbers, but we do not have buttons for increase or decrease numerical value)


## Thanks
Thanks to my superiors and peers at work, where I felt unappreciated, overlooked and unsupported, I was highly motivated to change my job and career and, consequently, get this project completed despite having a 10-hour work day.



6. ~~About us is placed at the end of the row as it needs to be presented to potential customers, but it is not something everyone will look at~~ Had to be removed as 6 tabs was too much and I had to restrict 

~~Order is placed in a way that each item will *always* be positioned at its place (food on 1st, contact on 2nd, Loyalty on 3rdm Gallery on 4th and About on 5th place), while the "landing page" will by default be in the title or take up the position in the header when the selected item moves to the title.~~

~~I went with an approach that each section has a separate webpage, but the user can always return to the main page or any other 5 pages available from the top (all 6 pages have a consistent look/appearance).~~