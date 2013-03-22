isn't
=====

Use it to keep track of the stuff that is installed on your computer.

Then when you get a new computer, use it to help you install that stuff on it.

It isn't complicated.


Usage
-----

0. Ensure you have the appropriate package managers (and git) installed. I do it like this:

````
    # install Xcode
    # install Xcode CLI Tools
    # install gcc
    ruby -e "$(curl -fsSL https://raw.github.com/mxcl/homebrew/go)"
    brew install node
    brew install python
    brew install git
````

1. Download `isnt` onto your computer

````
    git clone git@github.com:mnewt/isnt.git
    cd isnt
````

2. Save a list of your packages and applications

````
    ./save.sh  # creates some *.txt files in the working directory
````

3. Install said applications on another computer

````
    ./isnt.sh  # reads some *.txt files in the working directory
````

Supported Platforms
-------------------

Right now, `isnt` assumes it's running on a Mac. It will probably mostly work on other Unix-like operating systems, except for Homebrew.


Help
----

Yes, please!


License
-------

Public domain
