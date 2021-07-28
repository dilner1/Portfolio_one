# Studio Six

Studio Six is a recording studio that allows potential clients to hire either a recording studio, one of two rehearsal rooms or book equipement through the rental service for live music. As it is a busnieness area centered around artists I wanted to give the website a bold look to really capture the eye of the potential client.

The site uses a one page format, this makes it especially easy to naviagte on mobile and doesn't hinder use on a desktop. This also gives the site a sleek and modern feel.

![alt](assets/images/responsive_design.png)

# Features

## Opening Screen

- opening section of the page starts with a large, bright and colorful picture and focuses eye on central logo

- this is an attempt to make the site memorable and unique.



## Navigation Bar

- Navigation is located under the header and sticks to the top when scrolling down

- Has hover function that changes the nav colour 

- As is a one page site have not included an 'active' element as not necessary.


## Who We Are

- gives short information on company, explains what the studio can do 

- As opening section is very dramatic this section was kept simple and easy to read

- Uses wide line-spacing and solid background to achieve this


## Rooms

- Uses image gallary to seperate sections

- Shows the specific rooms that can be booked


## Equipment 

- Similar to Who We Are section, focus on ease of reading.

- Contains a brief disclaimer for anyone wanting to use this service

- Encourages peopclientsle to book early and get in contact through bookings section below


## Bookings form

- Form for users that covers all of the above areas

- requires name / email, what service they would like and a text box to give aditional context


## Footer

- Links to social media

- Bold white against dark grey / almost black

- like navigation has hover colour 

# Testing

## validation

- No errors were returned when passing through the official Validator

![html validation](assets/images/html_validation.png)

- No errors were returned when passing through the official validator

![css_validation](assets/images/css_validation.png)

- Tested Lighthouse on mobile
![desktop_lighthouse](assets/images/lighthouse mobile result.png)

- Tested Lighthouse on desktop
![desktop_lighthouse](assets/images/lighthouse desktop result.png)


## Linking Images
I ran into a bug almost immediately, after the initial submit and deployment to github the site did not update, this was because the css was not linked correctly - I had gone out of the directory because I used the file path '../assets/images/nameofpicture.jpeg' - when i removed the '..' it worked as the index file is located next to the assets file.

Similarly I encountered an issue with the images in the Rooms section would not load, the file path looked correct as I compared it to my mistake above. I relalised this was because I had put '/' in front of assets. Removing this connected the links.

## Responsive Elements

The site was designed with a mobile first approach. 

Had an issue with the form sections text and email boxes as they would not line up in the centre of the page. this was not an issue with the inquiery section that contains the radio buttons. The problem was more pronounced when used on tablet and desktop, so originally I used margin with percentages to fix this however it still persisted, tried padding and changing different display element types.

The issue stopped when I removed the display element, the natural flow of the page correted the mistake as it was already responsive. This has taught me it is very easy to over code something.

# Unfixed Bugs

Whilst not a but as such I have found that when I move to a section of the page it crops out the titles, this is because of the navigation bar that sticks to the top of the page. I would still keep the navigation bars design as it is very useful for navigating the page however to clean up the design I would look to change where the link take the user. 

# deployment

The site was deployed to GitHub pages. The steps to deploy are as follows:


In the GitHub repository, navigate to the Settings tab
From the source section drop-down menu, select the Master Branch
Once the master branch has been selected, the page will be automatically refreshed with a detailed ribbon display to indicate the successful deployment.

The live link can be found here - https://dilner1.github.io/Studio-Six/


# credits


# content


# media