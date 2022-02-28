# hashcode_js
- Challenge 1

#### Solution in JS
- index.html file

#### Solution in C++
https://github.com/DavidUser/hash_code_2022

## Description

People
  Skills
    level

Project
  Roles
    Skill
      Level

Filling role

- Have the minimum required level
- Have -1 skill revel required, but have a collegue on project with the required level

A project with N days duration will take the days 0, 1, 2, 3, ..., N-1 at day N the project was completed and the contributors could be realocated to new projects.

Contributors gain skill points when:

- complete a assigned role position with -1 level or equal level

**Mentorship doesn't give skill points**
**Complete assignment having +1 or greater skill level doesn't give skill points**

Given many projects allocate the contributors to the projects...

- A contributor can only contribute in one project by time
- The project just starts when all needed contributors are available

**If one of the assigned contributors is locked in a previous project the entire team need wait to continue the project**

- Projects lose 1 score point at each delayed day after best before day


## Strategies

Leve up needed skills:
  Place contributors in one project, N contributors to 1 project
    If other project needs a higher skill level, try place contributors that need evolves the needed skill
