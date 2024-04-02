# Sample Project

This is an example of how teams can structure their project repositories and format their project README.md file.

## Files and folders in your project repository

This template provides the following suggested organizaiton structure for the project repository, but each project team is free to organize their repository as they see fit.

* **`contributors/`**
<br> Each team member can create their own folder under contributors, within which they can work on their own scripts, notebooks, and other files. Having a dedicated folder for each person helps to prevent conflicts when merging with the main branch. This is a good place for team members to start off exploring data and methods for the project.
* **`notebooks/`**
<br> Notebooks that are considered delivered results for the project should go in here.
* **`scripts/`**
<br> Helper utilities that are shared with the team should go in here.
* `.gitignore`
<br> This file sets the files that will be globally ignored by `git` for the project. (e.g. you may want git to ignore temporary files or large data files)
* `environment.yml`
<br> `conda` environment description needed to run this project.
* `README.md`
<br> Description of the project (see suggested headings below)

# Recommended content for your README.md file:

(you can remove the content here and above from your final project README.md file so that it begins with the Project or Team Name title below)

# Project or Team Name

## Project Title and Introduction

Brief introduction describing the proposed work.

### Collaborators

List all participants on the project.

* Project lead
* Team member
* Team member
* Team member
* ...

### The problem

What problem are you going to explore? Provide a few sentences. If this is a technical exploration of software or data science methods, explain why this work is important in a broader context and specific applications of this work. To get some ideas, see example use cases on the GeoSMART website [here](https://geo-smart.github.io/usecases).

### Specific questions / project goals

List the specific tasks you want to accomplish, project goals, or research questions you want to answer. Think about what outcomes or deliverables you'd like to create (e.g. a series of tutorial notebooks demonstrating a [use case](https://geo-smart.github.io/usecases#Contributing), or a new python package).

### Data

Briefly describe the data that will be used here (size, format, how to access).

### Existing methods

How would you or others traditionally try to address this problem?

### Proposed methods/tools

What new approaches would you like to try to implement to address your specific question(s) or application(s)?

### Additional resources or background reading

Optional: links to manuscripts or technical documents providing background information, context, or other relevant information.

### Tasks

What are the individual tasks or steps that need to be taken to achieve the project goals? Think about which tasks are dependent on prior tasks, or which tasks can be performed in parallel. This can help divide up project work among team members.

* Task 1 (all team members)
* Task 2
  * Task 2a (assigned to team member A)
  * Task 2b (assigned to team member B)
* Task 3
* ...

## Project Results

Use this section to briefly summarize your project results. These could take the form of describing the progress your team made to answering a research question, developing a tool or tutorial, interesting things found in exploring a new dataset, lessons learned for applying a new method, personal accomplishments of each team member, or anything else the team wants to share.

You could include figures or images here, links to notebooks or code elsewhere in the repository (such as in the [notebooks](notebooks/) folder), and information on how others can run your notebooks or code.
