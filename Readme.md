# Documentation for running GitHub Action

1. Go to Settings > Secrets and Variables > Actions
2. Click on new repository secret
3. then add the following:

```bash
AWS_ACCESS_KEY_ID
AWS_SECRET_KEY_ID
AWS_REGION
```

## Run the pipeline

Connect your repository to your localhost then push, the pipeline will be triggered automatically.
