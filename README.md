# laravel-to-postman
Create Importable Json File for PostMan from laravel routes



##### Run Command In Your Laravel Project Folder

###### For Mac OSX

``	node -e "$(curl 'https://raw.githubusercontent.com/nkitku/laravel-to-postman/master/main.min.js')" nkitku "$(php artisan route:list)" http://projectUrlDomain.com projectName api > project.postman_collection.json;``


    http://projectUrlDomain.com -> will be your api url like http://localhost/myproject/

    projectName -> will be your Project Name

    api -> will be your api prefix

