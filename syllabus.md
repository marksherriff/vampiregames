---
layout: default
title: Syllabus
nav_order: 2
---

# Course Syllabus
{: .no_toc }

## Table of Contents
{: .no_toc .text-delta }

1. TOC
{:toc}

## Basic Info
{: .no_toc }
SLAV 2500: Topics in Slavic Literature and Culture   
_Topic: Bits & Bytes: Exploring Vampires in Video Games_   
Spring 2025 Semester   
https://vampiregames.org   

## Lecture
{% for section in site.data.semesterinfo.lecture_sections %} {{ section }}    
{% endfor %}   
## Staff Information

{% for professor in site.data.professors %}

__Instructor:__ {{ professor.name }}   
Office: {{ professor.office }}   
Office Hours: {{ professor.office_hours }}        
Email: [{{ professor.email }}]({{ professor.email }})   
Website: [{{ professor.website }}]({{ professor.website }})     

{% endfor %}

__Teaching Assistants:__ {% for ta in site.data.tas %} {{ ta.name }}, {% endfor %}  

{: .warning }
This is a course on VAMPIRES. We will be discussing blood, corpses, death, murder, and all the things that make the human race interesting and terrifying! If you are concerned the content may disturb you, it probably will!

## Communication and Logistics

### Textbook / Online Coursepack
{: .no_toc }

* There is no official textbook for the course that you need to purchase.  We will make resources available to you during the semester.
* We will be utilizing the Top Hat interactive platform for class slides, in-class participation questions, and pop quizzes.  More information on joining the Top Hat instance for the course will be available in Canvas.

### Piazza
{: .no_toc }

Piazza @ [{{ site.data.externallinks.piazza }}]({{ site.data.externallinks.piazza }})    

We will be using Piazza for the following:

* Long-form questions about the class, code, or project (please post all code privately!)
* Private messages for faculty or the entire staff
* A searchable repository of common questions in the course about the project, assignments, etc.

### Email
{: .no_toc }

We will be using email for the following:

* Personal issues that can and should only be handled by a professor

We will not be using email for:

* Tech help (use Piazza)
* Project questions (use Piazza)

_PLEASE_ make sure to put "SLAV 2500" in the subject line somewhere so we can keep track of your request!  And please be patient with us in responding.  We all receive A LOT of email and it's easy to get behind.  If there is a time-critical nature to your note, please let us know that as well.

### GitHub
{: .no_toc }

Class GitHub Organization @ [{{ site.data.externallinks.github_organization }}]({{site.data.externallinks.github_organization}})

Students with experience with source control management through GitHub are strongly encouraged to use the class GitHub organization.  Access will be made available before the first programming assignment.

Students with no experience with source control management are welcome to learn, but it is not required.

### Where or who do I ask about...?
{: .no_toc }

* Office hours (TAs and Professors) -> See Canvas for information
* Technical questions -> Piazza, TA office hours, Prof. Sherriff's office hours
* Project requirements -> Piazza or office hours
* Reassessment of graded work -> Gradescope (office hours only if issues with Gradescope, such as a non-submission)
* Personal issues -> Email the professors

## Course Description
This class will explore the origins of the vampire in the world of video games and how original folklore, over time, was altered. This will include an overview of the vampire’s movement into popular culture from old belief, how it first entered video games, and the most culturally significant games starting in the late 1970s and entering the modern era. Students will have the opportunity to explore both literature and video games to analyze how vampires and the lore surrounding them is represented and, through this, create a final portfolio that includes a literature and game review and a game they make themselves.

### Course Objectives
{: .no_toc }   
Upon completion of this course students will:

- Explore the origins of the vampire in the world of video games and how original folklore, over time, was altered. This will include an overview of the vampire’s movement into popular culture from old belief, how it first entered video games, and the most culturally significant games starting in the late 1970s and entering the modern era.
- Understand the basics of game development, particularly around concepts of world building and mental models.
- Understand the "game loop," - the steps a game must take to update the screen at roughly 60 frames a second, including:
  - Physics and collision detection
  - Game AI
  - Player input and control
  - Basic drawing algorithms


### Course Topics
{: .no_toc }    
The topics to be covered in the course include:  

Vampire topics:
- What is the vampire? How did it enter popular culture?
- Early PC and Console Vampires
- The Castelvania Revolution
- The Vampire of Video Games through the End of the 20th Century
- The New Vampire for the New Century
- Modern-Day Vampires in Video Games

