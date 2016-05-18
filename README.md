Docker image - Laravel
-----------------------

### Details
- Laravel 5.2
- Ngnix 1.8.1
- PHP 7.0.6

### Build image
    docker build -t skywidesoft/laravel .

### Push image
    docker push skywidesoft/laravel

### Run container (example)
    docker run -d --name=laravel-test2 -p=8080:80 -v /Users/clarence/workspace/laravel-learn/laravel-test2:/var/www/html skywidesoft/laravel
