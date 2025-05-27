What are Github actions?
Ans:- Github actions are continuous integration and continuous delivery {CI/CD} platform built directly on Github.
It allows you to automate various task within your software development workflow.


What are the Github actions components?
Ans:- There are 5 components of github actions, They namely mentioned as(1) workflows
(2) jobs
(3) events
(4) actions
(5) runners


What are workflows?
Ans:- A workflow is a configurable automated process that will run one Or more jobs.
workflows are defined in the .github/workflows directory in a repositoryworkfloes are written in YAML file

What is job?
Ans:- A job is set of steps in a workflow that is executed on the same runner.
each step is either a shell script that will be executed Or an action that will be run.
steps are executed in order and are dependent on each other.

What are events?
Ans:- An event is a specific activity in a repository that tiggers a workflow run.
for example, activity orginated from Github when someone creates a pull request, opens an issue Or pushes a commit to a repository.

What are actions?
Ans:- An actions is custom application for the Github actions platforms that performs a complex but frequently repeated task.
use an action to help to reducse the amount of repetitive code that you write in your workflow files

What are runners?
Ans:- A runner is a server that runs your workflow when they're triggered.Each runner can run a single job at a time.
Github provides githosted runners also we can create self hosted runners to run our workflows 
