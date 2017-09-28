This package is http://pear.php.net/package/OLE and has been migrated from https://svn.php.net/repository/pear/packages/OLE

Please report all new issues via the PEAR bug tracker.

If this package is marked as unmaintained and you have fixes, please submit your pull requests and start discussion on the pear-qa mailing list.

To test, run either
$ phpunit tests/
  or
$ pear run-tests -r

To build, simply
$ pear package

To install from scratch
$ pear install package.xml

To upgrade
$ pear upgrade -f package.xml

## Migration

- This package has no dependencies from any pear classes and uses php5 native exceptions for error handling.
Be careful, currently many unexpected issues can throw unexpected exceptions instead of silent fail

- Used standard psr-0 composer autoloader

- Constants OLE_* moved to class OLE

- Do not try to run it on php5 < 5.4
