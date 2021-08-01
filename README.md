![am-i-responsive-screenshot](https://user-images.githubusercontent.com/85314939/127751405-a74b5b0d-abbe-4c83-b979-2cecf7e5a3de.PNG)

Wireframes:
![laptop-home-page](https://user-images.githubusercontent.com/85314939/127764841-3151000b-f904-4141-b11d-46329b84f52b.PNG)

![laptop-range-page](https://user-images.githubusercontent.com/85314939/127764847-dabeb02a-a30f-4f67-a99f-6c7c5735a15a.PNG)

![laptop-support-page](https://user-images.githubusercontent.com/85314939/127764858-965fa040-f1d5-497d-98f6-9d491b7b2689.PNG)

![tablet-home-page](https://user-images.githubusercontent.com/85314939/127764862-d46e360c-b0fd-482e-9785-0d1e48c5136b.PNG)

![tablet-range-page](https://user-images.githubusercontent.com/85314939/127764863-e92f285b-5d04-44cf-b6eb-ff953c6d49fe.PNG)

![tablet-support-page](https://user-images.githubusercontent.com/85314939/127764867-63a61e34-7d42-49fd-8509-ed57eb6c20bd.PNG)

![mobile-home-page](https://user-images.githubusercontent.com/85314939/127764872-d5640007-3bc3-46dc-ad09-92769845b0b9.PNG)

![mobile-range-page](https://user-images.githubusercontent.com/85314939/127764877-2933493e-d21a-4c9b-9100-2f1a95ca793d.PNG)

![mobile-support-page](https://user-images.githubusercontent.com/85314939/127764882-afd3dadb-67e7-466e-8ed6-30c1fcb67a02.PNG)

Champion Cycles is a bicycle leasing company aimed at providing low cost and flexible ways of using a bike. The site is targeted towards individuals looking at using a bike as a preferred mode of transport and people who are looking at ditching motor vehicles for trips. Champion Cycles will be useful for the targeted individuals as it will provide comparative information regarding different styles of bikes and video content which allow individuals to complete various standards of maintenance at home. For more complex fixes, the site will offer in house assistance.

Features:
- Navigation Bar
![navigation-bar](https://user-images.githubusercontent.com/85314939/127751269-6bdf2932-ea4c-42c3-af1f-3272ac895481.PNG)
The home page consists of a main navigation bar which is consistent throughout the website to allow for simple navigation. The navigation bar is fully responsive accross the three pages, which includes links to the Home Page, The Range Page and Support Page. This will allows the user to request different pages of the website without the need to use the 'back' button on the browser.

- Landing Page
![hero-image](https://user-images.githubusercontent.com/85314939/127751277-178f66b1-e9ee-47f1-ae42-23d66bfa6f8d.PNG)
The landing page consists of a photograph with a text overlay with a short sentance to outline the websites purpose. This provides a quick idea to the content of the rest of the website.

- About Us
![about-us](https://user-images.githubusercontent.com/85314939/127751284-16ee60e6-0cfb-4013-bbfe-f5ffd082a030.PNG)
The about us section is split into two areas: one includes the benefits of cycling and anonther is the benefits of going through the company. This will assist the user in making a snapshot decision as to whether to proceed with viewing the rest of the website.

-Contact Us
![contact-us](https://user-images.githubusercontent.com/85314939/127751286-7c66c671-9579-4c6d-be6c-ba1a3952ea17.PNG)
The contact us page allows the user to start communication with Champion Cycles. The user will be asked to submit their full name and email address, with a telephone number as an optional feature. The dropdown menu includes all the bicycles that can be found on the Range page and are titled identically. This allows for a consistant viewing and the user can identify precisely which bike they are interested in.

- The Range Page
![the-range-page](https://user-images.githubusercontent.com/85314939/127751291-0605fb74-80dc-4a0d-b613-6b63c956f650.PNG)
The range page consists of all the bicycles that the company can provide as part of a lease. Each bicycle image consists of the full name as detailed on the Decathlon website (https://www.decathlon.co.uk/) and a brief description of the bike. This will allow the user to get a brief idea of the style of bicycle that they wish to use. An additional feature to this mode will be the introduction of greater detail of the individual bicycles, and the option to the expand the image of the bicycle.

- The Support Page
![the-support-page](https://user-images.githubusercontent.com/85314939/127751295-5079308e-d5af-414d-bbc4-6fed4535402e.PNG)
This page consists of links to basic video tutorials to enable the user to solve problems without the need to take the bike to a garage or shop. Each video possesses an image of an area on the bike to which the video relates to and a description of what the video will show. Each video, once selected, will open in a separate browser to enable the user to remain on the web page.

Testing:
Each responsive item has been tested to ensure that it opens or changes page as intended. There are no broken links between pages, each "Enquire Now" anchor opens the Contact Us section correctly, and each video link on the Support Page opens correctly in a new tab.

The website was also tested through Google Chrome's Lighthouse feature under Developer Tools. These tests produced the following results:

For Mobile:

![accessibility-testing-mobile-image](https://user-images.githubusercontent.com/85314939/127751306-c7d78a84-6463-45f5-a9d8-cc08b8048c35.PNG)
For Desktop:

![accessibility-testing-desktop-image](https://user-images.githubusercontent.com/85314939/127751309-c218bfca-6512-4fa1-ab72-d2d3b3b9b04d.PNG)

Validator Testing:
- HTML
Four errors were raised for the index.html document when passed through the official W3C Validator and are as follows:
    1. Element option without attribute label must not be empty (from line 85, column 43 to line 85, column 51)
    2.  input start tag with select open. (from line 123, column 21 to line 123, column 81)
    3.  Stray end tag select. (from line 124, column 17 to line 124, column 25)
    4. The value of the for attribute of the label element must be the ID of a non-hidden form control. (from line 83, column 17 to line 83, column 39).

Sixty Four errors were raised for the-range.html document when passed through the official W3C Validator and are as follows:
    1. Bad value as illegal character in path segment: space is not allowed. This occured 32 times.
    2. The element a must not appear as a descendant of the button element. This occured 32 times.

All Sixty eight errors have been corrected and no more errors were raised when passed through the official W3C Validator

- CSS
No errors were found when passing through the official (Jigsaw) Validator.

Unfixed Bugs:
One unfixed bug with regards to the contact us form submission as the storage of this information does not fall within the scope of this project. For the purpose of this project, the form submission is sent to the Code Institute form dump at https://formdump.codeinstitute.net/.

It is also noted that when the site is run through the "Am I Repsonsive" website, the site at under 425px width does not correctly show the navigation bar which has been centered in the same manner to that at less then 768px in width.

Deployment:

The site was developed using GitPod with a remote connection to Github.

1. Once the all the code was added, the repository was saved using CTL+S.
2. The changes were then add to the local git using Gitpod's terminal functions. This included "git add ." and git commit -m "Final commit for deployment".
3. The Git was then pushed to Github through the terminal function "git push".

A live website from the repository was then created through Github using the following steps:

1. The project was searched for under the repositories section on Github.
2. After selecting the Champion Cycles repository, navigate to the settings tab
3. Select the "Pages" option located within a self-contained window left on screen
4. Under "Source", select the Branch as "Master", and in this case, the file as "Root" before selecting save. This then generated the live site.

Credits:
- Code
1. Credit to W3Schools for demonstration how to overlay text over images for Range page https://www.w3schools.com/howto/howto_css_image_text.asp.
2. Credit to W3Schools for detailing how to create a fade in overlay for Range page https://www.w3schools.com/howto/tryit.asp?filename=tryhow_css_image_overlay_fade
3. Credit to answer from Wes Foster on Stackflow for zoom animation on Support Page https://stackoverflow.com/questions/32524423/zooming-an-image-on-hover-and-not-exceeding-parent-div-borders
4. Code used from Code Institute "Love Running" walkthrough for Contact Us page and Social Media icons.
5. Credit to W3Docs for detailing how to link anchors to divs in other pages. This allowed the creation of the link between the "Enquire Now" option on the Range page to connect to the "Contact Us" on the Home page. https://www.w3docs.com/snippets/html/how-to-create-an-anchor-link-to-jump-to-a-specific-part-of-a-page.html
6. Credit to W3Schools for detailing how to disable options for the Home page Contact Us section https://www.w3schools.com/tags/att_option_disabled.asp

- Media and Content
1. Images and bicycles description on the Range Page found and extracted from the Decathlons website (https://www.decathlon.co.uk/)
2. All remaining images were sourced through Unsplash https://unsplash.com/.
3. Video links to Youtube on Support Page used from the Global Cycling Network and Jesse McDonough through Howcast.
4. Content for "Mental Health" section in About Us used from Cycle Scheme Article. https://www.cyclescheme.co.uk/community/featured/cycling-and-the-mental-health-benefits
5. Content for "Immunity Benefits" section in About Us used from Cyclist Article. https://www.cyclist.co.uk/in-depth/8120/too-much-of-a-good-thing-how-cycling-can-harm-or-hurt-your-immunity
6. Content for "Heart Disease" section in About Us used from Cycling Weekly Article. https://www.cyclingweekly.com/news/latest-news/benefits-of-cycling-334144