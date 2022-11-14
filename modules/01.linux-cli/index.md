---
duration: 10 minutes
---

# Command line quickstart

## What is the command line/command prompt/CLI/terminal?

* A typed interface to your operating system using a shell language
* Direct access to applications and OS instructions
* Light, often simplified and quick compared to large GUI applications
* Scriptable
* Tightly defined command scope
* Packages are free (install with a package manager)

## Where is it?

* Windows:
  * CMD (builtin), don't use it
  * Powershell (builtin), don't use it
  * Embedded linux kernel
    * `wsl --install (Turn Windows features on or off -> Hyper-V)`
* Mac & Linux:
  * Built-in

## Basic usage

Terminal commands usually take the form of: `<application> <application-function> -<letter-parameter> --<word parameter> <argument1>..<argumentN>`
e.g. `git clone git@github.com:DanielJohnHarty/cat_snapper.git`

> Note: Use the tab key to auto-complete commands on most terminals

## Take a tour

* On Windows, install a Shell environment
* Launch the terminal
* You're in a directory of your ﬁle system

### Inspecting the filesystem

* Use `pwd` to see your position in the file system
* Use `ls` to check what's in this directory
* Try again with `ls -l`. What’s different?
* Try `ls <insert a different directory path>`

### Moving around your ﬁle system

* Use `cd <directory path>` change your position in the filesystem
* Create a directory with `mkdir <path to directory>`
* Create a ﬁle with `touch <path to file>`

## Getting help

It’s rare that a CLI application does not have a guide available. Accessing the manual can take different
forms:

* `<application> -h`
* `<application> <application-function> -h`
* `<application> --help`
* `<application> <application-function> --help`
* `man <application>`

## Important to know

* Use online references for your terminal interface (e.g. `CMD` or `Powershell` on Windows, `bash` or `shell` on Mac & Linux)
* Windows and Linux CLI applications may differ or not exist on both. A google search will help to ﬁnd the name of the equivalent commands accross operating systems  * Windows and Mac/Linux package managers offer a staggering number of applications
