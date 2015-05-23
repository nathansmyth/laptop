Laptop
======

Laptop is a script to set up an chromebook laptop for web development.

Roadmap
======
It can be run multiple times on the same machine safely.
It installs, upgrades, or skips packages
based on what is already installed on the machine.

Requirements
------------

We support:

* [HP Chromebook 14](http://store.hp.com/webapp/wcs/stores/servlet/us/en/mdp/Laptops/chromebook-14)

Other versions may work but aren't tested. Bug reports for older
versions are welcome.

Install
-------

Download, review, then execute the script:

```sh
curl --remote-name https://raw.githubusercontent.com/nathansmyth/laptop/master/chromebook
less chromebook
sh chromebook
```

What it sets up
---------------

* [Bundler] for managing Ruby libraries
* [Node.js] and [NPM], for running apps and installing JavaScript packages
* [Zsh] as your shell

[Bundler]: http://bundler.io/
[Node.js]: http://nodejs.org/
[NPM]: https://www.npmjs.org/
[Zsh]: http://www.zsh.org/

It should take less than 15 minutes to install (depends on your machine).
Credits
-------

Thank you, [contributors]!

[contributors]: https://github.com/thoughtbot/laptop/graphs/contributors

By participating in this project,
you agree to abide by the thoughtbot [code of conduct].

[code of conduct]: https://thoughtbot.com/open-source-code-of-conduct

License
-------

Laptop is © 2011-2015 thoughtbot, inc.
It is free software,
and may be redistributed under the terms specified in the [LICENSE] file.

[LICENSE]: LICENSE

About thoughtbot
----------------

![thoughtbot](https://thoughtbot.com/logo.png)

Laptop is maintained and funded by thoughtbot, inc.
The names and logos for thoughtbot are trademarks of thoughtbot, inc.

We are passionate about open source software.
See [our other projects][community].
We are [available for hire][hire].

[community]: https://thoughtbot.com/community?utm_source=github
[hire]: https://thoughtbot.com?utm_source=github
