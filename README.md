#FizzBuzz Kata in PHP 7.0.13
# Fizzbuzz PHP

FizzBuzz is a simple Kata I used to learn my first two programming languages: Ruby and Javascript. It's a great kata to get a quick grasp on the syntax for the language and for testing.
I'm doing this kata in PHP 7.0.13 and using PHPunit 5.7.6 for testing on Linux Mint 18 and will include links to install all the requirements.

### Instructions:

* Ensure you have PHP installed on your machine by running `$ php -v`.
```
Most linux distros have a version of php preinstalled but in case you don't have it here's some instructions: https://www.storagecraft.com/blog/install-lamp-server-linux-mint-18-command/
```

* Ensure you have PHPUnit installed on your machine by running `$ phpunit --verion`.
```
If you don't have it: https://phpunit.de/manual/current/en/installation.html
```
* Ensure you have Composer installed on your machine `$ composer -V`.
```
Instructions: http://tecadmin.net/install-php-composer-in-linux/
```
* Run `$ composer init` to iniate a dependencies file.
* Add dependencies shown in composer.json file (see above) and run $ composer install

* $ touch phpunit.xml and copy contents (see above) to show colours on your tests.

* To run a test (for this example): $ phpunit fizzBuzzTest.php


FizzBuzz rules:
```
Lets divide this into different steps so, we can easily write and test this.
- Print numbers from 1 to 100
- Print "Fizz" instead of number which is divisible by 3
- Print "Buzz" instead of number which is divisible by 5
- Print "FizzBuzz" instead of number which is divisible by both 3 and 5
```

If you would like to contribute to this repo please feel free to make a pull request.

Happy FizzBuzz'ing
