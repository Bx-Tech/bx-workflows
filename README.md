# bx-workflows

Shared GitHub Action Workflows

**<sup>Note: in order to use environment variables, they must be passed as an input to the workflow using the `with` keyword in the parent job. They can then be set in the child job using:</sup>**

```
env:
    MY_VARIABLE: ${{ inputs.myInput }}
```