Install Web Development Environment Without XCode
========

__Please read through each sentence before you act on it or anything before it__.  Since you're not installing this on a standard install, you'll need to be extra dilligent about installing this!


Step 1 (Install the GCC toolkit - these are the parts of XCode you need):
-------
* Determine what version of OSx you're running.  To do this click on the Apple Button in the top left corner of the menu bar and press "About this Mac".  A dialog box should pop up and tell you, you are using OSX 10.x.y.  Remember this version.
* Download and run the GCC compiler from [here](https://github.com/kennethreitz/osx-gcc-installer/downloads).  Go under 'downloads' to find it. Make sure the version of the installer you grab matches the version of OSx you saw in the previous step. 
* In the standard install guide skip ahead to the __Homebrew__ section and follow that step.
* Install libksba by running the following command:

```
brew install libksba
```

* Install git by runing the following command:

```
brew install git
```


