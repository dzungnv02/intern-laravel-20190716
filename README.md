## Environment requirement
Installed Git
Installed Docker & Docker compose

## Build environment:
Steps:
1. Clone project from Github: https://github.com/dzungnv02/intern-laravel-20190716.git
2. Go to project directory
3. Go to /stacks directory
4. Open Terminal window (PowerShell or CMD in Windows 10)
4. Run command to build (run only first time or need to rebuild): 
docker-compose build

5. After build command, run command:
docker-compose up -d

6. In Terminal window: type: docker exec -it stacks_webapp_1 /bin/bash
7. Type: composer install
8. Type: php artisan config:cache
9: Open web browser, type http://localhost:82
