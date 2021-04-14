# gh workflow

> List, view, and run workflows in GitHub Actions.
> More information: <https://cli.github.com/manual/gh_workflow>.

- Interactively select a workflow to view latest jobs:

`gh workflow view`

- View a specific workflow in the default browser:

`gh workflow view {{ID|filename.yml}} --web`

- Display the YAML definition of a specific workflow:

`gh workflow view {{ID|filename.yml}} --yaml`

- List workflow files (use `--all` to include disabled workflows):

`gh workflow list`

- Run a manual workflow using a specific branch:

`gh workflow run {{ID|filename.yml}} --ref {{branch_name}}`

- Enable or disable a specific workflow:

`gh workflow {{enable|disable}} {{ID|filename.yml}}`
