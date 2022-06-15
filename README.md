# SalesforceStudy

# README <!-- omit in toc -->

- [Project Planning](#Project-Planning)
  - [Overview](#Overview)
  - [Wireframes](#Wireframes)
  - [MVP](#MVP)
    - [Goals](#Goals)
    - [Libraries](#Libraries)
    - [Data](#Data)
    - [Component Hierarchy](#Component-Hierarchy)
    - [Component Breakdown](#Component-Breakdown)
  - [Post-MVP](#Post-MVP)
- [Project Delivery](#Project-Delivery)
  - [Code Showcase](#Code-Showcase)
  - [Code Issues & Resolutions](#Code-Issues--Resolutions)

## Project Planning

> Want to create a salesforce study guide to pass certifications

<br>

### Overview

\_**SalesforceStudy** is an elite personal note taking app that included note tabs to log daily notes and find resources consisting of salesforce help.

<br>

### Wireframes

> Use the Wireframes section to display potential mobile, tablet, and desktop views.

- Mobile
! https://drive.google.com/file/d/1vwETSi3Pr5jsoUvXblYQhZrcSBQxuKMv/view?usp=sharing

- Tablet
! https://drive.google.com/file/d/1B9OiWKrW9-NLVLWafVM6YFLpbXBGjEti/view?usp=sharing

- Desktop
! https://drive.google.com/file/d/14C7C7pvSaCFy_IUGBptHDiHwa8cg0Ydn/view?usp=sharing

<br>

### MVP

> CRUD format with simple Layout, at least 5 components, a react router, some API, and coded in mobile first to then extend to tablet, and desktop mode with minor styling.

\_The **SalesforceStudy** app

<br>

#### Goals

- MondoDB database
- API setups
- Crud complete within first 2 days
- Simple design layout
- Complete responsive layout for all devices
- Post MVP update in styling
- Post mvp add more indepth Salesforce topics for the Admin, JavaScript, and Developer certification.

<br>

#### Libraries

> Libraries and their role in the project.

|     Library      | Description                 |
| :--------------: | :-------------------------- |
|   React Router   | Routing links and pages     |
|      Axios       | Pulling Air table API key   |
| Reacts-Bootstrap | Styling cards for resources |

<br>

#### Data

> Defining the API(s) with sample URL queries.

|     API     | Quality Docs? | Website               | Sample Query                                                              |
| :---------: | :-----------: | :-------------------- | :------------------------------------------------------------------------ |
| AirtableAPI |      yes      | https://airtable.com/ | https://api.airtable.com/v0/app2aFIfy94WFful9/Table%201/recLXsRslsXAP7O80 |

<br>

#### Component Hierarchy

> Defining  React components and the data architecture of Salesforce app.

```
src
|__ assets/
      |__
|__ components/ (Added Image links and Resources links)
      |__ Header on App.js (PROductivity)
      |__ DailyNotes.js
      |__ ToDoNotes.js
      |__ Dynamic Resource cards from bootstrap w/links
      |__ Add note button
      |__ Delete note button (On description of task)
```

<br>

#### Component Breakdown

> Use this section to go into further depth regarding your components, including breaking down the components as stateless or stateful, and considering the passing of data between those components.

|   Component   |    Type    | state | props | Description                                                            |
| :-----------: | :--------: | :---: | :---: | :--------------------------------------------------------------------- |
|    Header     | functional |   n   |   y   | \_The header will link to the home page of current To-Dos & Daily Task |
|  Add Note     |   class    |   y   |   y   | \_The Add Notes will render the post info via props & state                 |
| Update Note's |   class    |   y   |   y   | \_The Update Note's will render the notes post via props & state       |
|   Resources   | functional |   n   |   n   | \_The blocks will render the post that wont change                     |
|  add button   | functional |   y   |   n   | \_Buttons will create a post                                           |
| delete button | functional |   y   |   n   | \_Buttons will delete a post                                           |

<br>

### Post-MVP

> Ideas that would be fun (or necessary) for your Post-MVP. 

- Indepth CSS for styling
- Turn to social notes app like quizlet
- Add social account component

<br>

---

## Project Delivery

### Code Showcase

> I am proud of using React-Boostrap library because It was self-taught.
> I am proud of the projects purpose and the amount of people it will help starting with myself
> Happy studies for life learners!

### Code Issues & Resolutions

> I did not know how to make the cards grid view and fixed it in CSS
> I did not know how to make the cards contain links to resources and added new code with help
> I did not know how to seperate description of notes with adding notes and seprated each with help
> Started mobile first and had trouble sizing efficeintly but it works
