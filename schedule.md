---
layout: default
title: Schedule
nav_order: 3
---

# Course Schedule
{: .no_toc }

1. TOC
{:toc} 

## Lecture Schedule

<table class="schedtab"><thead>
<tr>
    <th>Date</th>
    <th>Topic</th>
    <th>Due Dates</th>
    </tr>
    </thead>
    <tbody>
{% for day in site.data.lectureschedule %}
{% if day.type == 'holiday' %}
<tr class="holiday">
{% elsif day.type == 'quiz' %}
<tr class="quiz">
{% else %}
<tr>
{% endif %}
<td class="text-center sched">{{day.date}}</td>
<td class="sched">
{% if day.coursepack %}
<a href="{{day.coursepack}}">
{% endif %}
{{day.topic}}
{% if day.coursepack %}
    </a>
{% endif %}
{% if day.topic2 %}
&
{% if day.coursepack2 %}
<a href="{{day.coursepack2}}">
{% endif %}
{{day.topic2}}
{% if day.coursepack2 %}
    </a>
{% endif %}
{% endif %}
<br>
<em>Instructor: 
{{day.instructor}}
</em>
</td>
<td class="sched">
{% if day.due %}
{% if day.due_link%}
<a href="{{day.due_link}}">
{% endif %}
{{day.due}}
{% if day.due_link%}
</a>
{% endif %}
{% endif %}
{% if day.due2 %}
<br>
{% if day.due_link2%}
<a href="{{day.due_link2}}">
{% endif %}
{{day.due2}}
{% if day.due_link2%}
</a>
{% endif %}
{% endif %}
</td>
</tr>
{% endfor %}
</tbody></table>

## Project Schedule Overview

_Schedule is tentative and subject to change!_

* Jan 12-18: Beginning of class
* Jan 19-25: History of vampires and games
* Jan 26-Feb 1: Background research
* Feb 2-8: Consider various vampire mechanics & start Critical Analysis of game
* Feb 9-15: Work on Critical Analysis
* Feb 16-22: Work on Critical Analysis
* Feb 23-Mar 1: ritical Analysis Due
* Mar 2-8: Learning about game engines in class / work on game tutorials
* Mar 9-15: Spring Break
* Mar 16-22: Form groups and choose topics
* Mar 23-29: Background research and work on game design
* Mar 30-Apr 5: Work on projects
* Apr 6-12: Work on projects
* Apr 13-19: Project checkpoint
* Apr 20-26: Work on projects
* Apr 28: Game Expo & Projects Due



## Office Hours Calendar

_Coming Soon!_