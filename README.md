## Synopsis

This is the Jekyll based source code for the Roaring Fork Technologist's group website.

## Motivation

This project serves as an independent ( outside of Facebook, for example ) platform for supporting the Roaring Fork Technologist's mission, including the promotion and nurturing of the technological community and economy in the Roaring Fork Valley in Colorado.

## Installation

Jekyll uses the Ruby programming language and package environment to translate templates and data files into a static set of website assets. While you will not need to write Ruby programs, you will need to install Ruby on to your local environment.

If you are on windows, the easiest way to install Ruby is probably via Rubyinstaller. Follow the instructions for installing the latest version here: https://rubyinstaller.org/

On OS X, your best bet is to use homebrew, as described here: https://www.ruby-lang.org/en/documentation/installation/#homebrew

Ruby programs use a package manager called Bundler. This manages sets of shared functionality or libraries called gems. In order to build and run Jekyll locally, you will need to install a set of gems, including Bundler.

Gems can be installed locally within a project, or globally for all projects on your computer. The gem command, is installed alongside the version of Ruby.

Install the bundler program:

```sh
gem install bundler
```

```sh
gem install jekyll
```

With these gems installed, you should now be able to build and serve the website locally.

```sh
jekyll serve
```

This will run a server at http://localhost:4000. Enter that URL into your web browser and it should present the website from the local source code.


## Contributors

The github issuetracker for this project is current. Please check there for info.

## License

Until this is defined, all rights retained by the Roaring Fork Technology group. This code may not be used without permission from the Roaring Fork Technology Group and its leader Justin.
