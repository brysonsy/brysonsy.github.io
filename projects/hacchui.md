---
layout: project
type: project
image: images/hacchui.png
title: HACC-Hui
permalink: projects/hacchui
# All dates must be YYYY-MM-DD format!
date: 2020-12-15
labels:
  - ICS 414
  - React
  - Meteor
summary: A website developed to help participants of the Hawaii Annual Code Challenge with team formation.
---

With over 200 developers attending the initial <a href="https://hacc.hawaii.gov/">Hawaii Annual Code Challenge</a> kick-off, there was a need for a better way to simplify the formation and management of teams between developers. Especially with the pandemic, which made it difficult for developers to meet and form teams in person. This all lead to the creation of <a href="https://hacchui.ics.hawaii.edu/#/">HACC-Hui</a>, a website to help HACC participants to gather members to form teams, which was created with React, Meteor, MongoDB, and Semantic-UI.

<img class="ui image" src="../images/hacchuilanding.png">

At the beginning of the semester we were initially split into groups of 4-5 people where each group would create a different version of the website that would fulfill the requirements for the milestone we were working on at the time. At the start of each milestone each team would fork the master HACC-Hui repo into their respective team's organization. Then each team would work on implementing the user stories from each <a href="https://hacc-hui.github.io/docs/requirements/milestone1/">milestone</a> and at the end of the milestone's deadline our professor chose the implementation of the milestone that would be added to the original master repository of HACC-Hui. Though this changed after the third milestone, where instead of each team working separately on the same milestone, we would all work on the master repository to implement the final features that the last milestone required.

<img class="ui image" src="../images/MilestoneFlow.png">

## Milestone 1

For the <a href="https://hacc-hui.github.io/docs/requirements/milestone1">first milestone</a> our team decided to make a design mockup for website in order to have a cohesive user interface. After that we all assigned ourselves an issue that the milestone had. The one I was responsible for was US-D4: Create Team, which involved the creation of a team form where users could submit the information for a team they wished to create, and when the submit button was clicked this information would be added to the team collection. While creating the user interface for the add team page was fairly simple, working with the collections component of the page was a lot more difficult. The main issue was my unfamiliarity and inexperience when working with the collections. As I was not sure how to add the data that needed to be added like the challenges, skills, and tools of the team into the collection for that team. Though eventually I was able to get it to work after gaining a deeper understanding of how the collection worked.

<img class="ui image" src="../images/milestone1.png">

Relevant Links:

<a href="https://github.com/Team-CCC/HACC-Hui/blob/issue-3/app/imports/ui/pages/CreateTeam.jsx">Create Team Page</a>

<a href="https://github.com/Team-CCC/HACC-Hui/projects/1">Milestone 1 Project Board</a>

## Milestone 2

