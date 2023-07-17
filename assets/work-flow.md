# User Story:

**AS AN employer:**
>*I WANT* to view a potential employee's deployed portfolio of work samples
>*SO THAT I* can review samples of their work and assess whether they're a good candidate for an open position.

---

# Acceptance Criteria:
**GIVEN I need to sample a potential employee's previous work.**
1. *WHEN I* load their portfolio
    *THEN* I am presented with the developer's name, a recent photo or avatar, and links to sections about them, their work, and how to contact them.
2. *WHEN I* click one of the links in the navigation
    *THEN* the UI scrolls to the corresponding section
3. *WHEN I* click on the link to the section about their work
    *THEN* the UI scrolls to a section with titled images of the developer's applications
4. *WHEN I* am presented with the developer's first application
    *THEN* that application's image should be larger in size than the others
5. *WHEN I* click on the images of the applications
    *THEN* I am taken to that deployed application
6. *WHEN I* resize the page or view the site on various screens and devices
    *THEN* I am presented with a responsive layout that adapts to my viewport

---

# Algorithm:
>Create and deploy a portfolio website which contains work samples, contact, about and every related elements.

---
## Tasks:
1. Add author's name, picture and links to; about, contact and work samples.
2. Create a nav bar with related links inside. Connect each link to the corresponding section.
3. Create a container, then add images related to applications and projects that has been done so far with proper title. connect that container to the related link.
4. First application's image should be larger than the others.
5. Define a link for each application's image inorder to connect that image to the related deployed application.
6. Preper sample applications  and connect them to related section in the main webpage.
7. Design and modify the webside with respect to Rsposive Web Design, so that the whole application functions properly through every viewport and screen size. 
8. Test and run the application to make sure that every element and link is functioning.
9. Provide a decent README file.
10. Deploy the application through GitHub pages, then submit the live URL and code repositery's link. 

---
## Pattern Recognition:
- Use CSS Reset
- Use HTML semantic elements.
- Use anchor tags and style them as button.
- Connect each link to the corresponding section by using id.
- Apply Flexbox, position property(if needed), media queries and proper relative units to make the website responsive
- Use git and github to track every step and changes.

---
## Abstraction:
- Ignore functionalities related to Java Script for now.

---
## sequence:
**N/A**

---
## Debug:
**N/A**