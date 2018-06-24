# upgradePHP5.5to5.6

Manual upgrade PHP5.5 to 5.6 for Windows and Wamp server

> Open PHP download page https://windows.php.net/download/

> Download latest x64 Thread Safe zip folder 
  e.g https://windows.php.net/downloads/releases/php-5.6.36-Win32-VC11-x64.zip 
  
> Open Wampserver folder 
  e.g c:\wamp\bin\php

> create new folder according to your downloaed version like 
  e.g c:\wamp\bin\php\php5.6.36
  
> Copy 3 old files from folder php5.5.12 to php5.6.36
  Files : php.ini
          phpForApache.ini
          wampserver.conf

> Open c:\wamp\bin\php\php5.6.36\php.ini 
  1. update line
    extension_dir = "c:/wamp/bin/php/php5.5.12/ext/"
  to 
    extension_dir = "c:/wamp/bin/php/php5.6.36/ext/"
  
  2. update line
    zend_extension = "c:/wamp/bin/php/php5.5.12/zend_ext/php_xdebug-2.2.5-5.5-vc11-x86_64.dll"
  to 
    zend_extension = "c:/wamp/bin/php/php5.6.36/zend_ext/php_xdebug-2.2.5-5.5-vc11-x86_64.dll"
    
 > Open C:\wamp\bin\php\php5.6.3\phpForApache.ini
   1. update line
    extension_dir = "c:/wamp/bin/php/php5.5.12/ext/"
  to 
    extension_dir = "c:/wamp/bin/php/php5.6.36/ext/"
  
   2. update line
    zend_extension = "c:/wamp/bin/php/php5.5.12/zend_ext/php_xdebug-2.2.5-5.5-vc11-x86_64.dll"
  to 
    zend_extension = "c:/wamp/bin/php/php5.6.36/zend_ext/php_xdebug-2.2.5-5.5-vc11-x86_64.dll"
    
  > Shut down wamp server
  
  > Start wamp server 
  
  > Change php version to 5.6
  
  > Stop wamp server 
  
  > Stgart / Restart all wamp server service
  
  > Open http://localhost/?phpinfo=1
  
  > Check php version
  
  > Thank you
  
  Mahesh Jagadale
