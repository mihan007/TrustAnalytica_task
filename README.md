# Trustanalytica task
## Deploy
Url: http://trustanalytica-trial.herokuapp.com/
I choose Heroku because it takes just 2 minutes to get it work. For db I used https://db4free.net/ for demo.

For sure I can do docker / AWS / any hosting and setup it manually or with Ansible but this task is very simple and standard.
So I chose the simplest way.

If it's needed I can add docker to the branch of this repo or create ansible playbooks to deploy it to any server from zero.

# Local
To run it locally please do
    
    git pull
    cp .env.example .env
    // configure your db and add it to .env variables
    composer install  
    php artisan key:generate
    php artisan serve
Then visit link that it gives, it'll show login page. Use links at top to Register. After register you may use 
login password for login and logout then.