Game Design topics:
- What exactly is a “game?”  How is it different from other media?
- World Building
- The Game Loop
- Collision Detection and Physics
- Game AI
- Play Testing


## Course Requirements
{: .no_toc }
You should meet the following requirements to take this class:

1. Be excited to learn about the history of vampires in video games!  
2. Understand and accept the content warning above.  We will be discussing, reading about, and playing video games that deal with vampires, blood, mythical creatures, death, resurrection, etc.  If this makes you uncomfortable, you may wish to consider a different course.  We cannot make content accommodations for this course.
3. No programming experience is required.  However, it is recommended that you have some exposure with some basic programming concepts, such as variables, methods/functions, loops, and if/else statements.  Opportunities to learn these concepts will be made available as optional work.
4. Students who have completed CS 4730: Computer Game Design can still take this course for credit.

## How Does This Course Count?

- BA in Computer Science Majors: This course has been approved as an Integration Elective.  You will have to submit a request after you have completed the course, but it will be automatically approved.
- Other College Majors: Check with your department, SIS, or Stellic.
- All Engineering Majors: This course counts as either a HSS Elective or an Unrestricted Elective.
- All Other Schools: Check with your school, SIS, or Stellic.

## Assessment and Grading
We will utilize a positive-reinforcement grading policy in this course. As you learn more about vampires and video games, you will earn experience points (XP). Every student begins the course with 0 XP.  As you complete assessments, work on the project, and complete other activities, you will earn XP.  


| Assessment             | Who        | Max XP Avail |
| :--------------------- | :--------- | :----------- |
| Game Critical Analyses | Individual | 200          |
| Literature Review      | Individual | 100          |
| Game Engine Tutorial   | Individual | 100          |
| Game Design Doc        | Team       | 50           |
| Top Hat Activities     | Individual | 250          |
| Game Project           | Team       | 300          |
| __Total Course XP__    |            | 1000         |

| Letter Grade | XP Required |
| ------------ | ----------- |
| A+           | 1000        |
| A            | 950         |
| A-           | 900         |
| B+           | 875         |
| B            | 850         |
| B-           | 825         |
| C+           | 775         |
| C            | 750         |
| C-           | 700         |
| D+           | 675         |
| D            | 650         |
| D-           | 625         |

### Assessment Notes
{: .no_toc }

* Bits and Bytes is an interactive course. If you were signed up for the course before the first day of class, you will have received an email from Top Hat with instructions and a special code to utilize their app to join the course. This is REQUIRED to participate in the course. It gives you access to slides during class, as well as interactive questions that appear during lecture. Access can be with any device such as a smartphone, tablet, laptop, or PC, the last obviously only for home usage. There are NO outside texts to pay for; your payment is entirely processed by Top Hat or through Inclusive Access (if you’re using the latter). Lectures include questions that require your participation and are part of your grade. They involve points based on participation (meaning there is no correct answer) or in combination with correctness points.
* Students will author three papers during this course: two critical analyses of video games that they have played that deal with vampires and one literature review of the origins and evolution of some aspect of vampyrism.
* Students will build two games during this course: one small game to learn the game engine and a team project that will be the final project for the course.

## Class Management

### Late Policy

The following late policies apply to the specified assignments.

- _Literature Review, Critical Analysis #1 and #2, Game Design Document, and Game Engine Tutorial:_ An extension of up to five calendar days may be requested for any reason by filling out the appropriate Google form with the assignment. No extensions will be given beyond what is requested through this form. SDAC students should use this form if they have modified deadlines to request their extension.
- _Team Game Project:_ As the final major submission of the semester on the last day, no extensions can be granted automatically.  Teams that feel that will not make this deadline need to reach out to the professors as soon as possible.  Our most likely response will be "turn in what you have."
- _Top Hat Activities:_ Students who miss class will inevitably miss some XP earned through Top Hat that day.  These points cannot be made up later, even if the class day was missed for a valid reason.  That said, these are low-stakes activities and there will be ample opportunities to earn the needed XP.  Students who miss only a couple days during the semester will have no problem earning enough XP. 


### This Syllabus
{: .no_toc }
This syllabus is to be considered a reference document that can and will be adjusted through the course of the semester to address changing needs. This syllabus can be changed at any time without notification. It is up to the student to monitor this page for any changes. Final authority on any decision in this course rests with the professor, not with this document.

### Professionalism
{: .no_toc }
Students and staff are all expected to treat each other with respect.  This includes, but certainly is not limited to:

