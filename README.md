### About
Perl script for visualizing repository summaries recursively starting from the specified directory location

While `git-summary` (from git-extras) provides statistics for a single repository, `git-summmary` recursively scans a directory tree and generates statistics for **all repositories** it finds. Perfect for getting an overview of entire organization, monorepo, or projects folder.

Built on top of `git-summary (git-extras)` for reliable Git analysis

### Dependencies
- perl
- git-extras

### Installation
Package manager installation is available in AUR Repository only

- Using yay
```sh
$ yay -S git-summmary
```

- Using makepkg
```sh
$ git clone https://aur.archlinux.org/git-summmary.git
$ cd git-summmary
$ makepkg -si
```

### Usage

```
$ git-summmary starting-directory

Git repository found repo1
Git repository found repo2
Git repository found repo3

base directory                  : <base directory name>
repo age (oldest / latest)      : <oldest> day(s) / <latest> day(s)
active (earliest / most recent) : <earliest> day(s) / <most recent> day(s)
commits                         : <total number of commits>
files                           : <total number of files>
authors                         :
  <author_1 commits count>  <author_1 name>  <author_1 commit percentage>
  ...
  <author_n commits count>  <author_n name>  <author_n commit percentage>
```
