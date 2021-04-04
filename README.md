<p align = "center">
  <img width="100" height="100" src="https://user-images.githubusercontent.com/45159366/102813619-fb3d3e80-437d-11eb-88a9-ef2b87a7ef70.png">
</p>


# <center> **Company Handbook on Software Quality** </center>

<br>

---
## <center> **Table of Content** </center>
---

<br>

* Handbook Introduction

<br>

* Task Estimation in Scrum

    - Introduction to Task Estimation in Scrum
    - Story Points/ Planning Poker
    - Task Estimation Advantages
    - Task Estimation Disadvantages
    - Conclusion
  
<br>

* Coding Standards

    - Introduction
    - Why are coding standards important and should they always be enforced
    - Coding Standards Document
    - Import topics in a Coding Standards Document
    - Conclusion

<br>

* Code Reviews

    - Introduction
    - Why do we code review?
    - Code Review Best Practices
    - Conclusion

<br>

---
## <center> **Handbook Introduction** </center>
---

<br>

The purpose of this handbook is to demonstrate our learning of GitHub / GitFlow as a team using a shared GitHub repository whilst discussing the following topics:

<br>

* Task Estimation in Scrum
* Coding Standards
* Code Reviews

<br>

---
## <center> **Task Estimation in Scrum** </center>
---

<p align = "center">
  <img width="600" height="300" src="https://d2o2utebsixu4k.cloudfront.net/media/images/c4aa8567-c70f-4966-8af3-e1ef56393f4c.png">
 </p>

---
### <center> **Authors** </center>
---

<br>

* Eugene McCormack
* Mark Grogan

<br>

---
### <center> **Introduction** </center>
---

<br>

Task Estimation in Scrum is used in Software Development to estimate the time it will take for a task to be complete. Task Estimation involves all aspect of the Team from software developers to software testers and requires everyone to work together to achieve the goals set out within a set amount of time.

The Scrum Team have Task Estimation Meetings where they estimate the effort required to complete each task in the Task List. The result of this meeting is an Effort Estimated Task List. The Scrum Team uses the Task List to create the Effort Estimated Task List. The Task List is used during Task Estimation Meetings to estimate the effort, people and resources required to complete a task or set of tasks within a Sprint.

<br>

---
### <center> **Story Points/ Planning Poker** </center>
---

<br>

The most commonly used Task Estimation technique in Scrum is the use of story points. Story points are measurement units for expressing an estimate of the effort required to fully implement a task. There is no set value for a story point. The Scrum Team decides on a value for the story points, whether it be an hour, a day or a week. Story points help teams set goals for a period of time and builds unity and commitment to the solution.

<br>

<br>

Story points are generally based around the Fibonacci sequence.  The Fibonacci sequence is a number sequence where every number is the sum of the previous two numbers, i.e. 0, 1, 2, 3, 5, 8, 13, 21 and so on. This technique is known as Planning Poker. In Scrum Planning Poker the Scrum team works to create accurate estimates. The team will take a task from the backlog and team members will mentally calculate an estimate. Each team member will then hold up a card with their estimate.

<br>

---
### <center> **Task Estimation Advantages** </center>
---

<br>

Task Estimations can allow a Team to determine how much work they should bring into a Sprint. This can allow a team to adjust, correct course, get features and their product to the end-user more quickly. This can lead to a project been delivery on time and not going overbudget. It can also help a Team to stay focused as some work well under time constraints which can enhance the learning ability of the developers.

<br>

---
### <center> **Task Estimation Disadvantages** </center>
---

<br>

Task underestimation can hinder work as it can lead to a worker been overwhelmed by time management which can have an adverse effect on their work. Sometimes Task Estimates can be though as a commitment that has to be carried out however things do not always go according to plan and this can result in a team member feeling mentally exhausted thus effecting their decisions. 

<br>

The time required to complete a Task can differ depending on the developer’s level of expertise and this can make some Task Estimation null and void. It is hard to perceive the result of complex tasks and usually these tasks are underestimated which can skew estimations causing undesirable delays in the project. 

<br>

---
### <center> **Conclusion** </center>
---
<br>

In conclusion, task estimation is a vital step in the scrum process. When carried out correctly, it enables teams to have clear goals and set objectives with time frames to reach them. Task estimation involves everyone and decisions are made together, which is very important when working in a team.

<br>

---
### <center> **Articles** </center>
---

<br>

