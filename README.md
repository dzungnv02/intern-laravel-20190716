## Environment requirement
Installed Git<br />
Installed Docker & Docker compose

## Build environment:
Steps:
1. Clone project from Github: https://github.com/dzungnv02/intern-laravel-20190716.git
2. Go to project directory
3. Go to <strong>/stacks</strong> directory
4. Open Terminal window (PowerShell or CMD in Windows 10)
4. Run command to build (run only first time or need to rebuild): <br />
<i>docker-compose build</i>

5. After build command, run command:<br />
<i>docker-compose up -d</i>

6. In Terminal window: type: <i>docker exec -it stacks_webapp_1 /bin/bash</i>
7. Type: <br /><i>composer install</i>
8. Type: <br /><i>php artisan config:cache</i>
9: Open web browser, type <i>http://localhost:82</i>
