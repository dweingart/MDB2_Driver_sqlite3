MDB2_Driver_sqlite3
===================

This is an MDB2 Driver for SQLite 3.

The MDB2 SQLite driver available from PEAR only works with obsolete SQLite 2 databases. This 
driver provides support for SQLite 3 databases.

It is not my work. It was written by the [ownCloud](http://owncloud.org/) team and used 
through version 5. All I've done is move the files to a single repository for the sake 
of convenience.

ownCloud no longer uses MDB2 in current releases. These files are copied from here: 
<https://github.com/owncloud/core/tree/v5.0.13/lib/MDB2>

License is the original license used by ownCloud: AGPL Version 3.

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