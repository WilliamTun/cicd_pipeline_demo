# Workflow

## Development
New change -> Create a new [feature branch] for the change
Commit changes to feature branch 
Once all commits are ready, MERGE REQUEST into the [master branch]
Trigger unit tests & linting
If tests are successful, MERGE new features into [master branch]

## Staging
Open option to test changes on staging environment.
The staging environment can be hosted on where the app will eventually be deployed 
such as a cloud environment.  
If successful, create a new merge request to [production branch]
This will trigger the DEPLOYMENT. 




