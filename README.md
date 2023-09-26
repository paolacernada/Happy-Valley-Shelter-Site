# Build a Small Non-Profit Website

Please read these directions carefully. There are links included in many places that will help you complete the project requirements.

To submit this project, you must push your code to GitHub.

## Requirements

Your task is to build a three-page website for a small non-profit organization: Happy Valley Dog Adoption.

The purpose of this project is to give you experience using a variety of HTML elements to build the content of the page. You should focus on the structure of the page and on selecting the appropriate elements for the content, not on the look and feel of the site. You do not need to write any CSS to style this page yet.

The three pages are:

- Homepage (`index.html`) - explains the mission of the organization
- Adopt (`adopt.html`) - shows the dogs that are up for adoption
- Contact Us (`contact.html`) - shows hours, location, and contact info

### On Each Page

Each page should have the header (using the `header` element) that shows the name of the organization and a navigation menu at the top (using the `nav` element), with three links pointing to the homepage, the Adopt page, and the info page. This navigation menu should be under the header on each page.

Make sure that you only show links to pages _other than_ the one you are on. For example, if you are on the "Adopt" page, you don't need to show a link to "Adopt", but you do need links to "Home" and "Contact Us"

### Home Page

The homepage should have the name of the business as a level 1 heading, followed by a picture of an adorable dog (images/dog-hero.jpg).

The following text should be included underneath the image:

> Happy Valley Shelter has been finding safe and loving homes for dogs in the Piedmont area since 1989. We work in cooperation with local county shelters and rescue organizations and specialize in caring for neglected and abandoned dogs.

> At Happy Valley, our staff are trained in all aspects of animal welfare and can give you expert advice on adoption, training, and care. We are proud of the work we do at Happy Valley and are grateful to our community for their support in helping us achieve our mission.

> We take great care in matching each dog with the right family to ensure a successful adoption. We believe that every dog deserves a loving home, and we work tirelessly to make that a reality.

### Adoption Page

"Adopt a Dog" should appear as a level 1 heading below the navigation links and header, followed by this text:

> If you are interested in adopting one of our animals, please fill out our online adoption form.

The following dogs should each be listed with their image and traits. The description should be used for an [`alt` attribute on the image](https://developer.mozilla.org/en-US/docs/Web/API/HTMLImageElement/alt).

1. Beans  
description: A black-and-white shaggy dog  
image: images/beans.jpg
traits: Adult, Male, Medium, Easygoing, Good with cats  

2. Zelda  
description: A Boston Terrier  
image: images/boston-terrier.jpg  
traits: Senior, Female, Small, Easygoing, Good with kids, Good with other dogs

3. Baby  
desription: A brown Boxer  
image: images/boxer.jpg  
traits: Young, Female, Large, Energetic, Good with kids, Good with other dogs

4. Tom-Tom  
description: A golden Lab  
image: images/golden-lab.jpg  
traits: Young, Male, Large, Energetic, Good with kids, Good with other dogs, Good with cats

5. Marco  
description: A little fuzzy dog
image: images/little-dog.jpg
traits: Adult, Male, Small, Energetic

6. Shackleton  
description: A shaggy white dog  
image: images/old-shaggy.jpg  
traits: Adult, Male, Medium, Easygoing, Energetic, Good with kids, Good with other dogs, Good with cats

7. Midge  
description: A Shih-Tzu  
image: images/shih-tzu.jpg  
traits: Adult, Female, Small, Easygoing, Good with kids  

8. Ladybird  
description: A silly Boxer  
image: images/young-bulldog.jpg  
traits: Young, Female, Large, Easygoing, Energetic, Good with kids, Good with other dogs, Good with cats

9. Mina  
description: A young brown and white dog  
image: images/young-peppy.jpg  
traits: Puppy, Female, Medium, Energetic, Good with kids, Good with other dogs, Good with cats

### Info Page

This page should show the following information:

Happy Valley Shelter is located at:

4400 Virginia Parkway  
Cedarville, NC

Phone: 919-962-DOGS  
email: adopt@happyvalleyshelter.org

Our hours are:

- Monday 9 AM - 6 PM
- Tuesday closed
- Wednesday closed
- Thursday 9 AM - 6 PM
- Friday 9 AM - 6 PM
- Saturday 7 AM - 7 PM
- Sunday 1 PM - 7 PM

## 🌶️ Spicy Options

If you get those three pages built and have time for more, here are some additional challenges.

- Review your HTML for formatting, organization, and semantics.
    - Are you using [the right HTML elements for the content](https://developers.google.com/style/semantic-tagging)? Some elements, like the `<div>`, are generic elements used for grouping. [Other elements have specific purposes](https://developer.mozilla.org/en-US/docs/Glossary/Semantics#semantic_elements). Are there opportunities to improve the semantics of your documents?
    - Have you indented nested elements consistently? Is your code organized and easy to read? [Follow some basic best practices](https://developers.google.com/style/html-formatting).
    - VS Code has built in tools to help you with [formatting your HTML](https://code.visualstudio.com/docs/languages/html#_formatting).
- Add a footer (using the `footer` element) to the bottom of each page. The footer should contain links to "Donate", "Volunteer", and "Location." Above each link, include the corresponding image from the images directory.
- Create an "Apply for Adoption" page. On this page build a [form](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/form) to allow aspiring pet owners to enter their information. The form should include input fields for name, address, email, phone number, and a textarea for a message. Each input should have a label. The form will also need a button to submit. You may find the [MDN documentation on building your first form](https://developer.mozilla.org/en-US/docs/Learn/Forms/Your_first_form) to be helpful. Add a link to this page to the text on the adoption page ("our online adoption form").
