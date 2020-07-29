A quick way to get a Laravel app spun up in a docker stack.

1.) Remove the README from the ./src directory.
2.) Install your Laravel app into the ./src directory.
3.) In the Laravel .env file update mysql variables to match the docker-compose.yml mysql variables.
4.) In your terminal run, "docker-compose build"
5.) After the build completes run, "docker-compose up -d"
6.) Once the stack is up run, "docker-compose exec php composer install"
7.) If you need to install NPM packages you can run, "docker-compose exec php npm install"
8.) Migrate with, "docker-compose exec php php artisan migrate" 