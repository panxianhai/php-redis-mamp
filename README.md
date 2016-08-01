# Installation:

1. Copy `redis.so` from the appropriate subdirectory of this repo to `/Applications/MAMP/bin/php/php5.x.x/lib/php/extensions/no-debug-non-zts-200xxxxx` (Channge 5.x.x to your PHP version)
2. Add `extension="redis.so"` to the end of `php.ini` (Open MAMP click on File → Edit Template → PHP → PHP 5.x.x php.ini), for non-pro users edit `/Applications/MAMP/bin/php/php5.x.x/conf/php.ini` (Channge 5.x.x to your PHP version)
3. Restart MAMP.

## How to do it yourself.

1. Mkdir `include/php` in `/Applications/MAMP/bin/php/php*.*.*/`, for example `/Applications/MAMP/bin/php/php5.5.10/include/php`.
2. Download php source file from php.net, if you want to compile extension for `php 5.4.42`, then download php5.4.42.tar.gz and extract to `include/php` dir.
3. Execute `./configure` in `include/php`.
4. `cd /Applications/MAMP/bin/php/php*.*.*/bin`, execute `./pecl install redis` for default version or `./pecl install redis-2.2.8` for special version.
5. Add extension="redis.so" to the end of php.ini (Open MAMP click on File → Edit Template → PHP → PHP 5.x.x php.ini), for non-pro users edit /Applications/MAMP/bin/php/php5.x.x/conf/php.ini (Channge 5.x.x to your PHP version)
6. Restart MAMP.




