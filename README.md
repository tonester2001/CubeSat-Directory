# CubeSat-Directory
ECS APU Department code to leverage for further CubeSat research.
Hello! Welcome to the code developed for the array-based CubeSat Directory API
The goal to make this code open-source so that any current CS/ENGR students can continue to build this directory platform to be used for years to come.
The code is mainly based on PHP and some HTML code.
--------------------------------------------------------------------------------------------------
Some updates we would love to see for this project:
-Security through token authentication 
-Subscription for users to access premium features
-Search fucntion to look for any possible satellites

How the code currently runs:

The are three different pages
- Dead satellites
- Alive satellites
- Future satellites

The currently tracked number of satellites total is 972.

Under each satellite there should be an information link that links back to the individual satellite website and if not, it will return null.

Every satellite is ran through an array which also connects them to their specific satellite image.

It is currently running off a REPL server but in order to allow constant accessibility it will need to run off an APU server which is an easy transition.
https://replit.com/@AnthonyCucinell/CUBESAT-Directory



