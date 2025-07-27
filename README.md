# jenkins-scm

Jenkins CI demo

This is to test auto build in jenkins when chenges are made to the repo.

Making another changes after successfully adding webhook on github

## Steps to add webhook

Navigate to your GitHub repository and go to "Settings" > "Webhooks." 
Click "Add webhook."
Payload URL: Enter your Jenkins server's URL followed by /github-webhook/ (e.g., http://your-jenkins-server:8080/github-webhook/).
Content type: Select application/json.
Secret (Optional): If desired, provide a secret token for enhanced security. This secret must also be configured in your Jenkins GitHub plugin settings.
Which events would you like to trigger this webhook? Select "Just the push event" or customize based on your needs.
Ensure "Active" is checked.
Click "Add webhook." 