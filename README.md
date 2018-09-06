# TIL

> Today I Learned

A collection of concise write-ups on small things I learn day to day across a
variety of languages and technologies. These are things that don't really
warrant a full blog post.


_17 TILs and counting..._

---

### Categories

* [Cmake](#cmake)
* [Cpp](#cpp)
* [Firefox](#firefox)
* [Git](#git)
* [Linux](#linux)
* [Markdown](#markdown)
* [Pelco](#pelco)
* [Teamcity](#teamcity)
* [Vim](#vim)

---

### Cmake

- [Forcing Cmake To Download From Artifactory](cmake/force_artifactory.md)

### Cpp

- [Measuring the time a function call takes](cpp/timing_function.md)

### Firefox

- [Open links is a new background tab](firefox/fix-tab-behavior.md)

### Git

- [Commit Part of File to Git](git/commit-part-of-file.md)
- [Create a Github repo from the command line](git/create-github-repo-command-line.md)
- [Show filename of files modified in a commit](git/show-files-in-SHA.md)

### Linux

- [Enabling core files on Centos](linux/enable-cores.md)
- [Finding Files By Date and Deleting Them](linux/find-and-delete.md)
- [Make clamscan or other high-cpu-load process play nice](linux/make-clamscan-more-responsive.md)

### Markdown

- [Formatting code in Pythonista Cafe](markdown/code-formatting.md)
- [Linking to a section in the same document](markdown/in-doc-links.md)

### Pelco

- [Address for the internal SMTP server](pelco/internal_smtp.md)

### Teamcity

- [Cancelling Jobs](teamcity/cancel_jobs.md)

### Vim

- [Create Helptags for new bundle](vim/create-helptags.md)
- [Open File Under Cursor](vim/open-file-under-cursor.md)
- [Reload vimrc File Without Restarting](vim/reload-vim-config.md)
- [Show Special Characters](vim/show-special-characters.md)

## Usage

After creating a new entry, run `./createReadme.py > README.md` to regenerate
the readme with the new data.

If you are using git, you can install this script as a pre-commit git hook so
that it is autogenerated on each commit.  Use the following command:
    cd .git/hooks/ && ln -s ../../createReadme.py pre-commit && cd -


## About

I shamelessly stole this idea from
[jbranchaud/til](https://github.com/jbranchaud/til) who claims to have stolen
it from others.

## Other TIL Collections

* [jbranchaud/til](https://github.com/jbranchaud/til) who claims to have stolen
* [Today I Learned by Hashrocket](https://til.hashrocket.com)
* [jwworth/til](https://github.com/jwworth/til)
* [thoughtbot/til](https://github.com/thoughtbot/til)

## License

&copy; 2017-2018 Jim Anderson

This repository is licensed under the MIT license. See `LICENSE` for
details.