# Testing for ''**_Storyteller_** '' (LINK TO WEBSITE HOME PAGE PUT HERE!!!)

Used [W3C HTML validator](https://validator.w3.org/#validate_by_input) website via the direct input path.

1. Index.html validator results.
 ## **INPUT IMAGE HERE !!!!** 
2. Contact.html validator results.
 ## **INPUT IMAGE HERE !!!!**
3. Work.html validator results.
 ## **INPUT IMAGE HERE !!!!**
4. About-me.html validator results.
 ## **INPUT IMAGE HERE !!!!**
5. CV.html validator results.
 ## **INPUT IMAGE HERE !!!!**

-------






Used [Jigsaw](https://jigsaw.w3.org/css-validator/#validate_by_input) via the direct input path.

6. Style.css validator results.
## **INPUT IMAGE HERE !!!!**

-----






# **User stories:**
- As a user, I want a simple and clean looking website as messy, busy pages with lots of information overwhelms me.

    - User views the homepage and sees that the colour scheme and layout is very clean and simple, the images and content is well spaced out. With 3 pages all with the same consistent style, with quality images and brief descriptions throughout so not to overwhelm users with too much information.

- As a user, I want an easy to navigate website to save time and not get frustrated or lost.

    - User goes to the website and on the home page, resource page and contact us page there is a simple navigation bar fixed on the top of the page. Wherever they scroll down to on each page the navigation menu bar is there for them to click and go to another page.

    - When you hover over the words the colour of the text goes a darker grey colour.

- As a user, I want to be able to use it on desktop, tablet and mobile devices.

    - Users who are browsing with Chrome, Safari, Firefox and IE can use the website on desktop, tablet and mobile views with full responsiveness.

- As a user, I want to find out what eco homes are.

    - Go to the home page and scroll down to underneath the ‘About Us’ section is ‘Why live in an eco home?’ This section gives an explanation of the benefits and what eco homes are.

- As a user, I am interested in one of the three eco home concepts introduced and would like to know more.

    - Go to the home page and scroll down to the section underneath the ‘Why live in an eco home?’ And there are three cards each introducing a different eco home concept with a corresponding image.

    - When you hover over the ‘More Info’ green buttons they turn a darker green colour. To find out more click on the green button ‘More Info’ and it will open a new tab to an external website, the green button also stays a dark green with a light green border around it, to indicate it has been clicked.

- As a user, I want to find out more about one of the three related interests introduced on the home page.

    - Go to the home page and scroll down to the ‘Related Interests’ section where there are three cards introducing ‘Off Grid Living’, or ‘Zero Waste Living’ or ‘Eco Home Products’ with a corresponding image.

    - When you hover over the green buttons they turn a darker green colour. To find out more click on the green button ‘More Info’ and it will open a new tab to an external website, the green button also stays a dark green with a light green border around it, to indicate it has been clicked.

- As a user, I would like to sign up to Greener Homes latest news.

    - Go to the bottom of the home page by scrolling down and there is a green form labelled ‘Receive the latest news from Greener Homes’.

    - If user hovers over the ‘Sign Up!’ button it goes a darker green colour but does not stay dark green. This does not happen in iPad or phone view it only goes a darker green when it is clicked on and it stays dark green until you click another area of the screen.

    - If user clicks on the ‘Sign Up!’ button without filling in the form it will indicate with a message to ‘Please fill in this field’ indicating the area to type into.

    - If the form has been filled in but with an invalid email address and you click the ‘Sign Up!’ Button then another message comes up ‘Please include a ‘@‘ in the email address ‘___’ is missing a ‘@‘.

    - If the form has been partly filled in with half the email address and you click the ‘Sign Up!’ Button then another message comes up ’Please enter a part following ‘@‘, ‘___@‘ is incomplete’.

    - If the form has been filled correctly with a full email address and you click the ‘Sign Up!’ Button then the page goes to the top and the form clears.

- As a user, I want to know even more information about one of the eco homes introduced on the home page.

    - Go to navigation menu bar and click on ‘More Resources’. Under the ‘Website Links’ There are three lists corresponding to the three eco home concepts, each list has five links which open up a new tab to an external link giving more information.

    - All links open up into a new tab so the user doesn’t forget Greener Homes website and can go back to it easily.

    - **Bug**: The last link of the three lists has a blue border once it has been clicked which is useful for the user to know when they come back from the external link which was the last link they clicked. But the other links do not do that.

    - **Debugged**: Added the same code from the last link to the rest of the links. Now they all show a blue border when the link has been clicked.

    - **Bug**: The other three white background links go light grey when it has been clicked and the green background link does not indicate anything when clicked.

    - **Debugged**: Changed all the background colour links to light green and added the border code to all the links. Now when user hovers over the link it goes a darker green and when clicked shows a blue border to indicate it was the last link clicked.

- As a user, I want to watch an informative video of one of the eco home concepts.

    - Go the resource page and scroll down to the section ‘Video Links’ there are three short YouTube videos introducing each of the three eco home concepts.

    - **Bug**: The left and middle videos are unable to go to full screen within the website, only if you click ‘YouTube’ to watch via the Youtube website.

    - **Debugged**: Moved the > to the end of allowfullscreen

    - All videos play on the website when you click on them.

- As a user, I want to know what kind of resources are available to help them know more about eco homes.

    - Go to the resource page and when you scroll down you will find three types: Website Links, Video Links and Book Resources.

- As a user, I want to find out more information, so would like to contact Greener Homes via the contact page.

    - Go to the navigation menu bar and click on ‘Contact Us’

    - Scroll down to the form.

    - Fill in the ‘Full Name’ field, ‘Email Address’ field and ‘Message’ field, if the form has been filled in correctly and click on the ‘Submit’ green button, then it goes to the top of the page and the form clears.

    - **Bug**: The ‘Full Name’ field is accepting all characters and numbers and just one name. So would like to validate it so it only accepts letters and two names at least.

    - If the ‘Full Name’ field is not filled and user clicks 'Submit' then the message ‘Please fill in this field’ appears.

    - If the ‘Email Address’ field is not filled and user clicks 'Submit' then the message ‘Please fill in this field’ appears.

    - If the ‘Email Address’ field is not valid and you click the ‘Submit’ button then the message ‘Please include a ‘@‘ in the email address ‘___’ is missing a ‘@‘ appears.

    - If the ‘Email Address’ field has been partly filled in with half the email address and you click the ‘Submit’ Button then another message comes up ’Please enter a part following ‘@‘, ‘___@‘ is incomplete’.

    - **Bug**: After the form is correctly filled and the'Submit' button is clicked, the form goes to the top of the page and the form clears.

    - The ‘Submit’ button goes a darker green when you hover over it and when you click it and then goes back to the previous green colour.

- As a user, I have read through the information on the home page and feel this is too much change in my life but I still want to change a small part of my lifestyle, so I want to know what eco products to buy.

    - Go to the navigation menu bar and click on ‘Home’, scroll down to the ‘Related Interests’ section and click on ‘More Info’ in the ‘Eco Home Products’ card.

- As a user, I want to know the cost of an earthship, tiny house or shipping container home in the UK.

    - There are many factors to consider to find out the cost such as land price, size of house, energy resources, water supply, modern conveniences and technologies. Go to the resources page and in the website links there is information for how much it would cost for these factors.

------

# **Responsiveness of website**
## Home.html in Desktop view.
In desktop mode, the navigation menu bar on the top is fixed and the words are clearly displayed. The screen shows the hero image displaying the full width of the browser. The main heading ‘Greener Homes’ and sub-headings ‘About Us’ and ‘Why live in an eco home?’ and the horizontal dividers and its content are centred on the page.

The three cards displaying the three eco homes are in a row neatly spaced and in line, the content is justified and centred within the border. The green buttons are on the bottom of the card within the border.

The next heading ‘Related Interests’ and the horizontal divider are centred on the page.

The three cards displaying ‘Off Grid Living’, ‘Zero Waste Living’ and ‘Eco Home Products’ are in a neat row equally spaced and in line, the content is centred within the border of the card. The green buttons are on the bottom of the card also within the border.

The green form ‘Receive the latest news from Greener Homes’ at the bottom of the page is centred on the page. All the text and text box area is equally spaced and within the border of the form.

The horizontal divider and social links are centred at the bottom of the page. The social media links are equally spaced and in a row.

----
## Home.html in iPad/iPad Pro view.
In iPad mode, the navigation menu bar on the top is fixed and the words are clearly displayed. The ‘Home’, ‘More Resources’ and ‘Contact Us’ text, once clicked the font colour goes a dark grey and then goes back to the original light grey and the page opens. The hero image displays the full width of the browser with no distortions just trimmed on either side of the image. The main heading ‘Greener Homes’ and sub-headings ‘About Us’ and ‘Why live in an eco home?’ and the horizontal dividers and its content are centred on the page. The fonts have decreased in size to adjust to the smaller size and looks in proportion to each other.

Bug: When you scroll up the top of the words are hidden on the navigation bar but still clickable. For the top margin to appear user has to scroll down.
The three cards displaying the three eco homes are in a row neatly spaced and in line, the content is justified and centred within the border. The green buttons are on the bottom of the card within the border. The shape of the cards adjust to the narrower width and then go from three cards in iPad pro into a single column of cards in iPad view.

The next heading ‘Related Interests’ and the horizontal divider are centred on the page. The font size and length of the horizontal divider have decreased and are in proportion to each other.

The three cards displaying ‘Off Grid Living’, ‘Zero Waste Living’ and ‘Eco Home Products’ are in a neat row equally spaced and in line, the content is centred within the border of the card. The green buttons are on the bottom of the card also within the border. The shape of the cards adjust to the narrower width and then go from three cards in iPad pro into a single column of cards in iPad view.

The green form ‘Receive the latest news from Greener Homes’ at the bottom of the page is centred on the page. All the text and text box area is equally spaced and within the border of the form. Everything has decreased in size and is still in proportion to each other.

The horizontal divider and social links are centred at the bottom of the page. The social media links are equally spaced and in a row.

----

## Home.html in iPhone X, 5, 6, 7, 8 view.
In mobile phone mode, the navigation menu bar on the top is fixed and the burger icon appears. When clicked the drop down menu appears with the ‘Home’, ‘More Resources’ and ‘Contact Us’, when you click on them the font colour goes a dark grey and then goes back to the original light grey.

- Bug: When you scroll up the top of the burger icon are hidden on the navigation bar but still clickable. For the top margin to appear user has to scroll down.
The hero image displays the full width of the browser with no distortions just trimmed on either side of the image. The main heading ‘Greener Homes’ and sub-headings ‘About Us’ and ‘Why live in an eco home?’ and the horizontal dividers and its content are centred on the page. The fonts have decreased in size to adjust to the smaller size and looks in proportion to each other.

The three cards displaying the three eco homes are now displaying the full width of the screen one at a time, one after another, the content is centred within the border. The green buttons are on the bottom of the card within the border.

The next heading ‘Related Interests’ and the horizontal divider are centred on the page. The font size and length of the horizontal divider have decreased and are in proportion to each other.

The three cards displaying ‘Off Grid Living’, ‘Zero Waste Living’ and ‘Eco Home Products’ are in a neat single column equally spaced and in line, the content is centred within the border of the card. The green buttons are on the bottom of the card also within the border. The shape of the cards have adjusted to the narrower width but still looks good.

The green form ‘Receive the latest news from Greener Homes’ at the bottom of the page is centred on the page. All the text and text box area is equally spaced and within the border of the form. Everything has decreased in size and is still in proportion to each other.

The horizontal divider and social links are centred at the bottom of the page. The social media links are equally spaced and in a row.

-----

## Contact.html in Desktop view.
## Contact.html in iPad/iPad Pro view.
## Contact.html in iPhone X, 5, 6, 7, 8 view.

----

## Work.html in Desktop view.
## Work.html in iPad/iPad Pro view.
## Work.html in iPhone X, 5, 6, 7, 8 view.

----

## About-me.html in Desktop view.
## About-me.html in iPad/iPad Pro view.
## About-me.html in iPhone X, 5, 6, 7, 8 view.

----

## CV.html in Desktop view.
## CV.html in iPad/iPad Pro view.
## CV.html in iPhone X, 5, 6, 7, 8 view.

-----

# **Responsiveness on different browsers:**
[Google Chrome](https://www.google.com/) all the testing information has been tested on Chrome browser using DevTools.

[Mozilla Firefox](https://www.mozilla.org/en-GB/firefox/new/) and [Microsofte Edge](https://www.microsoft.com/en-us/edge) browsers responsiveness is good on desktop, tablet and phone. 

Only difference found is the website links on the 'Resources page' where the blue border does not appear but when clicked the cell is a darker shade of green and stays that way when the user come back the Greener Homes site.

[Safari](https://www.apple.com/uk/safari/) browser responsiveness is the same as Chrome browser, no bugs.

-----

# **Bugs whilst creating the website:**
1.
2.
3.
4.

----

# **Bugs to be fixed:**

1.
2.
3.
4.
