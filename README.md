BBEdit scripts 
======

Scripts to be used with [BBEdit][]

[BBEdit]: http://barebones.com/bbedit

## Installation ##

These scripts should be installed to 

	~/Dropbox/Application Support/BBEdit/Scripts/

or

	~/Dropbox/Application Support/BBEdit/Text Filters/

(Because you *are* using Dropbox, right? If not I think the path is `~/Library/Application Support/BBEdit/` but I'm not sure because *why would you not be using Dropbox?*)

## Usage ##

The Scripts can be found in BBEdit under the scripts menu:

![](images/scripts-menu.jpg)

The Text Filters can be found in BBEdit under the **Text/Apply Text Filter** menu:

![](images/text-filter-menu.jpg)

The filename will become the menu item name.

## What do they do? ##

Each script should have a `Purpose:` line at the top of the file. For example:

[MMD to HTML.sh][]
: Convert the current BBEdit file to HTML using [MultiMarkdown][]. 


[MultiMarkdown]: http://fletcherpenney.net/multimarkdown/
[MMD to HTML.sh]: https://github.com/tjluoma/bbedit/blob/master/Scripts/MMD-to-HTML/MMD-to-HTML.sh


## There are a few provisos, a couple of *quid pro quos*. ##

* I am not now, nor have I ever been, an employee of Bare Bones Software, Inc. and these scripts are in no way from or endorsed by Bare Bones Software, Inc. 
* These scripts come with no warrantee, guarantee, hint, implication, or other suggestion that any/all of them will work for you. You accept complete liability for anything that happens.
* Feel free to use, adapt, change, fix, modify, and re-release as you wish. Crediting me by name and/or linking to my Github (or other) page would be appreciated, but is not required. After all, they're only shell scripts, not the cure for cancer.

## Requirements ##

*	Some of the scripts require `lynx` which is, unfortunately, not installed by default in Mac OS X. Fortunately it's very easy to install. If you use [Homebrew](http://mxcl.github.com/homebrew/) (and you should!) it's as simple as **`brew install lynx`** or you can get a standalone installer from <http://code.google.com/p/rudix/wiki/lynx>. 



