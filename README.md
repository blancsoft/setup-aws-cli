# AWS CLI GitHub Action

This GitHub Action sets up AWS CLI by adding a step to your workflow.

```yaml
  - name: AWS CLI
    uses: blancsoft/setup-aws-cli@v1
```

## Defining version

Set which AWS CLI version to use and other inputs.

```yaml
  - name: AWS CLI
    uses: blancsoft/setup-aws-cli@v1
    with:
      version: 1.6.2
      python_version: 3.12.1
      aws-region: global
      aws-access-key-id: xxxxxxxxxx
      aws-secret-access-key: xxxxxxxxxx
```
