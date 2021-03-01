# Eazy Git [![EazyGit Version](https://img.shields.io/badge/version-0.9-blue)](https://github.com/ZechBron/EazyGit)

How lazy are you?
Upload files in your github repository using one command only.


## Compatability && Requirements

+ Linux (Tested in Ubuntu)
   
   sudo apt install git -y

+ Termux - For Android

   Install termux on Google Play

   + Type this Commands:

      apt update

      apt upgrade

      apt install git -y

+ Git Bash - For Windows

   Install Git Bash for Windows here


## Installation:

> git clone https://github.com/ZechBron/EazyGit

> cd EazyGit

> chmod -R +x *

> ./setup


## How to use:
__Setup user__

> eazygit -n github-username -e email-addrs


__Upload file with commit message__

> eazygit -c filename -h commit-message -b github-repo-url

__Upload file with default commit__

> eazygit -c filename -z -b github-repo-url


---


If you encounter an error, problems or bugs.
There are two things you can do:

Email me here zech@mbox.re

Or submit an issue here

![Issues](https://github.com/ZechBron/EazyGit/issues/new)
