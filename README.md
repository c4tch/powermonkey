# powermonkey
climbing logger
Heroku Setup
Get an heroku account, you can start with a free Hobby account
Install the cli https://devcenter.heroku.com/articles/heroku-cli#download-and-install
Create a new application (you can do this from the UI or CLI tool, your choice)
Identify your region (you need this later) using the CLI: heroku info your-app-name

Install Heroku Postgres Add-on
Enriovnment variable (set automatically by add-on): DATABASE_URL

S3
Create a new S3 bucket in the same region as your Heroku Application. Free tier Heroku apps are eithr EU or US; The Heroku US region is AWS's us-east-1. EU is eu-west-1. 
Define envionemntal variables for S3
AWS_ACCESS_KEY_ID
AWS_SECRET_ACCESS_KEY
S3_BUCKET_NAME
