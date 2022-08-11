Plugin Installation (for production)
------------------------------------
The installation is pretty straight forward. Steps have been given at [Wordpress Plugin page](https://wordpress.org/plugins/address-bar-colorizer/installation/).

Please do not use the current release here for production. Although efforts are made to keep it stable and usable but the [Wordpress repository](https://wordpress.org/plugins/address-bar-colorizer/) is always recommended.

Support
------------------------------------
This is a developer's portal for Address Bar Colorizer and hence should not be used for support. For such queries please visit the [support forums](https://wordpress.org/support/plugin/address-bar-colorizer).

Reporting bugs
------------------------------------
Decent efforts are made to ensure that plugin is relatively bug free. However, if you do notice a bug creep create a [new issue here](https://github.com/ParitoshBh/Address-bar-colorizer/issues/new) or mention about the same in [support forums](https://wordpress.org/support/plugin/address-bar-colorizer).

Contributions
------------------------------------
Anyone is welcome to contribute to Address Bar Colorizer! There are various ways you can contribute:
* Raise an issue on GitHub.
* Send a Pull Request with your bug fixes and/or new features.
* Provide feedback and suggestions.
* Provide idea(s) for enhancements.

Development
------------------------------------
To setup the repository for development, follow steps mentioned below,
1. Clone svn repository - `svn checkout http://plugins.svn.wordpress.org/address-bar-colorizer`
2. Navigate to directory - `cd address-bar-colorizer`
3. Run docker containers (if needed for testing, note that plugin will be available after setup) - `docker compose up -d`
4. Make changes as required
5. Create new tag with latest changes - `svn cp trunk tags/<plugin_version>`
6. Commit (and push) changes - `svn ci -m "<commit_message>"`

_Note - If credentials for pushing to svn are required, make sure that username is case sensitive!_