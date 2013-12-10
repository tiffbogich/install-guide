#Mac OSx#

Alright, let's get you set-up with a web development environment on your mac. This is going to be a bit of a process so reserve a few hours going through everything in this document. 

If you have any trouble please leave a comment below this document or open an issue so others can see your question and the solution as well. 


__How to read this document:__

Everything that is in a little box is a command you need to run in your terminal. For example, if you see a box like the one below copy that line and paste it in your terminal:

``` 
copy everything in here an paste it into the terminal
```

__Open the terminal__ by pressing command and then the spacebar. In the search box type terminal and open it by clicking on it.

##Stuff you need##

###XCode###

You  most likely already have a version of Xcode on your maching. Search in your applications folder to double check, but it's best if you upgrade to the latest version:
--> Get it from itunes: https://itunes.apple.com/us/app/xcode/id497799835?mt=12


If you have problems installing XCode because it says something like the version of your operating system is out of date, we can work around that by following the instructions [here](gcc.md)

--> Read Step 1 of this tutorial for any trouble with XCode: http://www.moncefbelyamani.com/how-to-install-xcode-homebrew-git-rvm-ruby-on-mac/


###XCode Command Line Tools###

Once you install XCode, you need to install the command line integration.  

* Press Command+[Space] to launch spotlight in the top right window
* Type `xcode` and press enter
* In the menu bar click `XCode>Preferences`
* Press the downloads tab in the top bar of the dialog (See [this](http://i.imgur.com/V0MnjNS.png) picture for a screenshot of this and the next step)
* Press the `Install` next to the "Command Line Tools" listing


###Homebrew###
Why? with homebrew you can install a lot of programs with a single command line. It will save you a lot of time.

```
 ruby -e "$(curl -fsSL https://raw.github.com/mxcl/homebrew/go)"
```

###Git###
We'll be using Git and Github to do version control. Think of this a place where you story all your work in the cloud so you can share it with other people, save different revisions and do all kind of cool things. 

If you __need a break from the command line__ you can use the visual installer for git here:
http://git-scm.com/downloads

If you want to keep going with the command line type:

```
brew update
```
```
brew install git
```

We will set-up git so it connects to your github after you have your github account set up. If you don't know what that means right now, don't worry, just remember we have to come back to here and do a few more lines to make everything work.


###Awesome! You're all done here!###

__--> Now get your software and accounts set-up [here](https://github.com/tiffbogich/install-guide)__