* Proper use of class platforms (Top Hat, Discord, Piazza, YouTube comments, etc.)
* Respectful behavior in class (including extraneous internet browsing, social media, phone usage, etc.)
* Respectful language or actions to course staff or other students
* Promptness for all deadlines and class meetings
* Quality work
* Working well with your partners
* Following the honor code and other collaboration policies

Students can and will be penalized for unprofessional behavior.

## Academic Integrity
_Summary_:

* Know the honor code
* Work with your team, but not any other team
* Using code from other students (from any semester) is an honor violation
* Using publically-available example code and libraries is fine, but you must cite your resources
* More information on what is allowed will be included with each assignment if necessary
* It never hurts to ask the staff what is allowed or not allowed!

We firmly endorse, uphold, and embrace the University’s Honor principle that students will not lie, cheat, or steal, nor shall they tolerate those who do. We recognize that even one honor infraction can destroy an exemplary reputation that has taken years to build. Acting in a manner consistent with the principles of honor will benefit every member of the community both while enrolled in the Engineering School and in the future. 

Students are expected to be familiar with the university honor code, including the section on academic fraud [http://honor.virginia.edu/academic-fraud](http://honor.virginia.edu/academic-fraud). Assessments will describe allowed collaborations, and deviations from these will be considered Honor violations. If you have questions on what is allowable, ask! Unless otherwise noted, all assessments will be considered pledged that you have neither given nor received help. (Among other things, this means that you are not allowed to describe problems on an exam, assignment, or project to a student who has not taken it yet. You are not allowed to show exam papers to another student or view another student’s exam papers while working on an exam.) Sending, receiving, or otherwise copying or describing the contents of electronic files that are part of course assignments are not allowed collaborations (except for those explicitly allowed in assignment instructions). 

Assignments or exams where honor infractions or prohibited collaborations occur will receive a zero grade for that entire assignment or exam. Such infractions will also be submitted to the Honor Committee if that is appropriate. Students who have had prohibited collaborations may not be allowed to work with partners on remaining homeworks. 

In general, we expect that you will be using code, examples, and ideas from many different websites and resources for your projects.  This is allowed within reason.  Wholesale copying of an entire project or any major feature from any source (the web, another student, etc.) is definitely not allowed.  Using code snippts that you find to round out a feature is allowed.  If you ever have a question about what is or is not appropriate, ask first!

In ALL cases, you need to cite all sources at the top of the file where the code or algorithm was used AND you should note all sources in your documentation.  Failure to properly attribute your sources will result in a 50% penalty for the project at a minimum.

## Policy on Use of Generative AI
{: .no_toc }
_With respect to the coding portions of this class:_ In general, we will treat the use of generative AI the same as we would a student asking for help on StackOverflow or finding other sources of code.  For coding questions (i.e. "How do I a sprite move left in Godot?"), students are welcome to use generative AI.  This includes tools such as ChatGPT, GitHub Copilot, and other code completion systems.  

_With respect to the writing portions of this class:_ We care much more about your experiences with the literature and material than the opinion of an AI system.  Please refrain from using generative AI for the composition of creative written work in this course.  Use of AI for written assignments can result in a failure for the course.

## Miscellaneous Policies

### Inclement Weather Policy
{: .no_toc }
If there is the possibility of inclement weather that could affect class, it is your responsibility to stay informed.  Information about how to sign up for email and/or text alerts from UVA Emergency Management, along with the current University status, can be found at [https://uvaemergency.virginia.edu/](https://uvaemergency.virginia.edu/).

### SDAC / Students with Disabilities or other Learning Needs
{: .no_toc }
It is our goal to create a learning experience that is as accessible as possible. If you anticipate any issues related to the format, materials, or requirements of this course, please make an appointment to with your instructor outside of class so we can explore potential options. Students with disabilities may also wish to work with the Student Disability Access Center (SDAC) to discuss a range of options to removing barriers in this course, including official accommodations. For general questions please visit the SDAC website: [sdac.studenthealth.virginia.edu](http://sdac.studenthealth.virginia.edu). 

__Policies for Common Accommodations__

- _Alternative Testing:_ As we will not have tests, quizzes, or exams in this course, the extended time do not apply.  If a student requires a reduced distraction environment in the classroom, they should speak with the professors about specific seating during lecture.  There will be in-class questions taken in Top Hat ranging from multiple choice to short paragraph in length.  Students who have issues completing these during the class session should reach out to the professors to discuss alternatives.
- _Reasonable Modification of Assignment Deadlines:_ Students who have extended time for assignments should complete the extension forms found with all individual assignments in Canvas to have their extensions applied.  No further extensions will be granted beyond the five days allotted as this is already more than SDAC guidance indicates.
- _Reasonable Modification of Course Attendance Policy:_ Students with this accommodation should inform the professor of a given missed lecture that they will be missing due to their accommodation via email so we can adjust points in Top Hat accordingly.  Please remember that the standard accommodation is 4 allotted absences.
- _Notetaking:_ If there are students with the notetaking accommodation, we will announce to the class asking for volunteers.  We do not give extra credit for volunteer notetakers.  Once a notetaker volunteers has been identified, the process is passed off to SDAC and questions/concerns should be addressed to them.


If you have other special circumstances (athletics, other university-related activities, etc.), please contact the instructor as soon as you know these may affect you in class.

### Health Accommodations
{: .no_toc }
It is in the best interest of everyone in our community to keep the spread of infectious disease to a minimum.  If you are ill, please do not come to class.  Lectures from previous semesters will be made available along with the course materials on the course pack and you can follow along there.  Quiz accommodations can be made on a case-by-case basis.  Due to their team-based nature, certain Guided Practices cannot be made up, but we build in a free drop into the Guided Practice grading to handle these cases.  If a student must miss an excessive number of Guided Practices, they should meet with the instructor to discuss options.

### Religious Accommodations
{: .no_toc }
It is the University's long-standing policy and practice to reasonably accommodate students so that they do not experience an adverse academic consequence when sincerely held religious beliefs or observances conflict with academic requirements.

Students who wish to request academic accommodation for a religious observance should submit their request to their instructor by email as far in advance as possible. Students who have questions or concerns about academic accommodations for religious observance or religious beliefs may contact the University’s Office for Equal Opportunity and Civil Rights (EOCR) at [UVAEOCR@virginia.edu](mailto:UVAEOCR@virginia.edu) or 434-924-3200.

Accommodations do not relieve you of the responsibility for completion of any part of the coursework - including the team project - missed as the result of a religious observance.

### Support for Career Development
{: .no_toc }
Engaging in your career development is an important part of your student experience. For example, presenting at a research conference, attending an interview for a job or internship, or participating in an extern/shadowing experience are not only necessary steps on your path but are also invaluable lessons in and of themselves. We wish to encourage and support you in activities related to your career development. To that end, please notify your instructor by email as far in advance as possible to arrange for appropriate accommodations.

### Harassment, Discrimination, and Interpersonal Violence
{: .no_toc }
The University of Virginia is dedicated to providing a safe and equitable learning environment for all students. If you or someone you know has been affected by power-based personal violence, more information can be found on the [UVA Sexual Violence website](http://www.virginia.edu/sexualviolence) that describes reporting options and resources available.  

The same resources and options for individuals who experience sexual misconduct are available for discrimination, harassment, and retaliation.  [UVA prohibits discrimination and harassment](https://uvapolicy.virginia.edu/policy/HRM-009) based on age, color, disability, family medical or genetic information, gender identity or expression, marital status, military status, national or ethnic origin, political affiliation, pregnancy (including childbirth and related conditions), race, religion, sex, sexual orientation, veteran status. [UVA policy](https://uvapolicy.virginia.edu/policy/HRM-010) also prohibits retaliation for reporting such behavior. 

If you witness or are aware of someone who has experienced prohibited conduct, you are encouraged to submit a report to [Just Report It](https://justreportit.virginia.edu/) (justreportit.virginia.edu) or [contact EOCR](mailto:UVAEOCR@virginia.edu), the office of Equal Opportunity and Civil Rights.

If you would prefer to disclose such conduct to a confidential resource where what you share is not reported to the University, you can turn to [Counseling & Psychological Services (“CAPS”)](https://www.studenthealth.virginia.edu/caps) and [Women’s Center Counseling Staff and Confidential Advocates](https://womenscenter.virginia.edu/confidential-advocates) (for students of all genders).  

As your professor and as a person, know that I care about you and your well-being and stand ready to provide support and resources as I can. As a faculty member, I am a responsible employee, which means that I am required by University policy and by federal law to report certain kinds of conduct that you report to me to the University's Title IX Coordinator. The Title IX Coordinator's job is to ensure that the reporting student receives the resources and support that they need, while also determining whether further action is necessary to ensure survivor safety and the safety of the University community. 
