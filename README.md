Workflows:
-   Attached to repository
-   Contains one or more jobs
-   Triggered upon events like pushing the code to repo, pull request

Jobs:
-   Define a runner(execution environment)
-   Run in parallel or sequential
-   Can be conditional

Steps:
-   Must execute a shell script or action(must have one step in job)
-   Can be conditional
-   Steps are executed in order

Jobs are running in two types:
    -   parallel (default behaviour)
    -   sequential (needs keyword required)

How to skip the workflow ?
By adding [skip ci], [skip action] in the commit message

Service Containers ?

How to call one workflow from another workflow ? workflow_call

how to add inputs and outputs in nested workflow ?