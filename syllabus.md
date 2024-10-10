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
This is a course on VAMPIRES. We will be discussing blood, corpses, death, murder, and all the things that make the human race interesting and terrifying! If you are concerned the content may disturb you it probably will!

## Communication and Logistics

### Textbook / Online Coursepack
{: .no_toc }

There is no official textbook for the course that you need to purchase.  We will make resources available to you during the semester.

### Piazza
{: .no_toc }

Piazza @ [{{ site.data.externallinks.piazza }}]({{ site.data.externallinks.piazza }})    

We will be using Piazza for the following:

* Long-form questions about the class, code, or project (please post all code privately!)
* Private messages for faculty or the entire staff
* A searchable repository of common questions in the course about the project, assignments, etc.

We will not be using Piazza for:

* Reassessment of graded work (use Gradescope)

### Email
{: .no_toc }

We will be using email for the following:

* Personal issues that can and should only be handled by a professor
* Team issues that need to be escalated beyond the TA

We will not be using email for:

* Reassessment of graded work (use Gradescope)
* Tech help (use Piazza)
* Project questions (use Piazza)

You should, in general, email the professor for the section that you are enrolled in.  _PLEASE_ make sure to put "SLAV 2500" in the subject line somewhere so we can keep track of your request!  And please be patient with us in responding.  We all receive A LOT of email and it's easy to get behind.  If there is a time-critical nature to your note, please let us know that as well.

### Where or who do I ask about...?
{: .no_toc }

* Online office hours (TA) -> See Canvas for information
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

Game Design topic weeks:
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
3. No programming experience is required.  However, it is _highly_ recommended that you have some exposure with some basic programming concepts, such as variables, methods/functions, loops, and if/else statements.  Opportunities to learn these concepts will be made available as optional work.
4. Students who have completed CS 4730: Computer Game Design can still take this course for credit.

## How Does This Course Count?

- BA in Computer Science Majors: This course has been approved as an Integration Elective.  You will have to submit a request after you have completed the course, but it will be automatically approved.
- All Engineering Majors: This course counts as either a HSS Elective or an Unrestricted Elective.

## Assessment and Grading
We will utilize a positive-reinforcement grading policy in this course. As you learn more about vampires and video games, you will earn experience points (XP). Every student begins the course with 0 XP.  As you complete assessments, work on the project, and complete other activities, you will earn XP.  

| Assessment	| Who	| Instances	| Max XP 	| Max XP Avail |
|:--------------|:-----|:---|:-----|:-----|
|Critical Analysis |  Individual |	1 |	150 |	150 |
|Literature Review |	Individual |	1 |	150 |	150 |
|Game Design Doc |	Team |	1 |	50 |	50 |
|Random Encounters |	Individual |	10 |	5 |	50 |
|Class Portfolio |	Team |	1 |	200 |	200 |
|Game Project | Team | 1 | 200 | 200 |
|Examx |	Individual |	2 |	100 |	200 |
| __Total Course XP__ | | | | 1000 |

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

* Your one lowest Random Encunter is converted to 5 XP (full points) at the end of the semester.  This should primarily be used in case you are ill or must miss class for some other reason. 
* Due to the nature of most in-class Random Encounters, these cannot be made up if they are missed.  However, please note that these are relatively low-stakes and missing an additional Random Encounter is not going to have an outsized effect on your final grade.
* Students who miss a quiz due to a reason approved by a professor can make up the quiz only before it is returned to the class after it has been graded.  If it is not possible for a student to do this, they will be allowed to make up extra XP on the final exam for the missed quiz.
* We expect __all students__ to __fully participate__ in the coding of the project.  This includes:
  - Working successfully with other team members
  - Attending team meetings
  - Collaborating with team members
* Students who do not fully participate in the project per the information above will have XP _removed_ from various team-related scores, including the sprint scores, final team project score, and team evaluation score.  We do this because if the student did not fully participate, then that XP was not properly assigned because they gained no experience through the work.  Removing XP will be represented as a negative team evaluation score in Canvas so as to make the penalty clear to the staff and student.
* _Failure to participate in the team project can result in automatically failing the course, regardless of other assessment scores._

### Reassessment Policy
{: .no_toc }
You may request a reassessment of any graded work in this course, subject to the following conditions:

