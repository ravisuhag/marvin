# Marvin 

<img align="right" width="300" src="mascot.jpg">


> marvin is a script to set up an Mac OS laptop for web development.

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
curl --silent https://raw.githubusercontent.com/ravisuhag/marvin/master/mac | sh 2>&1 | tee ~/marvin.log
```
The script itself is available in this repo for you to review if you want to see what it does and how it works.

Once the script is done, quit and relaunch Terminal.

It is highly recommended to run the script regularly to keep your computer up to date. Once the script has been installed, you'll be able to run it at your convenience by typing laptop and pressing return in your Terminal.

Your last marvin run will be saved to `~/marvin.log`.
Read through it to see if you can debug the issue yourself.
If not, copy the lines where the script failed into a
[new GitHub Issue](https://github.com/ravisuhag/marvin/issues/new) for us.
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
* [Go] programming language by google
* [Ruby] a dynamic programming language with a focus on simplicity and productivity
* [Clojure] a dynamic, general-purpose programming language
* [Java] java Runtime Environment

[Node.js]: http://nodejs.org/
[Go]: https://golang.org/
[Ruby]: https://www.ruby-lang.org/en/
[Clojure]: https://clojure.org/
[Java]: https://www.java.com/en/

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

* [Consul] service Discovery and Configuration Made Easy
* [Zookeeper] develop and maintain an open-source servers
* [Kafka] a distributed streaming platform
* [GRPC] a high performance, open-source universal RPC framework
* [Image Magick] to create, edit, compose, or convert bitmap images
* [Heroku Toolbelt] for interacting with the Heroku API
* [Vagrant] for development environments
* [Chef] for automating your infrastructure

[Consul]: https://www.consul.io/
[Zookeeper]: https://zookeeper.apache.org/
[Kafka]: https://kafka.apache.org/
[GRPC]: http://www.grpc.io/
[Image Magick]: http://www.imagemagick.org/
[Heroku Toolbelt]: https://www.heroku.com/
[Vagrant]: https://www.vagrantup.com/
[Chef]: https://www.chef.io/chef/

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
* [fasd] command-line productivity booster

[youtube-dl]: https://rg3.github.io/youtube-dl/
[htop]: http://hisham.hm/htop/
[Tig]: https://github.com/jonas/tig
[logstalgia]: http://logstalgia.io/
[git-extras]: https://github.com/tj/git-extras
[fasd]: https://github.com/clvv/fasd

### Apps

* [VLC] media player
* [Transmission] bit torrent client
* [Atom] a hackable text editor
* [Sublime Text] sophisticated text editor for code
* [Android Studio] official IDE for Android
* [Iterm] mac terminal replacement
* [Chrome] fast, free web browser
* [Blisk] a browser for web developers
* [Firefox] a web browser by mozilla
* [Sip] collect, organize & share your colors
* [Resolutionator] embiggen your display
* [Flux] software to make your life better
* [1Password] password manager
* [Dropbox] cloud file storage
* [Google Drive] safe place for your files
* [Github Desktop] collaboration from your desktop
* [Virtual Box] powerful virtualization tool
* [Slack] where work happens
* [Rescuetime] track app usages
* [Tunnelblick] free software for OpenVPN
* [Spotify] listen to your fav music
* [Skype] free calls to friends and family
* [Postico] a modern postgres client
* [Mysql Workbench]  mysql client
* [Dash]  offline access to API documentation sets.
* [Tunnelbear] Secure VPN service

[VLC]: http://www.videolan.org/
[Transmission]: https://transmissionbt.com/download/
[Atom]: https://atom.io/
[Sublime Text]: https://www.sublimetext.com/
[Android Studio]: https://developer.android.com/studio
[Iterm]: https://www.iterm2.com/
[Chrome]: https://www.google.com/chrome/browser/desktop/
[Blisk]: https://blisk.io/
[Firefox]: https://www.mozilla.org/en-US/firefox/new/
[Sip]: http://sipapp.io/
[Resolutionator]: https://manytricks.com/resolutionator/
[Flux]: https://justgetflux.com/
[1Password]: https://1password.com/
[Dropbox]: https://www.dropbox.com
[Google Drive]: https://www.google.com/drive/
[Github Desktop]: https://desktop.github.com/
[Virtual Box]: https://www.virtualbox.org/
[Slack]: https://slack.com/
[Rescuetime]: https://www.rescuetime.com/
[Tunnelblick]: https://tunnelblick.net/
[Spotify]: https://www.spotify.com/
[Skype]: https://www.skype.com/en/
[Postico]: https://eggerapps.at/postico/
[Mysql Workbench]: https://www.mysql.com/products/workbench/
[Dash]: https://kapeli.com/dash
[Tunnelbear]: https://www.tunnelbear.com/

It should take less than 20 minutes to install (depends on your machine).

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

[contributors]: https://github.com/ravisuhag/marvin/graphs/contributors

## License

marvin is inspired by laptop script, customized for my own needs. It is free software, and may be redistributed under the terms specified in the [LICENSE] file.

[LICENSE]: LICENSE
