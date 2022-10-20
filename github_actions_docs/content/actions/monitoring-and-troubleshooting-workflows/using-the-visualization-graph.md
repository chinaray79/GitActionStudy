---
title: Using the visualization graph
shortTitle: Visualization graph
intro: Every workflow run generates a real-time graph that illustrates the run progress. You can use this graph to monitor and debug workflows.
redirect_from:
  - /actions/managing-workflow-runs/using-the-visualization-graph
versions:
  fpt: '*'
  ghes: '*'
  ghae: '*'
  ghec: '*'
---

{% data reusables.actions.enterprise-beta %}
{% data reusables.actions.enterprise-github-hosted-runners %}

{% data reusables.repositories.navigate-to-repo %}
{% data reusables.repositories.actions-tab %}
{% data reusables.repositories.navigate-to-workflow %}
{% data reusables.repositories.view-run %}

1. The graph displays each job in the workflow. An icon to the left of the job name indicates the status of the job. Lines between jobs indicate dependencies.
   ![Workflow graph](/assets/images/help/images/workflow-graph.png)

2. Click on a job to view the job log.
   ![Workflow graph](/assets/images/help/images/workflow-graph-job.png)