
# TODO

> Please use the below questions as guidelines to help you think and plan your Learning Reflection Report

## 1. How was your experience testing the given Webapp?
Testing a real-world, complex application like GitLab was a very eye-opening and practical experience. It helped me understand how even seemingly simple functionalities, like user registration or project creation, require careful systematic testing to ensure quality.


## 2. How did you write or manage your test case? Describe the process.
First, I navigated the GitLab application manually to understand the actual user flow and the required fields for each page. Then, I used the provided text templates to structure my test cases. I defined the preconditions, test data (variables), step-by-step actions, and the expected outcomes for both positive and negative testing scenarios.
    

## 3. Do you recommend any other tools or styles for Test case management. 
While using text files is a good way to learn the basic structure of a test case, in a professional environment, I would highly recommend dedicated Test Management tools like Jira (with Xray or Zephyr plugins) or TestRail. As far as I somehow understood, these tools provide better traceability, reporting, and easier integration with bug tracking and automation.


## 4. Which IDE (Visual Code or Atom or else) have you used to edit files?
I used Visual Studio Code (VS Code). It was very helpful, especially because it allowed me to use the Markdown Preview feature to verify that my bug report images and formatting were correct before submitting.


## 5. Did you find any trouble? how did you solve the trouble?
Yes, I noticed a discrepancy between the assignment template and the actual application. The template suggested testing a reCAPTCHA during registration, but the actual GitLab site did not have one active at the moment. I solved this by thinking like a real tester: I adapted my test cases to reflect the actual system behavior and replaced that specific test with another negative test case (registering with an already existing email).


## 6. Did you find any trouble using Github? have you used Github before? where?
I didn't have any trouble using GitHub. In fact, I use it regularly for my own personal projects and studies, so I am quite familiar with it. The process for this assignment was very smooth, and I just made sure to carefully follow the specific instructions to upload the files and folders directly instead of uploading the ZIP file.
     

## 7. If in the future if you need to automate these test cases, which framework or language will you use? and describe why (Robot Framework, Cypress, Selenium, or any other )
I do not have hands-on experience with test automation frameworks yet, but based on a quick investigation, I would choose my tools based on the testing level:
**For Unit and Integration Testing:** Since I frequently work with JavaScript, TypeScript, React, and Node.js, **Jest** would be my absolute top choice. Industry resources highly recommend Jest because it works out-of-the-box with zero configuration for most JS projects. It also includes built-in mocking and assertion libraries, and its "snapshot testing" feature is incredibly powerful for testing React components.
**For End-to-End (E2E) / Functional Testing:** I would highly consider **Playwright** or **Cypress**.
 **Playwright:** A powerful, modern tool that allows automating browsers using a single API. It provides reliable cross-platform support and covers multiple browsers (Chromium, Edge, WebKit, Firefox).
**Cypress:** A fast, JavaScript-based framework that integrates seamlessly with modern front-end workflows. Its ability to allow developers to debug tests visually in real-time makes it very appealing.
*(I also looked into **Selenium**, which is great for multi-language support, but for a JS/TS stack, Playwright and Cypress offer a more modern developer experience).*


## 8. Kindly search the term `Tester` `Automation Tester` glassdoor and LinkedIn or any other job search website. Currently, list the skills and competencies that are most in-demand in software testing
Based on current job listings, the most in-demand skills include:
- Test Automation frameworks (Cypress, Playwright, Selenium, Robot Framework)
- Programming languages (Python, JavaScript/TypeScript, Java)
- API Testing (Postman, REST-assured)
- CI/CD pipeline knowledge (Jenkins, GitHub Actions, GitLab CI)
- Agile/Scrum methodologies and tools like Jira.
- Communication skills
- Problem solving skills


## 9. **Let's assume** that if you are going to continue with the career in Software Testing, which technical and soft skills do you need to fill up the blank in your resume?
Technically, I would need to deepen my programming skills (e.g., Python or JavaScript) to write efficient automated test scripts. I also need to learn how to integrate tests into continuous integration (CI) pipelines. On the soft skills side, I would want to improve my communication skills to effectively advocate for quality and explain complex technical bugs to developers and project managers.


## 10. Write short Learning Reflection and  Free words Do you think that project helped in putting theoretical knowledge into practice? Describe? (is there anything else that you would like to share with us concerning the current study module). e.g. regarding the quality of content and your learning (or) improvement ideas? 
This project was excellent for bridging the gap between theory and practice. Reading about test design and bug reporting is one thing, but actually structuring test steps and writing a formal bug report with severity, priority, and screenshots made the concepts tangible. It gave me a clear picture of what a QA professional actually does on a day-to-day basis. Overall, this assignment and the entire course were highly beneficial and provided me with practical skills that I will definitely utilize in my own software projects, as well as in my upcoming thesis!




 





