"# pirate-resort" 
#
# Pirate-resort
#



##*Table of content*

#1. Project Goal

##User goals
- Finding a place distant from all civilization and pollution (calm and filled with tranquillity)
- Trying out the food not by any standards or specific recipes
- Taste something different
- Different environment
- Different theme
- More casual, but still high quality service

##Site owner goal
- Provide a unique experience
- Attract specific types of people (passengers on a long voyage, adventures and people who appreciate finer things)
- Attract people who want to experience peace, calm, good food and rest from a long voyage
- Promote business but in a way that remains high quality and less grow
- Provide basic but unique food choices found nowhere else
- Provide basic information on how the restaurant came to be and why it was established


#2. User Exp
##Targeted group
- People who are travellers on a specific route
- People who appreciate good, unique food, atmosphere and environment
- Adventures 
- People who like peace and calm, sun and waves, palm beaches and do not mind the sand
- Anyone who wants to escape busy street (or law)
- People who like less formal, more casual and relaxed atmospheres, while still receiving perfect service

#User expectation
- Simple directions (it is the only island 100 miles away)
- Limited food choices but with excellent quality and unique ingredients
- Warm and nice weather, palm trees, chill atmosphere, relaxed mood, delicious food
- Affordable prices
- Trying something that cannot be found normally

###1st time users
- I want to know the location
- I want to know the availability of the food menu
- I want to know the prices
- I want discounts
- I want to taste food that is nowhere to be found 
- I want to have breakfast, lunch or dinner in a place that barely has any civilization

###Returning users
- I want to continue getting discounts
- I want to try other dishes
- I want to experience what I had 1st time around
- I want contact details so I can reserve a spot

###Owner of the restaurant
- I want more subscribers so I can share updates regularly and increase potential clients as a targeted group is smaller than usual
- I want clients to have our contact to have them visit again
- I want potential customers to have all info in a very simple and straightforward way
- I want the user to find their way around easily and quickly
- I want to show a few pictures for potential customers so they can get an idea of what they can expect


#3. Design of the webpage
##Design decisions
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

##*Fonts:*
I tried to create more "Adventure/Pirate/Caribbean/Ocean atmosphere from the late 18th century, so specific fonts were used like "Rouge Script", "Tangerine", "Dancing Floor", and "Lavishly Yours". I still decided to add more "common" fonts like "lato", "Oswald" as a fallback font to distinguish from whatever browser might use.


##Structure
To match the style of casual I decided to go with a straightforward and simpler approach. 
I decided to go with 6 (six) separate pages divided into
![Navigation bar](https://github.com/user-attachments/assets/8310347f-d1ed-4b73-8954-14d893fdf825)

1. Landing page
2. Food menu (first from the top left position)
3. Contact (second after the food menu, as it is most important after checking the availability of items on the menu)
4. Loyalty and Reward centre (as I believe this would be the next step in attracting the customers - discounts/vouchers)
5. Gallery where user can see pictures of the location and food prepared
6. About us is placed at the end of the row as it needs to be presented to potential customers, but it is not something everyone will look at 

Order is placed in a way that each item will *always* be positioned at its place (food on 1st, contact on 2nd, Loyalty on 3rdm Gallery on 4th and About on 5th place), while the "landing page" will by default be in the title or take up the position in the header when the selected item moves to the title.

I went with an approach that each section has a separate webpage, but the user can always return to the main page or any other 5 pages available from the top (all 6 pages have a consistent look/appearance).
![Order 1 nav bar](https://github.com/user-attachments/assets/4aa2c581-4a57-45b4-875d-b4d5c53e6ab2)
![Order 2 nav bar](https://github.com/user-attachments/assets/f2dd8622-d55a-44a2-9a0d-c24023486615)
![Order 3 nav bar](https://github.com/user-attachments/assets/cb030125-dbf5-4b90-b24e-949a87087501)
![Order 4 nav bar](https://github.com/user-attachments/assets/de655eef-0fe4-4bc2-838a-89eeaf499875)
![Order 5 nav bar](https://github.com/user-attachments/assets/688540c6-9713-4375-b1e3-7c44f4918ddf)



Making it complex with lots of dropdown menus (despite consuming less space) seems like a setback and an additional click.

I avoided truncations by replacing full title names (using characters) with symbols and emojis on smaller devices. On larger devices, I set that the full name is displayed.


Small devices nav bar
![Nav bar - small](https://github.com/user-attachments/assets/066505e6-3541-4b7e-9ffe-90ae530c6c9d)

Large dvices nav bar
![Nav bar - big](https://github.com/user-attachments/assets/4ab8951f-e764-4ced-8049-cf3e002b2dce)


# Tab names
![Tab names](https://github.com/user-attachments/assets/c8b365a6-d764-40bb-94b8-1e67ac1acb79)
All tabs have names and symbols


#Home page / Main Page and header
#***ADD CONTEXT HERE***
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

For the Gallery page, I set both colour and background image in case images do not load, background colour can give contrast to the context making it stand out.
![water_background_for_gallery](https://github.com/user-attachments/assets/f6958bcd-c712-4f22-8a5d-692f44e3516d)

For the nav bar I did something similar where I wanted to represent more sky
![header_background_image](https://github.com/user-attachments/assets/f8511518-8410-410c-915f-ca455d9be1b7)

The footer was something related to water (so opposite of the nav bar and sky)
![Footer](https://github.com/user-attachments/assets/bf482c12-a1e6-4660-86c7-a82bf085f86c)


# Footer
![Footer](https://github.com/user-attachments/assets/e91709ae-b2ec-43d5-a216-c24818e5fce4)
Shadows added for stilistic reasons
More than ususal number of icons placed to make sure it will wrap nicely

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

# Feature
## Navigation bar

Contains 5 (five) pages, while selected page goes "on top" and "landing page" takes up position of "landing page" so that the order remains the same all the time 
0. Landing page
1. Food menu 
2. Contact 
3. Loyalty and Reward centre
4. Gallery
5. About us 

#***ADD CONTEXT HERE***

Difference is between small and large devices to accomodate spacing and avoid truncations and overlapping

#***ADD CONTEXT HERE***



# Validation
## HTML

## CSS

## Accessibility

## Devices used

## Browsers used
### Chrome
### Safari


# Deployment



