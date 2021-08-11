# Assignment-7_8_9
Setup a postgres DB for the previous application. Replace JSON with the new DB created. Push the code to the repo on github. Generate a PR for review.
Add a customers table and roles table in DB. Customer table columns - name, website, address. Role columns - name, key (must be from enum), description. Each user can belong to one customer and have one role. Change the DB schema accordingly. Show customer name and role name for each user in UI. Push the code to the repo on github. Generate a PR for review.
Add created on and modified on columns to all the tables. These should auto populate. Push the code to the repo on github. Generate a PR for review.
The web is open at GET =>http://localhost:5555/todo 
POST => http://localhost:5555/todo
PUT -> http://localhost:5555/todo/:id
DELETE => http://localhost:5555/todo/:id
