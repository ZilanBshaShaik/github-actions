Using Variable in GitHub Actions:-
Variables are defined in GitHub Action in three different ways.
(1) Variables for a single workflow:-
define it using the env key in the workflow file. The scope of a custom variable set by this meathod is limited to the element in which it is defined. You can define variable that are scoped for
(a) The entire workflow by using env at the top level of the workflow file
(b) The contents of a job within a workflow
(c) A specific step within in a job
