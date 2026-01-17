This Maven project is used to test Jenkins build triggers via GitHub Webhooks.
The Jenkins job is configured with GitHub hook trigger for GITScm polling.
Any commit or push to the GitHub repository automatically triggers a Jenkins build.
Successful triggering confirms proper webhook and Jenkins integration.
Build logs in Jenkins verify the received webhook event and execution.
