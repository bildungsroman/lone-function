# PR instructions
Please follow the guidelines documented in our [Engineering Notion Wiki](https://www.notion.so/stackery/Pull-Requests-Guidelines-d2a30986f1c24fdbbe6d231866848b19).

## PR Outline

### Summary of changes
A brief explanation of what is being changed and why

### Tradeoffs
Identify any shortcomings or tradeoffs considered (Do via comments if it is easier)

### Dependencies
List out any service dependency (ie, depends on stackery/stackery-ui-2#201)

### Testing Environment
If applicable, link to a deployed instance for the reviewer to test

### Internal Documentation updates
Link to Notion documents updated

### External Documentation
Is external documentation needed? If so, link to the ticket

### Stackery Environment updates needed?
Are there any new keys or updates needed in the Stackery environment to enable this change?
If so, please list them out and briefly explain what they are, how they can be generated for staging and individual developer environments

## Labels
Please add one or more of the following labels to the PR
* `Minor` - (small bug fixes, small refactor, etc)
* `Migration` - Updates to RDS
* `Data` - New or updates to other data storage systems (DynamoDB)
* `Architecture` - New or updates to the service architecture
* `UX` - New or modified user experience (new resource, update user work flow, etc)
