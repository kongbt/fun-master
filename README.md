How to deploy 'fun' (CODENAME) project with SandPHP to fun.local at your local server
===

+ Install basics , following http://sandphp.com requirements
(mongodb, phpredis)

+ Email hoang@pear.vn for a copy of SandPHP's core framework.
+ Extract sandPHP to a folder, its folder will be called 'core'
+ Codebase for this project will be under a folder named 'fun'
+ touch fun/logs and chmod to 777 for log files write permissions
+ Adjust SAND_ROOT path in fun/public/index.php to point to this Core folder
+ Soft link core/assets to fun/public/sandassets
+ Soft link fun/assets to fun/public/assets
+ Deploy site to http://fun.local/ . For example on Ubuntu Apache, the vhosts looks like misc/fun.local
+ Setup http://funstatic.local to point to fun/public/ufiles . This is where the user's uploaded files are
+ Congbt
