# phing-build-example
build.xml and build.properties these files is used by phing
to automate build process, as a part of Continuous Integration in hungryhouse.co.uk
```
available targets:
Default target:
-------------------------------------------------------------------------------
 build

Main targets:
-------------------------------------------------------------------------------
 check-js-debug   Check Javascript code for debug statements
 check-php-debug  Check PHP code for debug statements
 clean            Clean up and create artifact directories
 lint-css         Check all CSS files using CSS Lint
 lint-js          Check all Javascript files using JSlint
 lint-php         Check all PHP files for syntax errors using PHPLint
 phpcb            Aggregate tool output with PHP_CodeBrowser
 phpcpd           Generate pmd-cpd.xml using phpcpd (Copy/Paste Detector (CPD) for PHP code)
 phpcs            Generate checkstyle.xml using PHP_CodeSniffer
 phpdoc           Generate PHP documentation using phpDocumentor
 phploc           Generate phploc.csv using phploc (phploc is a tool for quickly measuring the size and analyzing the structure of a PHP project)
 phpmd            Generate pmd.xml using PHPMD
 unit-test        Run PHPUnit

```