- Students may only request the reassessment of returned coursework in writing via Gradescope. A verbal appeal is not appropriate and will not be accepted nor will requests made through other methods (e.g. email, office hours, etc.).  If a follow up is necessary, we will reach out to you to come to office hours to provide additional information. All reassessment requests will be handled by the instructors (except for programming assessments, such as Django Practice).
- Reassessment requests will open 24 hours after grades are released and will close 7 days after a grade has been released.
- Students must provide a written rationale for requesting reassessment, with specific reference to: the learning outcomes, assessment rubric, qualitative grade descriptors, and any feedback provided to you.
- Reassessment requests that are based on feeling or hearsay rather than information indicated above will not be considered and no further reassessment may be made. Examples include: "I feel you graded this too harshly", "My friend did the same thing and got a better score", etc.
- Students who submit an item for reassessment are advised that the entire work will may be reconsidered and that the result of the reassessment may be that the grade will increase, stay the same, or decrease accordingly.
- Graded work may only be reassessed once -- you may not request reassessment a second time for the same item/problem and any changes to the grade made during reassessment will be final.


### Final Exam and Project Demos
{: .no_toc }

_More info coming soon!_

## Class Management

### Project Groups
{: .no_toc }
You are expected to work as a member of your group in this course and cooperate with your colleagues. Cooperation means attending group meetings, completing your assignments properly and on time, letting your group know if you will be out of contact, responding to e-mail from your group, and so on. If there is a lack of cooperation by any group member, it must be brought to the attention of the instructor as soon as it happens. If the lack of cooperation is serious, the offending group member’s semester grade will be lowered (see information above under Assessment).  _Note that this can result in a student automatically failing the course!_

### Attendance
{: .no_toc }
* No attendance will be taken during the lectures sessions.  
* We do not plan to record lectures this semester to better encourage attendance and participation.

### Late Policy
{: .no_toc }
_TBD_

### This Syllabus
{: .no_toc }
This syllabus is to be considered a reference document that can and will be adjusted through the course of the semester to address changing needs. This syllabus can be changed at any time without notification. It is up to the student to monitor this page for any changes. Final authority on any decision in this course rests with the professor, not with this document.

### Professionalism
{: .no_toc }
In this course, there will be a focus on working well together and learning about the development process. A large portion of that process involves interpersonal skills and conflict management. Students and staff are all expected to treat each other with respect.  This includes, but certainly is not limited to:

* Proper use of class platforms (Discord, Piazza, YouTube comments, etc.)
* Respectful behavior in class (including extraneous internet browsing, social media, phone usage, etc.)
* Respectful language or actions to course staff or other students
* Promptness for all deadlines and class meetings
* Quality work
* Working well with your partners
* Following the honor code and other collaboration policies
* Following any University health and safety regulations

Students can and will be penalized for unprofessional behavior.  This will be represented as a negative XP score on the Team/Staff Evaluation.

## Academic Integrity
_Summary_:

* Know the honor code
* Work with your team, but not any other team
* Using code from other students (from any semester) is an honor violation
* Using publically-available example code and libraries is fine, but you must cite your resources
* More information on what is allowed will be included with each assignment if necessary
* It never hurts to ask the staff what is allowed or not allowed!

The School of Engineering and Applied Science relies upon and cherishes its community of trust. We firmly endorse, uphold, and embrace the University’s Honor principle that students will not lie, cheat, or steal, nor shall they tolerate those who do. We recognize that even one honor infraction can destroy an exemplary reputation that has taken years to build. Acting in a manner consistent with the principles of honor will benefit every member of the community both while enrolled in the Engineering School and in the future. 

