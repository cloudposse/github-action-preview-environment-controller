<!-- markdownlint-disable -->
## Inputs

| Name | Description | Default | Required |
|------|-------------|---------|----------|
| env-label | YAML formatted {environment}: {label} map  | preview: deploy<br> | true |
| labels | Existing PR labels | [] | true |
| open | Is PR open? | true | true |

## Outputs

| Name | Description |
|------|-------------|
| deploy\_envs | Environments that need to be deployed |
| destroy\_envs | Environments that need to be destroyed |
| labels\_env | JSON formatted {label}: {environment} map |
<!-- markdownlint-restore -->
