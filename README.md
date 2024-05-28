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