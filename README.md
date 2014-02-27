MDB2_Driver_sqlite3
===================

This is an MDB2 Driver for SQLite3.

The SQLite driver available from PEAR only works with obsolete SQLite 2 databases. This 
driver works with SQLite3 databases.

This is not my work. It was written by the [ownCloud](http://owncloud.org/) team and used 
up until version 5. 

ownCloud no longer uses MDB2 in current releases. The version of the files here are from 
here: https://github.com/owncloud/core/tree/v5.0.13/lib/MDB2

All I've done is to move the files to a single repository for the sake of convenience.

License is the original license used by ownCloud: GNU Affero GPL.

### Installation Using Composer

To install with Composer, add the following repository to your project's composer.json file:

    "repositories": [
        {
            "type": "git",
            "url": "https://github.com/dweingart/MDB2_Driver_sqlite3.git"
        }
    ]
    
And then require the package:

	"require" : {
		"pear/mdb2_driver_sqlite3": "dev-master"
	}