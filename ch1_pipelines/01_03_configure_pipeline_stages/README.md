# 01_03 Configure Pipeline Stages

If our deployments include multiple steps, we can group them together using stages.

Use the configuration for this lesson to update the pipeline configuration.
    - [`bitbucket-pipelines.yml`](./bitbucket-pipelines.yml)

The new configuration uses the `stage` keyword to group all the steps together for the "staging" and "production" deployments.

The `manual` trigger is also removed.

## Pipeline before update

![Pipeline before update](./images/0-before-SCR-20240602-maod.png)

## Pipeline after update

![Pipeline after update](./images/1-after-SCR-20240602-mabh.png)
