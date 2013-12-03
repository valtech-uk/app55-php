App55 PHP Library
=================
Please see https://www.app55.com/docs for information on the service endpoints.

Run the Tests
-------------
1. Edit TestConguration.php and update it with your `$APP55_API_KEY` and `$APP55_API_SECRET`.
2. Install and run composer to get phpunit: curl -sS https://getcomposer.org/installer | php ; php composer.phar install
3. There is an `integration.php` script in the root folder. Run this using `php integration.php` from the command line.
4. Or (on mac/linux) run the unit tests with ./runtests.sh

Revision History
----------------
0.8.2 Initial Release

0.8.3 Fix incorrect Certificate in initial release 

0.8.4 Introduced basic scheduling support and integration tests.

0.8.5 Added full scheduling as well as get user support.