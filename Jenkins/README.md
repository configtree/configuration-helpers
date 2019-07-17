# Best practices for Jenkins

## Secure access retrieval
In [`SecureRetrieveJenkinsfile`](SecureRetrieveJenkinsfile) we show how to properly store and retrive secrets in Jenkins without leaking secret information into your logs. Here a code snippet to securely access ConfigTree using Jenkins, without leaking your username/password and access tokens.