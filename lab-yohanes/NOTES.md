#O-Auth Route
1. client lg in page sends an "anchor" to googles login front end
2. google front end connects with googles back-end which sends authentication back to the front end
3. (a) Googles backend connects with our backend
3. (b) our backend sends code to googles backend 
3. (c) google gives our backend an authorized token
4. the user is given a token based off their google account that communicates with our backend throughout the users application experince and re-routes, giving them authorized access throught our application
5. the user now can create an account on our application
6. When steps 1-5 our successfully completed the user now has an access token to use our application

#Connecting Front End To Back
thorugh our .env files, we pasted in our back end GOOGLE_AUTH_ID to our front end html file 

#OVERVIEW
re-watch 41.3 around 6 minutes explaining id scope and other details about google API