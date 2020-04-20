# PROJECT 3 GROUP EXPECTATIONS <!-- omit in toc -->

> This template is required for the Project 3 Pitch. Your group should take at least 15 minutes to discuss and review the sections together. Please, do not leave the provided filler text.

- [The Team](#The-Team)
    - [Personal Strengths](#Personal-Strengths)
    - [Personal Challenges](#Personal-Challenges)
- [Group Expectations](#Group-Expectations)
    - [Group Timeline](#Group-Timeline)
    - [Team Goals & Values](#Team-Goals--Values)
    - [Communication Preferences](#Communication-Preferences)
- [Code Conventions & Practices](#Code-Conventions--Practices)
    - [Git](#Git)
    - [Function & Variable Names](#Function--Variable-Names)
    - [Route Names](#Route-Names)
    - [Database/Collection Names](#DatabaseCollection-Names)
    - [React Component & Folder Names](#React-Component--Folder-Names)

## The Team

- [James Madison](https://github.com/mishakessler)
- [George Washington](https://github.com/mishakessler)
- [John Lansing, Jr.](https://github.com/mishakessler) (Git Czar)

#### Personal Strengths

> This section should cover every group member's strengths, to enable groupmates to excel on the project, but also where they might be able to provide pair programming benefits.

- James: React logic
- George: React UI/CSS, Branding & Color
- JL: Backend/deployment

#### Personal Challenges

> This section should cover every group member's challenges, to enable groupmates to gain more exposure and clarity through pair programming.

- James: Styling, responsiveness
- George: Sequel in React, Auth
- JL: Front End

<br>

## Group Expectations

> This section should thoroughly document the groups goals, values, schedules, communication preferences, so there's no ambiguity during project week.

#### Group Timeline

- Wednesday (All groupmates in morning class; staying on campus from 12:00PM to 4:00PM.)
- Thursday (3 groupmates in class, 1 missing for prior commitment; available online and via Slack from 6:00PM to 10:00PM.)
- Friday (All groupmates in class, for MVP due at 2:00PM; evening off.)
- Saturday (All groupmates online and available via slack from 10:00AM to 4:00PM.)
- Sunday (All groupmates flexible, online and available via Slack.)
- Monday (All groupmates in class for 9AM checkin, final changes; Project Presentations due at 3PM.)

#### Team Goals & Values

1) Functional Code
1) Interactive, Attractive UI
1) Thorough Communication Between Teammates

#### Communication Preferences

- Star the group channel and turn on all push notifications.
- Slack the group channel at any time; groupmates' Do Not Disturb is on during sleeping hours.
- Respond to all messages within 8 hours.
- Use the team Kanban board and update as tasks are started and completed.

<br>

## Code Conventions & Practices

> This section should thoroughly document the naming conventions and practices to be followed by each groupmate. A sample git practice for branching and merging is included for your benefit.

#### Git

##### Naming <!-- omit in toc -->

- Group will have two main branches, `master` and `development`, and three sub-branches, `feature`, `hotfix`, and `refactor`.
- Branches should be named using kebab case and adhering to the convention `initials-branchtype-branchfocus`, such as `mk-refactor-globalstyling`.
- Pull requests should be titled adhereing to the convention `Merge [BRANCH] to [BRANCH]`, such as `Merge MK-REFACTOR-GLOBALSTYLING to DEVELOPMENT.`.

##### Branching & Merging Practices <!-- omit in toc -->

- **Never** code on, merge, or push to Master.

To Start:

- Git Czar will create the main repo, the README.md, and create a development branch and set the upstream so it’s available to all group members.
- Git Czar will add branch protection rules (found at _repo > settings > branches > branch protection rules_) to master, requiring majority review and approval from groupmates, and development, requiring only the Czar's approval.
- Group members should clone the repo (**without forking**) and confirm they have both the master and development branches, with the correct origin URLs for each. (`git branch` & `git remote -v`)
- Group members can then run `git checkout -b initials-feature-branchname` from their local development branch, before creating any code.

Merging to Development

- Once a group member’s code ready to merge with development, that group member should `add`, `commit`, and `push` to their origin branch before running a “safety pull” from origin development, confirming there were no other updates made without their knowledge.
- **If there are no conflicts**, that group member can initiate a pull request on GitHub. On the _Compare Changes_ page, the group member should confirm the pull request is _base: development_ and _compare: branchname_, subsequently titling the pull request according to naming conventions.
- Once that merge is finalized, all group members should immediately `add` and `commit` their code before running a `git pull origin development`, to minimize future merge conflicts, before continuing to work on their code.

Merging to Master

- Once your group's development branch is ready to merge with master, the Git Czar should make a pull request, confirming it is _base: master_ and _compare: development_ and titling the pull request according to naming conventions.
- Due to branch restriction rules, this pull request requires an established majority consent accept the changes and merge the branch.
- Once that merge is complete, all members should run `git pull origin master` to **all** of their local branches.

#### Function & Variable Names

- Lorem ipsum dolor sit amet, consectetur adipiscing elit. Morbi lacinia, tortor ut consectetur tincidunt, eros libero dictum neque, quis maximus lectus urna eu erat.

#### Route Names

- Lorem ipsum dolor sit amet, consectetur adipiscing elit. Morbi lacinia, tortor ut consectetur tincidunt, eros libero dictum neque, quis maximus lectus urna eu erat.

#### Database/Collection Names

- Lorem ipsum dolor sit amet, consectetur adipiscing elit. Morbi lacinia, tortor ut consectetur tincidunt, eros libero dictum neque, quis maximus lectus urna eu erat.

#### React Component & Folder Names

- Lorem ipsum dolor sit amet, consectetur adipiscing elit. Morbi lacinia, tortor ut consectetur tincidunt, eros libero dictum neque, quis maximus lectus urna eu erat.