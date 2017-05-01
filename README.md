# Rasbot

<img align="right" width="300" src="mascot.jpg">


> Rasbot is a script to set up an Mac OS laptop for web development.

It can be run multiple times on the same machine safely. It installs, upgrades, or skips packages based on what is already installed on the machine.

We support:

* macOS Mavericks (10.9)
* macOS Yosemite (10.10)
* macOS El Capitan (10.11)
* macOS Sierra (10.12)

Older versions may work but aren't regularly tested. Bug reports for older
versions are welcome.


## Install

In your Terminal window, copy and paste the command below, then press return.
```sh
curl --silent https://raw.githubusercontent.com/ravisuhag/rasbot/master/mac | sh 2>&1 | tee ~/rasbot.log
```
The script itself is available in this repo for you to review if you want to see what it does and how it works.

Once the script is done, quit and relaunch Terminal.

It is highly recommended to run the script regularly to keep your computer up to date. Once the script has been installed, you'll be able to run it at your convenience by typing laptop and pressing return in your Terminal.

Your last rasbot run will be saved to `~/rasbot.log`.
Read through it to see if you can debug the issue yourself.
If not, copy the lines where the script failed into a
[new GitHub Issue](https://github.com/ravisuhag/rasbot/issues/new) for us.
Or, attach the whole log file as an attachment.

## What it sets up

#### Mac OS tools:

* [Homebrew] for managing operating system libraries.

[Homebrew]: http://brew.sh/

#### Unix tools:

* [Git] for version control
* [OpenSSL] for Transport Layer Security (TLS)
* [The Silver Searcher] for finding things in files
* [Zsh] as your shell

[Git]: https://git-scm.com/
[OpenSSL]: https://www.openssl.org/
[The Silver Searcher]: https://github.com/ggreer/the_silver_searcher
[Zsh]: http://www.zsh.org/

#### Programming languages:

* [Node.js] for running apps and installing JavaScript packages
* [Go] programming langugae by google
* [Ruby] a dynamic programming language with a focus on simplicity and productivity
* [Clojure] a dynamic, general-purpose programming language

[Node.js]: http://nodejs.org/
[Go]: https://golang.org/
[Ruby]: https://www.ruby-lang.org/en/
[Clojure]: https://clojure.org/

#### Package Managers:

* [Yarn] for managing JavaScript packages
* [NPM] node package manager
* [Rbenv] for managing versions of Ruby
* [Ruby Build] for installing Rubies
* [Bundler] for managing Ruby libraries
* [Leiningen] for automating Clojure projects
* [Glide] package Management for Go

[Yarn]: https://yarnpkg.com/en/
[NPM]: https://www.npmjs.org/
[Rbenv]: https://github.com/sstephenson/rbenv
[Ruby Build]: https://github.com/sstephenson/ruby-build
[Bundler]: http://bundler.io/
[Leiningen]: https://leiningen.org/
[Glide]: https://glide.sh/


#### Tools:

* [Consul] Service Discovery and Configuration Made Easy
* [Zookeeper] develop and maintain an open-source servers
* [Kafka] a distributed streaming platform
* [GRPC] a high performance, open-source universal RPC framework
* [Image Magick] create, edit, compose, or convert bitmap images
* [Heroku Toolbelt] for interacting with the Heroku API

[Consul]: https://www.consul.io/
[Zookeeper]: https://zookeeper.apache.org/
[Kafka]: https://kafka.apache.org/
[GRPC]: http://www.grpc.io/
[Image Magick]: http://www.imagemagick.org/
[Heroku Toolbelt]: https://www.heroku.com/

#### Databases:

* [Postgres] for storing relational data
* [Redis] for storing key-value data
* [My Sql] for storing relational data
* [Mongo DB] for storing non relational data

[Postgres]: http://www.postgresql.org/
[Redis]: http://redis.io/
[My Sql]: https://www.mysql.com/
[Mongo DB]: https://www.mongodb.com/

#### Utilities
* [youtube-dl] download videos from YouTube
* [htop] interactive system-monitor
* [tig] text-mode interface for git
* [logstalgia] Website Access Log Visualization
* [git-extras] repo summary, repl, changelog population, author commit percentages

[youtube-dl]: https://rg3.github.io/youtube-dl/
[htop]: http://hisham.hm/htop/
[Tig]: https://github.com/jonas/tig
[logstalgia]: http://logstalgia.io/
[git-extras]: https://github.com/tj/git-extras

It should take less than 15 minutes to install (depends on your machine).

## Contributing


Edit the `mac` file.
Document in the `README.md` file.
Follow shell style guidelines by using [ShellCheck] and [Syntastic].

```sh
brew install shellcheck
```

[ShellCheck]: http://www.shellcheck.net/about.html
[Syntastic]: https://github.com/scrooloose/syntastic

Thank you, [contributors]!

[contributors]: https://github.com/ravisuhag/rasbot/graphs/contributors

## License

Rasbot is inspired by laptop script, customized for my own needs. It is free software, and may be redistributed under the terms specified in the [LICENSE] file.

[LICENSE]: LICENSE
