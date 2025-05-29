Using Variable in GitHub Actions:-
Variables are defined in GitHub Action in three different ways.
(1) Variables for a single workflow:-
define it using the env key in the workflow file. The scope of a custom variable set by this meathod is limited to the element in which it is defined. You can define variable that are scoped for
(a) The entire workflow by using env at the top level of the workflow file
(b) The contents of a job within a workflow
(c) A specific step within in a job

(2) Configuration variable for multiple workflow:-
You can create configuration variables for use across multiple workflows and can define them at either the organization, repository, or environment level.

(3) Context Variable from Github Metadata:-
Contexts are a way to access information about workflow run, variables,runners environments, job and steps.

URL: https://docs.github.com/en/actions/writing-workflows/choosing-what-your-workflow-does/accessing-contextual-information-about-workflow-runs#github-context

from the above URL you can find more information about Context Varible.


(4) Input for Manually Triggered Workflow:-
when you using workflow_dispatch event you can optionally specify inputs that are passed to the workflow.
