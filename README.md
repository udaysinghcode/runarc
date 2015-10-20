# How to Run Arc 3.1

This is a quick way to run and install Arc 3.1

## 1. Pull repo

To try and pull the code with SSH run the following.

```Shell
git clone git@github.com:udaysinghcode/runarc.git && cd runarc
```
If that doesn't work try and do this:

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
