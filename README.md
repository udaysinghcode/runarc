# How to Run Arc 3.1

This is a quick way to run and install Arc 3.1

## 1. Pull repo

To try and pull the code with SSH run the following.

```Shell
git clone https://github.com/udaysinghcode/runarc.git && cd runarc  
```

## 2. Install Homebrew

Make sure you have brew installed. 

```Shell
brew -v
```

This should return a Homebrew version. If not run the following:

```Shell
ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"
```

## 3. Install rlwrap

This is to help you deal with parentheses when running the Arc REPL.

```Shell
brew install rlwrap
```

## 4. Run Arc with MZScheme 372 Compiler

Change directory and get into the top level of the folder.
Then run the following:
```Shell
rlwrap mzscheme372/bin/mzscheme -m -f as.scm  
```

You should be running!

## Additional

Information from
[http://arclanguage.org/install](http://arclanguage.org/install)


----
### Arc Language Installation Instructions
1. Install version 372 of MzScheme. (Don't use the latest version. Versions
   after 372 made lists immutable.)
2. Get http://www.arclanguage.org/arc3.1.tar and untar it.

3. Type mzscheme -m -f as.scm and you should get an Arc prompt.

4. If you ^C an Arc program, you'll get the Scheme REPL. Use (tl) to get back to
   the Arc REPL.

5. If you have questions or suggestions, post them on the [forum]1. Install
   version 372 of MzScheme. (Don't use the latest version. Versions after 372
made lists immutable.)
2. Get http://www.arclanguage.org/arc3.1.tar and untar it.

3. Type mzscheme -m -f as.scm and you should get an Arc prompt.

4. If you ^C an Arc program, you'll get the Scheme REPL. Use (tl) to get back to
   the Arc REPL.

5. If you have questions or suggestions, post them on the
   [forum](http://arclanguage.org/forum). 

---
### My Repo Installation

My repo is just version 372 of MzScheme and the Arc 3.1 codebase stored in a
single repo. You can inspect everything if you want. I just found it difficult
to explain to beginners how to get an Arc REPL up and running so I stored
MzScheme and Arc 3.1 together so all you have to do is download the repo and run
the following to get started. Feel free to share!

See Paul Graham's page on [Arc](http://www.paulgraham.com/arc.html) and check
out the [Arc Tutorial](http://old.ycombinator.com/arc/tut.txt) to get started. 
