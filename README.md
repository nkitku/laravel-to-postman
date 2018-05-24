# laravel-to-postman
Create Importable Json File for PostMan from laravel routes



##### Run Command In Your Laravel Project Folder

###### For Mac OSX

``	node -e "$(curl -k --compressed 'https://raw.githubusercontent.com/nkitku/laravel-to-postman/master/main.min.js')" nkitku "$(php artisan route:list)" http://projectUrlDomain.com projectName api > project.postman_collection.json``


    http://projectUrlDomain.com -> will be your api url like http://localhost/myproject/
         you can also change this later in postman : YourCollection > Right Click > Edit > Varaibles(tab) > change the domain value > update

    projectName -> will be your Project Name
         you can also change this later in postman : YourCollection > Right Click > Rename 

    api -> will be your api prefix, default empty
