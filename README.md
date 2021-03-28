# SlackBotRW
SlackBot

Purpose: The goal of this repository is to create a bot in slack that communicates with Google Cloud Storage
         and alerts the team when .csv or JSON files are uploaded

Execution
  1. Created a Slack appplication with the Slack API and added it to our test workspace
  2. Enabled incoming webhooks on slack API
  3. Created new Google Cloud Project called 'My First Project' and enabled API services
  4. Created HTTP serverless function that sends messages to Slack with a Cloud Function (Through Google Cloud)
  5. Scheduled job that calls Cloud Function every given interval with Cloud Scheduler
