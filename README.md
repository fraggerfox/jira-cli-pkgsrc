jira-cli-pkgsrc
===============

NetBSD [pkgsrc][4] script for `jira-cli`.

You can find `jira-cli` [here][1]

NOTE: This is `pkgsrc-wip` package for now.

Installation
------------

Copy `www/jira-cli` folder to `/usr/pkgsrc` directory.

NOTE: If your pkgsrc directory is different from above, copy to the respective
place.

Usage
-----

Once you have copied the folder, install it as you would do for any port.

`$ cd /usr/pkgsrc/sysutils/jira-cli`<br>
`$ make install clean`

For a list of dependencies for the build check [here][2]

NOTE: If you are using pkgsrc in a non NetBSD system, replace `make` with
`bmake` in the above jira-cli example.

Credits
-------

* `jira-cli` is developed and maintained by the [Ankit Pokhrel][3]

License
-------

BSD 2-clause. See LICENSE.

[1]: https://github.com/ankitpokhrel/jira-cli
[2]: https://github.com/ankitpokhrel/jira-cli#installation
[3]: https://github.com/ankitpokhrel
[4]: http://pkgsrc.se/wip/jira
