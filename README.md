# CrudderApp
Curdder app

First Things First

Protect your root account with MFA
create IAM user with to perform actions on your aws account and not to use root aws account.

Json folder have files to create budget in .json format. So I have use aws cli mode to create aws budget of usd 5.
Aws user access key is used to work on aws cli. but not to share you aws access key and please remove/inactive the key after use.

I get the front end and backend of my crudder file. 
The back and front is tested on local machine with port 3000 for frontend and 4567 for backend. 

To fetch the data from backend do append to the url to `/api/activities/home`

Used Docker-complose file to run frontend and backend docker at the same time.

