# OZI Publish

Publish python packages built with OZI.

## Inputs

* github-token - workflow-generated token - optional
* create-pull-request - create a pull request on the default branch - optional
* pull-request-body - text to use for the pull request body - defaults to ``"Created automatically. Manually close and reopen to enable checks."``

## Permissions

Use the following:

```yaml
    permissions:
      contents: write
      id-token: write
```
