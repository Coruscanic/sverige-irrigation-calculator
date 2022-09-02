# Social Contract

The social contract defines how the team members should behave, and what they can expect from the other team members, as well as some general organization of the team.

## Definitions

### Methodology

We will use the scrum agile project management framework to achieve incremental and iterative progress towards our objectives, while staying flexible regarding to our goals.

Standups:
- We will have bi-weekly standups on Mondays and Fridays. 
- Standups will last 20min. 
- Every developer will go over blockers, what they've been doing, what they're going to do, and update their progress on their sprint goals. 
- Afterwards, any outstanding issues will be raised in post-standup.

Sprints:
- Sprints will last 2 weeks. 
- Sprint capacity will be 10 points per developer. 1 point represents 2 hours of work. 
- Developers must update the team on their progress towards the sprint goal. 
- Sprint capacity and length may be revised as the team deems fit.

Planning:
- Sprints begin with planning. 
- In planning, the team, lead by the scrum master will define what features are to be delivered and how. 
- The team estimates story points. 
- The scrum master gooms and assigns tickets based on developer capacity (grooming is integrated into planning).

Retro:
- Sprints end with retro. 
- In retro the team goes over what went well, what didnt go well, and what the team should do going forward. 
- Each team member is expected to contribute to retro as much as possible.

### Roles

Each member of the team will be assigned with a role among the following:

- Scrum Master: The scrum master will lead the team and make sure every member can work in the best conditions. They will also be responsible for keeping track of the team progress and objectives.
- Data Scientist: The data scientist will be responsible for the dataset(s) and make sure it is accessible and usable for the other team members. They will also make sure that the data is used in a meaningful way throughout the project.
- Developer(s): The developers will be responsible for making components for our program based on their respective tickets and writing test cases.

In addition to their usual roles, all members of the team are responsible for validating and approving pull requests.


### Repository Setup
The github repository will be used to keep track of the software. We will be working out of the development branch untill 'production'.
- Tickets will be implemented in their own branch, with the branch naming scheme as follows: `${feature|bugfix|hotfix|support}/${ticket-number}`
- Tickets are only merged to master after >=2 PR approvals and no conflicts. Merging is setup to be fast-forward only. Devleopers are responsible for merging their own tickets.

### General Rules
- Every team member will be ontime for meetings unless something urgent happend.
- Every team member has an equal voice and valuable contribution to the project.
- When assigned a job/ticket the team member will take ownership and keep it up to date.
- There must be clear communication before assigning new stories/tickets to a team member.
- Developers are responsible for merging their own pull requests.
- Developers must implement unit and integration tests for their own tickets.
- Every team member keeps his JIRA board updated at all times
- Every team member is expected to participate actively in meetings.
- Every team member is responsible for the quality of the whole project.
- If after a discussion of 15 to 30 minutes not every team member agrees, the side with the most votes wins.
- When a team member is not able to submit assigned work in due time, it is their responsibility to be realistic and inform the rest of the team as soon as possible so they can decide how to handle the situation.
