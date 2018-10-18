# User Centric Frontend Development Milestone Project - Hey Hey We're the Monkees

In this project I have created a new website for the band "The Monkees". The website is a one stop shop for all things Monkees. Fans
can come and listen to their favourite tracks, watch videos and find links to the various social media platforms that their favourite
Monkees use. Additionally new fans can come and find out information about the Monkees or find links to purchase cool Monkees merch to show the world how much they love the Monkees. 

In this project I have utilised mobile first design principles to create a responsive webpage that is intended to look good and
and perform well on any size of device. I have also put good user experience at the front and center of all designs and have strived to create an intuitive and enjoyable journey through all things Monkee for my users. 
 
## UX

###Strategy

There are a number of reasons for creating this project. First and foremost it is to provide a convienent and easy to use resource for Fans of The Monkees to listen to music, watch videos and find up to date information about their favourite (or at least one of their favourite bands). Secondly it serves as a platform for the Monkees to promote their new material, their social media channels, and allow them to stay in touch with their fans. Finally users can use the site to arrange to have the Monkees play at their parties, weddings or other events.

Our Key demographic are fans of the Monkees. Whilst this is not exactly the most specific demographic, there are a couple of common threads. Primarly that they love the band the Monkees. Therefore to help me identify my user stories I spoke to my family, friends and mentor aboout what they / I expect to find on a bands website and what I would like to do on a bands website. From this process, along with the specification document and research looking at other bands websites i identified the following user stories
 

#### User Stories

I Identified two users for this site. Existing, Long Term Fans of the Monkees and Brand New Fans who have just first heard the Monkees and want to hear more.

##### New and Existing Fans
1. As a fan of the Monkees I should be able to see any upcoming tour dates and associated ticket information.
2. As a fan of the Monkees I should be quickly find out about any recent news or developments.
3. As a fan I should be able to listen to my favourite Monkees Tracks on the site.
4. As a fan I should be able to watch my favourite Monkees Music Videos on the site.
5. As a fan of the Monkees I should be able to contact them to book them for Wedding or Party.
6. AS a fan of the Monkees I should be able to sign up for the Monkees mailing list, to receive updates about the Monkees.
7. As a fan of the Monkees I should be able to order Monkee Merch.
8. AS a fan I should be able to view photos of the band.

##### New Fans
*These could also apply to old fans, but I'm assuming that many of existing fans will already know this information*
1. As a new Monkees fan I should be able to find out about the monkees, who they are, their history etc.
2. As a new fan I should be able to use the site to find the band and the band members social media pages. 

####Scope
Using the user the above user storys and he project brief I identified the follwoing requirements: 

####Functional Requirements
1. The Project must be a series of static webpages or one large webpages with multiple sections
2. The webpages must work in a range of browsers
3. Across a range of different devices, mobiles, phablets, tablets, laptops, desktops
4. Each of the pages of the site should be accessible from the others.
5. The project will need to be able to play a range of different media.

#####Non-Functional Requirements
1. The site should be intuitive to use
2. The site should be eye-catching and easy to read/use

####Content Requirements
1. The project will need to contain videos
2. The project will need to include audio clips
3. The project will need to include text content
4. The project will need to contain images.
5. The project will need a form

###Structure

After considering the scope of my project I decided that it would be better to approach the project as a series of webpages as opposed to a single long pages in multiple sections. My concerns stemmed from the content requirements. I was worried that if there were lots of different types on media on one long page it might take a long time to load, and ultimately turn off users. I decided to structure my website as multiple pages.

The pages I included are:

**Homepage** - AS the first page my users will see I decided to include information that I feel is most important on a bands website, namely tour dates, news, and new musical releases. This page also provides links to all the other subsequent pages.

**Bios** - A page for the new fans to learn about the Monkees

**Music** - This page is where users will go to listen to the music, and find out information about the albums each track comes from.

**Videos** - This page is where the users will go to find out about the latest Monkees videos.

**Gallery** - Another self explanatory page, users can find image galleries of the monkees on this page.

**Bookus** - This page houses a form that the users can submit to make enquirees about booking the monkees.

The pages appear in his order in the navbar.  I felt that the bios, music, videos and gallerys are of equal importance, so no particular order was applied. Bookus was put last as this would useually be a parting action on the site, so by putting it at the end of the navbar, users have to make a concious effort to select it, passing over all the links other content.

The project uses a flat structure and every page is only 1 click away from every other page.

###skeleton - to be continued


This section is also where you would share links to any wireframes, mockups, diagrams etc. that you created as part of the design process. These files should themselves either be included in the project itself (in an separate directory), or just hosted elsewhere online and can be in any format that is viewable inside the browser.

## Features

In this section, you should go over the different parts of your project, and describe each in a sentence or so.
 
### Existing Features
- Feature 1 - allows users X to achieve Y, by having them fill out Z
- ...

For some/all of your features, you may choose to reference the specific project files that implement them, although this is entirely optional.

In addition, you may also use this section to discuss plans for additional features to be implemented in the future:

### Features Left to Implement
- Another feature idea

## Technologies Used

In this section, you should mention all of the languages, frameworks, libraries, and any other tools that you have used to construct this project. For each, provide its name, a link to its official site and a short sentence of why it was used.

- [JQuery](https://jquery.com)
    - The project uses **JQuery** to simplify DOM manipulation.


## Testing

In this section, you need to convince the assessor that you have conducted enough testing to legitimately believe that the site works well. Essentially, in this part you will want to go over all of your user stories from the UX section and ensure that they all work as intended, with the project providing an easy and straightforward way for the users to achieve their goals.

Whenever it is feasible, prefer to automate your tests, and if you've done so, provide a brief explanation of your approach, link to the test file(s) and explain how to run them.

For any scenarios that have not been automated, test the user stories manually and provide as much detail as is relevant. A particularly useful form for describing your testing process is via scenarios, such as:

1. Contact form:
    1. Go to the "Contact Us" page
    2. Try to submit the empty form and verify that an error message about the required fields appears
    3. Try to submit the form with an invalid email address and verify that a relevant error message appears
    4. Try to submit the form with all inputs valid and verify that a success message appears.

In addition, you should mention in this section how your project looks and works on different browsers and screen sizes.

You should also mention in this section any interesting bugs or problems you discovered during your testing, even if you haven't addressed them yet.

If this section grows too long, you may want to split it off into a separate file and link to it from here.

## Deployment

This section should describe the process you went through to deploy the project to a hosting platform (e.g. GitHub Pages or Heroku).

In particular, you should provide all details of the differences between the deployed version and the development version, if any, including:
- Different values for environment variables (Heroku Config Vars)?
- Different configuration files?
- Separate git branch?

In addition, if it is not obvious, you should also describe how to run your code locally.


## Credits

### Content
- The text for section Y was copied from the [Wikipedia article Z](https://en.wikipedia.org/wiki/Z)

### Media
- The photos used in this site were obtained from ...

### Acknowledgements

- I received inspiration for this project from X
