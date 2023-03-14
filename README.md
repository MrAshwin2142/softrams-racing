# Softrams Racing

Welcome to the Softrams Racing Team Trials where you'll be tested on your development skills.  We have brought you on board today because you specialize in a particular skill that we believe will not only benefit us a as a team, but you as a developer.  Softrams Racing prides itself as being one of the top competitors in many racing series including Formula 1 and the World Endurance Championship.  Competing in multiple categories requires many personnel and we are having trouble keeping track of the roster of each team.  We have already began to construct a mini-application which currently only retrieves members of the organization.  This is where you come in.  Softrams Racing needs you to add a feature to this application that allows us to add new members to our organization, and most importantly to a specific team.  You have been provided the application source code and your job is to create this feature.  Softrams Racing looks forward to seeing what you can accomplish!  Good luck!

## Requirements

As a user, I need to be able to add a member to the organization so that I can keep track of each team roster.

Member properties

1. First Name
2. Last Name
3. Job Title
4. Status
5. Team

### Acceptance Criteria
* Clone the repo
* On the member summary page, I should be able to click a button that navigates to a member detail form
* The member detail form should include fields for each of the member properties above
* Saving the member should redirect me back to the member summary page where I should see the new user listed on the table
* Create a Zip from the updated source code and send it to your point of contact for review

## Development Environment 

* [Express](https://expressjs.com/)
* [Angular CLI](https://cli.angular.io/)
* [json-server](https://github.com/typicode/json-server)
  * A full fake REST API

## Running the Application

Review the available scripts in the [package.json](package.json)   

### Run in Production Mode

Application will run on [localhost:8000](http://localhost:8000)

`npm start`

### Run in Development Mode

Application will run on [localhost:4200](http://localhost:4200)

`npm run start-dev`

_Please Note:  To have Angular call `json-server` directly, set `DEBUG` to `true` in [app.service.ts](./src/app/app.service.ts)_

## Submit a Pull Request

Once you have pushed the completed work to your feature branch, submit a pull request which will then be reviewed by our development team.
