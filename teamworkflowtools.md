# Teams Workflows and Tools for productivity

This year I joined a new company! Coming from working solo and working on school projects it was my first time to work in a team and more interestingly working in a distributed team.

> Working as a team can be a pain in the neck when there is no clear workflow and tools to help the team to stay productive.

Someone in the team will mess up and tasks that could take a week to complete will take two. The project will stagnate and everyone will be unhappy.But there is another side of the story!

In a big picture, a _Workflow_ is a sequence of related steps that are necessary to complete a particular task. As a development team, how do you get a task completed? That is your team's workflow, it deals with connecting small steps that lead to the main task.

For us at Andela, [Agile](https://www.agilealliance.org/agile101/) is our way of doing things(especially the [Scrum](https://www.atlassian.com/agile/scrum) framework).

Each team is made up of 5 to 8 people.

There is the _**Product Owner**_ whose role is to oversee all the business conditions of the project to ensure the right product is built and in the right order. There is the _**Team Lead**_ who also act as a _**scrum master**_, the TL has to make sure that there is no blocker in the process, facilitate meetings and discussions, track progress, solve problems... Then there are _**developers/designers**_ whose main role is to develop the product envisioned by the PO.

Our shortest amount of work is measured as a _**sprint**_, which is one week. Before starting to work on any task(or starting a sprint), the team works together to determine the best approach to achieve the tasks outlined by the product owner. Everyone on the team decides which tasks he/she will work on, and outline the technical practices required to achieve the desired goals. This process is called _**sprint planning**_ and happens once each week.

Each day we have a _**standup**_ which can be a video call or posting. The standup is the perfect time to share _**our progress**_ on the sprint tasks, _**blockers**_ we are having and any other important info. Standups help Team Leads to keep track of progress. Product owners don't attend standups.

During the week, the TL can reach out to any team member to see how far there are with there tasks. Developers also can reach out to the TL for blockers or to the product owner for clarification or updating them on progress.

On the last day of the sprint, there is a _**demo.**_ The demo is for the TL and developers to show the product owner what has been achieved in that sprint i.e: completed features as requested on the start of the sprint.

Now, let's turn our focus on different _**tools**_ that make this workflow easy and productive.

For communication, we use [Zoom](https://zoom.us/) for video call sessions like the demo, sprint planning. For any other cases, we use [Slack](https://slack.com/). Slack is the backbone of communication in our team when you want to get help from your colleague you can slack him and get an instant answer. Slack also can be integrated with other tools we use so that we can get updates on everything in one place.

We use Pivotal Tracker as a project management tool. [Pivotal Tracker](https://www.pivotaltracker.com/) follows Agile's scrum methodology. On the start of the project, the PO create a board and fills the icebox with all the tasks. The board is updated as it becomes a necessity.

For each sprint, the PO removes the tasks to work on from the icebox to the backlog. Then a developer can choose a task which shows as assigned to him/her. When the task is finished he/she can change the status of the task to finished and deliver it. After the demo, the PO can accept a task and remove it from the backlog or he can reject it and it will remain there.

We use [GitHub](https://github.com/) for version control. Github makes it easy for a distributed team to work on the same project. When a developer on the team completes his/her task he/she raises a pull request so that the code can be merged into the main project. Other developers have to review the code and approve them before the TL merges them.

There are many other tools that we use like [TravisCI](https://travis-ci.com) for continuous integration, [Code Climate](http://codeclimate.com/) for test coverage and code quality, [Postman](https://www.getpostman.com/) for API testing and [Swagger](https://swagger.io/) for API documentation, etc.

> While deciding on which tool to use can be a problem; don't change your workflow to fit a tool, instead find a tool that fits your workflow.

As a developer in the team, my utmost role is to _deliver tasks meeting or expecting the PO's expectations_. I also have to _offer my support_ for other members, _take initiative_ on the project. The best way to achieve all of the above is to _communicate_ and _be an active listener_ during meetings(sprint planning, standups, etc).

One last thing to note, for software development teams you must have a coding convention. Coding conventions are style guides on a project, they show how code should be written or formatted. Style guides can be extensive documents with hundreds of pages. We use the [Airbnb Javascript style guide](https://github.com/airbnb/javascript) which is an extended version of the famous [Eslint](https://github.com/eslint/eslint).

One of the conventions we follow:

- Using ES6 in favor of ES5 i.e: const and let instead of var
- using camel case when naming variables
- Commenting code
- Use object destructuring
- Single quotes for strings
- Modular design

We also have a [git naming convention](https://github.com/andela/bestpractices/wiki/Git-naming-conventions-and-best-practices) for branches, commits, and PRs.

---

Some links to tools we use in our workflow showing personal contribution:

- [GitHub](https://github.com/andela/ah-kgl-avengers-backend) team project and personal account [avpaul](https://github.com/avpaul)
- [Pivotal Tracker board](https://www.pivotaltracker.com/n/projects/2321840) Initials **VI**
- [Slack](https://andela.slack.com) handle **_@paul_**
