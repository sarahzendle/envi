# Group 203_7 for CSCI 3308 in Fall 2020 at CU Boulder
## Project Team Members:

- Matthew Teta
- Brian Mayers
- Samuel Mast
- Charlie Koepke
- Rebecca Coryell
- Lakshya Jaishankar
- Sarah Zendle

NOTE: Project was completed on a private repository through the University of Colorado Boulder. Source code was uploaded directly from Sarah Zendle's machine, and does not show actual commit history. Sarah Zendle contributed most of the css and front end for the home, friends, signup, and tracking pages.

## Application Name: envi

## Application Description:
Envi is an environmental impact tracking application. Create an account, log environmentally friendly actions, and connect with friends. Earn milestones and personalize your profile.

## Vision Statement:
For environmentally conscious people who would like to track and share the positive impacts they’re making, envi is a social platform where users can build a communal sense of environmental accountability that unites us during these troubling times.

Development Method: agile

Communication Plan: We will have two meetings a week over Zoom and communicate as we work over a Slack channel. Standup meetings once a week with our TA will keep us up to date on how each individual team member’s work is going.

Meeting Plan: Tuesday at 7:15pm and Wednesday at 6:45pm(Zoom)



# Proposed Architecture Plan:

- Backend Database: PostgreSQL
- Integration Layer:
  - Node.js
   Node-postgres
  - Express.js
    - Used to define endpoints for a REST api
  - Jsonwebtoken
    - For user authentication similar to this tutorial
- Frontend UI:
  - The frontend will communicate with the backend through HTTPS calls to the REST api
  - HTML
  - Bootstrap CSS and custom CSS
  - JS