# guvi-task2
#test
Project Title
Jenkins GitHub Webhook Automation with Email Notification
Tools Used
Amazon Web Services EC2
GitHub
Jenkins
OpenJDK 21
Objective

To configure Jenkins on AWS EC2 and automate build triggering using GitHub Webhooks.
Whenever code is pushed to the GitHub repository, Jenkins automatically triggers the build and sends the build output through email notification.

Steps Performed
Created AWS EC2 instance
Installed Java (OpenJDK 21)
Installed Jenkins
Started Jenkins service
Added inbound rule for port 8080
Accessed Jenkins dashboard
Configured GitHub credentials
Created Jenkins freestyle project
Connected GitHub repository
Enabled GitHub webhook trigger
Added build script
Configured email notification
Pushed code to GitHub
Jenkins build triggered automatically
Build success email received
Sample Build Script
#!/bin/bash
echo "Hello Jenkins Automation"
date
hostname
GitHub Repository URL

(Add your GitHub repo URL here)

Example:

https://github.com/yourusername/jenkins-webhook-project
Output
Automatic build triggered after git push
Email notification received successfully
Conclusion

Successfully implemented Jenkins CI automation using GitHub Webhooks on AWS EC2 with email notification integration.
