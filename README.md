# CodeIgniter HMVC and ci-phpunit-test

* CodeIgniter 3.0.3
* codeigniter-modular-extensions-hmvc codeigniter-3.x (2015-11-04)
* PHPUnit 4.8.21
* ci-phpunit-test 1.0.x@dev

codeigniter-modular-extensions-hmvc is popular but a very complex system, and is against CodeIgnier's basic design. It brings complexity to CodeIgniter.

So to work CodeIgniter HMVC and ci-phpunit-test together is still under way.

If you can avoid to use it, I recommend not use it. If you look for modular system, see <https://github.com/kenjis/codeigniter-simple-module>.

## Requirements

* PHP 5.4 or later
* composer

## How to Run Tests

~~~
$ git clone https://github.com/kenjis/ci-hmvc-ci-phpunit-test.git
$ cd ci-hmvc-ci-phpunit-test/
$ composer install
$ vendor/bin/phpunit -c application/tests/
~~~

## References

* https://github.com/bcit-ci/CodeIgniter
* https://github.com/kenjis/codeigniter-composer-installer
* https://bitbucket.org/wiredesignz/codeigniter-modular-extensions-hmvc
* https://github.com/sebastianbergmann/phpunit
* https://github.com/kenjis/ci-phpunit-test
