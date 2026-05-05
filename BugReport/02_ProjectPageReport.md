
## Summary (Summarize the bug encountered concisely)
Typo in the project creation options: The text for creating a blank project is misspelled as "Create black project".


## Steps to reproduce     
1. Log in to the GitLab application.
2. Navigate to the project creation page (`https://gitlab.com/projects/new`).
3. Look at the available options for creating a new project.
4. Observe the text on the card/button intended for creating a blank project.
   

## What is the current bug behavior?
The text on the user interface displays "Create black project".
     

## What is the expected correct behavior?
The text on the user interface should display "Create blank project".

     
## Relevant logs and/or screenshots
As this is a visual UI typo, there are no server or console logs available. Please see the attached screenshot for reference.

![Image info](../Image/Bug_Project_create_blank.png)
      

## Possible fixes
Update the localization or HTML file for the project creation view. Change the string `"Create black project"` to `"Create blank project"`.


## Whom do you report/ Assign To/ Tags
/label ~bug ~UI-typo ~minor
/cc @project-manager 
/assign @frontend-developer


## Priority
Minor / Trivial (This is a cosmetic UI typo that does not prevent the user from creating the project, but looks unprofessional).
      
