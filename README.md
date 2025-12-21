#### About
Perl script for visualizing repository summaries recursively starting from the specified directory location
Uses git-summary (git-extras) as a dependency

#### Dependencies
- perl
- git-extras

#### Installation
Available in AUR Repository only
```sh
$ yay -S git-summmary
```

#### Usage

```
$ ./git-summmary starting-directory

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
