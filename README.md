# `test-fork` branch

This branch uses https://github.com/hultberg/phpstan-shim/commit/077da131679a62865e140c9602a758be9eb0d4bf to allow installing `nikic/php-parser`. 

As expected with a PHAR, phpstan runs nice and smooth:
```console
$ vendor/bin/phpstan analyse -c phpstan.neon -l 1 test.php
 1/1 [▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓] 100%

                                                                                                               
 [OK] No errors                                                                                                
                                                                                                               

```
