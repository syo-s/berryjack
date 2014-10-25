berryjack
=========

berryjack is simple twitter media downloader.
It access to Twitter media timeline via HTTP/JSON instead of Twitter API.

* Not required some script environment, This script use basic UNIX commands only.
* No limit for getting timeline. DO NOT USE FOR LARGE AMOUNTS OF ACCESS. 

Dependency
----------

* Commands:
  * bash
  * wget
  * grep
  * sort
  * uniq
  * sed
  * head
  * test
  * mkdir
* Filesystem:
  * /tmp
  * current directory

Setup
-----

Clone the repository and add executable parmission to berryjack.

    git clone git@github.com:dyama/berryjack
    cd berryjack
    chmod a+x berryjack

Usage
-----

The media files saved into new directory named 'twitter_account_name' in current directroy.

    ./berryjack twitter_account_name[, ...]

License
-------

* MIT License

Author
------

dyama <dyama@member.fsf.org>
http://dyama.org/
