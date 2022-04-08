# Moodle 
<p>
This is repository where is docker-compose.yaml for Moodle. This repository was made in order to make instalation of Moodle on PC easier because of XapiProject.
</p>


## Instalation of connection with XapiProject
1. Install Docker
2. Download this repository 
3. Run command
```
docker compose up
```
4. Moodle should run on htttp://localhost:80
5. Default credentials are `user` with password `bitnami`
6. Download and install Logstore xAPI plugin from https://moodle.org/plugins/logstore_xapi
7. Go to > Site administration / Plugins / Logging / Logstore xAPI and fill key and secret from Watershed LRS 
8. Go to > Site administration / advanced features and select yes for Enable web serices
9. Go to > Site administration / Server / Web services / Manage protocols and select Rest protocol enable
10. Create new user in > Site administration / Users / Accounts / Add a new user
11. Go to > Site administration / Users /Permissions / Check system permissions and check permissions of created user
12. Go to > Site administration / Server / Web services / External services and create new Custom service
13. Click on Functions and then Add functions and add several functions which will our app use 
14. Go to > Site administration / Server / Web services / Manage tokens and create token for created user
15. Go to > Site administration / Server / Web services / Manage protocols and select web service documentation to yes
  

