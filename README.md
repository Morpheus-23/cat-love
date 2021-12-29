# for LOVE of CATS (fLoC)

for (LOVE of CATS)[https://morpheus-23.github.io/cat-love/] is a website for people who want to adopt a rescued cat. It enables people to browse through a list of cats that are available for adoption and gives information about each cat. It also allows people to send their contact information along with the cat they are interested in.

## User Experience (UX)

### User stories

-__First Time Visitor__

    - As a First Time Visitor, I want the home screen to entice me to further indulge my curiosity about adopting a rescued cat.
    - As a First Time Visitor, I want the home screen to clearly indicate the navigation possibilities of the site.
    - As a First Time Visitor, I want to find the website easy to navigate and move between the pages of the site.
    - As a First Time Visitor, I want the site to provide information about the background/backstory of the site owner.
    - As a First Time Visitor, I want to be able to browse through the list of available cats and read about their characteristics and special needs, if any.
    - As a First Time Visitor, I want to be able to apply for the adoption of a cat.
    - As a First Time Visitor, I want to easily find the contact details of the site owner.
    - As a First Time Visitor, I want to establish that the intention of the site owner is clearly aligned with the safe and responsible rescue efforts of homeless cats.

-__Returning Visitor__

    - As a Returning Visitor, I want to see new cats available for adoption.
    - As a Returning Visitor, I want to read about success stories of adopted cats, whether rescued or rehomed.
    - As a Returning Visitor, I want to read about collaborations with other rescue organisations, thus growing the rescue and rehoming efforts.

### Strategy

 - The main aim and focus of fLoC are to establish a reputation as a reputable rescuer that constantly rescues feral and/or homeless cats and find safe and loving homes where the cats can happily live out the remainder of their 9 lives.
 - For fLoC it is of utmost importance to:
        - rescue cats living on the streets / from vulnerable situations;
        - rehabilitate/socialise the cats before opening them up to adoption;
        - find good and loving homes for the adoptable cats;
        - find foster homes to help rehabilitate/socialise cats/kittens until they are ready to be adopted;
        - find other rescuers, whether individuals and/or organisations to collaborate efforts to enable more cats to be rescued from the streets / undesirable situations;
        - create an online presence to enable other rescuers, potential foster homes, potential adopters to make contact with fLoC to help as many cats as possible;
- For a further release:
        - Once fLoC is well established and growing in efforts, the intention is to attract donors such as companies producing and/or selling cat food, treats, accessories, medical supplies and supplements. 
        - When fLoC has a well-established following, it may consider endorsing products for cats, provided that the production and distribution of said products are in line with the aim of fLoC, thus no harm to cats in any way or form.  No harm to any animal during the product research, product development, production, or distribution of any products will be tolerated/endorsed.

### Scope

- Sprint 1: the functional specifications
    - For the launch of the website the following critical pages should form part of the first release:
        - Our Story page, providing basic information about fLoC and the purpose of the website;
        - Our Cats page, introducing the cats currently available for adoption;
        - Adoption request page, enabling potentional adopters to apply for the adoption of a specifically selected cat, from the Our Cats page;
        - Find Us page, enabling potental adopters, collaborators and general public who may have information about cats needing rescue to make contact with fLoC.

- Sprint 2: future specifications intended for release within 6 - 8 weeks from website launch:
    - For the next release, the following pages should be added:
        - Rescue success stories, making provision for messages and photographs to be submitted to fLoC and published by fLoC following administrator approval in an effort to motivate potential adoptees or persons needing to surrender their cat to contact fLoC;

- Sprint 3
    - For the following release, the following pages should be added:
        - Emergency contact page, setting out contact details of rescuers and/or organisations that have agreed to collaborate efforts and are willing to stand in if/when fLoC cannot be reached in case of an emergency rescue;

- Sprint 4
    - For the fourth release, the following pages should be considered / developed;
        - Video footage, photographs and stories documenting rescue efforts with or without collaborations, provided the required consents and legal waivers have been obtained from any and all participants;
        - Donation / sponsor requests;
        - Product endorsement possibilities; 







    
## Features

### Existing Features

#### Common Page features



- __Logo__
    - The logo is clickable and provides an easy way to navigate back to the home page.
    - It is consistently located on each page allowing the user to easily find it.
  
- __Navigation Bar__
    - Consistently located on each page allowing an intuitive user experience
    - Provides links to the Home, Selection, Adoption and Find Us pages
    - The active menu item is highlighted and themed according to it's target page

- __Hero images__
    - Each page contains a different hero image
    - Each hero image has a colour theme that matches the navigation bar item and the cover text
    - The hero images uses a zoom animation to draw the user into the page

- __Footer__
    - Pinned at the bottom of the page
    - Contains social media links for fast sharing or communication
    
#### Page specific features

- __Our Story page__
    - Provides information about who fLoC is, what they do and why they do it
    
- __Our Cats page__
    - Allows the user to see a list of cats available for adoption
    - Shows a photo, the cat's name and other useful information about cat
    - Updated when new cats become available and existing cats are adopted

- __Adoption request page__
    - Allows the user to submit a request to adopt a specific cat
    - The user supplies all required fields allowing fLoC to to establish contact and start the process
    
- __Find Us page__
    - Provides operating hours, adress and contact information

## Testing

### Layout

* Page title remains constant for all pages
* Logo location always remains constant
* Navigation bar location always remains constant
* Footer remains pinned to bottom of browser window
* Content pages header location remains constant on each page

### Navigation

* Clicking the logo navigates to landing page in the same tab
* Clicking the navigation menu items navigates to the correct site page in the same tab
* Clicking the social media links navigate to the correct external social media site in a new tab

### Form

* Input form validates required input fields and guides the user correctly to remedy the problem
* Submit button submits to the CI backend and displays information in a new tab

### UX

* Each page has a unique colour theme and the navigation hover and active page colour matches the target page's theme
* The selected navigation menu item background colour indicates which page is displayed

### Validator testing

- HTML
    - No html errors were returned for all four pages when passing through the official [W3C validator](https://validator.w3.org/nu/?doc=https%3A%2F%2Fcode-institute-org.github.io%2Flove-running-2.0%2Findex.html)
- CSS
    - One validation failure in the styles.css file reported by [(Jigsaw) validator](https://jigsaw.w3.org/css-validator/validator?uri=https%3A%2F%2Fvalidator.w3.org%2Fnu%2F%3Fdoc%3Dhttps%253A%252F%252Fcode-institute-org.github.io%252Flove-running-2.0%252Findex.html&profile=css3svg&usermedium=all&warning=1&vextwarning=&lang=en#css)
    - This issue will be fixed in the next release

### Unfixed Bugs

* See Validator testing error - Fixed in the next release
* Content on 'Our Cats' and 'I want one' is not dynamically centered - Fixed in next release
* Layout of cover text on hero images - Fixed in next release

## Deployment

- The site is deployed to GitHub pages. The steps to deploy were as follows:
    - In the fLoC GitHub repository, navigate to the Settings tab and select the Pages 
    - From the source section drop-down menu, select the Master Branch
- The live link can be found here - [https://morpheus-23.github.io/cat-love/](https://morpheus-23.github.io/cat-love/)

## Unimplemented assessment criteria

* Alt text equivalents to cater for the visually impaired
* Layout changes for all screen sizes

## Content

- All icons were taken from [Font Awesome](https://fontawesome.com/)
- All images were taken from [pixabay](https://pixabay.com/)
- Some design ideas were taken from Love Running and Coders Coffeehouse
- A lot of technical implementation information were taken from [W3Schools](www.w3schools.com)

## Directory structure

The site content is structured as follows:

| Directory | Description |
|---|---|
| / | html files  |
| /assets | non-html content |
| /assets/css | all style sheets |
| /assets/images | all images |