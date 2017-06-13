# README

This application is only a public chat using faye pub/sub protocol.




Steps needed to start the application:


1. open command window in the directory of the project.

2. run "bundle install".

3. run "rails s -p 3001" for intitializing the rails server on port no. 3001.

4. open another command window in the directory of the project.

5. run "rackup faye.ru -E production -s thin" for intializing faye server.