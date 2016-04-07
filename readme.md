#PHPUnit Testing in Laravel

Decided to create a repo and code the following test cases while watching [phpunit-testing-in-laravel](https://laracasts.com/series/phpunit-testing-in-laravel)
 from [Laracasts.com](https://laracasts.com)

This will also serve my future reference guide for conducting unit test.

The series consists of 11 epesodes and this repo finished the episode 4.


#### Quick Notes
running test on a single test method
```
phpunit --filter name_of_the_test_method()
```

running test on a single class
```
phpunit tests/unit/ClassNameTest.php
```

running test on a single directory
```
phpunit tests/unit/
```

create model class with migration
```
    php artisan make:model ClassName -m
```
reset database table
```
    php artisan tinker
    App\Article::truncate();
```