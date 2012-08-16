Locker
======

Locker.php is a PHP class that can be used to make sure that
the single instance of the PHP script is running at any given time.

For example, if you have a slow cronjob (report generator, cleanup 
task, etc) and want to make sure that cron won't start another
instance of this script until the first one is finished, use this
class to lock the process.

[![Build Status](https://secure.travis-ci.org/mamchenkov/locker.png)](http://travis-ci.org/mamchenkov/locker)
