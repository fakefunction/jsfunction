
to access app setting
The act of providing environment variables is referred to as provisioning. 

simply do 
   process.env.ENV_VARIABLE

Done!

for env helper you'll need these :

    npm install dotenv --save

    keep it out by adding .env to your .gitignore file.

    Loading your environment variables is a one-liner:
    require('dotenv').config();


https://stackoverflow.com/questions/4870328/read-environment-variables-in-node-js
https://stackoverflow.com/questions/47019381/environment-variables-in-azure-webapp-with-node-js