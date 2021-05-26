# Sprint 3 Review

<hr/>

## Table of Contents

- [Summary](https://github.com/Rammina/chingu-voyage-sprint-3#summary)
- [Tasks](https://github.com/Rammina/chingu-voyage-sprint-3#tasks)
  - [Completed tasks](https://github.com/Rammina/chingu-voyage-sprint-3#completed-tasks-or-task-groups-from-sprint-3)
  - [Ongoing Tasks](https://github.com/Rammina/chingu-voyage-sprint-3#ongoing-tasks-started-in-s3-but-unfinished)
  - [Sprint 4 Tasks](https://github.com/Rammina/chingu-voyage-sprint-3#sprint-4-tasks-should-be-done-in-s4-after-finishing-ongoing-tasks-from-s3)
- [Personal Opinions](https://github.com/Rammina/chingu-voyage-sprint-3#personal-opinions)

<hr>

## Summary

Objectively, I think that this was our best Sprint so far.

**Positives:**

- The best part is that we have improved our communication and collaboration as a team.
- We report our status with teammates more often.
- More of us are open to giving and receiving feedback, and asking for help.
- We also started doing pair programming more often, which helps us understand how each teammate codes.
- Fewer duplicate work done (the less we do what someone else already did, the better)

<br>

**Negatives/Shortcomings:**

- We may have only finished 60-70% of our tasks assigned for the week, but it is okay because there were unexpected things that happened that interrupted us from working (e.g. getting sick, external/family interruptions, personal life stuff).
- We have to do more work and be more efficient in the coming weeks, if we want to finish the application.
- We still have outdated branches that are not in-sync, and we did not merge the refactored file structure that Seb made yet.
- I think we are not completely familiar with the application's overall structure yet.

<hr />

## Tasks

### Completed tasks (or task groups) from Sprint 3:

**Frontend**

- User dashboard skeleton layout
- Projects skeleton layout
- AllProjects skeleton layout
- Header skeleton layout

<br>

- Create Project Form
- Cancel Project Form
- Delete Project Form

<br>

- Project actions and reducers (no update)

<br>

- react-router dynamic routing (need to confirm with Seb once we merge everything)
- folder and file restructuring and cleaning up of unnecessary folders and files

<hr />

**API/Backend**

- CRD (no update) Projects API
- Project routes and controllers

<br>

- GoogleAuth login works, and is dynamically routing (this is carryover from Sprint 2)
- Log in and register user and store in database (from Sprint 2)

<hr />

**Others**

- learn git basics and merging with teammates branch (carryover from Sprint 2)
- pair programming

<hr />

### Ongoing Tasks (started in S3 but unfinished)

**Frontend**

- User dashboard design
- User dashboard should retrieve and display list of projects owned
- User dashboard should retrieve and display user information (username, email)
- User dashboard links and buttons are not finalized yet

<br>

- All projects list should retrieve and display up to 9 projects from the database
- Increment Projects by 9 each time the user clicks "Show More", until there are no more Projects
- Clicking a project in the projects list (both here and the dashboard) should redirect to the specific project page

<br>

- Specific project page skeleton still incomplete? (I don't know if desktop version is completed)
- Specific project page design
- specific project page should display actual project information (name, amountDonated, targetGoal, deadline, description)

<br>

- react-router routes not yet finalized

<hr />

**Backend/API**

- GET User & Project controller functions should use .populate to retrieve the actual objects

<hr />

**Others**

- study application logic/structure (ideally, everyone should have a rough idea where things are and what they do)
- keep coding style consistent with teammates if possible
- follow BEM CSS className style and refactor the ones that don't follow it (I know I'm very guilty of this, I should go back and refactor my CSS classNames -Tella)

<br>

- use github PR more (I will admit I don't have much time to do this when I'm busy coding on things as well)

<br>

- try using useSelector instead of connect with react-redux, test if it works on the components I made, and if there are no errors switch to useSelector
- we should be more specific when pointing out errors

<hr />

### Sprint 4 Tasks (should be done in S4 after finishing Ongoing Tasks from S3)

- Checkout page

  - skeleton layout
  - design
  - payment form

  <br>

  - Stripe API (mocking can lead to technical debt, meaning it will need to be refactored again which may use up time)
  - owners of a project should not be allowed to donate to their own project
  - backend controllers and routes

  <br>

  - donating to a project should add that project to projectsSupported of the user object
  - donating to a project should add the user to donors of the project object
  - donating to a project should increase the amountDonated

  <br>

  - I'm not sure yet if there should be a transaction object/model

- Dashboard

  - Update user information (action, reducer, controllers, route)
  - User account deletion

- Projects

  - Update project information (action, reducer, controllers, route)
  - Delete project (action, reducer, controllers, route)
  - Connect Edit Project Form with a Edit Project button in the project page
  - Only show Edit Project button when the current user is the owner of the project, do not display it otherwise
  - Connect Delete Project Form with a Delete Project button in the project page
  - Only show Delete Project button when the current user is the owner of the project, do not display it otherwise
  - Donate button should be hidden if the owner of the project is viewing their own project

  <br>

  - We need to decide where the user will be able to see the projects they supported (this is different from projects owned)

  <hr>

### Personal Opinions

These are just my thoughts based on what we've experienced in the past 3 weeks, how you guys feel or think could be different from mine and that's okay:

**Team Workflow**

- Do a status report at least 3 times per week, let the team know what you're doing and what you're having trouble with.
- Let's make sure to push to our own branch everyday (ideally) after working, even if it's not complete or there are bugs. (It makes it easy for other teammates to know what you're currently doing and what code you have)

<br>

- We should work on different parts of the application when alone, to avoid duplicate work and conflict with other teammates. (It feels really bad when the work you've done has to be deleted or removed because it doesn't work with what another person made.)

<br>

- If we want to add something to someone else's work or assist someone, make sure to ask for permission first and checkout to a different branch after pulling or cloning their work.
- If we want to collaborate or assist someone with their components/pages/tasks, pair programming is great to ensure smooth workflow and also to exchange information.
- Duplicate work and out of sync files (files that are completely different from up-to-date branches) can really use up a lot of time that we have in a Sprint. It's best to avoid these as much as possible.

<br>

- When talking about a bug or error, let's try to be as specific as we can so that teammates understand and know where to look for them. (copying the error code, screenshots)

- Feel free to ask about anything or bring up topics, as long as it's constructively stated. Other teammates could be unaware of an issue and bringing it up can help the team resolve something.

**Application (MVP)**

- 3 weeks for the rest of the application definitely feels short, but I think it's enough time for us to reach MVP status.
- I think we can complete our application or get it decently functional, if we continue to work on the parts or tasks we are assigned for each Sprint.
- I think our working speed/efficiency will improve from here. We are starting to collaborate better than we did weeks ago, and I think we have a clear idea of what we have to do.
