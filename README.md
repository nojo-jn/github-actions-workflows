# Activity Types Workflow / activity-types-workflows.yaml

The workflow in `.github\workflows\activity-types-workflows.yaml` runs on pull
requests **targeting `main`**, but only for these activity types:

| Activity type | Fires when… |
| --- | --- |
| `opened` | a new PR is opened |
| `synchronize` | new commits are pushed to the PR branch |
| `closed` | a PR is closed |
| `reopened` | a previously closed PR is reopened |

Each run prints the triggering action:

Activity Types Workflow is running for action: `<action>`
