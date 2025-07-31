---
title: Egress Check Failed
labels: ["bug", "o&m", "egress"]
---

Workflow with Issue: {{ workflow }}
Job Failed: {{ env.GITHUB_JOB }}
Type of Failure: {{ env.COMMAND }}
Cloud.gov Environment: {{ env.ENVIRONMENT }}

Last Commit: {{ env.LAST_COMMIT }}
Number of times run: {{ env.GITHUB_ATTEMPTS }}
Last run by: {{ env.LAST_RUN_BY }}
Github Action Run: https://github.com/GSA/datagov-harvester/actions/runs/{{ env.RUN_ID }}