Students are expected to be familiar with the university honor code, including the section on academic fraud [http://honor.virginia.edu/academic-fraud](http://honor.virginia.edu/academic-fraud). Assessments will describe allowed collaborations, and deviations from these will be considered Honor violations. If you have questions on what is allowable, ask! Unless otherwise noted, all assessments will be considered pledged that you have neither given nor received help. (Among other things, this means that you are not allowed to describe problems on an exam, assignment, or project to a student who has not taken it yet. You are not allowed to show exam papers to another student or view another student’s exam papers while working on an exam.) Sending, receiving, or otherwise copying or describing the contents of electronic files that are part of course assignments are not allowed collaborations (except for those explicitly allowed in assignment instructions). 

Assignments or exams where honor infractions or prohibited collaborations occur will receive a zero grade for that entire assignment or exam. Such infractions will also be submitted to the Honor Committee if that is appropriate. Students who have had prohibited collaborations may not be allowed to work with partners on remaining homeworks. 

In general, we expect that you will be using code, examples, and ideas from many different websites and resources for your projects.  This is allowed within reason.  Wholesale copying of an entire project or any major feature from any source (the web, another student, etc.) is definitely not allowed.  Using code snippts that you find to round out a feature is allowed.  If you ever have a question about what is or is not appropriate, ask first!

In ALL cases, you need to cite all sources at the top of the file where the code or algorithm was used AND you should note all sources in your documentation.  Failure to properly attribute your sources will result in a 50% penalty for the project at a minimum.

## How to Cite Code
{: .no_toc }
Use the following general format as an example for citing code you use. You may not have all of these fields available, but this should give you a good idea of things to look for.  Use the appropriate commenting format for the programming language of your source code.  Does yours have to look *exactly* like this?  No, it just has to have enough to give the proper credit and so we can find the resource if needed.

```
/***************************************************************************************
*  REFERENCES
*  Title: <title of program/source code>
*  Author: <author(s) names>
*  Date: <date>
*  Code version: <code version>
*  URL: <where it's located>
*  Software License: <license software is released under>
*
*  Title: ....
*
***************************************************************************************/
```

## Policy on Use of Generative AI
{: .no_toc }
_TBD_

## Miscellaneous Policies

### Inclement Weather Policy
{: .no_toc }
If there is the possibility of inclement weather that could affect class, it is your responsibility to stay informed.  Information about how to sign up for email and/or text alerts from UVA Emergency Management, along with the current University status, can be found at [https://uvaemergency.virginia.edu/](https://uvaemergency.virginia.edu/).

### SDAC / Students with Disabilities or other Learning Needs
{: .no_toc }
It is our goal to create a learning experience that is as accessible as possible. If you anticipate any issues related to the format, materials, or requirements of this course, please make an appointment to with your instructor outside of class so we can explore potential options. Students with disabilities may also wish to work with the Student Disability Access Center (SDAC) to discuss a range of options to removing barriers in this course, including official accommodations. For general questions please visit the SDAC website: [sdac.studenthealth.virginia.edu](http://sdac.studenthealth.virginia.edu). 

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

### Community and Identity
{: .no_toc }
The [Center for Diversity in Engineering](https://engineering.virginia.edu/about/diversity-and-engagement/center-diversity-engineering) (CDE) is a student space dedicated to advocating for underrepresented groups in STEM. It exists to connect students with the academic, financial, health, and community resources they need to thrive both at UVA and in the world.  The CDE includes an open study area, event space, and staff members on site. Through this space, we affirm and empower equitable participation toward intercultural fluency and provide the resources necessary for students to be successful during their academic journey and future careers.

### Harassment, Discrimination, and Interpersonal Violence
{: .no_toc }
The University of Virginia is dedicated to providing a safe and equitable learning environment for all students. If you or someone you know has been affected by power-based personal violence, more information can be found on the [UVA Sexual Violence website](http://www.virginia.edu/sexualviolence) that describes reporting options and resources available.  

The same resources and options for individuals who experience sexual misconduct are available for discrimination, harassment, and retaliation.  [UVA prohibits discrimination and harassment](https://uvapolicy.virginia.edu/policy/HRM-009) based on age, color, disability, family medical or genetic information, gender identity or expression, marital status, military status, national or ethnic origin, political affiliation, pregnancy (including childbirth and related conditions), race, religion, sex, sexual orientation, veteran status. [UVA policy](https://uvapolicy.virginia.edu/policy/HRM-010) also prohibits retaliation for reporting such behavior. 

If you witness or are aware of someone who has experienced prohibited conduct, you are encouraged to submit a report to [Just Report It](https://justreportit.virginia.edu/) (justreportit.virginia.edu) or [contact EOCR](mailto:UVAEOCR@virginia.edu), the office of Equal Opportunity and Civil Rights.

If you would prefer to disclose such conduct to a confidential resource where what you share is not reported to the University, you can turn to [Counseling & Psychological Services (“CAPS”)](https://www.studenthealth.virginia.edu/caps) and [Women’s Center Counseling Staff and Confidential Advocates](https://womenscenter.virginia.edu/confidential-advocates) (for students of all genders).  

As your professor and as a person, know that I care about you and your well-being and stand ready to provide support and resources as I can. As a faculty member, I am a responsible employee, which means that I am required by University policy and by federal law to report certain kinds of conduct that you report to me to the University's Title IX Coordinator. The Title IX Coordinator's job is to ensure that the reporting student receives the resources and support that they need, while also determining whether further action is necessary to ensure survivor safety and the safety of the University community. 


