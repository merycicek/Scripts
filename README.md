# Scripts

## Dear Coder,

### When I wrote this code, only I and God 
### knew what it was.
### Now, only God knows!

### So if you are done trying to 'optimize'
### this routine (and failed),
### please increment the following counter
### as a warning
### to the next guy:

### total_hours_wasted_here = 67

# What is ShellCheck???

ShellCheck is a static analysis tool that shows warnings and suggestions concerning bad code in bash/sh shell scripts. It can be used in several ways: from the web by pasting your shell script in an online editor (Ace – a standalone code editor written in JavaScript) in https://www.shellcheck.net (it is always synchronized to the latest git commit, and is the simplest way to give ShellCheck a go) for instant feedback.

Alternatively, you can install it on your machine and run it from the terminal, integrate it with your text editor as well as in your build or test suites.

There are three things ShellCheck does primarily:

* It points out and explains typical beginner’s syntax issues that cause a shell to give cryptic error messages.
* It points out and explains typical intermediate level semantic problems that cause a shell to behave strangely and counter-intuitively.
* It also points out subtle caveats, corner cases and pitfalls that may cause an advanced user’s otherwise working script to fail under future circumstances.


## ShellCheck installation on centos7

```python
yum install epel-release -y
```

for amazon linux use the following command:

```python
sudo amazon-linux-extras install epel
```

install shellcheck

```python
yum install ShellCheck -y
```

## ShellCheck installation on Debian/Ubuntu

```python
apt-get install shellcheck
```

## ShellCheck installation on Fedora

```python
dnf install ShellCheck
```


## Usage

```
shellcheck test.sh
```