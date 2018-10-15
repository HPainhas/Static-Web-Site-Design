# Static-Web-Site-Design

Redesigned home page of Michael D. Bond (old page: http://web.cse.ohio-state.edu/~mikebond/)

## Getting Started

### Prerequisites
Make sure you have [git](https://git-scm.com/) and [Ruby 2.5.1](https://ruby-doc.org/) installed. Refer to the links on how to install them.

### Installation
Clone the repo using
```
$ git clone https://github.com/HPainhas/Static-Web-Site-Design
```

Install required gems by executing the following command
```
$ bundle install
```
If the running version of Bundler (1.16.4) is older than the version that created the lockfile (1.16.5), upgrade to the latest version of Bundler by running the following command
```
$ gem install bundler
```

## Execution

First, go to your Static-Web-Site-Design directory.

### Installing Middleman
The first step is to be sure Middleman and all gem dependencies have been installed. Type the following command in your terminal:
```
$ gem install middleman
```

This will install Middleman. Now, go to the source folder in the project, and install all gem dependencies.
```
$ bundle install
```

You should now be set to build the website with the following command:
```
$ bundle exec middleman build
```

To run the website, you can use the Middleman server command.
``` 
$ bundle exec middleman server
```

The output of the command above will include the site's URL that can be copied and pasted into Firefox's address bar.

You can used <Control><C> to terminate the program/server.
