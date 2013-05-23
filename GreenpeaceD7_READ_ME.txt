Greenpeace

To view locally: 

Download wamp: http://www.wampserver.com/en/#download-wrapper

create mysql user: 
user: green
pass: green

create mysql db: 
DB name: greenpeace

import greenpeace.sql into mysql greenpeace db

unzip greenpeace.7z into the wamp/www

you should be all set to navigate to http://localhost/greenpeace/

however if your local version of tomcat is using port 80 or 8080 you might need to change the port that wamp's localhost uses.  I changed mine to port 90

http://localhost:90/greenpeace/

users: 
giarcjc - admin 
mike - (pass: greenpeace)

Those are the only ones right now but we can add as many as necessary, and keep the pass as greenpeace for simplicity.



