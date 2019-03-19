# github-topics

Small and incomplete experimental scripts to maintain consistent GitHub topics on a set of repositories.

## Usage

Retrieve the current topics for the repositories defined in the `repos` file:

```
GITHUB_TOKEN=<personal_access_token> ./do_query
```

Mutate the topics on the queried repositories to contain `laa-needs-owner`:

```
GITHUB_TOKEN=<personal_access_token> ./do_update
```
