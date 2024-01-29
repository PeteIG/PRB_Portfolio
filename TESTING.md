# TESTING

## Compatibility

In order to confirm the correct functionality, responsiveness, and appearance:

- My website was tested on the following browsers: Chrome, Firefox, Edge.

    + Chrome:

    ![Chrome](docs/chrome.gif)

    + Firefox:

    ![Firefox](docs/firefox.gif)

    + Edge:

    ![Edge](docs/edge.gif)

## Responsiveness

The website was checked using DevTools

![Main Page](docs/home_all.png)

![Bio Page](docs/bio_all.png)

![Contact Page](docs/form_all.png)

![Project Page](docs/project_all.png)

## Manual Testing

## Manual Testing

| Feature              | Action                                          | Expected Result                                      | Tested | Passed | Comments                                             |
|----------------------|-------------------------------------------------|------------------------------------------------------|--------|--------|------------------------------------------------------|
| Navbar               |                                                 |                                                      |        |        |                                                      |
| Home                 | Click on "Read More" under each project         | The user is redirected to the respective project page | Yes    | Yes    | -                                                    |
| Bio                  | Click on the "Bio" link                         | The user is redirected to the bio page                | Yes    | Yes    | -                                                    |
| Contact              | Click on the "Contact" link                     | The user is redirected to the contact page            | Yes    | Yes    | -                                                    |
| Footer               |                                                 |                                                      |        |        |                                                      |
| LinkedIn icon        | Click on the LinkedIn icon                      | The user is redirected to the LinkedIn page           | Yes    | Yes    | -                                                    |
| Home Page            |                                                 |                                                      |        |        |                                                      |
| Project "Read More"  | Click on each "Read More" button                | The user is redirected to the respective project page | Yes    | Yes    | There are four "Read More" buttons, one for each project |
| Bio Page             |                                                 |                                                      |        |        | No interactive elements                             |
| Contact Page         |                                                 |                                                      |        |        |                                                      |
| Name Input           | Enter the name                                  | The name is entered                                  | Yes    | Yes    | If user doesn't enter the name, an error message appears |
| Email Input          | Enter the email                                 | The email is entered                                 | Yes    | Yes    | Error if email is missing or invalid                |
| Message Input        | Enter a message                                 | The message is entered                               | Yes    | Yes    | If user doesn't enter a message, an error message appears |
| "Submit" button      | Click on the "Submit" button                    | The user is redirected to the success page            | Yes    | Yes    | Redirects to home page after 5 seconds               |
| Success Page         | After form submission                           | The user is on the success page for 5 seconds         | Yes    | Yes    | Then automatically redirected to the home page      |




## User Stories
1.	As a tech recruiter, I want to easily understand Pete's core competencies and technical skills, so that I can quickly assess if he fits our company's needs.
•	Met by: Clear categorisation of skills and competencies in the homepage summary, specific project examples, and bio section.
2.	As a startup founder, I want to view examples of Pete's previous projects, including his role and contributions, to evaluate his experience and problem-solving abilities.
•	Met by: A 'Projects' section showcasing detailed case studies of key projects worked on.
3.	As a potential collaborator, I need to easily find Pete's contact information, so that I can reach out to him for potential partnerships or collaborative projects.
•	Met by: A visible 'Contact' section with more than one contact option, including a form, and LinkedIn.


## Bugs
*I had difficulty making the navbar sticky. The sticky-top class should have worked but did not. I could not find where in the code Bootstrap or CSS was overriding it. *Resolved: I found the answer in Stackoverflow chat explaining that sticky-top will not work unless it is applied to the outermost element (which it wasn't), In this case, the class needed to be applied to the header, and not the nav element. This change has been applied.

*I have not been able to centre the image on the contact form success page.

*There was a scaling issue with the work examples on the home page where, at medium screen sizes, the top row was splitting into two vertically stacked images while the second row remained horizontally stacked. The issue had been caused by applying the 'a' tag to the outermost div rather than to the div containing the image. 