1. [Agile Planning and Estimation: Generally Accepted Scrum Practices](https://www.oreilly.com/library/view/head-first-agile/9781491944684/ch04.html)
2. [How do Scrum Teams Estimate Tasks in a Project?](http://blog.scrumstudy.com/how-do-scrum-teams-estimate-tasks-in-a-project/)
3. [Story points and estimation](https://www.atlassian.com/agile/project-management/estimation)
4. [What is Agile Estimation?](https://www.visual-paradigm.com/scrum/what-is-agile-estimation/)
5. [What Scrum Says About Estimates](https://www.scrum.org/resources/blog/what-scrum-says-about-estimates)

<br>

---
## <center> **Code Review** </center>
---

<p align="center">
  <img src="https://i.imgur.com/3JVclYV.png" alt="Image header"/>

---
### <center> **Authors** </center>
---

<br>

* Mark Grogan
* Conor Baker

<br>

---
### <center> **Introduction** </center>
---

<br>

Code review, also known as Peer Code Review, is a systematic examination of software code. The intention is to find bugs and improve software quality. Code review allows team members maintain a consistency between design and implementation techniques.

<br>


---
### <center> **Why do we code review?** </center>
---

<br>

- Consistent design and implementation

  - Enforces a consistent coding style throughout the project, allowing the source code to be more readable to anyone who might be introduced to the project at any given time during the development.

- Minimizing mistakes and their impact

  - Gives a fresh set of eyes to identify bugs and simple coding errors before the code is pushed to the next step.    

- Ensuring project quality and meeting requirements 

  - Ensures that the scope and requirements of any given software run through the hands of several developers. This serves as a check and balance against different interpretations of the scope of and requirements.

<br>

---
### <center> **Code Review Best Practices** </center>
---

<br>

- When reviewing areas such as style, structure, design, logic and functionality of code it is very important that you know what to look for. A good practice is to keep certain questions in your head as you analyze the code. These questions may be as simple as, do I understand what the code is doing or is the code doing what it is meant to.

- If a coder and reviewer arrive at a disagreement, it is important to know who should win the argument. Many would assume that the more experienced person should have the final say, but adopting a culture where the best argument wins is the best practice. When two solutions are just as good the argument should simply be skipped.

- Never review code for longer than an hour at a time and always review less than 400 lines at a time. After 60 minutes performance is significantly reduced and it will not be your best work. Similarly, when reviewing too many lines at one time, attention to detail is lessened.

- When carrying out a code review, it is important to keep a good relationship between the coder and reviewer. Feedback should be constructive and praise should be given when earned. Mistakes will be made and teammates will be in the wrong, but don't blame or complain as it will get you nowhere. Reviews should be enjoyable and following these practices will make that possible.

<br>
<br> 

<p align="center">
  <img src="https://i.imgur.com/CQWy3og.png" alt="Image header"/>


<br>

---
### <center> **Conclusion** </center>
---

<br>

Code reviews, when done right, can make code reviews more effective and enjoyable while also benefiting code quality, knowledge sharing and team culture. Every project can benefit from code review regardless of the development style and methodology. When it comes to code reviews it is important to remember that no one is the only person who knows a specific part of the code and code reviews help facilitate knowledge sharing across the code base and across the team.


<br>

---
### <center> **Articles** </center>
---

<br>

1. [Investigating the effectiveness of peer code review in distributed software development based on objective and subjective data](https://jserd.springeropen.com/articles/10.1186/s40411-018-0058-0)
2. [Modern code review: a case study at google](https://www.researchgate.net/publication/325730783_Modern_code_review_a_case_study_at_google)
3. [13 Practices for Better Code Reviews](https://www.infoq.com/articles/practices-better-code-reviews/)
4. [9 Code Review Best Practices](https://www.perforce.com/blog/qac/9-best-practices-for-code-review)
5. [Code Review — The Ultimate Guide](https://www.freecodecamp.org/news/code-review-the-ultimate-guide-aa45c358bbf5/) 

 
 <br>
 
---
## <center> **Coding standards** </center>
---

<p align="center">
  <img src="https://1.bp.blogspot.com/-VNfkKRh9nSI/X5ZknrraRRI/AAAAAAAAASw/g7aijFhOGEcVrY2zqth39kvtPAG0POiXgCPcBGAYYCw/w640-h360/Blogging%2BTips%2BLinkedIn%2BPost%2BHeader%2B%25281%2529.png" alt="Image header"/>

---
### <center> **Authors** </center>
---

<br>

* Patrick Corbett
* Conor Baker 

<br>

---
### <center> **Introduction** </center>
---

<br>

>Coding standards are collections of coding rules, guidelines, and best practices. 
=======
# Project Plan

## Content Owners:

<br>

* Project Plan: Eugene & Paddy
* Task Estimation in Scrum: Eugene & Mark
* Coding Standards: Conor & Paddy
* Code Reviews: Conor & Mark

<br>

<br>

<p align="center">
  <img src="https://i.imgur.com/GhMggNe.png" alt="Image header"/>

<br>
<br>

---
### <center> **Why are coding standards important and should they always be enforced** </center>
---

<br>

Without coding standards there would be zero structure and cohesion to a project, this would impede the developer’s ability to work as a team and encourage bugs and errors when work is delegated to multiple developers. However, it is important to remember that 
<br>
> Coding standards are a process, and not a goal
=======

---
## Rules:

<br>

* Users Working on a Section together are to "Approve" each others content before "Merging".
* Comments / Feedback is to be added on "Pull Requests" and also when "Committing" or "Reviewing Changes" before "Approval"


<br>

---

<br>

## GitHub / GitFlow Steps:

<br>

1. Create Repository - Eugene McCormack
2. Inivte users to Repository / Collaborators - Eugene McCormack
3. Accept Inivation (Email Confirmation / Github) - Everyone
4. **Fork Repository** - Everyone
5. Clone Repository to local machine (**forked Copy**) - Everyone
6. Create a Feature Branch e.g. "Code_Standards" - One User Per Section
7. Add Content to Feature Branch - Everyone
8. Stage and Commit Changes Made (Do Not Forget Comments / Description) - Everyone
9. Push Changes to **Fork** - Everyone
10. Enjoy

<br>

---

## Useful Links for GitFlow
---

<br>

[Assignment Details](https://1drv.ms/w/s!Ap4JPbfie2zTg7I12fy6V3s3fmqqVw?e=MxFjr1)

<br>

[Github Setup](https://github.com/neiloconnor/git-flow-exercise/blob/master/walkthrough/1-setup.md)

<br>

[Branching](https://github.com/neiloconnor/git-flow-exercise/blob/master/walkthrough/2-feature-branches.md)

<br>

[Understanding the GitHub Flow](https://guides.github.com/introduction/flow/)

<br>

---

<br>

---
### <center> **Coding Standards Document** </center>
---

<br>

The purpose of a coding standards document is to ensure all code is designed, written, and laid out the same by all contributors. A company’s coding standards guidelines and best practices should be followed by all contributors to code. The purpose is to achieve uniformity. There is no "Right and Wrong" way. Each organization will have their own preferences and techniques that may be unique to the org. Ensuring all contributors are comfortable with the coding standards guideline will result in increase in productivity.

<br>

---
### <center> **Import topics in a Coding Standards Document** </center>
---

<br>

> Naming conventions

Meaningful and understandable variable names help people follow code they have not written. Avoid the use of digits. Names of functions should briefly describe the reason for the function as briefly as possible
> Indentation

Proper indentation helps improves the structure of the code. It is also more pleasing to the eye allowing readers more ease.
>Length of Functions

Functions should be short and precise where possible. Lengthy functions should be split into smaller tasks
>Global variables

Limit the use of global variables where possible

<br>

---
### <center> **Conclusion** </center>
---

<br>

In sum, its vital that we understand the importance of coding standards not as a textbook set of rules, but as an adaptive and contingent method that moulds to the needs of the project. Coding Standards excel based on consistency and while some of its strengths come from a level of stability they still constantly need to be revisited and updated. This leads to an ever-growing process that allows developers to ask, not whether coding standards should be enforced, but instead ask how appropriate certain standards are to their given project. 
<br>
<br>

---
### <center> **Articles** </center>
---

<br>
=======

1. [Why You Need Coding Standards](https://www.sitepoint.com/coding-standards/) 
2. [Write Better Code with Coding Standards](https://levelup.gitconnected.com/write-better-code-with-coding-standards-546faf3fd4d1)
3. [Coding Standards and Development: A General Overview](https://blog.acromedia.com/coding-standards-and-development-a-general-overview)
4. [Creating a coding standards document](https://softwareengineering.stackexchange.com/questions/196706/creating-a-coding-standards-document#:~:text=A%20coding%20standards%20document's%20purpose,to%20read%20someone%20else's%20style.)
5. [Coding Standards and Guidelines](https://www.geeksforgeeks.org/coding-standards-and-guidelines/#:~:text=A%20coding%20standard%20gives%20a,helps%20to%20detect%20error%20easily.) 

<br>


---
=======

